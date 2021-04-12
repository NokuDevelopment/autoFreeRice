# autoFreeRice
A python bot that plays FreeRice, an online game that donates to the hungry.

FreeRice is a website developed by the UN World Food Program. You answer multiple-choice questions on a variety of topics, and for every answer you get right FreeRice's sponsors will donate the cash equivalent of one grain of rice to the WFP. 

This bot uses Selenium WebDriver to interact with the FreeRice website.

Because the website is programmed to block bots and this bot interacts directly with the website (as opposed to using and OCR like Tesseract), it can be unstable and may take some time to start up as well as having to restart itself occasionally. 

Another complication is that you need to use the ChromeDriver included in the release, otherwise the program will not be able to connect to FreeRice.

This application generates approximately 20 rice per minute. At this rate, you can earn the price of a meal in about two hours.

Note: I would advise against running this program while you are using your PC. The web browser being restarted every 20-30 minutes can get very annoying, especially if it takes multiple restarts to connect.
