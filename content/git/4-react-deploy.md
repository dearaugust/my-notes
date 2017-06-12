#create-react-app 项目部署到Github

- 1.运行 ’‘’npm run build‘’’

- 2.**添加 package.json**

```
  "name": "kakaka-demo",
  "homepage": "http://dearaugust.github.io/kakaka-demo",
```

```
  "scripts": {
      "start": "react-scripts start",
      "build": "react-scripts build",
      "test": "react-scripts test --env=jsdom",
      "eject": "react-scripts eject",
      "predeploy": "npm run build",
      "deploy": "gh-pages -d build"
    }
```

- 4.运行 `npm run deploy` 部署成功
