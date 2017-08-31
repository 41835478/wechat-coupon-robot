# Morobot 微信优惠券推广机器人

## 使用说明
1. 对应的群需要保存到通讯录
2. 设置`conf.ini`
  - 一般只需要修改robot的内容，具体参考conf.ini中的说明
3. 运行`run.exe`
4. 弹出二维码, 扫描登录即可
5. 程序会隔一段时间检查是否有新数据，添加新数据直接在main.xlsx新行添加

## QA
- 如何重置excel下次开始行号？
  
  删除excel.data文件即可

- 如何修改新成员欢迎信息？
  
  conf.ini中welcome对应的文件，打开修改即可，实时生效

## 注意
- 文件路径,目录尽量不要中文名。
- 对设置的群一定要先保存到通讯录。

## 交流群
QQ: [219974900](https://shang.qq.com/wpa/qunwpa?idkey=b01ae3447f0a9341eb7b13f41ce4ead7fed68a2e6ef79f48c89da96ce8c8a7ed)