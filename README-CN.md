# Image Viewer

一个简单的html页面，但是模拟了浏览器原生图片查看的行为。

点击试试吧:

<div style="display: grid; grid-template-columns: repeat(2, minmax(auto, 200px)); gap: 20px; align-self: center;">
    <a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png">
        <img src="https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png">
    </a>
    <a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg">
        <img src="https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg">
    </a>
</div>

页面会从你请求的url的hash中得到图片的src

格式: `https://img-viewer.netlify.app/#${img-src}`
