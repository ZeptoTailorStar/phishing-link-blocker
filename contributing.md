

# 🛡️ Phishing Link Blocker

<p align="center">
  <img src="https://img.shields.io/badge/Downloads-18K+-0F766E?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Rating-4.9/5-0F766E?style=for-the-badge&logo=star" />
  <img src="https://img.shields.io/badge/Release-2026-1C1917?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Win%20%7C%20mac%20%7C%20Linux-0F766E?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/Type-Security%20Tool-0F766E?style=for-the-badge&logo=shield" />
  <img src="https://img.shields.io/badge/License-Free%20Guide-0F766E?style=for-the-badge&logo=opensourceinitiative" />
</p>

**🛡️ Phishing Link Blocker** is the complete English-language guide to building a phishing link blocker for browsers and chat apps. Learn how to score URLs in real time, detect punycode and homograph tricks, flag shorteners and open redirects, and show a clear warning before a click goes through — with runnable JavaScript and a clean rule engine. Built for security engineers, browser extension developers, and anyone shipping a link-safety layer. **Completely free.** No signup. No paywall. No hidden chapters.

<p align="center">
  <img src="https://skillicons.dev/icons?i=js" />
  <img src="https://skillicons.dev/icons?i=ts" />
  <img src="https://skillicons.dev/icons?i=nodejs" />
  <img src="https://skillicons.dev/icons?i=git" />
  <img src="https://skillicons.dev/icons?i=vscode" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=FB923C&size=27&center=true&vCenter=true&width=920&lines=🛡️+Phishing+Link+Blocker;🔗+Punycode+%2B+Homograph+%2B+Redirect;⚠️+Warn+Before+Click;💚+100%25+Free+Guide">
</p>

<!-- Button 1 -->
<div align="center">
  <a href="https://share.google/qF11QKHt1FalfvGA7">
    <img src="https://img.shields.io/badge/📖%20OPEN%20THE%20GUIDE-0F766E?style=for-the-badge&logo=google&labelColor=1C1917&color=FB923C" alt="Open the Guide" />
  </a>
</div>

<div align="center">
  <img width="516" height="387" alt="images (42)" src="https://github.com/user-attachments/assets/537f3b47-7f60-4804-8836-53eb1c1eddd8" />

</div>

---

## 🚨 Symptoms of a Broken Link Blocker

Before you ship another rule, check whether your blocker suffers from any of these classic symptoms. Each one points to a specific fix this guide teaches.

| **Symptom** | **What It Really Means** | **Fix This Guide Teaches** |
|-------------|---------------------------|------------------------------|
| 😵 Blocks legit links | Over-broad regex | Rule scoring |
| 🐌 Slow page load | Sync checks | Async + cache |
| 🧊 Misses punycode | No IDN check | Unicode normalization |
| 🔥 Shortener bypass | No redirect follow | Head-request expand |
| 📉 False positives | No allowlist | Domain allowlist |
| 🔇 Silent block | No UI | Warning modal |

> **💡 Tip:** If legit links are blocked, your regex is too broad — switch from binary block to weighted scoring.

---

## 🚀 First 5 Minutes — Minimal Working Example

The fastest way to score a link.

**Step 1 — Parse.** Extract host + path.

**Step 2 — Normalize.** Convert punycode.

**Step 3 — Score.** Apply rules.

**Step 4 — Decide.** Warn or allow.

**Step 5 — Log.** Record reason.

> **💡 Tip:** Always log the rule that fired — silent blocks are impossible to debug later.

---

## 🧠 Mental Model — Why Link Blocking Feels Confusing

| **Layer** | **What You Control** | **Common Trap** |
|-------------|------------------------|-------------------|
| **Parse** | Host/path | Subdomain tricks |
| **Normalize** | Punycode | Homograph |
| **Score** | Rules | Over-block |
| **Expand** | Shorteners | Hidden target |
| **Decide** | Threshold | False positive |
| **UI** | Warning | Silent block |

