<p align="center">
  <img src="https://github.com/SkidGod4444/TeleGram-Member-Adder/blob/master/Settings/Images/telegram.jpg">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-2.1.0.1-brightgreen"></p>
<p align="center">
  <a href="https://github.com/th3unkn0n">
    <img src="https://img.shields.io/github/followers/SkidGod4444?label=Follow&style=social">
  </a>
  <a href="https://github.com/SkidGod4444/TeleGram-Member-Adder">
    <img src="https://img.shields.io/github/stars/SkidGod4444/TeleGram-Member-Adder?style=social">
  </a>
</p>
<p align="center">
  Telegram Member Adder 
</p>
<p align="center">
</p>

---

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use

`$ pkg install -y git python`

`$ git clone https://github.com/SkidGod4444/TeleGram-Member-Adder`

`$ cd TeleGram-Member-Adder`

* Install requierments

`$ python Setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python Setup.py -c`

* To Genrate User Data

`$ python Scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python MassDM.py members.csv`

* Update Tool

`$ python Setup.py -u`
