# SocialScraper <img src="https://cdn3.iconfinder.com/data/icons/web-hosting-2-1/128/95-512.png" alt="logo" width="40" height="40"/>

Social Scraper is a python tool meant for Detection of Child Predators/Cyber Harassers on Social Media

```
Tool intends to identify the cyber predators/child harassers on social media with a malevolent intent.The   posts, comments and followers on the social media are subjected to analysis using Artificial Intelligence,   Machine Learning with IGPL and NSFW(Not Safe For Work) to categorise the offensive contents.  

This system is capable of analyzing all social media platforms like Instagram, Twitter, Facebook, LinkedIn,   etc., and other outlets seeking the same suspect. If the suspect doesn’t have the same user ID   on different platforms, then Reverse Image Searching is done to identify the suspect. A set of user_id   is used as a key to grab their personal information and their post information(Post ID, Comments,   Timestamp, location, Captions) from multiple social platforms using ​ OSINT(Open Source   INTelligence) and Beautifulsoup Python Package. The above data of various posts are subjected to analyze   malevolent contents using Machine Learning and Pandas Python library.Based on the statistical analysis,   suspects are categorized based on their behavior(also Polite harassment). The users whose suspect level is   greater than the threshold value will be scrutinized and monitored for further analysis. The suspected    user’s post information(media like Image, Audio, and Video) is retrieved and analyzed using   the ​ IGPL Python package, ​ Urllib and ​ Artificial Intelligence with ​ NSFW (Not Safe For Work) library   to make them fall under the category suspects/predators. Finally, the Child grooming patterns followers and   statistical results that are generated are analyzed and the concerned person is classified as   predator and reported to the law enforcement authorities  
```

**Creators:**
> [Aravindha Hariharan M](https://github.com/Aravindha1234u)  
> [Kabilan S](https://github.com/kabilan1290)  
> [Gowtham G](https://github.com/Gowtham-18)  
> [Giridhara Prasath G](https://github.com/giridhar30)  



### Prerequisites
1.Python 3.X with pip3 Installed  

If not then,pip3 installation  
```
apt install python3-pip
```  
To Check pip versioon  
```
pip3 --version
```

### User List Creation
Tool can handle N-number of user account scrapping which can be given a user.txt

You can use any kind of text editor to edit user.txt
```
gedit user.txt | vim user.txt
```

### Installation
Open Terminal and type
```
git clone https://github.com/Aravindha1234u/SocialScraper
```
cd SocialScraper
To Install required Python package

```
pip3 install -r requirements.txt
```
or
```
python3 -m pip install -r requirements.txt
```

### Execution
To Run SocialScraper
```
python3 main.py
```

### License
SocialScraper is licensed under GNU General Public License v3.0. Take a look at the [License](https://github.com/Aravindha1234u/SocialScraper/blob/master/LICENSE)
