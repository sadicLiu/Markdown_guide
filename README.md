## 简单说明
- 将这个文件下载到本地，用文本编辑器打开，你就会看到这个文档是怎么写出来的，这里面用的语法就是Markdown语法
- 下面的内容是Markdown中常用的语法，比如#是一级标题，浏览器会将它渲染成h1标签，##是二级标题
- 在sublime按ctrl+shift+p，输入install，安装markdown editing（用于编辑md文件）和markdown preview（用于在浏览器中渲染md文件）这两个插件，然后打开此文件,按ctrl+shift+p,输入mp(preview in browser)就能看到浏览器将这个文件渲染成了html
- 如果觉得上面的查看方法比较麻烦，你也可以配置一下你的快捷键，直接在浏览器中查看，选择Preferences->Key Bindings，在user那栏添加下面一行代码：
`{ "keys": ["alt+m"], "command": "markdown_preview", "args": { "target": "browser"} }`
然后重启sublime，再按alt+m，效果同输入mp命令一样

### 这是索引
[TOC]

# 这是一级标题 
## 这是二级标题

>这是引用

#### 这是无序列表
* 1
* 2
* 3

#### 这是有序列表
1. 天王盖地虎
2. 小鸡炖蘑菇

#### 插入链接
[百度](http://www.baidu.com)

#### 插入图片
![Google](http://www.google.com.hk/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

#### 粗体、斜体
**这是粗体**
*这是斜体*

#### 这是表格
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

#### 这是代码块
---
    Public class HelloWorld
    {
        public static void main(String[] args)
        {
            System.out.println("hello, world");
        }
    }

`这也是代码块`

#### 这是分割线
***

#### 设置字体、颜色
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font color=red size=5>gray</font>

#### 这是目录结构(>)
>数据结构  
>>树  
>>>二叉树  
>>>>平衡二叉树  
>>>>>满二叉树  

#### 目录结构描述
```
├── Readme.md                   // help
├── app                         // 应用
├── config                      // 配置
│   ├── default.json
│   ├── dev.json                // 开发环境
│   ├── experiment.json         // 实验
│  ├── index.js                // 配置控制
│   ├── local.json              // 本地
│   ├── production.json         // 生产环境
│   └── test.json               // 测试环境
├── data
├── doc                         // 文档
├── environment
├── gulpfile.js
├── locales
├── logger-service.js           // 启动日志配置
├── node_modules
├── package.json
├── app-service.js              // 启动应用配置
├── static                      // web静态资源加载
│   └── initjson
│       └── config.js       // 提供给前端的配置
├── test
├── test-service.js
└── tools
```

#### Markdown中换行
- 如果想在这行之后换行，在这行最后加两个空格之后再回车，或者在下行最前面加两个空格
  换行啦
