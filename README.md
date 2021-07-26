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