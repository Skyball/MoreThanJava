持续整理中....

<p align="center">
  <a href="https://github.com/wmyskxz/MoreThanJava/">
    <img src="/images/README/logo.png" width="400" height="200">
  </a>
</p>
<p align="center">
  <a href="#微信"><img src="https://img.shields.io/badge/WeChat-微信-green.svg" alt="微信"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E6%88%91%E6%B2%A1%E6%9C%89%E4%B8%89%E9%A2%97%E5%BF%83%E8%84%8F-green.svg" alt="公众号"></a>
  <a href="https://www.jianshu.com/u/a40d61a49221"><img src="https://img.shields.io/badge/JianShu-%E7%AE%80%E4%B9%A6-red.svg" alt="简书"></a>
  <a href="https://www.zhihu.com/people/wo-mei-you-san-ke-xin-zang"><img src="https://img.shields.io/badge/Zhihu-%E7%9F%A5%E4%B9%8E-blue.svg" alt="知乎"></a>
  <a href="https://www.cnblogs.com/wmyskxz/"><img src="https://img.shields.io/badge/cnblogs-博客园-important.svg" alt="cnblogs"></a>
  <a href="https://juejin.im/user/5cfb61a36fb9a07ef819ef3a"><img src="https://img.shields.io/badge/JueJin-%E6%8E%98%E9%87%91-blue.svg" alt="掘金"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/Contribute-%E6%8A%95%E7%A8%BF-blue.svg" alt="投稿"></a>
</p>

# 说明

当走出学校，跨入职场，你会发现写代码这件事除了 CODING，还有很多的【认知】需要提升，所以本项目致力于【MORE THAN JAVA】的学习，不仅仅是 CODING，还有很多不止于 CODING 的【知识】。

