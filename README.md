# DevOps Marketplace

灵感来自
- Backstage
- OAM

Dev + Ops:
- 应用所需的资源也通过spec来定义
    - k8s yaml resource 定义了 cpu 和 memory
    - 更进一步，需要的DB、LB、网络、sidecard也通过spec来定义
- 通过pipeline来provision资源
    - setup a pipeline setup the pipeline，流水线自动化
- module化、marketplace化
    - 可以挑选组合相关服务
    - 返回必要的参数（屏蔽细节
- 多云、多实现桥接


工具化：
go + kotlin
用linuxacademy做测试
- [ ] go + oam 实现资源provision
- [ ] kotlin jenkins 实现marketplace
- [ ] react实现前端
- [ ] 参考blackstage，项目管理（模板 技术栈 tag
向社区化发展（ref to whoisthebest）

# witb - WhoIsTheBest

提供云原生服务的横向比较，来帮助开发者制定技术栈

服务提供者

增删改查服务（描述 文档）
标签（类型 场景 领域 架构 使用模式…）
按标签搜索 聚合
维度评分 评分比较（论坛 豆瓣模式）
审批使用者编辑请求
解决方案聚合

服务使用者

评价服务（打分 评价）
请求编辑（提出请求待审批）

游客

按标签浏览
按相关类型浏览
按相关行业浏览
按解决方案浏览


建模

服务
服务组合（类似商品组合）
标签
解决方案（类似套装）
评论
打分
审批
