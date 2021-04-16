# extension_login_gmail_chrome_process - Captcha69.Com - MMO69.Com

- Step 1: 

Download 3 file [background.js] + [inject.js] + [manifest.json] to [ C:\extension_login_gmail_chrome_process\ ]

- Step 2:

Replace account google in file [inject.js]

Demo replace email google + password google + mail recovery of google ( gmail )

var g_acc =
{
	email : "nttrung9x@gmail.com",
	pass : "captcha69.com",
	recovery : "mmo69.com"
};

- Step 3: 

Run chrome.exe = cmd Run Process aguments

string argument = $"--load-extension=\"C:\extension_login_gmail_chrome_process\" --user-data-dir=\"C:\extension_login_gmail_chrome_process_profile\" \"https://accounts.google.com/\"";

- Step 4:

waitting Process chrome exit >>> Done

- Step 5:

Open chrome with Selenium success !

