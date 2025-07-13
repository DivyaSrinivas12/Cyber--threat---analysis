
# 📊 Cybersecurity Analysis Projects

## 👩‍💻 Author
**Divya S**  
📧 divya2k05@gmail.com  
📞 6361571334

---

## 📁 Project 1: Cyber Analysis on OpenAI SORA

### 🔎 Objective
Analyzing the cybersecurity posture and online presence of **SORA**, OpenAI’s text-to-video AI platform.

### 📌 Key Components

- **Footprinting**
  - Website header inspection
  - Metadata analysis
  - Domain & subdomain details
  - Email address reconnaissance

- **Host & Network Discovery**
  - Target: SORA (Specific Operations Risk Assessment)

- **SORA Overview**
  - Generates 60s realistic videos from text prompts
  - Uses diffusion models
  - Founded by OpenAI (2024), based in San Francisco
  - Involved in DeFi via Polkaswap & SORA Wallet

- **SORA Versions**
  - `V1` (2018): Based on Hyperledger Iroha  
  - `V2` (2021): Added tokenomics, Substrate parachain  
  - `V3` (2024–): Multi-chain support, DeFi, High TPS  

- **Audience**
  - Students, parents, marketers, creatives, educators

### 🌐 Web & Media Presence

| Platform    | Activity |
|-------------|----------|
| Instagram   | Monthly posts & reels |
| LinkedIn    | Infrequent (last ~5 months ago) |
| Twitter     | Very few annual posts |
| Facebook    | Inactive |
| YouTube     | 1–2 videos/year (e.g., tokenomics) |

### 📮 Active Emails
- support@openai.com  
- contact@openai.com  
- ar@openai.com  

### 👍 Pros
- High-quality video generation from text  
- Advanced editing: Remix, Storyboard, Re-cut  
- Accessible to non-experts  

### 👎 Cons
- Struggles with scene continuity  
- Unnatural physics  
- Slow rendering on high-res  

### ⚙️ Tools Used
- `curl -i` to test web headers (403 Forbidden shown)  
- Intrusion Detection System (IDS)
- Nmap- Zenmap GUI
- Who is, (WEBSITE)
- Command Prompt, CMD

---

## 🛡️ Project 2: Cloud Security & Memory Injection

### 🎯 Role: Information Security Officer

#### 🌩️ Cloud Data Protection

- **Authentication**: Physical (e.g., biometrics), digital (e.g., captchas, passwords)  
- **Encryption**: Pre-transfer & in-storage, cloud cryptography (quantum-based)  
- **Integrity**: ALOCA principle (Attributable, Legible, Original...)  
- **Multi-Factor Authentication**: Enhances access control  
- **Firewall & Software Patching**: Protect against malware and DoS attacks  

#### ☁️ Cloud Type Recommendation

| Model | Description | Use Case |
|-------|-------------|----------|
| Public | Shared, scalable | Standard workloads |
| Private | Dedicated | Critical systems |
| Hybrid | Both | Balanced, scalable & secure |

> **Preferred:** Hybrid cloud (secure + scalable)

#### 📂 Data Classification

- Based on sensitivity: Public, Internal, Confidential  
- Helps prioritize encryption & access policies  
- Use of automated tools + manual oversight

---

### 🕵️‍♂️ Digital Forensics Decision

- **Forensic Imaging Only**: Do not store evidence directly on hard drive  
- Preserve integrity, avoid altering data, maintain chain of custody

---

### 💉 Memory Injection Techniques

#### What is Process Injection?
Injecting malicious code into another process to inherit its privileges and bypass detection.

#### Common Techniques

| Technique | Description |
|----------|-------------|
| **DLL Injection** | Loads malicious DLL via remote thread |
| **Reflective DLL Injection** | Loads DLL entirely in-memory (fileless) |
| **Process Hollowing** | Replaces code of a legitimate suspended process |
| **Thread Hijacking** | Redirects execution of an existing thread |

#### Malware Using These Techniques
- Trojan Horses
- Remote Access Trojans (RATs)
- Worms (Email, IRC, IM)
- Fileless Malware (Memory-resident, hard to detect)

---

### 🔬 Forensic Analysis Tools
- **Sysmon** (Windows logs)  
- **Volatility** (Memory dump analysis)  
- **Metasploit** (Reflective DLL injection)  
- **WinDBG** (Low-level inspection)

---

## 📎 References

- [SORA Review](https://medium.com/artificial-corner/my-honest-review-of-openais-sora-and-how-it-compares-with-other-ai-video-generators-e9b19c251b27)  
- [MITRE ATT&CK T1055](https://attack.mitre.org/techniques/T1055/)  
- [Volatility Plugin Docs](https://volatilityfoundation.org/)  
- [Reflective DLL GitHub](https://github.com/stephenfewer/ReflectiveDLLInjection)  
