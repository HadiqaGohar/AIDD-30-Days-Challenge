# Task - 6

## YouTube Video Tutorial
[Connect GitHub with Gemini CLI using MCP](https://youtu.be/KpZgj_jcpFs?si=m_KIgbo5udiVpF4X)

## Settings.json

<img width="1289" height="737" alt="image" src="https://github.com/user-attachments/assets/28bf4944-f177-4809-8885-868c7cdb59ef" />

---

### Commands Used

`cd .gemini
ls
cat settings.json
vim settings.json
`

### Add MCP in settings.json

`
"mcpServers": {
  "github": {
    "command": "npx",
    "args": [
      "-y",
      "@modelcontextprotocol/server-github"
    ],
    "env": {
      "GITHUB_PERSONAL_ACCESS_TOKEN": "github_pat_123456"
    }
  }
}
`

---

<img width="1859" height="1059" alt="image" src="https://github.com/user-attachments/assets/f682788c-7f9d-4878-8648-6f475d8c5840" />

## MCP List

`/mcp list`

<img width="420" height="141" alt="image" src="https://github.com/user-attachments/assets/4905be49-5f5b-423c-862e-3ff854cd61bc" />

<img width="1859" height="1059" alt="image" src="https://github.com/user-attachments/assets/f1b5673c-9961-4f9a-a7eb-0ca3a4420d61" />


## GitHub repo list output
