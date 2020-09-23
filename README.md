<div align="center">

## \_\_\_OneLine Shutdown\.


</div>

### Description

Not sure if this has been posted before.

Allows you to shutdown quickly using the shell command. This also enables you to restart as well.
 
### More Info
 
Nope

Save any work that you've done since you last saved it..but thats kinda a given.

Depending on your time given before the pc shuts down...a Window that gives the time remaining before it shutsdown and it will give you who shutdown the computer, by your computer name.

Sorry if this doesn't make sense, I'm not too well of a writer.

....umm...shuttingdown your computer :P.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Michael Fausett](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/michael-fausett.md)
**Level**          |Beginner
**User Rating**    |4.9 (34 globes from 7 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/michael-fausett-oneline-shutdown__1-59671/archive/master.zip)





### Source Code

```
Shell "shutdown -s -t 60"
'Shell will execute the command "shutdown -s -t 60"
'the shutdown -s -t 60 means:
' shutdown -s(shutdown) -t(time) 60(in this many seconds)
'So this will shutdown your PC in 60 seconds.
'Shell "shutdown -s -t 12" will shutdown your PC 'in 12 seconds.
'Shell "shutdown -r -t 60"
'This will restart the pc in 60 seconds.
Hope this helps for those who just can't figure it out.
'[edit]
'When you just want to shutdown without any windows popping up, type:
' Shell "shutdown -s -t 00"
' same thing for restart
'canceling a shutdown is easy as well, just type:
' Shell "shutdown -a"
```

