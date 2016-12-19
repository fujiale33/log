做一个检查每天销量的和排名的脚本
- [ ] 软件测试视频课程视频转文字
- [x] 做一个查死链的自动化测试脚本  
  做出了一个 links.html 脚本，能够把页面上的所有链接信息打印出来，剩下只要 open URL 就可以了。唯一需要考虑和完善的地方是，open URL 之后，这个页面是否能打开 404 错误信息，如何获取。如果这个 404 页面是个定制的，是不是页面的 title 中有 404 的字样，这样就好验证了。在 while 循环中 open URL 之后，检查 title 中的 404，然后再 open 下一个 URL 即可。 
- [ ] 研究 Selenium Builder 考虑是否能开出一门课程  
  Selenium Builder 功能比 Selenium 提升不少，支持 Github 存放脚本代码，导出格式支持 node.js 的 web driver 代码，甚至 json 格式的自动化脚本。录制脚本差不多，录制之后，没有跑脚本，因为，跑脚本都是在 Selenium Server 上跑，没有搭建 Selenium Server 环境，所以没有跑成。这些功能的设计和体现，都说明 Selenium Builder 面对的问题比 Selenium 更复杂，更专业。
- [ ] 研究并搭建 Selenium Server 环境
- [ ] 研究 seLite 考虑是否能开出一门课程   
  seLite 是 Selenium + SQLite，组件太过过于复杂。貌似已经停止维护了。
- [ ] 软件测试书在淘宝上找电子版
- [ ] 翻译 Selenium 官方资料 Test Pattern Design，考虑是否能开出一门课程
- [ ] 完善 Selenium IDE web 自动化测试课程的作业任务
- [ ] 制作 Github 开源社区之旅启程课程
- [ ] 制作 vimperator 高效上网课程
- [ ] 制作 ProcessOn 网站的脚本
- [ ] Selenium IDE 的其他组件可以继续研究测试一下
- [ ] node + webdriver 研究一下
- [ ] 完善各门课程简介
- [ ] 考虑制作 processOn 综合案例自动化测试脚本，开一门综合案例讲解的课程
- [ ] 整理一下 Selenium IDE 最佳实践之类的资料，可以开一门课程
- [ ] python + webdriver 解决作业评判问题
- [x] 完成 2.6 数组学习
- [x] 完成 2.5 对象学习
- [x] 完成 2.4 字符串学习
- [x] 完成 2.3 数值学习
- [x] 完成 2.2 数据类型学习
- [x] 完成 2.1 基本语法学习
- [x] 整理了配置测试的课堂练习
- [x] var b = 3 和 b = 3 两个等价，改一下脚本测试一下  
    没有问题，确实等价。问题是，这两个的差别是什么？搞明白了，delete 操作的行为不同。看来在 Selenium IDE 中应该不加 var。
