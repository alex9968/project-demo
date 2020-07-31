
## 文件结构命名及规范示例

project-demo
├── README.md
├── node_modules
├── package.json
├── public
└── src
    ├── components
    │   ├── Button
    │   │   ├── Button.js
    │   │   └── index.scss
    │   ├── Icon
    │   │   ├── Icon.js
    │   │   └── index.scss
    │   └── Layout
    │       ├── Layout.js
    │       └── index.scss
    ├── pages
    │   ├── my-page1
    │   │   ├── DetailPage      //子页面
    │   │   │   ├── index.jsx
    │   │   │   └── index.scss
    │   │   ├── EditPage         //子页面
    │   │   │   ├── index.jsx
    │   │   │   └── index.scss
    │   │   ├── MyLayout       //子组件
    │   │   │   ├── MyLayout.jsx
    │   │   │   └── index.scss
    │   │   ├── Table               //子组件
    │   │   │   ├── Table.jsx
    │   │   │   └── index.scss
    │   │   ├── consts.jsx 
    │   │   ├── index.jsx    
    │   │   └── index.scss
    │   └── my-page2
    │       ├── consts.jsx
    │       ├── index.jsx
    │       └── index.scss
    ├── router
    │   └── index.js
    ├── services
    │   └── index.js
    └── utils
        ├── http.js
        ├── index.js
        └── time.js