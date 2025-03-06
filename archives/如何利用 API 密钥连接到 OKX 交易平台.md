# 如何利用 API 密钥连接到 OKX 交易平台

本文将详细说明如何利用 API 密钥将您的交易机器人连接到 [OKX官网](https://bit.ly/OKXe)。在使用过程中，确保您的交易账户和资金账户中有足够资金，并且完成了必要的身份认证（KYC）。如果遇到错误，请尝试点击“不进行测试继续”，稍后您仍可在 Base config 中核对您的 API 密钥设置。

---

## API 密钥连接简介

API 密钥就像 Cryptohopper 与您的数字货币交易平台之间的桥梁。借助 API 密钥，机器人可以执行自动下单、读取账户余额等操作。确保 API 密钥配置正确，您就可以体验自动化交易带来的便利和效率。

---

## 使用步骤

### 步骤一：注册 OKX 账户
1. 访问 [OKX官网](https://bit.ly/OKXe)创建账户（如果您尚未注册）。
2. 完成注册后登录 OKX 平台。

### 步骤二：创建 API 密钥
1. 登录后，点击 OKX 仪表盘右上角的个人图标。
2. 在下拉菜单中选择 **API**，进入 API 管理页面。
   
   ![API 创建步骤](https://www.jmhbdh.com/wp-content/img/8429345167.webp)

### 步骤三：配置 API 密钥
1. 在 API 设置页面中，您可以调整各项参数。请务必记住您的密钥密码，这在后续使用中至关重要。
2. 为保证兼容性，确保为 Cryptohopper 启用 **Read** 和 **Trade** 权限，并将 **Withdrawal** 权限保持关闭。
   
   ![API 密钥配置](https://cdn.cryptohopper.com/documentation/OKX2.PNG)
   
   ![权限设置](https://cdn.cryptohopper.com/documentation/OKX3.PNG)

### 步骤四：设置 IP 白名单
1. 新用户在首次使用时，其 IP 地址会在初始界面显示。
2. 对于老用户，请前往 Cryptohopper 账户中的 Base config，点击 “exchange” 选项页，将显示的 IP 地址复制并粘贴至 OKX 的相应输入框中。

### 步骤五：将 API 密钥添加至 Cryptohopper
1. 再次进入 Cryptohopper 账户中的 Base config，并选择 “exchange” 选项页。
2. 选择您的交易平台（OKX），填写 API 密钥信息，并确认填写上步骤三中保存的密钥密码。
3. 系统将自动进行链接，稍作等待后，账户余额便会正确显示。

---

## 常见问题：无法显示交易余额

若您的交易余额未能同步显示，可能的原因包括：
- 浏览器启用了自动填充功能
- 浏览器缓存问题或密码管理器干扰

可尝试以下方法：
- 关闭自动填充
- 使用隐私模式或更换浏览器
- 暂时禁用密码管理器

更多解决方案请参阅 Cryptohopper 的 troubleshooting article。

---

<figure>
  <iframe src="https://www.youtube.com/embed/Noe7V68X3j4" data-aspect-ratio="0.5625"></iframe>
</figure>