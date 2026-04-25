# 🚀 ChatGPT Exporter

**ChatGPT Exporter** is a powerful Chrome Extension that allows you to seamlessly export your ChatGPT conversations directly to your GitHub repositories as clean, formatted Markdown files. 

Stop copy-pasting and manually formatting your prompts and responses. With ChatGPT Exporter, you can back up your valuable chats, create documentation, and save code snippets to GitHub with just one click!

---

## ✨ Features

- **Direct GitHub Integration:** Upload chats directly to any of your GitHub repositories.
- **Markdown Formatting:** Conversations are automatically formatted into clean, readable Markdown (`.md`).
- **Selective Exporting:** Filter your export by specifying exact start and end turns.
- **Custom Commits:** Write your own custom commit messages right from the extension.
- **Folder Organization:** Save files into specific subfolders within your repository.
- **Secure:** Uses your GitHub Personal Access Token (PAT) with built-in token validation and expiration tracking. All credentials are saved locally on your machine.

---


<img width="262" height="413" alt="Screenshot 2026-04-22 233747" src="https://github.com/user-attachments/assets/0afb0c73-1b6f-42cb-a38e-f5f5b8dade70" />
<img width="960" height="315" alt="Screenshot 2026-04-22 234052" src="https://github.com/user-attachments/assets/15830b93-7c35-474d-969b-36c5610a672b" />
<img width="959" height="348" alt="Screenshot 2026-04-22 234300" src="https://github.com/user-attachments/assets/9009b7ee-5bc9-4566-a018-0360aabceb82" />
<img width="960" height="368" alt="Screenshot 2026-04-22 234446" src="https://github.com/user-attachments/assets/dacd5f83-4bd5-4e3a-a4b6-d98b8e1916f3" />
<img width="960" height="383" alt="Screenshot 2026-04-22 234502" src="https://github.com/user-attachments/assets/722f47b0-1cfc-41b6-99dd-6620bdbadb1f" />



## 📖 How to Use (Step-by-Step)

### Step 1: Generate a GitHub Personal Access Token (PAT)
To allow the extension to upload files to your repository, you need a GitHub Token.
1. Go to your GitHub [Developer Settings](https://github.com/settings/tokens).
2. Click **"Generate new token (classic)"**.
3. Give it a note (e.g., "ChatGPT Exporter").
4. Under **Select scopes**, check the `repo` box (Full control of private repositories).
5. Click **Generate token** and **copy it immediately** (you won't be able to see it again).

### Step 2: Configure the Extension
1. Open a conversation on `chatgpt.com` or `chat.openai.com`.
2. Click the **ChatGPT Exporter icon** in your Chrome toolbar.
3. Fill in the required fields:
   - **GitHub Username:** Your GitHub handle.
   - **Repository Name:** The name of the repo you want to save to (e.g., `my-chatgpt-logs`).
   - **GitHub Token:** Paste the token you generated in Step 1.
4. Click **"Save Credentials"**. *(Note: These are saved securely on your local browser storage).*

### Step 3: Export Your Chat
1. In the extension popup, type a **Filename** (e.g., `react-help.md`). *You can use the 🕒 button to generate a timestamped filename.*
2. *(Optional)* Specify a **Subfolder** if you want to organize your files (e.g., `coding/react`).
3. *(Optional)* Set a **Start Turn** and **End Turn** if you only want to export a specific part of the conversation.
4. *(Optional)* Add a **Custom Commit Message** (e.g., "Added React debugging chat").
5. Click **"Export to GitHub"**! 

The extension will process the chat, upload it, and notify you when it's successfully pushed to your repository.

---

## 🔒 Privacy & Security

- **Local Storage:** Your GitHub Username, Repository Name, and Personal Access Token are saved **locally** in your browser using `chrome.storage.local`. They are never sent to any third-party servers.
- **Direct API Calls:** The extension communicates directly with the official GitHub API (`api.github.com`).
- **No Tracking:** This extension does not track your browsing history or collect analytics. It only runs when you actively click the "Export" button on a ChatGPT tab.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](link-to-your-issues-page) if you want to contribute.

---

## 📝 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.
