# Image Viewer

一个简单的html页面，但是模拟了浏览器原生图片查看的行为。

点击试试吧:

<a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png">
    <img src="https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" style="width: 200px; margin-right: 20px">
</a>
<a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg">
    <img src="https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" style="width: 200px;">
</a>

页面会从你请求的url的hash中得到图片的src

格式: `https://img-viewer.netlify.app/#${img-src}`
