# Flex-Bot

### About:
Flex Bot uses BanWeb to register for courses. When 10,000 students log in at the same time, it can be difficult to sign up for the courses you want. This python script saves time by automatically logging in and entering the courses, minimizing the amount of time spent to sign in. 

### Initial Setup:
* Install Python 3.6.5 for:
[Mac](https://www.python.org/ftp/python/3.6.5/python-3.6.5-macosx10.6.pkg), [Windows](https://www.python.org/ftp/python/3.6.5/python-3.6.5-amd64.exe), [Linux](https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tar.xz)
if you do not have it

* Install chromedriver for:
[Mac](https://chromedriver.storage.googleapis.com/2.37/chromedriver_mac64.zip),
[Windows](https://chromedriver.storage.googleapis.com/2.37/chromedriver_win32.zip),
[Linux](https://chromedriver.storage.googleapis.com/2.37/chromedriver_linux64.zip)

### For Beginners:

* Download github folder [here](https://github.com/TAHASHAH12/flex-bot/archive/master.zip) and unzip
* Unzip chromedriver & move into folder FLex-bot

### For Advanced Users:

* `pip install virtualenv`

* Create a virtual environment:
`virtualenv -p python3 env`

* Source the environment
`source env/bin/activate`

### Run:
* Open up `terminal` in finder or searchbar

* Change directory to where FLex-bot is: i.e:
`cd Downloads/FLex-bot`

* Locate current directory:
`pwd`

* Inside `flex.py` change `chromedriver = path/of/chromedriver`
* Ex: `chromedriver = /home/User/Desktop/Flex-bot/chromedriver/chromedriver`

* Install pip if not installed
`sudo apt-get install python-setuptools`


* Run the python script in your terminal
`python flex.py`

### Things to Note:

* If you want to add more CRNS add this after the last CRN: `mydriver.find_element_by_id("crn_id6").send_keys(crn6)`
* After the above statement, in the bottom, add:
`crn6 = '666666'`

* If you want less CRNS, simply delete the ones you do not want

* YOU MUST CLICK THE SUBMIT BUTTON BEFORE **SEMESTER YEAR** (ex: **Fall 2021**) 

* Feel free to contact me with any questions or submit an issue!
