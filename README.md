# toggle-cleartype

Toggle ClearType and enable the Audio Service on Windows

## To compile to exe from ps scripts

Install ps2exe

```powershell
Install-Module ps2exe
```

Compile

```powershell
Invoke-ps2exe -inputFile '.\toggleCT.ps1' -outputFile '.\ToggleCT.exe' -noConsole -title 'https://github.com/shaansubbaiah/toggle-cleartype' -iconFile '.\icons\lettuce64.ico' -noOutput
```

Compile with Audio toggle

```powershell
Invoke-ps2exe -inputFile '.\toggleCTandAudio.ps1' -outputFile '.\ToggleCTandAudio.exe' -noConsole -requireAdmin -title 'https://github.com/shaansubbaiah/toggle-cleartype' -iconFile '.\icons\lettuce64.ico' -noOutput
```
