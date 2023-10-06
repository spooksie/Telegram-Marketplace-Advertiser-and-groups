<div align="center" dir="auto">
  <a href="https://github.com/spooksie">
    <img src="https://camo.githubusercontent.com/cd5e319c5e8d58acb6122c2525120409628c4c49f72fd5f71b542212035c0963/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f382f38322f54656c656772616d5f6c6f676f2e7376672f3230343870782d54656c656772616d5f6c6f676f2e7376672e706e67" alt="Logo" width="120" height="120" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/2048px-Telegram_logo.svg.png" style="max-width: 100%;">
  </a>
  <h2 align="center" tabindex="-1" id="user-content-telegram-adbot" dir="auto"><a  >Telegram AdBot</a></h2>
  <p align="center" dir="auto">
    Promote your Telegram services effortlessly and effectively with our advanced adbot, reaching an impressive network of 2600 advertisement groups. Elevate your visibility and connect with a broader audience today!
  </p>
</div>

---------------------------------------

* Efficiently join groups in bulk while ensuring safety through smart time management, minimizing the risk of bans.

* Simplify setup with a user-friendly configuration and intuitive interface design.

* Get your hands on a single file packed with 2600 ad groups, each containing 500 groups for joining without a premium account! 

---------------------------------------

  # How to use it

    DO NOT USE THIS TO SPAM NORMAL GROUPS! You will get banned

1) Marketplaces are located in  `Market Place Groups`.<br>
> You will see 1 text file, this is the 2600 groups
> You will see 1 folder, this is the the groups of 500 for non premium accounts

2) Make Sure you use your **main account** as new accounts will get banned instantly<br>
> Non Premium: You can join 500 groups
> Premium: 1000 groups
> You need to disable 2fa for this to work
- If you don't want to use your main account, you will need to buy **aged accounts** that are older than 1 years. The older the better. 
> Check my [Free Instagram Pod Group](https://t.me/podswapapp) to get real engagement

3) You will need to create an API with Telegram, [Click here](https://my.telegram.org/auth) to get your keys
	> Add your phone number with country code, then check Telegram for your code.
- Add the name, shortname & website (You can add anything you like) & select any platform (it doesn't matter)
- You need to copy and save the **api_id** & **api_hash**
-  Open `Adbot/assets/config.toml` in any text editor
	>  Replace the 00000000 with the **api_id**  
	>  Replace the xxxxxx with the **api_hash**  
	>  Remember to add your **phone_number**  
	
-  Sending Limits: I've set the default to 1 message per hour to all groups
	> If you want to change it to 2 messages per hour **send_interval=3** & **loop_interval=1800** this could be risky at first

4) Open `Adbot/assets/groups.txt`
	> I've already added 495 ad groups to the list. If you want to edit the list and change the groups. Look at the `Market Place Groups` folder or add your own.

5) You now need to create a public channel for your promotional message to be forwarded to the AdGroups.
> In Telegram  `New Channel > Enter Any Name > Next > Public > Enter the channel slug after https://t.me/ > done`
> Now Broadcast your Promotional Message that you want to advertise in the groups

 - Example message

> **FREE Instagram Pods 2.0**
> ⚪️ Eliminate Leechers and phony engagement
> ⚪️ Automatically organized by Follower Count
> ⚪️ Precision matching based on your specific Niche
> ⚪️ 160 unique niches for you to choose from
> ⚪️ Comprehensive Engagement History & Reporting System
> ⚪️ Customize and create your personalized Comment Groups
> ⚪️ Telegram/WhatsApp Not Required, PodSwap is an app
> 🔴 We Never will ask for your Instagram Password
> 
> 🔥 PodSwap is the next Generation of Instagram Pods
> 
> **AND ITS 100% FREE FOREVER!**
> 🧪 Currently in Beta phase
> 🔗 https://PodSwap.app 🔗
> Telegram Group: https://t.me/podswapapp

 - **Tip!** Pin the public channel you have just created with your main account or aged
 
6) Make sure you've installed Python. I've used 3.12 and it works great. Future versions may break the code. [Python Release Python 3.12.0 | Python.org](https://www.python.org/downloads/release/python-3120/) > Scroll to the bottom > Download for Windows Installer (64-bit) or if on MacOs the 64-bit Universal2 Installer

>    Install and open Your command prompt (Windows) `cmd` or Terminal on Mac
>    To see if its working type `pip` if it shows loads of text, its working
>    If it shows this  

    'pip' is not recognized as an internal or external command,
    operable program or batch file.
>   close command prompt and reopen or restart PC

7) Install Requirements for Python

 - Go to your command prompt and cd into the folder where you downloaded this code.
 - Change directory to `Adbot`
 - paste this `pip install -r requirements.txt` this will install all the requirements to make it work
 - Once installed you are ready to start

8) Joining the groups and starting the app
 - Make sure you are in the `Adbot` folder on command prompt
 - If in windows `start.bat` or `python main.py`
 - You will be alerted for a Verification code, check your Telegram to receive it and enter
 - It will say `[?] Join groups?:` Type `Y`
 - Time to be patient as it will take 1-2 days for your account to join the 500 groups. Keep your computer on at all times or use a VPS (Private Cloud PC). I use [GreenVPS](https://greencloudvps.com/billing/aff.php?aff=5859) and they work awesome, they are cheap and the support is amazing. Windows 8gb can run 6 bots 247 from the same IP. If its 1 account you can get away with 1-2gb of ram.
 
 9) Sending the messages from your Public channel once you've added 
 - Make sure you are in the `Adbot` folder on command prompt
 - If in windows `start.bat` or `python main.py`

 `Please select the group you would like to forward the message from
[?] ID: `
- It will ask for the ID of the channel, if you pinned it. You can go to the top of the page on command prompt to find it. Copy the ID and save it. It should look like `1874909578` enter the number and hit return

`Selected PodSwap Ads as your promotions chat.`
 ` ID  Content`
`----  ------------------------`
`   2  🟣🔴🟡🟠🔵🟢⚪️🟣🔴🟡🟠🔵🟢⚪️`
`      FREE Instagram Pods 2.0`

`Please select the message you would like to forward`
`[?] ID: `

 - It will ask for the ID of the post that you want to forward to the groups. Enter the number, in this case for me its 2
 `Sending out your message to 495 groups!`
 - Sit back and relax, close the VPS window so it runs 247. If running on a PC, make sure your computer doesn't go to sleep.
 - Please don't message me for support, if something doesn't work. Read the tutorial again without missing anything
---------------------------------------

### Come say Hi in my Telegram Group

I've developed an Instagram growth app and the Telegram group is https://t.me/podswapapp
If you are interested in the app, visit https://PodSwap.app its 100% FREE

### Warning

> I'm not held responsible for any actions performed while using this program.
> If you spam this to non Market groups, you will get banned

### Credits

The [Original Developer](https://github.com/dropout1337/Telegram-AdBot)
