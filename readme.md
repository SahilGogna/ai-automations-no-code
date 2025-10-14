# AI Automations No-Code  
A collection of no-code / low-code automations using Make.com + OpenAI + other tools to power LinkedIn workflows and more.

> 💡 You’ll find ready-to-import blueprints, instructions, prompts, and examples for automating LinkedIn tasks with minimal code.

---

## 🚀 Current Automations

| Name | Description | Authors | Folder | Platform
|---|---|---|---|---|
| **LinkedIn Latest Jobs** | Fetch latest job listings from LinkedIn → enrich via OpenAI → append to Google Sheets | [@SahilGogna](https://github.com/SahilGogna) | [View Folder](https://github.com/SahilGogna/ai-automations-no-code/tree/main/linkedin-latest-jobs) | make.com |
| **LinkedIn Post Automation** | Fetch the db for context and post on LinkedIn | [@SahilGogna](https://github.com/SahilGogna), [@SahibSingh](https://github.com/sahibseehra) | [View Folder](https://github.com/SahilGogna/ai-automations-no-code/tree/main/linkedin-post-automation) | make.com |
| **LinkedIn Generate Tailored Resume & Cover Letter** | Fetch the Latest Jobs Posted on LinkedIn & Prepare Tailored Resume & CL for each of them | [@KanwarSandhu](https://github.com/kanwarrajsinghsandhu) | [View Folder](./resume-cl-generator/) | make.com |


> More automations will be added over time — this repo is your central place for all active “AI + no-code” workflows.

---

## 📂 Repository Structure

```
ai-automations-no-code/
├── linkedin-latest-jobs/
│   ├── latest-jobs-make-automation.json
│   ├── instructions.md
│   └── (screenshots, helper files)
├── linkedin-post-automation/
│   ├── (json, instructions, assets)
│   └── …
└── readme.md
```

- Each folder represents one automation blueprint + instructions.
- JSON files are importable into Make.com (or similar).
- `instructions.md` within each folder details step-by-step setup for that automation.
- Screenshots or visuals should be placed in each automation folder (e.g. `images/` subfolder).

---

## ✅ Setup Guide (for a given automation folder)

1. Open the folder (e.g. `linkedin-latest-jobs`)  
2. Follow its `instructions.md` — ideally the steps are consistent across automations.  
3. Replace placeholder URLs, keys, and connections with your own (RSS feed, OpenAI key, Google Sheets, etc.).  
4. Import the `.json` blueprint into your automation tool (Make.com, etc.).  
5. Run a test to verify data flow end-to-end.

---

## ✍️ Prompt Templates

Each automation includes a prompt template used inside the OpenAI module.  
You’re free to tweak it, add more fields, or adjust formatting — just ensure the JSON schema aligns with your sheet/target.

---

## 🧪 Testing & Troubleshooting

- Use sample data with just a couple of items to test flow.
- Check execution history in Make.com (or your tool) to see failures or mapping issues.
- Confirm the output JSON fields exactly match your Google Sheets headers.
- Watch for API rate limits or malformed responses.

---

## 🗓️ Roadmap & Future Features

- Add more LinkedIn automations (e.g. auto-post, comment analyzer).  
- Expand beyond LinkedIn (e.g. Twitter, GitHub, job boards).  
- Make a central dashboard to run and monitor all automations.  
- Add retry logic, error alerts, logging, and versioning.

---

## 🙏 Acknowledgments

Thanks to openAI, Make.com, and the broader no-code community for inspiring these automations. Special thanks to all direct contributors.
