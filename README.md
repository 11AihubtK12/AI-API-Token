# AI-API-Token / AI-API-令牌

> 稳定且低延迟的AI API令牌销售 | OneAPI 中继接口 | 支持 GPT、Claude、Gemini 等主流大模型 | 高可用性、高并发性，专业的售后服务技术支持
> Stable & Low-Latency AI API Token Sales | OneAPI Proxy | Support GPT, Claude, Gemini & More | High Availability, High Concurrency, Professional Support

---

## 📊 服务状态 / Service Status
![Status](https://img.shields.io/badge/Status-Stable-green)
![Uptime](https://img.shields.io/badge/Uptime-99.9%25-success)
![Models](https://img.shields.io/badge/Models-20%2B-blueviolet)
![Support](https://img.shields.io/badge/Support-24%2F7-orange)

- 实时在线率 / Real-time Uptime: 99.9%
- 平均延迟 / Average Latency: < 100ms
- 线路 / Network: Premium Global Dedicated Lines

---

## ✨ 核心优势 / Core Advantages
- 兼容 OpenAI 标准格式，一键切换即可使用
- 支持 GPT-3.5/4o/GPT-4V、Claude 3、Gemini 等主流模型
- 高并发、不限速、风控宽松，稳定不掉线
- 按量付费 / 包月套餐 / 企业定制，灵活选择
- 售后秒回，技术问题快速解决
- 支持免费试用，先测后买

> English:
- Fully compatible with OpenAI standard API format, ready to use with one-click switch
- Supports mainstream models: GPT-3.5/4o/GPT-4V, Claude 3, Gemini, and more
- High concurrency, no speed limits, low risk of rate-limiting
- Pay-as-you-go / Monthly plans / Custom enterprise solutions
- Fast response & reliable technical support
- Free trial available before purchase

---

## 🚀 支持模型 / Supported Models
- GPT-3.5-turbo / GPT-4o / GPT-4V
- Claude 3 Sonnet / Opus
- Gemini Pro / 1.5 Flash
- 文生图 / Image Generation: Midjourney, Stable Diffusion
- Embedding、TTS、Whisper 语音转文字 / Speech-to-Text

---

## 💰 套餐价格 / Pricing Plans
All plans support cross-model usage, with tiered discounts for SVIP/VIP members.

### 体验套餐（新手测试）/ Trial Plan (New Users)
- Token Quota: 100,000 Tokens
- Validity: 7 Days
- **Standard**: $2.5 (¥18)
- **SVIP**: $2.1 (¥15)
- **VIP**: $1.9 (¥13)

### 基础套餐（个人开发者）/ Basic Plan (Individual Developers)
- Token Quota: 500,000 Tokens
- Validity: 30 Days
- **Standard**: $10 (¥70)
- **SVIP**: $8.5 (¥60)
- **VIP**: $7.5 (¥53)

### 高级套餐（小团队/工作室）/ Premium Plan (Small Teams)
- Token Quota: 2,000,000 Tokens
- Validity: 30 Days
- **Standard**: $35 (¥245)
- **SVIP**: $30 (¥210)
- **VIP**: $26 (¥180)

### 企业定制套餐（生产环境）/ Enterprise Custom Plan (Production)
- Custom quota & validity
- Dedicated lines + high concurrency
- Dedicated technical support & invoicing
- **Contact us for a custom quote** (Bulk pricing available)

> 注：实际消耗按模型单价计费，套餐额度为总Token数，可跨所有模型使用。
> Note: Usage is billed per model rate; quota can be used across all supported models.


---

## 🧪 快速调用测试 / Quick API Test
### 接口地址 / API Endpoint
`https://aihubapi.xyz/v1

### API-Key
购买后获取 / Provided after purchase

### Python 调用示例 / Python Example
```python
import openai

openai.api_key = "YOUR_TOKEN_KEY"
openai.api_base = "https://aihubapi.xyz/v1

resp = openai.ChatCompletion.create(
    model="gpt-3.5-turbo",
    messages=[{"role":"user","content":"你好 / Hello"}]
)
print(resp)
