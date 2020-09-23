<div align="center">

## a more usable ShellExecute


</div>

### Description

I´we sen alot of ShellExecute tutorials but thay arent that good, there is stuff thats missing.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Erik Ellis](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/erik-ellis.md)
**Level**          |Beginner
**User Rating**    |3.0 (21 globes from 7 users)
**Compatibility**  |Delphi 7, Delphi 6, Delphi 5
**Category**       |[Delphi function enhancement](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/delphi-function-enhancement__7-25.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/erik-ellis-a-more-usable-shellexecute__7-947/archive/master.zip)





### Source Code

This is my first tutorial so dont get upset if its no good, just post a coment and ill fix it.<br>
<br>
ShellExecute(0,'open',PChar(prog),pchar(params),'',SW_SHOWNORMAL);<br>
<br>
1 (ShellExecute) Thats a ShellAPI command and therefore you need to add ShellAPI to Uses<br>
<br>
2 (The first "PChar" command) Betven the brakets you add Dir+FileName like so : c:\dir\file.exe<br>
<br>
3 (The second "PChar" command) Add parameters to it like hl.exe´s : -console -game ns<br>
<br>
Now thats more stable and is compateble with stuff like : edit1.text + '\hl.exe'<br>
<br>
Im uploading my updated verson of Jason´s apis.pas with stuff like RunApp, OpenBrowser and FileName.exe to FileName Converter

