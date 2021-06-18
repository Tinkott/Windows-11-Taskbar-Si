# Windows 11 Taskbar Size
### Personalize taskbar in developer version of your Windows 11!

![Screenshot_1](https://user-images.githubusercontent.com/38760591/122463200-fc15fc80-cfbd-11eb-813f-fc7c4cdced5d.png)

File name                     | Description
------------------------------|--------------------------------------------------------------------------------------------
Windows 11 large taskbar.reg  | Set large version of your Windows 11 taskbar
Windows 11 medium taskbar.reg | Set medium version of your Windows 11 taskbar (Default)
Windows 11 small taskbar.reg  | Set small version of your Windows 11 taskbar (equivalent to small icons in Windows 10)

#### Windows 11 (size) taskbar.reg file code:
```
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"TaskbarSi"=dword:00000000
```

where
- "dword:00000000" is the small size of the taskbar
- "dword:00000001" medium size
- "dword:00000002" large size





