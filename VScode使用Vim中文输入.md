*References:*
https://www.zhihu.com/question/303850876
win:
1. 安装im-select:https://github.com/daipeihust/im-select
2. 将以下插入vim的setting.json
 ```json
"vim.autoSwitchInputMethod.enable": true,
"vim.autoSwitchInputMethod.defaultIM": "1033",
"vim.autoSwitchInputMethod.obtainIMCmd": "C:\\im-select\\im-select.exe", 
"vim.autoSwitchInputMethod.switchIMCmd": "C:\\im-select\\im-select.exe {im}"
 ```
