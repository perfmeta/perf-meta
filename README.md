# 工具介绍
  这是一款专业的性能评测工具，致力帮助行业提供低成本高可用的性能自动化评测算法能力，帮助降低人力成本提升性能评测效率。 
 ![tutieshi_640x360_20s](https://github.com/testly/perf-meta/assets/10202802/b985667c-ac67-469e-b170-e0055b0d6dfc)

# 全景图
 <img width="975" alt="image" src="https://github.com/testly/perf-meta/assets/10202802/11ea23b8-2cf4-4244-884d-a859a71b927a">
 
# 工具示例
![image](https://github.com/testly/perf-meta/assets/10202802/3260fc36-332d-4acd-9a4c-a43562714461)

# 下载地址
### 小工具
Mac 安装包：[链接](https://github.com/testly/perf-meta/blob/main/tools/mac/perf-mac-1119.jar)

Windows 安装包：[链接](https://github.com/testly/perf-meta/blob/main/tools/windows/Perf-1119.exe)


# 线上算法调试
> 可以自己注册， 注册地址：http://console.smart-perf.com/register
调用地址：http://console.smart-perf.com/app/createtask
### 在线DEMO测试
![image](https://github.com/testly/perf-meta/assets/10202802/79e51f00-0a4d-40c0-9b1a-f2710d64ceb8)


### Java Sdk
[demo链接](https://github.com/testly/perf-sdk-demo)

### Python Sdk
[demo链接](待更新)

# 使用说明

### 环境要求
1.确保JAVA环境安装成功，一定要使用官方的JDK 1.8，不要使用其他的版本。

2.确保Android SDK环境安装成功，必须要求ADB环境成功安装

3.确保Scrcpy安装成功（安装请自行百度）

### 自检环境(热心群众本cat贡献)
![Logo](./assets/detectionTool.png)
- 可以检测当前工具是否运行(判断是否后台进程没了) 
- 杀毒软件安装了哪些，是否阻止了exe运行。
- adb和scrcpy是否配置了环境变量，位置在哪里，版本号多少
- JDK版本号和位置(区分是否符合标准的)

### 使用步骤
第一步： 打开工具客户端，连接测试设备
> 也可以使用网页模式，打开浏览器输入：localhost:9420

<img width="1432" alt="image" src="https://github.com/testly/perf-meta/assets/10202802/05b1e1e9-644e-4745-b2d2-29c796c3e6c2">

第二步： 等待任务运行完成
> 等待 1分钟左右
<img width="1418" alt="image" src="https://github.com/testly/perf-meta/assets/10202802/2a12d197-18c0-4592-9dc4-1aa055d4fa6c">


第三步：查看结果，并且校验准确性
> 一般查看识别到的关键帧的前后帧是否加载结束即可
<img width="1418" alt="image" src="https://github.com/testly/perf-meta/assets/10202802/f4dc6d51-2b87-4ec7-9616-72c12e03f3b8">

