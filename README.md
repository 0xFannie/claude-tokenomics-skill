# 🪙 Tokenomics Skill for Claude

A Claude Skill that gives Claude deep, structured expertise in crypto token economics — covering the full lifecycle from token design through TGE, vesting, compliance, and US GAAP accounting.

Built for founders, product managers, and Web3 builders who work with Claude regularly and want institutional-grade tokenomics reasoning without repeating context every session.

---

## What This Skill Does

When installed, Claude automatically applies this knowledge whenever your conversation touches tokenomics topics:

| Topic | What Claude Can Do |
|---|---|
| **Token Design** | Define utility, supply model, inflation/deflation mechanics, token sinks |
| **Allocation & Vesting** | Model stakeholder tranches, cliff periods, linear schedules, supply curves |
| **TGE Planning** | Structure TGE unlock %, float at launch, unlock pressure calendar |
| **Howey Test Analysis** | Score token against all 4 prongs with evidence; flag securities risk |
| **SEC 2025–26 Framework** | Apply the March 2026 5-category token taxonomy and Project Crypto guidance |
| **US GAAP Accounting** | Apply ASU 2023-08 (ASC 350-60) and ASC 820 to token holdings |
| **Whitepaper Drafting** | Structure tokenomics sections with allocation tables and vesting schedules |
| **Risk Assessment** | Identify red flags: low float/high FDV, short cliffs, insider concentration |

---

## Skill Contents

```
tokenomics-skill/
├── SKILL.md                      ← Core concepts, always loaded
└── references/
    ├── vesting-mechanics.md      ← Vesting types, supply curve modeling, 2024–25 market patterns
    ├── compliance.md             ← Howey Test, SEC framework, exemption pathways
    └── accounting.md             ← ASU 2023-08, ASC 820, issuer accounting edge cases
```

The skill uses **progressive loading** — core concepts load automatically, while detailed references are read only when relevant to the task.

---

## Installation

### Requirements
- A Claude.ai account (Pro, Team, or Enterprise)
- Access to the Skills feature in Claude settings

### Steps

1. **Download the skill file**  
   Download [`tokenomics.skill`](./tokenomics.skill) from this repo.

2. **Open Claude.ai Settings**  
   Go to [claude.ai](https://claude.ai) → click your profile icon → **Settings**

3. **Navigate to Skills**  
   Find the **Skills** section in the settings sidebar.

4. **Upload the skill**  
   Click **Add Skill** (or similar) → select the downloaded `tokenomics.skill` file → confirm.

5. **Verify installation**  
   Start a new conversation and ask:  
   > *"What are the standard vesting benchmarks for a token launch in 2025?"*  
   
   Claude should respond with structured, detailed tokenomics knowledge — not a generic answer.

> **Note**: The Skills feature availability may vary by Claude.ai plan. If you don't see it in settings, check Anthropic's [documentation](https://docs.claude.com) for the latest on skill support.

---

## Example Prompts

Once installed, try these:

```
Design a tokenomics model for a crypto rewards debit card.
The token is earned as cashback, not sold to investors.
```

```
Run a Howey Test on our token. 
It's distributed as cashback rewards, has no public sale, 
and we haven't made any price appreciation promises.
```

```
We hold 500 ETH on our balance sheet.
How do we account for it under ASU 2023-08?
```

```
Our seed investors have a 6-month cliff and 18-month linear vest.
Model the circulating supply at TGE, 6mo, 12mo, and 24mo,
assuming seed = 15% of total supply with 0% TGE unlock.
```

```
Write the tokenomics section for our whitepaper.
Total supply: 1B tokens. Team: 18%, Investors: 15%, 
Community: 40%, Treasury: 22%, Public: 5%.
```

---

## Knowledge Freshness

This skill reflects the regulatory and market environment as of **April 2026**:

- ✅ SEC "Project Crypto" framework (Atkins speech, November 12, 2025)
- ✅ SEC Crypto Asset Interpretation — 5-category taxonomy (March 17, 2026)
- ✅ ASU 2023-08 mandatory effective date (fiscal years beginning after December 15, 2024)
- ✅ 2024–2025 token unlock market patterns (low float / high FDV dynamics)
- ✅ 2025 tokenomics allocation benchmarks (based on 100+ token launch analysis)

The regulatory landscape evolves quickly. Always verify current SEC guidance and engage qualified legal/accounting counsel before token sales.

---

## Disclaimers

- **Not legal advice.** The Howey Test analysis in this skill is a framework tool. Engage qualified securities counsel before any token sale or offering.
- **Not accounting advice.** ASU 2023-08 analysis should be reviewed by a licensed CPA.
- **Not financial advice.** Token economic models are planning exercises, not price or performance forecasts.

---

## Contributing

Found an error, outdated regulation, or missing use case?  
Open an issue or PR — accuracy is the primary design goal of this skill.

---

## Author

Built by **[Xifang Zhang)](https://xifangzhang.work)** — fintech & Web3 PM with 8+ years across IBM, Wanxiang Blockchain/Hashkey, Tencent, FSL/STEPN, and BitGo.  
GitHub: [@0xFannie](https://github.com/0xFannie)

---

## License

MIT — free to use, modify, and distribute. Attribution appreciated.
