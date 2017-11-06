# Speedtest

![screenshoot](screenshoot.png)

## Dependencies
[Speedtest-cli](https://github.com/sivel/speedtest-cli)

[Awesome-font](http://fontawesome.io/)

## Setup
`cd ~/.config/polybar`

`git clone https://github.com/ShiroUsagi-san/speedtest-polybar-module`

## Module
```Ini
[module/speedtest]
type = custom/script
exec = ~/.config/polybar/speedtest_module/speedtest_api.py
tail = true
interval = 3600
```
