<div align="center">

# 🧩 GoPwnIt Challenge Format & Standards

### Official structure and guidelines for creating CTF challenges

</div>

---

## 🔍 Introduction

This document defines the **official format and standards** for creating Capture The Flag (CTF) challenges on **GoPwnIt**.

All challenge creators and contributors must follow these guidelines to ensure:
- Consistent quality  
- Fair difficulty distribution  
- Smooth deployment and evaluation  

---

## 📂 Standard Challenge Structure

Each challenge must follow the structure below:


---

## 📝 Challenge README Requirements

Every challenge **must include a `README.md`** containing:

- Challenge title  
- Category (Web / Pwn / Crypto / Forensics / OSINT / Misc)  
- Difficulty level (Easy / Medium / Hard)  
- Point value  
- Problem description  
- Flag format  
- Author name (optional)  

---

## 🚩 Flag Format

- Flags must follow the standard format:

  - Flags must be:
- Unique per challenge  
- Case-sensitive  
- Non-guessable  

Do not reuse flags across challenges.

---

## 🎯 Difficulty Guidelines

| Difficulty | Description |
|----------|-------------|
| Easy | Beginner-friendly, minimal tools |
| Medium | Requires chaining concepts |
| Hard | Advanced techniques and deep analysis |

Difficulty must reflect **actual solving complexity**, not guesswork.

---

## 🧠 Solution Writeup

Each challenge must include a solution writeup:
- Step-by-step explanation  
- Tools and techniques used  
- Clear reasoning  

Solution files must **never be publicly accessible** during active seasons.

---

## 🐳 Docker-Based Challenges (If Applicable)

For service-based challenges:
- Use Docker for isolation  
- Ensure stable startup and teardown  
- Expose only required ports  
- Avoid unnecessary services  

---

## 🔐 Security & Ethics

- Do not include real-world targets  
- Do not include sensitive credentials  
- Do not intentionally harm participants’ systems  
- Challenges must be self-contained  

---

## 🧪 Testing Requirements

Before submission:
- Test challenge from a fresh environment  
- Verify flag correctness  
- Ensure no unintended shortcuts exist  

Broken or unstable challenges may be rejected.

---

## 🚫 Prohibited Content

The following will **not** be accepted:
- Copied or leaked challenges  
- Malware with destructive intent  
- Real-world vulnerability exploits  
- Illegal or unethical content  

---

<div align="center">

**Build Fair. Test Hard. Challenge Smart.**

</div>



