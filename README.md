# MediumBot
🚀 Boost Your Profile Visibility with MediumBot! 👾

## About
Are you a content creator or a writer looking to expand your reach on Medium? Meet MediumBot, your ultimate ally in increasing profile visibility and driving social interaction with your articles and users! Say goodbye to manual promotion and tedious tasks - let MediumBot take the lead!

🔗 Link: https://mediumbot.gumroad.com/l/dtfoc?layout=profile

## Why Choose MediumBot?
🤖 Automated Engagement: MediumBot acts as your loyal assistant, automatically engaging with other users' content, sparking interest in your profile, and fostering connections within the Medium community.

📈 Profile Visibility: By driving social interaction with your articles and engaging with other users, MediumBot helps boost your profile visibility, making your content more discoverable to a broader audience.

📅 Scheduled Promotion: With MediumBot, you can schedule your posts for optimal timing, ensuring your articles reach the right audience at the right time, maximizing engagement and exposure.

🚀 Effortless Setup: Setting up MediumBot is a breeze! Just follow the simple installation steps, and you'll be on your way to enjoying the benefits of automated engagement.

## Getting Started with MediumBot:
👉 Step 1: Visit the provided link to access MediumBot on Gumroad.

👉 Step 2: Get the bot up and running by following the installation instructions.

👉 Step 3: Connect MediumBot to your Medium account to enable automated engagement.

👉 Step 4: Customize your preferences and set up scheduled promotion to maximize impact.

👉 Step 5: Sit back and watch as MediumBot works its magic, increasing your profile visibility and driving engagement!

## Unlock the Power of Automation:
🔹 Social Interaction: MediumBot engages with other users, interacts with their content, and encourages reciprocal engagement, creating a thriving community around your profile.

🔹 Network Growth: As MediumBot drives interaction, your network expands, connecting you with like-minded individuals and potential collaborators.

🔹 Content Discoverability: With increased profile visibility, your articles gain better exposure, making it easier for readers to discover and enjoy your valuable content.

🔹 Time Savings: No more spending hours on manual promotion! MediumBot handles the repetitive tasks, freeing up your time to focus on what matters most - your writing.

## Unleash the Potential of MediumBot Today:
Don't miss out on the incredible opportunities that MediumBot brings to the table. Elevate your Medium profile, expand your readership, and nurture valuable connections within the community. Increase your visibility and make a lasting impact with MediumBot!

👾 Get started now at https://mediumbot.gumroad.com/l/dtfoc?layout=profile and unleash the power of automation on Medium!

## Requirements
MediumBot was developed under [Pyhton 2.7](https://www.python.org/downloads).

Before you can run the bot, you will need to install a few Python dependencies.

*Note: Python 2.7.9 and later (on the python2 series), and Python 3.4 and later include pip by default, so you may have pip already. Otherwise, you can install [easy_install](https://pythonhosted.org/setuptools/easy_install.html) `sudo apt-get install python-setuptools` to install [pip](https://pypi.python.org/pypi/pip) `sudo easy_install pip`.*

- [BeautifulSoup4](https://pypi.python.org/pypi/beautifulsoup4), for parsing html: `pip install BeautifulSoup4`
- [lxml](http://lxml.de/intro.html), to assist with BeautifulSoups' parsing: `pip install lxml`
- [Selenium](http://www.seleniumhq.org/), for browser automation: `pip install Selenium`
If you plan to use Firefox (or Iceweasel) you don't need anything more. (Note: you actually may need to install GeckoDriver if your FireFox install is fairly new)

For Chrome, first get the [webdriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) then put it in the same folder than the bot if you are on Windows, or in the `/usr/bin` folder if you are on OS X.

PhantomJS:
- On Windows, download the binary from the [official website](http://phantomjs.org) and put it in the same folder than the bot.
- On OS X Yosemite, the binary provided by the PhantomJS crew doesn't work (*selenium.common.exceptions.WebDriverException: Message: 'Can not connect to GhostDriver'*). You can either compile it by yourself or download the binary provided by the awesome [eugene1g](https://github.com/eugene1g/phantomjs/releases). Then put it in the `/usr/bin` folder.
- It's the same for Raspbian : compile it and put it in the `/usr/bin` folder or download the binary provided by the awesome [fg2it](https://github.com/fg2it/phantomjs-on-raspberry/tree/master/rpi-2-3/wheezy-jessie/v2.1.1).

If you want to built your own binaries, here is the [build instructions](http://phantomjs.org/build.html) for PhantomJS.

## Configuration
Before you run the bot, edit the configuration portion of the script. This will include your account login information (email, password, and service your login is through, etc.) and other logical values to make the bot more of your own. It's that simple!

```python
# Configure constants here
EMAIL = 'youremail@gmail.com'
PASSWORD = 'password'
LOGIN_SERVICE = 'Google, Twitter, or Facebook'
DRIVER = 'Chrome, Firefox/Iceweasel, or PhantomJS'
LIKE_POSTS = True
RANDOMIZE_LIKING_POSTS = True
MAX_LIKES_ON_POST = 50 # only like posts with less than X posts.
COMMENT_ON_POSTS = False
RANDOMIZE_COMMENTING_ON_POSTS = True
COMMENTS = ['Great read!', 'Good work keep it up!', 'Really enjoyed the content!', 'Very interesting!']
ARTICLE_BLACK_LIST = ['Sex', 'Drugs', 'Child Labor']
FOLLOW_USERS = False
RANDOMIZE_FOLLOWING_USERS = True
UNFOLLOW_USERS = False
RANDOMIZE_UNFOLLOWING_USERS = False
UNFOLLOW_USERS_BLACK_LIST = ['DontUnFollowMe']
USE_RELATED_TAGS = True
ARTICLES_PER_TAG = 250
VERBOSE = True
```

## Run
Once you have installed the required dependencies and edited the configuration constants, you can run the bot.

If you would prefer to use the GUI to select your bot options through a GUI instead of editing a file make sure you are in the correct directory and run the MediumBotGUI using the following command: `python MediumBotGUI.py`
You will be prompted with a Gui as shown below:

If you'd rather not use the GUI make sure you are in the correct directory and run the following command: `python MediumBot.py`

Then, after choosing your favorite browser the bot will start visiting articles based on your tags and start liking and commenting articles or following and unfollowing users increase your visibility on Medium.

<!---
MediumBot2023/MediumBot2023 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
