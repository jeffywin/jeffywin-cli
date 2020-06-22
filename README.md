- 建立bin目录，下面www文件
``` js
    #! /usr/bin/env node
    // 告诉用node来执行文件， node 在usr/bin/env 中
```
- 接着在package.json中
``` json
 "bin": {
    "jeffywin-cli": "./bin/www"
  }
  // 在命令行中通过npm link 来生成 jeffywin-cli 命令
```

- 安装eslint
``` js
    npm install eslint
    npx eslint --init // 执行node_modules下的eslint

```