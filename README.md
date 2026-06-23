# haomabiaoji
手机号码标记查询 API 合集 · 聚合小米/华为/腾讯/百度/360/电话邦/泰迪熊/搜狗/联通等11家平台，免费调用，一键识别骚扰/诈骗/广告推销号码


# 📞 Phone-Mark-Query —— 手机号码标记查询 API 大全

聚合国内外 11 大主流平台的**手机号码标记检测 API**，覆盖小米、华为、腾讯、百度、360、电话邦、泰迪熊、搜狗、联通等平台，全部**免费调用**，助力开发者快速集成号码安全检测功能。

## ✨ 特性

- 🔍 **11 个免费 API**，覆盖主流号码标记数据源
- ⚡ **高频调用**：大部分接口 30 次/分钟，满足日常开发需求
- 🏷️ **多维度标记识别**：骚扰电话、广告推销、诈骗电话、房产中介、快递送餐、企业认证等
- 🌐 **归属地 + 运营商信息**：部分接口同时返回号码归属地与运营商
- 🛠️ **开箱即用**：所有接口均为 GET 请求，返回 JSON 格式
- 📖 **附带示例代码**：curl、axios、Python、Java、Go、PHP 等

## 📋 接口列表

| 序号 | 平台 | 接口地址 | 频率 | 主要功能 |
|:---:|------|----------|:----:|----------|
| 1 | 小米 | `https://tmini.net/api/haoma` | 30次/分 | 广告推销/诈骗标签、标记次数 |
| 2 | 泰迪熊 | `https://tmini.net/api/teddymobile` | 30次/分 | 号码有无异常标记 |
| 3 | 华为 | `https://tmini.net/api/huaweibiaoji` | 30次/分 | 认证信息、分类与标记详情 |
| 4 | 搜狗 | `https://tmini.net/api/qqhaoma` | 30次/分 | 骚扰/推销标签 + 归属地 + 运营商 |
| 5 | 电话邦 | `https://tmini.net/api/dianhua` | 30次/分 | 机构认证、号码分类、归属地 |
| 6 | 360 | `https://tmini.net/api/dianhua360` | 30次/分 | 认证号/标记号/普通号识别 |
| 7 | 移动高频骚扰 | `https://tmini.net/api/querySys` | 30次/分 | 判断是否为高频骚扰号码 |
| 8 | 百度 | `https://tmini.net/api/baiduphone` | 30次/分 | 企业认证号/个人号/标记号 |
| 9 | 联通 | `https://tmini.net/api/unicom_number` | 30次/分 | 标记类型、次数、时间、申诉状态 |
| 10 | 百度（备用） | `https://tmini.net/api/baidubeiyong` | 3次/分 | 详细版归属地 + 标签 + POI |
| 11 | 腾讯 | `https://tmini.net/api/txbiaoji` | 30次/分 | 商业营销/广告营销/机构电话等 |

## 🚀 快速开始

以小米平台为例，查询号码 `02039575218`：

```bash
curl "https://tmini.net/api/haoma?phone=02039575218"
