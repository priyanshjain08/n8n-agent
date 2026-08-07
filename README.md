# 🚀 How I Use JSON Workflows in n8n

### For **aadityabhatnagar.online**

🌐 Website: https://aadityabhatnagar.online
🤖 Built by: Aaditya Bhatnagar
⚡ Purpose: Automating Website + AI Systems

---

# 📦 What Is the JSON File?

The `.json` file is a **complete export of an n8n workflow**.

It contains:

• All nodes
• All connections
• Logic structure
• Automation steps
• Webhook URLs (if configured)

Think of it as a **blueprint of the automation system**.

---

# 🧩 Step-By-Step: Import JSON Into n8n

## ✅ Step 1 — Open n8n Dashboard

Login to your n8n account (local or cloud version).

---

## ✅ Step 2 — Import Workflow

1. Go to **Workflows**
2. Click **Import**
3. Select **Import from File**
4. Upload your `.json` file
5. Click **Import**

Your automation will now appear inside n8n.

---

# 🔧 Step 3 — Configure The Workflow

After importing:

### 🔹 Check Credentials

Make sure:
• Google Sheets credentials are connected
• Email credentials are connected
• Google gemini (if used) is connected

If credentials are missing:

* Open the node
* Add credentials
* Save
