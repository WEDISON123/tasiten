# 塔斯汀小程序模仿项目
- 本项目归塔斯汀所有，只做学习所用，请尊重原创

- fiddler 抓包工具抓取图片

- 界面模仿采用Markman做标记
  1. 我们没有设计稿，如何1:1还原小程序？
  2. 拍屏得到小程序截图
  3. 使用在线格式大小[转换工具](https://www.gaitubao.com/)，将图片改成750px,以后再写wxss的时候，直接量像素就可以写进去，因为小程序以750rpx作为像素稿标准大小帮我们自动适配，很好用。
  4. 使用[markman](http://getmarkman.com/)先标注，再写样式。
  
- 项目配置在根目录app.json
  - 隐藏并定制navigationBar
  "navigationStyle": "custom"
  - 启动定位功能
  
- 使用了BEM国际css命名规范
  tst_banners 广告位 block
  tst_banners__img Element

- css 技巧
  1. 能不用定位就不用定位
    脱离文档流  计算位置，性能差
  2. 移动端多用弹性布局

- git 提交
  1. 第一次提交
  全局配置  git config --global user.name "WEDISON123"
  git config --global user.email "1651497852@qq.com"
