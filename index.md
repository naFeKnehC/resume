### github 预览

https://github.com/naFeKnehC/resume

# 个人信息

- 陈克凡/男/1998
- 本科/武汉工程大学邮电与信息工程学院
- 工作年限: 4 年
- 手机号: 13277067020
- 邮箱: 1037279223@qq.com

# 个人优势

- 负责组员代码 cr，具有良好的编码习惯
- 基于 antd 的组件二次封装，复杂业务组件封装，代码量减半
- react 深入理解与使用
  - 简化版 react github [https://github.com/naFeKnehC/mini-react](https://github.com/naFeKnehC/mini-react)
- 业务理解/合作能力出色，在职期间负责多名应届生成长
- 良好的业务代码拆分/预判能力，迭代工时缩减
- 新技术敏感
  - 22 年 GPT3 时期个人接入 openai [https://github.com/naFeKnehC/thinking](https://github.com/naFeKnehC/thinking)
- 历史个人创业项目：[https://easychat.site/webApp/#/chat](https://easychat.site/webApp/#/chat)

# 工作经历

## 睿唛科技（ 2024 年 6 月 ~ 2025 年 3 月 ）

技术栈: React + AntdPro + ProComponents + wx小程序(Taro)

### 新房通 pc 版

- 项目从 0 ～ 1 搭建，调研框架选用 Ant Design Pro，总工时减少 2 个月
- 复杂业务：部门员工组件开发，前团队耗时 1 月，独立耗时 2 周
- 交易/楼盘/作业 业务独立负责
  - 同一类型业务如订单选择/楼盘选择等业务组件抽离，首次开发速度/维护成本降低
- 组件二次开发封装，图片上传/可编辑表格/地图...等，对比原业务组件掉用代码量减少 50%
- 使用 generate-api-type 自动生成接口文件定义，请求出入参通用类封装

### 新房通 weChat 版

- 项目从 0 ～ 1 搭建，选型使用 Taro
- 独立负责交易，楼盘业务
- 文件上传组件优化，掉用代码减少 70%，增加日志监控，解决用户经常反馈的图片上传失败问题
- 自定义 tabbar 切换异常问题解决

## 数字马力 （ 2023 年 7 月 ~ 2024 年 5 月 ）

### 支付宝小程序

技术栈: 内部框架（类 vue）

负责业务沟通项目排期 涉及小程序：零工卡/蓝领阵地/医疗健康/ai 智能医疗

- 三环组件库开发/优化：feeds 流/角标/引导小黑条等
- 页面插件化，降低发版风险：零工卡/国家医保局 api 自建
- 动作队列：进入小程序首页时根据不同用户可能展示不同动作，纯逻辑判断比较费力，通过队列与绑定的 key 快速切换解除逻辑耦合性
- 支付宝图表封装：结合 antv-f2 封装支付宝小程序内可用的可视化组件，通过双 node 进程与 babel 降级，监听小程序内的 jsx 修改同时降级编译

## 螳螂科技 （ 2021 年 7 月 ~ 2023 年 2 月 ）

技术栈: React + Redux + Antd + wx小程序(Taro)

### 成人教育系统

- 系统 react antd 版本升级 日常迭代 常用组件、函数封装
- 考试流程：试卷组题 考前人脸验证 考中监考 考中答题流程
- 前端实现 pdf 单条与批量导出
- 前端实现用户自定义拖拽拼接图片数据组件 实现录取通知书预览并短信发送给学员在手机上浏览
- 根据不同链接动态生成二维码下载移动端预览
- 页面组织结构拆分 将查询区域 操作区域 列表区分离 列表高度自定计算自带分页 代码量减半
