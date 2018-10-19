# node 调试
https://i5ting.github.io/node-debug-tutorial/

- vscode
```
    "program": "${workspaceFolder}/vue-cli/bin/vue-init",
    "args": [
        "webpack2",
        "222"
    ],
```
https://code.visualstudio.com/docs/nodejs/nodejs-debugging

# 全局node的命令

- package.json

```javascript
  "bin": {
    "vue": "bin/vue",
    "vue-init": "bin/vue-init",
    "vue-list": "bin/vue-list"
  }
```

- bin相关文件
文件顶部
告诉程序使用node执行
```
#!/usr/bin/env node
```

- 本地开发调试
可以在package.json 所在文件夹执行
```
npm link
```
就会有全局命令软链接


# 参考
https://juejin.im/post/5b581795e51d453509561b34

