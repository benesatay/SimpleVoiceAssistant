# simpleVoiceAssistant

If sound.mp3/msound.mp3 does not exist, they will be created and saved to project directory when app is ran.

========================

--searchOrOpen.py--

You have to have chromedriver to open google chrome.

You should download suitable chromedriver version for you.

Put chromedriver to project directory.

Open the "searchOrOpen.py" and find this line:

driver = webdriver.Chrome(executable_path='chromedriverPath')

and then enter chromediver path into webdriver.Chrome()

**

If you want to open an application that exist in your computer with this app, you have to write directory of application to:

spotifyDir = 'HERE'

========================

--mailSender.py--

If you want to write a mail with your voice, please make sure you applied the following steps.

On the email sender's mail account, less secure app access has to be enabled to prevent bad credentials error because of SMTP PROTOCOLS.

Open the mailSender.py and

firstly, find this line:

"mail.login('youremail@gmail.com', 'youremailpassword')"

and then enter your email instead of "youremail@gmail.com" and password instead of "youremailpassword".
(This process is applied for authentication.)

secondly, find this line: 

"mail.sendmail('youremail@gmail.com', 'targetemail@gmail.com', content)"

and then enter the your email instead of "youremail@gmail.com" and receiver's email instead of "targetemail@gmail.com".

**

If you can not see the mail that is sent in the mailbox when you run the code, please check the spam part.
