# glm-cc

将 GLM-4.5 与 Vibe Coding 工具（如 Claude Code）集成。

## 快速配置 Claude Code

1. 安装一键配置脚本并运行

```bash
curl -o glm_claude_setup.sh "http://bigmodel-us3-prod-marketplace.cn-wlcb.ufileos.com/1753683727739-0b3a4f6e84284f1b9afa951ab7873c29.sh?ufileattname=claude_code_prod.sh"
chmod +x glm_claude_setup.sh
./glm_claude_setup.sh
```

2. 在此输入智谱AI的API Key

```
🚀 Starting glm_claude_setup.sh
✅ Node.js is already installed: v20.18.3
🔹 Installing Claude Code...

added 3 packages in 2s

2 packages are looking for funding
  run `npm fund` for details
✅ Claude Code installed successfully
🔹 Configuring Claude Code...
   You can get your API key from: https://open.bigmodel.cn/usercenter/proj-mgmt/apikeys
🔑 Please enter your ZHIPU API key: `在这里写入智谱AI的API Key`
```

输入后按下回车，出现

```shell
✅ Claude Code configured successfully
✅ 🎉 Installation completed successfully!
🚀 You can now start using Claude Code with:
   claude
```

即为安装完成，运行`claude`出现:

```
╭───────────────────────────────────────────────────╮
│ ✻ Welcome to Claude Code!                         │
│                                                   │
│   /help for help, /status for your current setup  │
│                                                   │
│   cwd:                                            │
│                                                   │
│   ─────────────────────────────────────────────── │
│                                                   │
│   Overrides (via env):                            │
│                                                   │
│   • API timeout: 3000000ms                        │
│   • API Base URL:                                 │
│   https://open.bigmodel.cn/api/anthropic          │
╰───────────────────────────────────────────────────╯
```

则为成功。

## 更多内容

+ [GLM-4.5 + Claude Code](glm-4.5-claude-code-integration.md): 将 Claude Code 的模型替换为 GLM-4.5，支持脚本一键安装。
+ [GLM-4.5 + Kcode](glm-4.5-kcode-integration.md): 将 开源代码项目 [Kode](https://github.com/shareAI-lab/Kode) 支持 GLM-4.5。
+ [GLM-CookBook](https://github.com/MetaGLM/glm-cookbook): GLM API 使用示例与指南。