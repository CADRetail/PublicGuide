
## What this??
gives you history and autocomplete in windows terminal

## install Clink

https://github.com/chrisant996/clink/releases/download/v1.7.10/clink.1.7.10.e3c993_setup.exe

* create file `oh-my-posh.lua` in `C:\Users\<UserName>\AppData\Local\clink`
`--config` is a link to file / url of OMP theme

>[!info]+ oh-my-posh.lua
>```lua
load(io.popen('oh-my-posh init cmd --config https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/multiverse-neon.omp.json'):read("*a"))()

>[!info]+ CMD
>```batch
clink config prompt use oh-my-posh


## Disable clink start message
>[!info]+ CMD
>```batch
clink set clink.logo none