# Gradient network 挂机脚本

- 项目地址：[https://app.gradient.network/](https://app.gradient.network/signup?code=EK8G9A)
- 购买代理IP：[https://app.proxy-cheap.com](https://app.proxy-cheap.com/r/ksvW8Z)
- 使用文档：<https://mirror.xyz/0xe8224b3E9C8d35b34D088BB5A216B733a5A6D9EA/jFFUw6Ew3rWThwMxXMoLaa1UMnV8axoQoMVN0EKEthY>
- TG: <https://t.me/web3bothub>

## 环境要求

- Node.js 版本 >= 16.x
- MongoDB 版本 >= 5.0
- PM2 (全局安装)

## 本地安装步骤

1. 安装 Node.js
   - 从 [Node.js 官网](https://nodejs.org/) 下载并安装 Node.js 16.x 或更高版本

2. 安装 MongoDB
   - 从 [MongoDB 官网](https://www.mongodb.com/try/download/community) 下载并安装 MongoDB 5.0 或更高版本
   - 确保 MongoDB 服务已启动

3. 安装 PM2
```bash
npm install pm2 -g
```

4. 安装项目依赖
```bash
npm install
```

5. 创建并配置 .env 文件
```bash
cp .env.example .env
```
然后编辑 .env 文件，填入您的账号信息：
```
APP_USER=user@mail.com
APP_PASS=password
```

6. 配置代理（可选）
   将代理地址保存到 `proxies.txt` 文件中，格式为：
   > socks5://username:password@proxyhost:port

7. 启动项目
```bash
node start.js
```

## 代理配置说明

项目支持使用 SOCKS5 代理。如需使用代理，请按以下步骤操作：

1. 在项目根目录创建 `proxies.txt` 文件
2. 每行添加一个代理地址，格式如下：
   ```
   socks5://username:password@proxyhost:port
   ```
   
   示例：
   ```
   socks5://user123:pass456@proxy1.example.com:1080
   socks5://admin:secret@proxy2.example.com:1080
   ```

3. 启动项目后，系统会自动为每个代理创建独立的实例

注意：
- 每个代理地址占一行
- 确保代理格式正确
- 如果不需要代理，可以不创建 proxies.txt 文件

## 常用命令

### 查看运行日志
```bash
pm2 logs
```

### 停止服务
```bash
pm2 stop all
```

### 重启服务
```bash
pm2 restart all
```

### 查看服务状态
```bash
pm2 status
```

## Note

- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

## Contribution

Feel free to contribute to this project by creating a pull request.

## Support Me

if you want to support me, you can donate to my address:

- TRC20: `TMwJhT5iCsQAfmRRKmAfasAXRaUhPWTSCE`
- ERC20: `0xa2f5b8d9689d20d452c5340745a9a2c0104c40de`
- SOLANA: `HCbbrqD9Xvfqx7nWjNPaejYDtXFp4iY8PT7F4i8PpE5K`
- TON: `UQBD-ms1jA9cmoo8O39BXI6jqh8zwRSoBMUAl4yjEPKD6ata`
