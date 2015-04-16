#海风上课系统

```javascript
static/
├── assets/
│   ├── css/            //css资源文件夹
│   │   ├── client.less     //学生端less样式表
│   │   ├── pub-style.less  //公共样式表
│   │   ├── server.less     //教师端less样式表
│   │   └── reset.css       //样式表重置
│   ├── dust-temp       //dust模板引擎编译后文件
│   ├── dustsrc         //dust模板引擎文件
│   ├── images          //图片资源文件夹
│   ├── js/              //主要开发js文件夹
│   │   ├── apps/       //主要js
│   │   │   ├── client/index.js     //学生端js主文件
│   │   │   ├── server/index.js     //教师端js主文件
│   │   │   ├── util/               //工具类
│   │   │   │   ├── wsy/
│   │   │   │   │    ├──animation_frame.js      //animation 兼容补丁
│   │   │   │   │    ├──canvas_board.js         //canvas画板实现库
│   │   │   │   │    ├──canvas_buff.js          //canvas对象缓存
│   │   │   │   │    ├──core.js                 //wsy类库入口
│   │   │   │   │    ├──emitter.js              //事件驱动实现库
│   │   │   │   │    ├──get_offset_point.js     //相对位置获取
│   │   │   │   │    ├──hf_canvas_board.js      //海风需求扩展
│   │   │   │   │    ├──hf_canvas_board.js      //海风websocket数据传输处理
│   │   │   │   │    ├──inherits.js             //js对象绑定
│   │   │   │   │    └──stepFn.js               //js异步等待处理运行处理
│   │   │   │   ├── canvas-to-blob.js           //canvas 导出二进制对象 扩展
│   │   │   │   ├── DetectRTC.js                //webrtc 诊断
│   │   │   │   ├── load-image-all.js           //加载图片库
│   │   │   │   ├── RTCPeerConnection-v1.5.js   //webrtc p2p 连接
│   │   │   │   └── runtime.js                  //用于计算运行时间
│   │   ├── client.js   //学生端js入口
│   │   ├── common.js   //js配置文件
│   │   ├── config.js   //项目配置文件
│   │   └── server.js   //教师端js入口
│   └── libs/           //第三方开源库
│       ├── async               //异步处理工具类库
│       ├── base64              //浏览器处理base64兼容性腻子
│       ├── draggabilly         //html5拖拽处理库
│       ├── dustjs-helpers      //dust模板引擎扩展库
│       ├── dustjs-linkedin     //dust模板引擎解析库
│       ├── jquery.raty         //jquery评星组件
│       ├── jquery-mousewheel   //jquery mousewhell 事件组件
│       ├── jScrollPane         //jquery 滚动条组件
│       ├── loaders             //css3 loading
│       ├── localforage         //indexdb 本地存储库
│       ├── lodash.js           //js异步工具库
│       ├── magnific-popup.js   //js弹层处理组件
│       ├── modernizr           //浏览器特效检测库
│       ├── q.js                //promises 实现库
│       ├── require.js          //amd r.js 加载库
│       ├── require-domReady    //r.js domReady 组件
│       ├── socket.io           //websocekt 传输处理库
│       ├── sweetalert          //美化提示框组件
│       └── umeditor-hf         //海风定制版 百度 um富文本编辑器组件
├── client.html         //客户端主页面
└── service.html        //服务端主页面
```