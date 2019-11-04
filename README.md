## 文件目录

    crm
    ├── public
    │   └── mock
    │       └── login.json
    ├── src
    │   ├── assets
    │   │   └── img
    │   ├── components
    │   │   ├── Header.vue
    │   │   ├── Footer.vue
    │   │   └── MyNav.vue
    │   ├── pages
    │   │   ├── home.vue
    │   │   ├── index.vue
    │   │   ├── login.vue
    │   │   ├── not.vue
    │   │   └── other.vue
    │   ├── router
    │   │   └── index.js
    │   ├── store
    │   │   ├── actions.js
    │   │   ├── getters.js
    │   │   ├── index.js
    │   │   ├── mutations.js
    │   │   └── state.js
    │   ├── App.vue
    │   └── main.js
    ├── .gitignore
    ├── babel.config.js
    ├── package-lock.json
    ├── package.json
    └── README.md

## 编写进度 ---- 每天抽空一点点，进步一点点

    *[ 
        完成模拟用户登陆、退出功能，
        根据是否已经登陆（vuex && 路由导航守卫） 强制控制用户页面 
    ]

    *[ 
        完成单层路由权限匹配，当前用户是否有权利进入某个页面，
        没有权限直接弹出404
        
        完成多层路由权限匹配，判断当前用户是否有权利进入某个页面路由，
        更改路由权限判断的方法，从判断路径 改为 用户权限标识
        添加动态渲染多级导航 （目前样式有问题） 
    ]

    *[ 
        完成根据路由渲染导航，以及面包屑导航的铺垫
        新增 验证身份证号 全局方法 
    ]
    