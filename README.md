# hacktiv8
hacktiv8（原项目名：A5_Bypass_OSS）是一款开源研究类项目
依托 itunesstored 沙盒逃逸漏洞
对老旧 iOS 设备激活机制进行研究与实操调试
无需越狱，即可跨平台一键完成老旧苹果设备绕激活操作

## 免责声明
本项目仅用于学术研究与技术学习交流
严禁用于商业用途及各类违规非法行为
项目作者与所有贡献者
不对任何设备损坏、数据丢失以及违规使用造成的一切后果承担任何责任

## 使用要求
操作全程请保证设备稳定连接无线网络
网络正常连通是工具正常运行的必要条件

## 兼容设备
支持全系 A5、A6 架构苹果设备
适配系统版本：iOS 10.3.4、iOS 10.3.3、iOS 9.3.6、iOS 9.3.5
无线局域网版设备额外兼容 iOS 8.4.1

## 后端配置
后端接口地址可在 main.py 文件内的 BACKEND_URL 常量中自行修改
由于老旧 iOS 系统不兼容现代主流 SSL 证书机构证书
后端服务建议使用 HTTP 协议部署
若使用 HTTPS，需配置老旧系统可信任的根证书链
Let's Encrypt 等新式证书在低版本 iOS 中无法正常授信
会直接导致网络请求失败

## 项目致谢
- [pkkf5673](https://github.com/bablaerrr)
- [bl_sbx](https://github.com/hanakim3945/bl_sbx)
- [pymobiledevice3](https://github.com/doronz88/pymobiledevice3)

## 编译与分发
项目开源协议：MIT License
源码原作者：[overcast302](https://github.com/overcast302)
程序编译打包：[yingna2](https://github.com/yingna2)
遵循开源协议前提下，可自由二次编译、免费分享分发
分发时请保留原项目版权与开源协议文件

## 开源协议
详细授权条例请查看项目内 LICENSE 许可证文件
