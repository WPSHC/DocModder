# doc-modder
Takes in arguments, searches and replaces a .docx Word template. For onboarding new users.

# Example Use
- Powershell

Start-Process -WindowStyle Minimized -FilePath "${CWD}\DocModder.exe" -ArgumentList "--email $UPN --name `"$fullName`" --username $username --password `"$clearPass`" --tempPath `"$tempPath`" --savePath `"$savePath`""
