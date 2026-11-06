<div align="center">

# 💼 BizPilot

### Your free AI business advisor

**Consultant + CFO + Marketing Head + Operations Manager, in one.**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Price: Free](https://img.shields.io/badge/Price-Free-brightgreen.svg)
![Languages](https://img.shields.io/badge/Languages-Bangla%20%7C%20Banglish%20%7C%20English%20%7C%20Hindi-blue.svg)
![Works with](https://img.shields.io/badge/Works%20with-Claude%20%7C%20ChatGPT%20%7C%20Any%20AI-purple.svg)

</div>

---

## 📖 What is BizPilot?

BizPilot helps business owners **organize, manage and grow** their business. It does not hand out generic textbook advice. It first learns about *your* business, then finds what is holding it back, and finally builds a practical **30-60-90 day growth plan** that fits your size and budget.

It is made for:

- 🏪 Shop owners and local businesses
- 🛒 Online sellers (Facebook page, website, marketplace)
- 🧑‍💻 Freelancers and agencies
- 🏭 Small manufacturers and service businesses
- 🚀 Startups and first-time business owners

You do not need to know finance or business terms. BizPilot uses simple words and explains any term it uses.

---

## ✨ Features

| Feature | What you get |
|---|---|
| 🗣️ **Guided intake** | Short rounds of simple questions (3-5 at a time) about your business |
| 📊 **Business Health Score** | 0-10 score for Sales, Profit/Finance, Marketing, Operations, Team, Customer Retention and Systems |
| 🧮 **Key numbers** | Gross margin, net margin, break-even point, cost breakdown %, average order value, estimated customer value |
| 🧭 **SWOT analysis** | Strengths, Weaknesses, Opportunities and Threats specific to your business |
| 🔍 **Root cause diagnosis** | The top 3 real causes holding you back, not just symptoms |
| ⚡ **Quick wins** | 3-5 things you can do this week with little or no money |
| 🚀 **Growth plan** | 30-day (fix), 60-day (grow), 90-day (scale) actions with steps, cost, expected result and how to measure it |
| 📈 **KPIs** | 5-7 numbers to track weekly or monthly, with simple targets |
| 🔁 **Weekly review** | Share new numbers and BizPilot compares them with your baseline and adjusts the plan |
| 🧾 **Templates** | Sales sheet, expense tracker, inventory sheet, pricing calculator, SOP checklist and more |

---

## 🔄 How it works: 3 phases

```
┌────────────────┐     ┌────────────────┐     ┌────────────────┐
│ 1. INTAKE      │ ──▶ │ 2. ANALYSIS    │ ──▶ │ 3. GROWTH PLAN │
│ Learn your     │     │ Score, numbers,│     │ 30-60-90 days, │
│ business       │     │ SWOT, problems │     │ KPIs, templates│
└────────────────┘     └────────────────┘     └────────────────┘
```

### Phase 1: Intake
BizPilot will **not** give advice before it understands your business. It asks in six short rounds:

1. **Basics:** business name, what you sell, type, location, how long running, team size, one-line goal
2. **Customers & Sales:** who buys, where customers come from, average order value, monthly orders, repeat rate, top 3 items
3. **Money:** revenue, costs, profit, loans or dues, cash situation, pricing method
4. **Operations & Team:** daily work process, suppliers, inventory, tools, who does what, time-wasters
5. **Marketing & Competition:** channels, budget, social media and website, competitors, why customers choose you
6. **Goals & Problems:** 6-month and 1-year goals, top 3 problems, budget and time for growth

Don't know a number? Say **"don't know"** or give an estimate. BizPilot never invents numbers. At the end it shows a short summary and asks you to confirm or correct it.

### Phase 2: Analysis
After you confirm the summary, you get a clear report: health scores, key numbers (with simple formulas), SWOT, top 3 root causes and quick wins. BizPilot tells you which conclusions come from your data and which are assumptions.

### Phase 3: Growth Plan
A prioritized plan for 30, 60 and 90 days. Every action includes **what, why, how (step by step), cost, expected result and how to measure it**. You also get weekly or monthly KPIs and ready-to-use templates.

---

## 💬 Example

> **You:** Hi
>
> **BizPilot:** Assalamu alaikum / Hello! I'm BizPilot. I will ask about your business, analyze it, and build a growth plan for you. Let's start with the basics:
> 1. What is your business name?
> 2. What do you sell, and what type of business is it?
> 3. Where are you located and how long has it been running?
> 4. How many people are on your team?
> 5. In one line, what do you want from this business right now?

BizPilot replies in the language you write in: Bangla, Banglish (Bangla in English letters), English or Hindi.

---

## 📦 What's in this repository

```
bizpilot/
├── .claude-plugin/
│   └── plugin.json                  # Plugin manifest
├── skills/
│   └── bizpilot/
│       ├── SKILL.md                 # Main skill (workflow and rules)
│       └── references/
│           ├── intake-rounds.md     # The 6 intake rounds
│           ├── formulas.md          # Simple business formulas
│           └── templates.md         # Sheets, checklists, scripts
├── master-prompt/
│   └── other-ai-tool-using-prompt.md   # Prompt for ChatGPT and other AI tools
├── LICENSE                          # MIT
└── README.md
```

### Release files (download from the [Releases page](https://github.com/RongonKairy/BizPilot/releases))

| File | Use it for |
|---|---|
| `bizpilot.skill` | Upload directly to Claude as a Skill |
| `other-ai-tool-using-prompt.md` | Prompt for ChatGPT or any other AI tool |
| `bizpilot-plugin.zip` | Full plugin package (Claude Code / Cowork, or to read and customize) |

---

## 🚀 Installation and usage

### Option 1: Claude (Skill)
1. Download `bizpilot.skill` from the [Releases page](https://github.com/RongonKairy/BizPilot/releases)
2. In Claude, go to **Settings → Capabilities → Skills**
3. Upload `bizpilot.skill`
4. Start a chat and type: *"Help me grow my business"* or just *"BizPilot"*

### Option 2: ChatGPT (Custom GPT)
1. Open [`master-prompt/other-ai-tool-using-prompt.md`](https://github.com/RongonKairy/BizPilot/releases) and copy everything below the line
2. In ChatGPT, create a new **Custom GPT** and paste it into **Instructions**
3. Save, open the GPT and say *"Hi"*

### Option 3: Any other AI tool (Gemini, Grok, DeepSeek, local models...)
1. Copy the prompt from [`master-prompt/other-ai-tool-using-prompt.md`](https://github.com/RongonKairy/BizPilot/releases)
2. Paste it as the first message of a new chat (or as the system prompt if the tool has one)
3. Say *"Hi"* and BizPilot will start

### Option 4: Claude Code / Cowork (Plugin)
1. Download and unzip `bizpilot-plugin.zip` from the [Releases page](https://github.com/RongonKairy/BizPilot/releases)
2. Add the folder as a plugin in your tool
3. Ask for business help and the `bizpilot` skill will be used

---

## 🧾 Included templates

BizPilot can give you these whenever they help (and can build them as spreadsheets if your AI tool supports files):

- Daily / weekly **sales sheet**
- **Expense tracker**
- **Inventory sheet**
- **Pricing calculator**
- **SOP checklist**
- **Job roles chart**
- **Marketing calendar**
- **Customer follow-up script**
- **Weekly KPI tracker**

See [`skills/bizpilot/references/templates.md`](https://github.com/RongonKairy/BizPilot/releases).

---

## 🧮 Formulas used

All calculations use **only the numbers you give**. Examples:

- Gross Margin % = (Revenue − Direct cost) / Revenue × 100
- Net Margin % = (Revenue − All costs) / Revenue × 100
- Average Order Value = Revenue / Number of orders
- Break-even (revenue) = Fixed monthly costs / Gross Margin %


---

## 🔁 Ongoing modes

After your plan is ready, ask BizPilot anything in these areas:

`Finance & Pricing` · `Marketing & Sales` · `Customer Service & Retention` · `Operations & Inventory` · `HR & Team Management` · `Business Structure & Registration basics` · `Strategy & Expansion` · `Weekly Review`

For a **Weekly Review**, come back with your new numbers. BizPilot compares them with your earlier baseline and adjusts the plan.

---

## ❓ FAQ

**Is it really free?**
Yes. BizPilot is free and open under the MIT License. Note that the AI tool you run it on (Claude, ChatGPT, etc.) may have its own plan or limits.

**Which language does it use?**
Whatever language you write in: Bangla, Banglish, English or Hindi. The default currency is BDT/Taka if you are in Bangladesh; otherwise your local currency.

**I don't know my exact numbers. Can I still use it?**
Yes. Give an estimate or say "don't know". BizPilot will never make up numbers, and it marks which conclusions are based on your data and which are assumptions.

**Does BizPilot search the web?**
Only if your AI tool has web search turned on. When it uses search results (market trends, competitor info, prices, local rules), it says so. Otherwise it labels the information as a general estimate.

**Is my business data private?**
BizPilot is only instructions (a prompt and a skill). It has no server and collects nothing. Your data goes only to the AI tool you choose, under that tool's own privacy policy.

**Can it replace an accountant or lawyer?**
No. BizPilot gives general guidance. For legal, tax, license or major financial decisions, confirm with a qualified local professional.

---

## 🤝 Contributing

Ideas and improvements are welcome.

- 🐛 Found a problem? [Open an Issue](https://github.com/RongonKairy/BizPilot/issues)
- 💡 Have an idea (new template, new industry guide, translation)? Open an **Issue** or a **Pull Request**
- 🌍 Want BizPilot in another language? Translations are welcome

---

## ⚠️ Disclaimer

BizPilot provides general business guidance based on the information you share. It does not guarantee results. Decisions about your business are yours. For legal, tax, licensing and major financial matters, please consult a qualified local professional.

---

## 📄 License

Released under the **MIT License**. Free to use, share and modify. See [`LICENSE`](LICENSE).

---

<div align="center">

Made with ❤️ by **Rongon Kairy**

If BizPilot helps your business, give this repo a ⭐ and share it with another business owner.

</div>
