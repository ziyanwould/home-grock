# 🏠 Home Grock

> 一个帮我省钱、早日上岸的工具
>
> 从"药品批量过期"到"提前用完不浪费"
> 从"不知道欠多少"到"清楚还有多少期"

## 💡 为什么做这个？

### 痛点1：物品总是浪费钱 😭

我之前的问题：
- **药品囤太多**：感冒药、创可贴、维生素...结果批量过期，扔掉几百块
- **厨房调料过期**：蚝油、豆瓣酱买了忘记用，半年后发霉了
- **重复购买**：家里明明有，出去又买了一瓶，浪费钱
- **冲动消费**：看到打折就囤货，结果用不完

**每个月光这些浪费，就要损失好几百。**

### 痛点2：债务压力大 😰

同时我还有债务：
- 3张信用卡分期
- 花呗、白条
- 每个月不知道要还多少钱
- 不知道什么时候能还完

**每月工资一发，还完债、再扔掉过期的东西，就所剩无几了。**

### 解决方案 💡

我做了这个工具，帮自己：

**物品管理** - 避免浪费
- ✅ 扫码记录家里所有东西（药品、调料、食材）
- ✅ 快过期自动提醒（提前用掉，不浪费）
- ✅ 买之前先查一下（避免重复购买）
- ✅ AI识别小票（超市购物一键导入）

**财务管理** - 早日上岸
- ✅ 理清所有债务（一共欠多少？每月要还多少？）
- ✅ 自动生成还款计划（什么时候能还完？）
- ✅ 提前还款计算（能省多少利息？）
- ✅ 记账分析（钱都花哪了？哪些可以省？）

**结果：省钱 + 还债 = 早日上岸**

现在几个同学同事也在用，他们说确实减少了很多浪费。

---

## 😫 你是不是也有这些问题？

### 药品管理痛点

<table>
<tr>
<td width="50%">

#### 😭 之前

- 感冒药买了好几盒，放在不同地方
- 等要用的时候找不到，又去买
- 某天大扫除，发现一堆过期药
- **几百块就这样扔掉了**

</td>
<td width="50%">

#### 😊 现在

- 买了就扫码记录，放哪都知道
- 快过期提前7天提醒
- 买之前查一下，家里有就不买了
- **再也没扔过过期药**

</td>
</tr>
</table>

### 厨房用品痛点

<table>
<tr>
<td width="50%">

#### 😭 之前

- 调料瓶太多，不知道有什么
- 蚝油、豆瓣酱开了忘记用
- 酱油买了3瓶，结果2瓶过期
- **每次都是批量过期，很心痛**

</td>
<td width="50%">

#### 😊 现在

- 所有调料扫码录入
- 快过期提前提醒（该用这个了！）
- 买之前查库存（家里还有2瓶呢）
- **半年没扔过过期调料了**

</td>
</tr>
</table>

### 债务管理痛点

<table>
<tr>
<td width="50%">

#### 😭 之前

- 信用卡、花呗、白条...搞不清
- 不知道每月要还多少
- 不知道什么时候能还完
- **有时候还错、还漏，逾期罚款**

</td>
<td width="50%">

#### 😊 现在

- 所有债务清清楚楚
- 自动生成还款计划
- 每月提前提醒还款
- **知道再有18个月就能还完了！**

</td>
</tr>
</table>

---

## ✨ 核心功能

### 📦 物品管理 - 扫码记录，避免浪费

<div align="center">
  <img src="screenshots/home-dashboard.png" width="280" alt="首页">
  <img src="screenshots/item-list.png" width="280" alt="物品列表">
  <img src="screenshots/item-detail.png" width="280" alt="物品详情">
</div>

<div align="center">
  <img src="screenshots/add-item.png" width="280" alt="添加物品">
</div>

```
买东西 → 扫条码 → AI识别 → 自动记录 → 快过期提醒 → 及时用掉
```

**支持识别**：
- 商品条形码（超市购物扫码）
- 药品追溯码（药品专用码）
- AI拍照识别（没有条码也能识别）
- 小票批量导入（超市小票拍照自动提取）

### 🔍 扫码识别 - 一扫即录

<div align="center">
  <img src="screenshots/scan-barcode.png" width="280" alt="扫码识别">
  <img src="screenshots/scan-barcode2.png" width="280" alt="扫码结果">
  <img src="screenshots/ai-recognition.png" width="280" alt="AI识别结果">
</div>

```
打开扫码 → 对准条码 → 自动识别 → 填充信息 → 保存
```

