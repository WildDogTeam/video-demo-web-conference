# video-demo-web-conference
使用野狗video sdk建立多人视频通话的示例
## 使用方式：
1. 使用node执行https_channel_server.js：

	node https_channel_server.js

2. 当8080端口没有被占用时，可以在浏览器中输入：https://localhost:8080来访问，如果8080端口被占用了，可以通过修改https_channel_server.js文件来更改demo使用的端口。

<div class="env">
    <p class="env-title">环境准备</p>
    <ul>
        <li>最低支持 Chrome 22、Firefox 23、Safari 11、Edge 15 等主流浏览器环境</li>
    </ul>
</div>

## 创建应用

### 1. 创建应用

首先，在控制面板中创建应用。

<img src="/images/video_quickstart_create.png" alt="video_quickstart_create">

### 2. 开启匿名登录

应用创建成功后，进入 管理应用-身份认证-登录方式，开启匿名登录。

<img src="/images/openanonymous.png" alt="video_quickstart_openanonymous">

### 3. 开启实时视频通话

进入 管理应用-实时视频通话，开启视频通话功能。此处注意记下配置页面的`VideoAppID`

<img src="/images/video_quickstart_openVideo.png" alt="video_quickstart_openVideo">

<blockquote class="notice">
  <p><strong>提示：</strong></p>
  如果之前没有使用过sync服务的需要手动开启
</blockquote>
<img src="/images/opensync.png" alt="video_quickstart_openSync">


## 文档：

[完整文档](https://docs.wilddog.com/conference/Web/index.html)

## 注：
*必须通过启动https服务器来访问页面才可使用，直接打开html无效
