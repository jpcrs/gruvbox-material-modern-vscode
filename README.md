<h1 align="center">
𝐆𝐫𝐮𝐯𝐛𝐨𝐱 𝐌𝐚𝐭𝐞𝐫𝐢𝐚𝐥 Modern
</h1>

<h2 align="center">
𝐃𝐚𝐫𝐤 Medium
</h2>

![dark-medium](assets/medium.png)

<h2 align="center">
𝐃𝐚𝐫𝐤 Soft
</h2>

![dark-medium](assets/soft.png)

This color scheme is just a small adaptation of [Gruvbox Material](https://github.com/sainnhe/gruvbox-material), inspired by the modern look of [Github Theme](https://github.com/primer/github-vscode-theme)

## Information

The screenshots showed in the repository are using customizations by the [Apc Customize UI++](https://github.com/drcika/apc-extension) extension.

These are my configurations:
<details>
    <summary>settings.json</summary>
    ```json
    "apc.electron": {
        "frame": false,
        "titleBarStyle": "customButtonsOnHover",
        "opacity": 0.99
    },
    "apc.activityBar": {
        "size": 36 // Size of icons in the activity bar
    },
    "apc.header": {
        "fontSize": 10 // Fontsize on tabs
    },
    "apc.listRow": {
        "height": 19, // Spacing in the explorer window
        "fontSize": 12 // Font size in the explorer window
    },
    "apc.statusBar": {
        "height": 19, // Status bar height
        "fontSize": 11 // Status bar size
    },
    "apc.font.family": "Zed Mono",
    "apc.sidebar.titlebar": {
        "height": 5,
        "fontSize": 11
    },
    "apc.stylesheet": {
        ".title-label > h2": "display:none;", // Hide title in the activity window
        "div.title-actions": "display:none;",
        ".quick-input-widget > .quick-input-titlebar": "display: none",
        ".quick-input-widget > .quick-input-list > .monaco-list": "font-size: 11px !important; max-height: 50vh !important;",
        "#quickInput_list > div > div.scrollbar.vertical": "display: none !important; width: 0px !important;",
        ".quick-input-widget > .quick-input-list .codicon": "font-size: 10px !important; color: #83a598 !important; padding-right: 5px;",
        ".quick-input-widget > .quick-input-list .monaco-list-row[aria-label*=\" +\"] .label-description": "color: #8ec07c;",
        ".monaco-grid-view > .monaco-sash": "display: none !important;",
        ".monaco-editor .scroll-decoration": "box-shadow: none;",
        ".monaco-icon-label:after": "font-size: 10px !important;",
        "div.inline-tabs-placeholder": "display: none !important;",
        "div.monaco-scrollable-element.mac": "height:  !important",
        ".quick-input-widget": {
            "margin-top": "12% !important",
            "border": "solid !important",
            "border-width": "0.5px !important",
            "box-shadow": "0 0 0 0 !important"
        },
        ".quick-input-header > .quick-input-and-message .monaco-inputbox": {
            "border-radius": "5px 5px 5px 5px !important"
        },
    }
    ```
</details>

## Credits

- [@sainnhe](https://github.com/sainnhe) for creating the original Gruvbox Material palette and extension

## License

[MIT License](LICENSE)