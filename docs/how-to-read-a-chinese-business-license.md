# How to Read a Chinese Business License (营业执照) — Line by Line

> The single document that separates real manufacturers from well-written websites. This guide decodes every field, shows you the four-name cross-check professionals run, and tells you exactly where to verify it for free.

Every legitimate supplier in China — factory, trading company, or one-person export shop — operates under a business license issued by the market regulator. The problem: most importers receive one, glance at the red stamp, and file it away. The license is not a formality. It is a **map of who you're actually dealing with**, and almost everything that matters is printed on it — if you know how to read it.

This is Step 1 of the [VERIFY system](../README.md#-the-verify-system). Here's the full decoding.

---

## Where you'll see the license

1. **The supplier sends it** (ask — a real company sends it in minutes; hesitation is itself data)
2. **The Alibaba/1688 storefront** — check the "Qualification" or 资质 section, where platforms display verified licenses
3. **You pull it yourself** from the official registry (next section — this is the version nobody can photoshop)

## Where to verify it for free

The authoritative source is the **National Enterprise Credit Information Publicity System** ([gsxt.gov.cn](http://www.gsxt.gov.cn)) — run by the market regulator itself. Search the exact Chinese company name or the 18-digit code. The site can be slow or fussy from overseas connections and may require a mainland mobile number for some detailed views.

In practice, professionals also use **Qichacha (企查查)** or **Tianyancha (天眼查)** — commercial registries that mirror government data with faster interfaces and better search (both have English-capable apps and freemium tiers).

What you're looking for on any of these:

- **经营状态 (status): 存续 / 在业 (active)** — anything reading 吊销 (revoked) or 注销 (deregistered) ends the conversation
- **经营异常名录 (abnormal operations list)** — companies flagged for failing annual reports or unverifiable registered addresses
- **严重违法失信 (serious dishonesty blacklist)** — self-explanatory
- **行政处罚 (administrative penalties)** and **court filings** — patterns matter more than single civil disputes

---

## The license, field by field

A standard license has nine fields that matter to a buyer. Here's each one and what it tells you.

### 1. 统一社会信用代码 (Unified Social Credit Code)

The 18-character ID every Chinese company carries. It encodes, in order: the registration authority, the entity type, the six-digit administrative region, a nine-digit organization code, and a check digit computed with the ISO 7064 MOD 31-2 algorithm.

What to do with it:

- **Copy it into gsxt/Qichacha and confirm it resolves to the same company name.** A fabricated license often fails this test — the code either doesn't exist or belongs to a different company.
- **Check the issue date.** Licenses reissued recently aren't suspicious, but a "long-established factory" whose code resolves to a company registered last year is lying about something.

### 2. 企业名称 (Company name)

Chinese company names follow a legal formula: **region + chosen name + industry + organization form**. Decode 深圳 (Shenzhen) 市 ××× 实业 有限公司 like this:

- **Region (深圳市)** — where the company is *registered*. Compare with the factory address they claim. A Dongguan factory with a Shanghai-registered company is common and explainable (HQ + plant), but the addresses should connect.
- **Industry word (实业 / 科技 / 贸易 / 电子 / 日用品…)** — a hint, nothing more. 实业 (industrial) *suggests* manufacturing; 贸易 (trading) says trading outright; 科技 (technology) is the favorite label of companies that are neither.
- **Organization form (有限公司 = limited company; 厂 = factory, often a sole proprietorship)** — note that 个人独资企业 (sole-proprietorship factories) have *unlimited liability* for the owner and weaker paperwork discipline. Not a dealbreaker; a reason for tighter contracts.

**The name itself is not the verdict. The 经营范围 below is.**

### 3. 法定代表人 (Legal representative)

The natural person legally accountable for the company. Your sales contact is usually *not* this person — that's normal. What matters:

- The name on the **bank account you wire to must be the company name** — never the legal rep's personal account, never the salesperson's account. (This is red flag #2 in the toolkit.)
- If the legal rep of the "factory" is also the legal rep of five other shell companies in the registry, you're looking at a serial shell operator. Qichacha shows these affiliations automatically.

### 4. 注册资本 (Registered capital)

Read this carefully, because it's the field most importers misinterpret:

Since the 2014 registration reform, most industries have **no paid-in requirement**. The number printed on the license is usually **认缴 (subscribed)** — a promise, not a bank balance. ¥5,000,000 subscribed capital can legally mean ¥0 paid in.

The honest signal is **实缴 (paid-in) capital**, which companies must disclose in annual reports (when they choose to disclose at all). Practical translation: don't be impressed by big numbers, and don't dismiss a great factory for a small one. Registered capital tells you about paperwork ambition, not solvency.

### 5. 成立日期 (Date of establishment)

Two patterns worth attention:

- **Registered 2024 + quoting 15 years of history** — someone is telling stories. The registry doesn't lie; the website does.
- **Registered 3 months ago + asking for 50% deposit on a large order** — new companies aren't evil, but they carry maximum counterparty risk with zero track record. Small trial orders, tighter payment terms, third-party inspection non-negotiable.

### 6. 公司类型 (Company type) & 7. 营业期限 (Business term)

Limited company (有限责任公司) is standard. Check the term end date — licenses marked 长期 (long-term) are normal; an expiry date next year is worth a question.

### 8. 经营范围 (Business scope) — the most important field on the document

This is the line that settles the factory-vs-trader question, which is the question behind half of all sourcing disappointment.

The scope is a list of approved activities. Look for these keywords:

| Scope contains | Meaning |
|---|---|
| 生产 / 制造 (production / manufacturing) | The company is *licensed to make things* |
| 销售 / 批发 (sales / wholesale) | Licensed to sell — only |
| 货物进出口 (import & export of goods) | Has or can arrange direct export rights |
| 佣金代理 / 拍卖 / other financial words | Unrelated scope = unrelated risk |

A company whose scope contains **only 销售/批发 (sales/wholesale) with no 生产/制造** is a **trading company** — whatever their Alibaba badges say. That's not automatically bad: good trading companies earn their margin with sourcing muscle, QC, and English-speaking staff. But you deserve to know what you're paying, and factory prices should not silently become trader prices.

**One caveat:** many manufacturers hold their production license under a related entity (the factory) while quoting you through their sales arm (the trading company) — extremely common in export. The correct response isn't panic, it's the four-name check below.

### 9. 住所 (Registered address)

Cross-check three addresses: the license address, the Alibaba storefront address, and the factory address from your video call. They don't have to be identical, but **the story has to connect**. Registered in an office tower while claiming a 20,000 m² production floor? The production floor belongs to somebody else — maybe a partner, maybe nobody.

---

## The 5-minute protocol: the four-name check

After you've decoded the license, run the check that catches most fraud before money moves. Collect these four names:

1. **Company name on the business license**
2. **Company name on the Alibaba/1688 storefront qualification page**
3. **Bank account name you're instructed to wire to**
4. **Company name that will appear on the export declaration** (ask; they know)

All four should be the **same legal entity** — or connected through entities you can see in the registry (same legal rep, shared registered address, or a documented parent/subsidiary link).

You wire money, so rule 3 is where the scam lives: the invoice says Shenzhen ××× Industrial Co., Ltd., the bank account belongs to Guangzhou ××× Trading Co., Ltd. — maybe "the finance company of the group," maybe the last you'll see of your deposit. **If the beneficiary name doesn't match the contract entity, the wire doesn't leave.**

## What a suspicious license looks like

- **Checksum failure** — the 18-digit code doesn't resolve to this company in the registry (fabricated or edited document)
- **Scope says manufacturing, address is a residential compound or office tower** — licensed on paper, producing nowhere
- **Registered capital ¥10M, established 6 weeks ago, legal rep runs 4 other companies** — shell topology
- **The license copy arrives with fields blurred** "for privacy" — the privacy of whom, exactly?

Any single item is a question. Two or more is an answer.

---

## Where this fits

License decoding is Step 1 (**V — Validate**) of the six-step [VERIFY system](../README.md#-the-verify-system) in this toolkit. The remaining five steps — factory video verification, reference checks, cross-channel sampling, written specifications, and record checks — build on it.

**Free templates in this repo:** [quality inspection checklists](../templates/), [Incoterms cheat sheet](../README.md#-incoterms-cheat-sheet), [negotiation email scripts](../README.md#-free-templates), and a [landed-cost calculator](../README.md#-landed-cost-calculator).

**Need the complete system?** The [China Sourcing Playbook](https://assassinationss.github.io/china-sourcing-playbook/) packages all 25 templates, the full verification protocol, and 10 AI sourcing prompts.

---

*Found this useful? Star the repo — it's the signal that tells us to keep publishing. Wrong somewhere? Open an issue or a discussion; corrections from practitioners make the toolkit better for everyone.*