### 🤖 AI过期提醒 - 再也不浪费

<div align="center">
  <img src="screenshots/expiring-items.png" width="280" alt="AI过期提醒">
  <img src="screenshots/stats-overview.png" width="280" alt="智能仓库">
</div>

- AI智能提醒（告诉你哪些物品快过期了）
- AI购物建议（根据库存给出建议）
- 智能仓库分析（物品分布、分类统计）

### 💰 财务记账 - AI识别，自动分类

<div align="center">
  <img src="screenshots/billing-dashboard.png" width="280" alt="财务首页">
  <img src="screenshots/ocr-receipt.png" width="280" alt="AI识别">
  <img src="screenshots/billing-analysis.png" width="280" alt="财务报表">
</div>

```
拍小票 → AI识别 → 自动导入 → 智能分类 → 查看分析 → 找出浪费
```

**支持导入**：
- AI小票识别（拍照自动提取）
- 微信账单导入（CSV文件）
- 支付宝账单导入（CSV文件）
- 手动记账（快捷输入）

### 📊 债务管理 - 理清欠款，早日上岸

<div align="center">
  <img src="screenshots/debt-overview.png" width="280" alt="财务分析">
  <img src="screenshots/loan-detail.png" width="280" alt="贷款详情">
  <img src="screenshots/repayment-plan.png" width="280" alt="还款计划">
</div>

<div align="center">
  <img src="screenshots/prepayment-calc.png" width="280" alt="提前还款计算">
</div>

```
记录贷款 → 自动生成还款计划 → 每月提醒 → 提前还款计算 → 优化策略
```

**支持债务类型**：
- 信用卡分期
- 花呗、白条、借呗
- 房贷、车贷
- 消费贷、现金贷

**支持还款方式**：
- 等额本息（房贷常用）
- 等本等息（信用卡分期）
- 等额本金（银行贷款）
- 先息后本（短期贷款）
- 到期还本付息
- 灵活还款

### 📈 现金流预测 - 避免断流

<div align="center">
  <img src="screenshots/cashflow-forecast.png" width="280" alt="现金流预测">
  <img src="screenshots/transaction-list.png" width="280" alt="交易详情">
</div>

- 推演未来12个月现金流
- 提前预警资金缺口
- 每月收入、支出、还款一目了然

### 🗂️ 更多功能

<div align="center">
  <img src="screenshots/inventory-check.png" width="280" alt="资产盘点">
  <img src="screenshots/print-label.png" width="280" alt="标签生成">
  <img src="screenshots/family-members.png" width="280" alt="家庭成员">
</div>

- **资产盘点**：年终大扫除，扫码确认，自动对比差异
- **标签生成**：批量生成二维码标签，贴在物品上方便管理
  - 每个物品都有唯一二维码
  - 扫码即可查看物品详情
  - 支持批量生成和打印
- **家庭协作**：邀请家人一起管理，数据共享

### 📱 物资二维码

<div align="center">
  <img src="screenshots/product-qrcode.jpg" width="200" alt="物资二维码">
  <p><strong>👆 物品标签示例</strong></p>
</div>

每个物品都有独一无二的二维码，扫一扫就能看到：
- 物品名称、分类、位置
- 购买日期、过期日期
- 数量、单价、总价
- 保存记录、编辑物品

---

## 🎉 真实用户故事

### 故事1：一年省出3000块

**用户**：小李，27岁，上海，程序员

**使用前**：
- 药品、调料经常过期，每月浪费200+
- 重复购买，每月浪费100+
- 冲动消费，每月浪费300+
- **每月至少浪费600块**

**使用后**：
- 扫码记录所有物品，过期提醒
- 买之前先查库存
- 消费前看分析报表
- **每月减少浪费500块**

**一年成果**：省了6000块，还清了一半的花呗

### 故事2：18个月还清所有债务

**用户**：小张，30岁，广州，设计师

**债务情况**：
- 招行信用卡：¥20,000，12期
- 花呗：¥8,000
- 京东白条：¥5,000
- **总负债：¥33,000**

**使用前**：
- 不知道总共欠多少
- 不知道每月要还多少
- 经常忘记还款，逾期罚款

**使用后**：
- 清楚看到总负债和还款计划
- 每月提醒，从不逾期
- 通过省钱加速还款
- **按时还款18个月全部还清**

**额外收获**：提前还款省了¥2,000利息

---

## 🚀 如何使用？

### 微信小程序（推荐）

<div align="center">
  <img src="screenshots/wechat-qrcode.jpg" width="200" alt="微信小程序二维码">
  <p><strong>👆 用微信扫一扫</strong></p>
