# whistle.rules_watcher
Use local file as whistle rules, the plugin will watch rules file change

## Install
`npm install -g whistle.rules_wacher`

## Usage
Add rules in the whistle rules： `* whistle.rules_watcher://${path}`

Path must absolute path, such as
```
# Rules
* whistle.rules_watcher:///Users/xxx/WebstormProjects/my_proxy/config/.proxy
```