[公众号](#公众号)和[本项目](https://github.com/wmyskxz/MoreThanJava)保持同步更新，喜欢的小伙伴可以点一波关注，有任何意见 or 建议请[联系我](#微信)，另外觉得卡的朋友也可以访问国内的 [Gitee](https://gitee.com/wmyskxz/MoreThanJava)，**您的[支持](#赞赏)是我前进最大的动力!**

# 目录

- [Part 0.开始之前必读](#part0)
- [Part 1.Java 基础](#part1)
	- [🔥推荐 Java 基础学习教程☕️](#part1-recommend)
	- [Java 高并发学习☕️](#part1-concurrency)
- [Part 2.Java Web](#part2)
	- [Spring 基础学习](#part2-spring)
	- [SpringBoot 学习](#part2-springboot)
- [Part 3. 框架相关](#part3)
	- [Redis 学习](#part3-redis)
- [Part 4.面试宝典](#part4)
	- [Java 面试知识点全解析📒](#part4-java)
	- [数据结构与算法📒](#part4-algorithm)
	- [其他优秀面试宝典收集📒](#part4-other)
	- [正确认识面试👨‍💼](#part4-about-interview)
    - [面试题目库👨‍💼](#part4-interview)
- [Part 5.程序人生](#part5)
- [Part 6.懂一点前端](#part6)
- [Part 7.懂一点Python](#part7)
- [Part 8.有趣集中营](#part8)

<h2 id="part0">Part 0.开始之前必读</h2>

<table width="100%">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">开始之前👨‍💻‍</th>
   </tr>
   <tr>
      <td><a href="https://www.cnblogs.com/ityouknow/p/6871580.html">思维的局限 | 我们为什么需要保持学习</a></td>
      <td><a href="/java-base/「MoreThanJava」当大学选择了计算机之后应该知道的.md">「MoreThanJava」当大学选择了计算机之后应该知道的</a></td>
      <td><a href="/java-base/「MoreThanJava」计算机发展史—从织布机到电脑.md">「MoreThanJava」计算机发展史—从织布机到IBM</a></td>
      <td><a href="/java-base/「MoreThanJava」计算机系统概述.md">「MoreThanJava」计算机系统概述</a></td>
      <td><a href="/java-base/「MoreThanJava」一文了解二进制和CPU工作原理.md">「MoreThanJava」一文了解二进制和CPU工作原理</a></td>
      <td><a href="/java-base/「MoreThanJava」机器指令到汇编再到高级编程语言.md">「MoreThanJava」机器指令到汇编再到高级编程语言</a></td>
   </tr>
   <tr>
      <td><a href="/java-base/「MoreThanJava」Java发展史及起航新世界.md">「MoreThanJava」Java发展史及起航新世界</a></td>
      <td><a href="/java-base/day1.md">「MoreThanJava」Day 1：环境搭建和程序基本结构元素</a></td>
      <td><a href="/java-base/day2.md">「MoreThanJava」Day 2：变量、数据类型和运算符</a></td>
      <td><a href="/java-base/day3.md">「MoreThanJava」Day 3：构建程序逻辑的方法</a></td>
   </tr>
   <tr>
      <td><a href="/java-base/【知乎问答】如何让不懂编程的人感受到编程的魅力.md">【知乎问答】如何让不懂编程的人感受到编程的魅力</a></td>
      <td><a href="/life/记这大半年来的挣扎与迷茫.md">96年/离职8个月/拒绝华为offer/目前自由职业-记这大半年来的挣扎与迷茫</a></td>
   </tr>
</table>


<h2 id="part1">Part 1.Java 基础</h2>

<table width="100%" id="part1-recommend">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">🔥推荐 Java 基础学习教程☕️</th>
   </tr>
   <tr>
      <td><a href="https://study.163.com/course/introduction.htm?courseId=1003108028&_trace_c_p_k2_=5f8d7fd692f34e739aed2915fb939e94">小码哥教育 - 经典免费 Java 零基础入门视频系列教程 | 建议 2 倍速观看</a></td>
      <td><a href="https://how2j.cn/">HOW2J - 项目驱动式 Java 全系列学习</a></td>
      <td><a href="https://www.liaoxuefeng.com/wiki/1252599548343744">廖雪峰 - Java 系列基础教程</a></td>
      <td><a href="https://book.douban.com/subject/30333948/">《码出高效 Java 开发手册》 - 孤尽著</a></td>
      <td><a href="https://book.douban.com/subject/34898994/">《Java 核心技术 卷 Ⅰ》  | 刚入门不建议食用，当参考书用</a></td>
      <td><a href="https://book.douban.com/subject/7059903/">《编写高质量代码》  | 加深对 Java 的认识，对刚入门很有帮助</a></td>
   </tr>
</table>

<table width="100%" id="part1-concurrency">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">Java 高并发学习☕️</th>
   </tr>
   <tr>
      <td><a href="https://www.wmyskxz.com/2019/11/26/gao-bing-fa-bian-cheng-xue-xi-1-bing-fa-ji-chu/">高并发编程学习(1)——并发基础</a></td>
      <td><a href="https://www.wmyskxz.com/2019/11/27/gao-bing-fa-bian-cheng-xue-xi-2-xian-cheng-tong-xin-xiang-jie/">高并发编程学习(2)——线程通信详解</a></td>
   </tr>
</table>

<table width="100%" id="part1-distributed-lock">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">Java 分布式锁☕️</th>
   </tr>
   <tr>
      <td><a href="https://juejin.im/post/5bbb0d8df265da0abd3533a5">再有人问你分布式锁，这篇文章扔给他</a></td>
   </tr>
</table>


<h2 id="part2">Part 2.Java Web</h2>

<table width="100%" id="part2-spring">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">Spring 框架基础🍃</th>
   </tr>
   <tr>
      <td><a href="https://www.wmyskxz.com/2018/04/10/spring-xue-xi-1-kuai-su-ru-men/">Spring学习（1）——快速入门</a></td>
      <td><a href="https://www.wmyskxz.com/2018/04/11/spring-xue-xi-2-spring-ioc-xiang-jie/">Spring学习（2）——Spring IoC详解</a></td>
      <td><a href="https://www.wmyskxz.com/2018/04/12/spring-xue-xi-3-zhuang-pei-spring-bean-xiang-jie/">Spring学习（3）——装配Spring Bean详解</a></td>
      <td><a href="https://www.wmyskxz.com/2018/04/12/spring-xue-xi-4-mian-xiang-qie-mian-bian-cheng-aop-mo-kuai/">Spring学习（4）——面向切面编程（AOP模块）</a></td>
      <td><a href="https://www.wmyskxz.com/2018/04/12/spring-xue-xi-5-spring-he-shu-ju-ku-bian-cheng/">Spring学习（5）——Spring和数据库编程</a></td>
      <td><a href="https://www.wmyskxz.com/2018/04/18/mybatis-yu-spring-zheng-he/">MyBatis与Spring整合</a></td>
   </tr>
  <tr>
    <td><a href="https://www.wmyskxz.com/2019/01/05/spring-data-jpa-chang-xian-kuai-su-da-jian-crud-fen-ye-hou-tai-shi-li/">Spring-Data-JPA尝鲜：快速搭建CRUD+分页后台实例</a></td>
  </tr>
</table>


<table width="100%" id="part2-springboot">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">SpringBoot 学习🌿</th>
   </tr>
   <tr>
      <td><a href="https://www.wmyskxz.com/2018/05/08/spring-boot-kuai-su-ru-men/">🔥Spring Boot【快速入门】</a></td>
   </tr>
</table>

<h2 id="part3">Part 3. 框架相关</h2>

<table width="100%" id="part3-redis">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae" data="875942250">Redis 系列☑️</th>
   </tr>
   <tr>
      <td><a href="https://www.wmyskxz.com/2020/02/28/redis-1-5-chong-ji-ben-shu-ju-jie-gou/">Redis(1)——5种基本数据结构</a></td>
     <td><a href="https://www.wmyskxz.com/2020/02/ 29/redis-2-tiao-yue-biao/">Redis(2)——跳跃表</a></td>
     <td><a href="https://www.wmyskxz.com/2020/03/01/redis-3/">Redis(3)——分布式锁深入探索</a></td>
     <td><a href="https://www.wmyskxz.com/2020/03/02/reids-4-shen-qi-de-hyperloglog-jie-jue-tong-ji-wen-ti/">Reids(4)——神奇的HyperLoglog解决统计问题</a></td>
     <td><a href="https://www.wmyskxz.com/2020/03/11/redis-5-yi-ji-shu-ju-guo-lu-he-bu-long-guo-lu-qi/">Redis(5)——亿级数据过滤和布隆过滤器</a></td>
     <td><a href="https://www.wmyskxz.com/2020/03/12/redis-6-geohash-cha-zhao-fu-jin-de-ren/">Redis(6)——GeoHash查找附近的人</a></td>
   </tr>
     <tr>
      <td><a href="https://www.wmyskxz.com/2020/03/13/redis-7-chi-jiu-hua-yi-wen-liao-jie/">Redis(7)——持久化【一文了解】</a></td>
       <td><a href="https://www.wmyskxz.com/2020/03/15/redis-8-fa-bu-ding-yue-yu-stream/">Redis(8)——发布/订阅与Stream</a></td>
       <td>Redis(9)——主从复制(待更新..)</td>
       <td>Redis(10)——高性能原因分析(待更新..)</td>
       <td>Redis面试指南(待更新..)</td>
   </tr>
</table>



<h2 id="part4">Part 4.面试宝典</h2>

<table width="100%" id="part4-java">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">Java 面试知识点全解析📒</th>
   </tr>
   <tr>
      <td><a href="https://www.wmyskxz.com/2018/05/09/java-mian-shi-zhi-shi-dian-jie-xi-yi-ji-chu-zhi-shi-pian/#toc-heading-20">Java面试知识点解析(一)——基础知识篇</a></td>
      <td><a href="https://www.wmyskxz.com/2018/05/10/java-mian-shi-zhi-shi-dian-jie-xi-er-gao-bing-fa-bian-cheng-pian/">Java面试知识点解析(二)——高并发编程篇</a></td>
      <td><a href="https://www.wmyskxz.com/2018/05/16/java-mian-shi-zhi-shi-dian-jie-xi-san-jvm-pian/">Java面试知识点解析(三)——JVM篇</a></td>
      <td><a href="https://www.wmyskxz.com/2018/05/17/java-mian-shi-zhi-shi-dian-jie-xi-si-ban-ben-te-xing-pian/">Java面试知识点解析(四)——版本特性篇</a></td>
      <td><a href="https://www.wmyskxz.com/2018/05/18/java-mian-shi-zhi-shi-dian-jie-xi-wu-wang-luo-xie-yi-pian/">Java面试知识点解析(五)——网络协议篇</a></td>
      <td><a href="https://www.wmyskxz.com/2018/05/21/java-mian-shi-zhi-shi-dian-jie-xi-liu-shu-ju-ku-pian/">Java面试知识点解析(六)——数据库篇</a></td>
   </tr>
  <tr>
    <td><a href="https://www.wmyskxz.com/2018/05/22/java-mian-shi-zhi-shi-dian-jie-xi-qi-web-pian/">Java面试知识点解析(七)——Web篇</a></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


<table width="100%" id="part4-algorithm">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">数据结构与算法📒</th>
   </tr>
   <tr>
     <td><a href="https://leetcode-cn.com/">LeetCode | 刷题必备</a></td>
      <td><a href="https://www.wmyskxz.com/2018/07/02/shu-ju-jie-gou-yu-suan-fa-1-shu-zu-yu-lian-biao/">数据结构与算法(1)——数组与链表</a></td>
      <td><a href="https://www.wmyskxz.com/2018/07/06/shu-ju-jie-gou-yu-suan-fa-2-zhan-he-dui-lie/">数据结构与算法(2)——栈和队列</a></td>
      <td><a href="https://www.wmyskxz.com/2018/07/11/shu-ju-jie-gou-yu-suan-fa-3-shu-er-cha-er-cha-sou-suo-shu/">数据结构与算法(3)——树（二叉、二叉搜索树）</a></td>
      <td><a href="https://www.wmyskxz.com/2018/07/12/shu-ju-jie-gou-yu-suan-fa-4-you-xian-dui-lie-he-dui/">数据结构与算法(4)——优先队列和堆</a></td>
   </tr>
</table>


<table width="100%" id="part4-other">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">其他优秀面试宝典收集📒</th>
   </tr>
   <tr>
      <td><a href="https://github.com/ZhongFuCheng3y/3y">Java3y | Java后端必备知识点</a></td>
      <td><a href="https://github.com/AobingJava/JavaFamily">JavaFamily | 互联网一线大场面试 + 学习指南</a></td>
      <td><a href="https://github.com/Snailclimb/JavaGuide">JavaGuide | Java学习 + 面试指南</a></td>
      <td><a href="https://github.com/yifeikong/reverse-interview-zh">技术面试最后反问面试官的话</a></td>
      <td><a href="https://www.nowcoder.com/discuss?type=2&order=0">牛客网 | 一线笔经面经</a></td>
      <td><a href="https://www.wmyskxz.com/2018/07/28/java-ji-he-bi-hui-14-wen-jing-xuan-mian-shi-ti-zheng-li/">Java集合必会14问(精选面试题整理)</a></td>
   </tr>
     <tr>
      <td><a href="https://www.wmyskxz.com/2018/08/15/java-i-o-bu-mi-mang-yi-wen-wei-nin-dao-hang/">Java I/O不迷茫，一文为您导航！</a></td>
      <td><a href="https://www.wmyskxz.com/2018/08/26/mian-shi-bi-bei-shou-si-dai-ma-ni-pa-bu-pa/">【面试必备】手撕代码，你怕不怕？</a></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
</table>

<table width="100%" id="part4-about-interview">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">正确认识面试👨‍💼</th>
   </tr>
   <tr>
      <td><a href="https://www.zhihu.com/question/306398832/answer/619633924">面试都有哪些面试技巧？ - 知乎 | @思宇爱读册</a></td>
</table>

<table width="100%" id="part4-interview">
   <tr align="center">
      <th colspan="6" style="background-color: #96a6ae">面试题目库👨‍💼</th>
   </tr>
   <tr>
      <td><a href="/interview/【转载】面试问我，创建多少个线程合适？我该怎么说.md">【转载】面试问我，创建多少个线程合适？我该怎么说</a></td>
</table>

<h2 id="part5">Part 5.程序人生</h2>

<h2 id="part6">Part 6.懂一点前端</h2>

- [懂一点前端——Vue快速入门](https://www.wmyskxz.com/2020/03/30/dong-yi-dian-qian-duan-vue-kuai-su-ru-men/)
 
<h2 id="part7">Part 7.懂一点Python</h2>

- [懂一点Python系列——快速入门](https://www.wmyskxz.com/2020/03/23/dong-yi-dian-python-xi-lie-kuai-su-ru-men/ø)

<h2 id="part8">Part 8.有趣集中营</h2>

- [扫地僧回来了](https://mp.weixin.qq.com/s/dFnkLelQBuGaL_mlMUcpeA)
- [面向对象圣经](https://mp.weixin.qq.com/s/TfcEzFN3HD3zV8PsjbM2KA)


