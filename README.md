<div align="center">

## Automatic Webbrowser  Popup Killer


</div>

### Description

This code is very usefull for webbrowser developers to block all popup windows if they look like popup windows eg. no toolbars....without Killing the 'open in new window' command.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ali Damji](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ali-damji.md)
**Level**          |Intermediate
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB 5\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ali-damji-automatic-webbrowser-popup-killer__1-42879/archive/master.zip)

### API Declarations

```
'Code By Ali Damji
'Email Me At ali_damji@hotmail.com
```


### Source Code

```
Private Sub WebBrowser1_OnToolBar(ByVal ToolBar As Boolean)
On Error Resume Next
If ToolBar = False Then
Unload Me
End If
End Sub
```

