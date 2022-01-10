在版本2.1.13修改
\src\controllers\handler.js
\src\controllers\updateCell.js
修改了chartmix.umd.min chartmix.css路径
const dependScripts = [
    'https://cdn.jsdelivr.net/npm/vue@2.6.11',
    'https://unpkg.com/vuex@3.4.0',
    'https://cdn.bootcdn.net/ajax/libs/element-ui/2.13.2/index.js',
    'https://cdn.bootcdn.net/ajax/libs/echarts/4.8.0/echarts.min.js',
    //'/static/sheet/chartmix.umd.js',
    '/expendPlugins/chart/chartmix.umd.min.js'
    // 'http://26.26.26.1:8000/chartmix.umd.js'
]

const dependLinks = [
    'https://cdn.bootcdn.net/ajax/libs/element-ui/2.13.2/theme-chalk/index.css',
    //  '/static/sheet/chartmix.css',
   '/expendPlugins/chart/chartmix.css',
    // 'http://26.26.26.1:8000/chartmix.css'
]