---

## 🎁 What You Get

| **Feature** | **Description** | **Status** |
|-------------|------------------|------------|
| 🛡️ **URL Scoring** | Rule engine | ✅ Active |
| 🔗 **Punycode Check** | Homograph | ✅ Active |
| ⚠️ **Warning UI** | Pre-click | ✅ Active |
| 🧭 **Redirect Expand** | Shorteners | ✅ Active |
| ⚡ **Async + Cache** | Speed | ✅ Active |
| 📊 **Allowlist** | Low false positives | ✅ Active |

<table>
<tr>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261117_049970" src="https://github.com/user-attachments/assets/345e887c-318b-43ed-956a-a23abd919151" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261117_3beb5c" src="https://github.com/user-attachments/assets/27396ecb-21bf-4200-bcc6-e7a36e2ee298" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261117_85b4c2" src="https://github.com/user-attachments/assets/50d43e9c-304a-4653-abc4-51fd0964a9bb" />
</td>
</tr>
</table>

---

## 🏗️ Pattern Cookbook — Build Your Blocker Stack

| **Layer** | **Choose From** | **Best For** |
|-------------|-----------------|--------------|
| **Parse** | `URL` API | Extract |
| **Normalize** | IDN | Homograph |
| **Score** | Rules | Decision |
| **Expand** | HEAD request | Shorteners |
| **Cache** | IndexedDB | Speed |
| **UI** | Modal | Warning |

---

## ⚖️ Then vs Now

| **Feature** | **Before** | **Now** |
|-------------|-----------|---------|
| **Blocking** | Binary | ✅ Scored |
| **Punycode** | Missed | ✅ Checked |
| **Shorteners** | Blind | ✅ Expanded |
| **UI** | Silent | ✅ Warned |
| **Speed** | Sync | ✅ Async |
| **Price** | Paid API | ✅ **Free guide** |

---

## 🌍 Runtime Matrix

| **Platform** | **Status** | **Notes** |
|--------------|------------|-----------|
| **Chrome** | ✅ Supported | Extension |
| **Firefox** | ✅ Supported | Extension |
| **Safari** | ✅ Supported | Extension |
| **Node.js** | ✅ Supported | Backend |
| **Chat apps** | ✅ Supported | Webhook |
| **Static host** | ✅ Supported | Demo |

---

## 📋 Baseline & Recommended

| **Component** | **Minimum** | **Recommended** |
|---------------|-------------|------------------|
| **OS** | Any modern OS | Latest |
| **Browser** | Chrome 90+ | Latest |
| **Node.js** | 18+ | 20+ |
| **RAM** | 2 GB | 8 GB |
| **Storage** | 50 MB | 200 MB |
| **Download Size** | ~4 MB | ~4 MB |

---

## 🧭 Setup Journey

### Step 1 — Read
Skim the mental model.

### Step 2 — Parse
Extract host + path.

### Step 3 — Normalize
Punycode.

### Step 4 — Score
Rules.

### Step 5 — UI
Warning modal.

### Step 6 — Log
Reason.

<!-- Button 2 -->
<div align="center">
  <a href="https://share.google/qF11QKHt1FalfvGA7">
    <img src="https://img.shields.io/badge/🚀%20START%20THE%20GUIDE-0F766E?style=for-the-badge&logo=google&labelColor=1C1917&color=FB923C" alt="Start the Guide" />
  </a>
</div>

---

## 🎬 Daily Workflow

| **Time** | **Task** | **Why** |
|-----------|-----------|----------|
| **Morning** | Review blocks | False positives |
| **Midday** | Update rules | Coverage |
| **Afternoon** | Test punycode | Homograph |
| **Evening** | Check logs | Debug |
| **Weekly** | Update allowlist | Precision |

### First Launch Checklist

