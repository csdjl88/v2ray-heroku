
## 一键部署

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/zizifn/v2ray-heroku/tree/main)

## Github Actions 管理

请 Fork 本项目到自己的账户下。 Actions 需要以下 Secrets 才能正常工作，这些 Secrets 会被 workflow 中的 [akhileshns/heroku-deploy](https://github.com/AkhileshNS/heroku-deploy) 使用。

具体实现细节，请查看 [workflow 配置文件](./.github/workflows/main.yml).

| Name              | Description                                |
| ----------------- | ------------------------------------------ |
| APP_NAME          | 就是你 heroku 项目的名字                   |
| EMAIL             | heroku 账户的 email                        |
| HEROKU_API_KEY    | heroku API key， 在 account 设置下可以找到 |
| HEROKU_V2RAY_UUID | V2rayUUID                                  |
