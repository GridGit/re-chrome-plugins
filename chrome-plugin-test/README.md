

#### chrome plugin开发
    * manifest.json
        * name
        * description
        * version
        * manifest_version: 2
        * browser_action {
            default_popuo: index.html,
            default_icon: icon.png 
        }
        * commands {
            _execute_browser_action {
                suggested_key {
                    default: Ctrl + shift + f,
                    mac: MacCtrl + shift + f
                }
            },
            description: 'Opens index.html'
        }
        * 
    * 