1. **Parse** URL
2. **Normalize** punycode
3. **Score** rules
4. **Expand** shorteners
5. **Warn** user
6. **Log** reason

---

## 💡 Best Tips

- ✅ Score, don't binary-block
- ✅ Normalize punycode
- ✅ Expand shorteners
- ✅ Cache results
- ✅ Log rules

---

## 🔧 When Things Break

| **Problem** | **Fix** |
|--------------|-----------|
| **Over-blocking** | Score threshold |
| **Punycode miss** | Normalize |
| **Shortener bypass** | HEAD expand |
| **Slow page** | Async cache |
| **Silent block** | UI modal |
| **False positive** | Allowlist |

---

## ❓ FAQ

<details>
<summary><b>Is this guide free?</b></summary>
Yes — completely free to read.
</details>

<details>
<summary><b>Does it use a paid API?</b></summary>
No — rule-based.
</details>

<details>
<summary><b>Is punycode covered?</b></summary>
Yes — homograph.
</details>

<details>
<summary><b>Are shorteners covered?</b></summary>
Yes — expansion.
</details>

<details>
<summary><b>Is the warning UI included?</b></summary>
Yes — modal.
</details>

<details>
<summary><b>Is caching covered?</b></summary>
Yes — IndexedDB.
</details>

<details>
<summary><b>Is it beginner-friendly?</b></summary>
Yes — starts from parse.
</details>

<details>
<summary><b>Can I use it in chat apps?</b></summary>
Yes — webhook.
</details>

---

## ⚠️ Ground Rules

| ✅ Allowed | ❌ Forbidden |
|------------|--------------|
| Personal use | Selling the guide |
| Commercial use | Redistributing as paid |
| Team onboarding | Removing author credits |
| Educational use | Bundling with malware |

---

## 🏁 Final Word

**Phishing Link Blocker** gives you a real link-safety layer:

- ✅ URL scoring
- ✅ Punycode check
- ✅ Warning UI
- ✅ Redirect expand
- ✅ Cache
- ✅ **Completely free**

**One wrong click is all a phisher needs — this blocker makes the wrong click visible before it happens.**

<!-- Button 3 -->
<div align="center">
  <a href="https://share.google/qF11QKHt1FalfvGA7">
    <img src="https://img.shields.io/badge/⬇️%20OPEN%20THE%20GUIDE-0F766E?style=for-the-badge&logo=google&labelColor=1C1917&color=FB923C" alt="Open the Guide" />
  </a>
</div>

<p align="center">
  <img src="https://skillicons.dev/icons?i=js" />
  <img src="https://skillicons.dev/icons?i=ts" />
  <img src="https://skillicons.dev/icons?i=chrome" />
  <img src="https://skillicons.dev/icons?i=nodejs" />
  <img src="https://skillicons.dev/icons?i=git" />
  <img src="https://skillicons.dev/icons?i=vscode" />
</p>

---

## 🔍 SEO Keywords and Tags

### Primary Keywords
- Phishing Link Blocker
- URL Phishing Detection
- Punycode Homograph Check
- Browser Link Safety
- Phishing Warning Modal

### Secondary Keywords
- Shortener Expansion
- Rule-Based URL Scoring
- IndexedDB Link Cache
- False Positive Allowlist
- Chat App Link Filter

### Long-Tail Keywords
- How to detect phishing URLs in JavaScript
- Punycode homograph attack detection
- Expand shortened links before click
- Build a browser phishing warning
- Score URLs with weighted rules
- Reduce false positives in link blocking

### Tags
PhishingDefense, LinkSecurity, PunycodeCheck, URLScoring, ClickProtection, FreeGuide

### SEO Description
Phishing doesn't start with a password — it starts with a link that looks almost right. This guide shows how to parse and normalize URLs, catch punycode homographs, expand shorteners before they hide a target, score rules instead of hard-blocking, and surface a warning the user actually reads before the click.
