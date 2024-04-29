# DocModder
A Python script that takes in arguments, searches and replaces text in a .docx Word template. For onboarding new users. I used Pyinstaller to compile the .py to an .exe.

# Parameters
-h, --help
-e EMAIL, --email EMAIL
-n NAME, --name NAME
-u USERNAME, --username USERNAME
-p PASSWORD, --password PASSWORD
-t TEMPPATH, --tempPath TEMPPATH
-s SAVEPATH, --savePath SAVEPATH

# Example Use
### Powershell

Start-Process -FilePath "${CWD}\DocModder.exe" -ArgumentList "-e $UPN -n `"$fullName`" -u $username -p `"$clearPass`" -s `"$tempPath`" -o `"$savePath`"" -NoNewWindow -Wait
