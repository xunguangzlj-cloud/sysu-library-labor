# 康乐园手记

[在线游玩](https://xunguangzlj-cloud.github.io/sysu-library-labor/)

在中山大学广州校区南校园图书馆里做半天志愿者。走到集合点签到，在一楼新书库整理错位的书，或去特藏工位为线装古籍轻刷浮尘。也可以先点「进馆漫游」，到三楼窗边看看彩玻台灯下摊开的书。

## 怎么玩

- **开始劳动**　阅读着装与纪律，选择时段和岗位，走近签到牌按 **E**。同一个键也能打开附近的工作台。手机上点画面里的互动提示。
- **顺架**　同层六册书里有三组相邻逆序。从书脊读出索书号，依次点两本相邻的书交换位置，也可以点击对应的编号按钮。
- **扫尘和巡检**　走到古籍台，依次轻刷上沿、中段和下沿。巡检时要逐台走近终端，核对屏幕与记录。签到和终端巡检都是游戏内模拟。
- **移动与视角**　WASD 移动，Shift 跑步，空格跳跃，拖动鼠标环视，滚轮缩放。手机使用摇杆和拖动手势。岗位采用第三人称，漫游时按 V 切换视角。在三楼窗边切到第一人称，可开启「静帧精绘」。

游戏入口是仓库根目录的 `index.html`，引擎、角色、动画和场景资源都在文件内。首次打开需加载约 35 MB。也可下载文件，在支持 WebGL 2 的现代浏览器中离线运行。

## 参考作品与致谢

- **角色与动画**　游戏中的蓝发角色使用《暖光玩具房》网页试玩版中的角色模型、贴图、骨骼和动作。感谢原作制作团队对角色造型、走跑和跳跃动作的创作。[《暖光玩具房》原作试玩](https://v25.dafeiyugame.site/)
- **馆内影像**　感谢 B 站作者**蜡笔小昕阳**拍下三楼窗边的彩玻台灯、红漆阅览桌和窗外树荫，也感谢**青春山河81**记录馆内漫游。两部作品用于对照机位、空间与陈设。[《天堂或许就该是图书馆的样子》](https://www.bilibili.com/video/BV1UTeozCEBr/) · [《带你逛中山大学图书馆~》](https://www.bilibili.com/video/BV14a41147aN/)
- **场景资料**　感谢中山大学图书馆、中山大学新闻网、人民网及中山大学农业与生物技术学院公开馆舍资料、照片和参观记录。馆内空间按公开影像重建，部分劳动工位为玩法模拟布置。[学人文库图集](https://www.sysu.edu.cn/news/info/2171/587861.htm) · [南校园参观记录](https://ab.sysu.edu.cn/zh-hans/article/339) · [特藏厅](https://library.sysu.edu.cn/basic/3743) · [珍藏馆](https://library.sysu.edu.cn/basic/3739)
- **开源工具**　感谢 Three.js、Dimforge 和 Garrett Johnson 及各项目贡献者提供实时渲染、物理碰撞和静帧光线追踪工具。相应开源许可随游戏内嵌。[Three.js](https://github.com/mrdoob/three.js) · [Rapier](https://github.com/dimforge/rapier) · [three-gpu-pathtracer](https://github.com/gkjohnson/three-gpu-pathtracer) · [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh)
