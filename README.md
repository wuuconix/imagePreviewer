# Image Viewer

[![Netlify Status](https://api.netlify.com/api/v1/badges/bba5e439-2e82-4b43-af18-164f23fd3617/deploy-status)](https://app.netlify.com/sites/img-viewer/deploys)

[中文说明](./README-CN.md)

an simple html page simulating browser native image viewer

click and try:

<a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2022/05/14/02/00/17/98325199_p0.png" target="_blank">
    <img src="./assets/98325199_p0.png" style="width: 200px; margin-right: 20px">
</a>
<a href="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" title="https://img-viewer.netlify.app/#https://i.pixiv.re/img-original/img/2021/11/12/20/22/55/91752738_p0.jpg" target="_blank">
    <img src="./assets/91752738_p0.jpg" style="width: 200px;">
</a>

the site will get the img src from the hash in the url you request.

format: `https://img-viewer.netlify.app/#${img-src}`