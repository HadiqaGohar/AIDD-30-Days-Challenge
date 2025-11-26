
# AIDD 30-Day Challenge — Task 6

## 📺 YouTube Video Tutorial
[Connect GitHub with Gemini CLI using MCP](https://youtu.be/KpZgj_jcpFs?si=m_KIgbo5udiVpF4X)

---

## ⚙️ Settings.json

<img width="1289" height="737" alt="settings.json screenshot" src="https://github.com/user-attachments/assets/28bf4944-f177-4809-8885-868c7cdb59ef" />

---

### 🖥 Commands Used

```bash
cd .gemini
ls
cat settings.json
vim settings.json
````

---

### ✏️ Add MCP in `settings.json`

```json
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
```

---

<img width="1859" height="1059" alt="MCP settings screenshot" src="https://github.com/user-attachments/assets/f682788c-7f9d-4878-8648-6f475d8c5840" />

---

## 📜 MCP List

```bash
/mcp list
```

<img width="420" height="141" alt="MCP list screenshot" src="https://github.com/user-attachments/assets/4905be49-5f5b-423c-862e-3ff854cd61bc" />

<img width="1859" height="1059" alt="MCP full list screenshot" src="https://github.com/user-attachments/assets/f1b5673c-9961-4f9a-a7eb-0ca3a4420d61" />

---

## 📂 GitHub Repo List Output

### 🔍 Searching Process

<img width="417" height="123" alt="searching repo screenshot" src="https://github.com/user-attachments/assets/080202d1-e575-4e5f-b999-042e889dfcc4" />

### ✅ Final Output

#### Question

<img width="356" height="84" alt="question screenshot" src="https://github.com/user-attachments/assets/28091edb-d660-40b9-86ab-4d4331b7d68a" />

#### Answer

<img width="508" height="200" alt="answer screenshot" src="https://github.com/user-attachments/assets/a34ef49a-112b-441b-b3af-11182db65a0f" />


