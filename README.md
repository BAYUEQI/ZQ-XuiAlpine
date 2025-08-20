# 3x-ui-alpines项目说明: 
本项目从3x-ui官方版本移植到Alpine系统, 面板功能与官方版本完全一致, 面板使用说明请参考官方文档.
```
https://github.com/MHSanaei/3x-ui
```

# 一键安装
```
apk add curl bash gzip
bash <(curl -Ls https://raw.githubusercontent.com/BAYUEQI/ZQ-XuiAlpine/master/install_alpine.sh)
```
# 官方功能移植列表:
  1. Install - 安装: 已完成(2024/12/16)
  2. Update - 更新: 已完成(2024/12/16)
  3. Update Menu - 更新主菜单: 已完成(2024/12/16)
  4. Legacy Version - 安装指定版本: 已完成(2024/12/16)
  5. Uninstall - 卸载: 已完成(2024/12/16)
  ---
  6. Reset Username & Password & Secret Token - 重置用户名密码: 已完成(2024/12/16)
  7. Reset Web Base Path - 重置面板路径: 已完成(2024/12/16)
  8. Reset Settings  - 重置配置数据(用户名密码和面板路径不变): 已完成(2024/12/16)
  9. Change Port - 重置面板端口: 已完成(2024/12/16)
  10. View Current Settings - 查看服务配置: 已完成(2024/12/16)
  ---
  11. Start - 启动服务: 已完成(2024/12/16)
  12. Stop - 停止服务: 已完成(2024/12/16)
  13. Restart - 重启服务: 已完成(2024/12/16)
  14. Check Status - 查看服务状态: 已完成(2024/12/16)
  15. Logs Management - 查看日志: 开发中......
  ---
  16. Enable Autostart - 设置开机启动: 已完成(2024/12/16)
  17. Disable Autostart - 关闭开机启动: 已完成(2024/12/16)
  ---
  18. SSL Certificate Management - ACME证书管理: 已完成(2024/12/16)
  19. Cloudflare SSL Certificate - Cloudflare证书管理: 已完成(2024/12/16)
  20. IP Limit Management - IP限制管理: 开发中......
  21. Firewall Management - 防火墙管理: 开发中......
  22. SSH Port Forwarding Management - SSH端口转发管理: 开发中......
  ---
  23. Enable BBR - BBR功能: 已完成(2024/12/16)
  24. Update Geo Files - 更新Geo文件: 已完成(2024/12/16)
  25. Speedtest by Ookla - 速度测试(Ookla): 开发中......

## log 2024/12/16
1. 翻译中文菜单
2. 移植部分功能列表
3. 同步官方版本v2.4.9
## log 2024/12/21
1. 同步官方版本v2.4.10
## log 2024/12/28
1. 同步官方版本v2.4.11
2. wget命令删除-N参数
