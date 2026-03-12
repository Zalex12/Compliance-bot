# Compliance Bot Clean Release / 合规检测机器人纯净版

## English

This project is a cross-border e-commerce compliance inspection bot.
It is designed for independent storefronts and marketing sites, and helps detect:

- product copy risks
- homepage visual marketing risks
- third-party privacy / tracking risks
- jurisdiction-specific compliance issues with internal knowledge base support

This repository is a sanitized GitHub upload package.

Included:
- `src/`
- `requirements.txt`
- `config.json` (example only)
- `.env.example`
- `.gitignore`

Excluded:
- real API keys and webhooks
- internal knowledge base documents
- company website task URLs
- runtime outputs, screenshots, HAR files, and reports

### Quick Start

1. Copy `.env.example` to `.env`
2. Fill in your own API keys and webhook
3. Replace the example sites in `config.json`
4. Put your private compliance documents into local `knowledge_base/`
5. Run:

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m src.main
```

### Notes

- Do not upload your real `.env`
- Do not upload real `knowledge_base/` files
- Do not upload `output/` reports, HAR files, screenshots, or logs

## 中文

这是一个面向跨境独立站的合规检测机器人项目。
它主要用于自动检查以下风险：

- 商品文案合规风险
- 首页视觉营销风险
- 第三方隐私 / 追踪风险
- 结合不同法域与内部知识库的合规问题

当前这个仓库版本是用于上传到 GitHub 的脱敏纯净版项目。

包含内容：
- `src/`
- `requirements.txt`
- `config.json`（示例配置）
- `.env.example`
- `.gitignore`

已移除内容：
- 真实 API Key 和 Webhook
- 内部知识库文档
- 公司网站任务 URL
- 运行输出、截图、HAR、报告和日志

### 快速开始

1. 将 `.env.example` 复制为 `.env`
2. 填入你自己的 API Key 和 Webhook
3. 将 `config.json` 替换成你自己的站点任务
4. 将内部合规知识库文档放到本地 `knowledge_base/`
5. 运行：

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m src.main
```

### 注意事项

- 不要上传真实 `.env`
- 不要上传真实 `knowledge_base/` 文档
- 不要上传 `output/` 下的报告、HAR、截图和日志
