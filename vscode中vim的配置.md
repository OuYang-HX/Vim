{
    "http.noProxy": "http://o30052464:oy2.71828@proxy.huawei.com",
    "editor.mouseWheelZoom": true,
    "explorer.confirmDragAndDrop": false,
    "java.semanticHighlighting.enabled": true,
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    "java.requirements.JDK11Warning": false,
    // 绑定vim前导键
    "vim.leader": "<space>",
    // 启用easymotion插件
    "vim.easymotion": true,
    // 启用系统粘贴板作为vim寄存器
    "vim.useSystemClipboard": true,
    // 由vim接管ctrl+any的按键，而不是vscode
    "vim.useCtrlKeys": true,
    // 突出显示与当前搜索匹配的所有文本
    "vim.hlsearch": true,
      // 普通模式下的非递归按键绑定
    "vim.normalModeKeyBindingsNonRecursive": [],
      // 插入模式下的非递归按键绑定
    "vim.insertModeKeyBindings": [
      {
        "before": ["j", "j"],
        "after": ["<Esc>"]
      },
      {
        "before": ["<C-h>"],
        "after": ["<Left>"]
      },
      {
        "before": ["<C-j>"],
        "after": ["<Down>"]
      },
      {
        "before": ["<C-k>"],
        "after": ["<Up>"]
      },
      {
        "before": ["<C-l>"],
        "after": ["<Right>"]
      },
      {
        "before": ["<C-d>"],
        "after": ["<backspace>"]
      },
      {
        "before": ["<C-w>"],
        "after": ["<Home>"]
      },
      {
        "before": ["<C-e>"],
        "after": ["<End>"]
      }
    ],
    // 命令模式下的非递归按键绑定
    "vim.commandLineModeKeyBindingsNonRecursive": [
      
    
    ],
    // 可视模式下的非递归按键绑定
    "vim.operatorPendingModeKeyBindings": [],
    // 下面定义的按键将交由vscode进行处理，而不是vscode-vim插件
    "vim.handleKeys": {
      "<C-a>": false,
      "<C-f>": false
    },
    "editor.wordWrap": "on",
    "explorer.confirmDelete": false,
    "vscode-office.openOutline": false,
    "vim.commandLineModeKeyBindings": [


    ],
    "markdown.extension.extraLangIds": [
    "quarto",
    "rmd"
    ],
    "markdown.extension.list.indentationSize": "inherit",
    "markdown.extension.preview.autoShowPreviewToSide": true,
    "markdown.extension.print.imgToBase64": true,
    "markdown.extension.theming.decoration.renderTrailingSpace": true,
    "markdown.extension.toc.orderedList": true,
    "markdown-preview-enhanced.enableHTML5Embed": true,
    "workbench.colorTheme": "One Dark Modern",
    "workbench.iconTheme": "office-material-icon-theme",
    "markdown-preview-enhanced.previewTheme": "atom-light.css",

    "vim.autoSwitchInputMethod.enable": true,
    "vim.autoSwitchInputMethod.defaultIM": "1033",
    "vim.autoSwitchInputMethod.obtainIMCmd": "C:\\im-select\\im-select.exe", 
    "vim.autoSwitchInputMethod.switchIMCmd": "C:\\im-select\\im-select.exe {im}"
}
