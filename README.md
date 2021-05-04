# SSR节点列表生成器
> 适配ios版shadowrocket，PC或Mac版小飞机,

## 说明
- `/dist `位节点生成的目录,这个目录是给[netlify](https://app.netlify.com/)应用的
- `node.txt`为SSR节点列表文件(支持类bash脚本注释，举个栗子: `# 注释`)
- `app.js`为项目的核心逻辑
## 操作
- 1.将此库设置为模板
- 2.利用此模板创建库，关键参数：项目名根据个人喜好重命名，并将库设置成私有库。
- 3.建库成功后，将个人ss、ssr、V2ray等Vpn链接粘贴在文本`node.txt`中，格式每条用“，”号或“换行”隔开。
- 4.点击[netlify](https://app.netlify.com/)，并通过GitHub账户关联注册，进入托管程序。
- 5.新建项目，并将github库中的对应库托管到该网站。
- 6.托管成功后记下对应的二级域名即可，此域名链接便是个人私密订阅地址。

如果你有什么问题，Please open an issues