</div>

```
扫码 → 授权登录 → 立即开始
```

**优势**：
- 随时随地使用
- 手机扫码很方便
- 无需安装 App
- 自动保存数据到云端

### Web管理后台

🔗 https://web.home-grock.com

**优势**：大屏幕操作，数据分析更强大

**登录方式**：
- 🔐 账号密码登录
- 📱 小程序扫码登录（推荐，无需记密码）

<div align="center">
  <img src="screenshots/web-dashboard.png" width="400" alt="Web管理后台首页">
  <img src="screenshots/web-item-list.png" width="400" alt="Web物品列表">
  <img src="screenshots/web-expiring-reminder.png" width="400" alt="Web过期提醒">
</div>

<div align="center">
  <img src="screenshots/web-shopping-list.png" width="400" alt="Web购物清单">
  <img src="screenshots/web-archived-items.png" width="400" alt="Web归档物品">
  <img src="screenshots/web-billing-analysis.png" width="400" alt="Web财务分析">
</div>

<div align="center">
  <img src="screenshots/web-login-qrcode.png" width="400" alt="Web扫码登录">
  <p>👆 用小程序扫二维码，一键登录 Web 管理后台</p>
</div>

---

## 📚 使用指南

### 新手入门

- [3分钟快速上手](docs/guides/quick-start.md)
- [物品管理指南](docs/guides/item-management.md) - 如何扫码记录物品
- [债务管理指南](docs/guides/debt-management.md) - 如何理清债务

### 常见问题

有问题？欢迎 [提 Issue](https://github.com/你的用户名/home-grock/issues) 或加入讨论！

---

## 💰 完全免费

这个项目是我自己用的，顺便开放给大家。

**完全免费，没有广告，数据私密。**

只要服务器能承受，就一直免费下去。

---

## 🔐 数据安全

### 你的数据完全私密

- ✅ 所有数据加密存储
- ✅ 不会分享给任何第三方
- ✅ 不会用于广告或其他商业目的
- ✅ 可以随时导出和删除数据

### 我们不收集什么

- ❌ 不收集真实姓名
- ❌ 不收集银行卡号
- ❌ 不收集身份证号
- ❌ 不收集位置信息

### 未来计划

会提供Docker镜像，你可以：
- 在自己服务器上运行
- 数据完全在自己手里
- 不依赖我的服务器

---

## 🤝 反馈和建议

如果你在用这个工具，欢迎：
- 提Issue反馈问题
- 提建议（你希望有什么功能？）
- 分享你的使用经验

---

## 🗺️ 产品路线图

### ✅ 已实现（v3.0）

- [x] 扫码识别物品（条码、二维码、药品追溯码）
- [x] AI小票识别（拍照自动提取商品）
- [x] 过期提醒（提前7/3/1天提醒）
- [x] 债务管理（6种还款方式）
- [x] 智能记账（AI自动分类）
- [x] 现金流预测（未来12个月预测）
- [x] 资产盘点（年终大扫除）

### 🚀 进行中（2026 Q1）

- [ ] 食谱推荐（根据快过期食材推荐菜谱）
- [ ] 智能购物清单（缺什么自动提醒）
- [ ] 家庭成员权限管理（协同管理）
- [ ] 数据导出（Excel/PDF报表）

### 💡 计划中（投票决定）

1. **食谱推荐** - AI根据快过期食材推荐菜谱
2. **采购提醒** - 常用物品快用完自动提醒
3. **闲置变现** - 闲置物品卖掉还债
4. **对接电商** - 一键下单补货

---

## 📊 系统架构

- **前端**：UniApp + Vue 3（跨平台）
- **后端**：Node.js + Express + MySQL
- **AI服务**：硅基流动（DeepSeek + Qwen视觉模型）
- **存储**：MinIO对象存储 + Redis缓存

---

## 📦 开源计划

目前核心代码暂不开源。

未来会开放：
- ✅ **工具库**（贷款计算、条码生成等）
- ✅ **API文档**（完整的接口文档）
- ✅ **Docker镜像**（一键部署）
- 📋 **完整源代码**（持续评估中...）

---

## ⭐ 如果对你有帮助

给个Star吧，这是对我最大的鼓励！

---

## 📧 联系方式

- **更新日志**：[CHANGELOG.md](CHANGELOG.md)

---

**作者**：一个想早日上岸、不再浪费的程序员 😊

**许可证**：MIT

**最后更新**：2026-02-10
