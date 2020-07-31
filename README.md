
## 文件结构命名及规范示例


```
project-demo
├── README.md
├── node_modules
├── package.json
├── public
│   └── index.html
└── src
    ├── components
    │   ├── Button
    │   │   ├── Button.js
    │   │   └── index.scss
    │   └── MyLayout
    │       ├── MyLayout.js
    │       └── index.scss
    ├── pages
    │   ├── my-page1
    │   │   ├── DetailPage
    │   │   │   ├── index.jsx
    │   │   │   └── index.scss
    │   │   ├── MyLayout
    │   │   │   ├── MyLayout.jsx
    │   │   │   └── index.scss
    │   │   ├── Table
    │   │   │   ├── Table.jsx
    │   │   │   └── index.scss
    │   │   ├── consts.jsx
    │   │   ├── index.jsx
    │   │   └── index.scss
    │   └── my-page2
    │       ├── consts.jsx
    │       ├── index.jsx
    │       └── index.scss
    ├── router
    │   └── index.js
    ├── services
    │   └── index.js
    └── utils
        ├── http.js
        ├── index.js
        └── time-transfrom.js
```

## 文件夹命名
* 全部小写，中划线连接
* 如`my-first-page`

## 普通文件命名
* 全部小写，中划线连接
```
index.js
docker-compose.yml
time-transfrom.js
```

## 组件命名
* 大写开头，组件文件夹首字母大写，如`MyLayout`
* 用相同的文件夹名称包裹
```
components
    ├── Button
        ├── Button.js
        └── index.scss
```


## page页面结构（最多两层）
```
src/pages/my-page1
├── DetailPage  //子页面，内部引用
│   ├── index.jsx
│   └── index.scss
├── MyLayout   //子组件，内部引用
│   ├── MyLayout.jsx
│   └── index.scss
├── consts.jsx
├── index.jsx
└── index.scss
```
*  子页面在内部引用，大写开头，以page后缀结尾
*  子组件在内部引用，大写开头



