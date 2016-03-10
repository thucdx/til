Notification in ubuntu is quite annoying to me, and may be to you as well

Apply: Ubuntu 14.04 -> Ubuntu 15.10, may others applicable as well

```
sudo add-apt-repository ppa:leolik/leolik
sudo apt-get update
sudo apt-get install notify-osd

pkill notify-osd
```

To install a graphical tool to configure Notify-OSD:

```
sudo add-apt-repository ppa:gsn/grabbelkiste
sudo apt-get update
sudo apt-get install notifyosdconfig
```

Launch NotifyOSD from Dash and choose options you want. Basically, there are : ptimeout, style, text formatting, Close on click.

Don't know why GUI does not support Positioning configure. Have to configure by using gsettings

```
gsettings set com.canonical.notify-osd gravity NUMBER
```

Number - position lookup
```
1 top-right corner
2 middle-right
3 bottom-right corner
4 bottom-left corner
5 middle-left
6 top-left corner
```



