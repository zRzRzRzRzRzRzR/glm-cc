# glm-cc

Integrating GLM-4.5 with Vibe Coding tools like Claude Code

## Quick Setup for Claude Code

1. Install and run the one-click setup script

```bash
curl -o glm_claude_setup.sh "http://bigmodel-us3-prod-marketplace.cn-wlcb.ufileos.com/1753683727739-0b3a4f6e84284f1b9afa951ab7873c29.sh?ufileattname=claude_code_prod.sh"
chmod +x glm_claude_setup.sh
./glm_claude_setup.sh
```

2. Enter your ZhipuAI API Key here

```shell
🚀 Starting glm_claude_setup.sh
✅ Node.js is already installed: v20.18.3
🔹 Installing Claude Code...

added 3 packages in 2s

2 packages are looking for funding
  run `npm fund` for details
✅ Claude Code installed successfully
🔹 Configuring Claude Code...
   You can get your API key from: https://open.bigmodel.cn/usercenter/proj-mgmt/apikeys
🔑 Please enter your ZHIPU API key: `Enter your ZhipuAI API Key here`
```

After entering the key and pressing Enter, you should see:

```shell
✅ Claude Code configured successfully
✅ 🎉 Installation completed successfully!
🚀 You can now start using Claude Code with:
   claude
```

This indicates successful installation. Running `claude` should display:

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


This confirms successful setup.

## More Content

+ [GLM-4.5 + Claude Code](glm-4.5-claude-code-integration.md): Replace Claude Code's model with GLM-4.5, supporting one-click script installation.
+ [GLM-4.5 + Kcode](glm-4.5-kcode-integration.md): Add GLM-4.5 support to the open-source project [Kode](https://github.com/shareAI-lab/Kode).
+ [GLM-CookBook](https://github.com/MetaGLM/glm-cookbook): Examples and guides for using the GLM APIs 