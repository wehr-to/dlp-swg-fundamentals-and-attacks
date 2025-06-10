# 🛡️ DLP & SWG Fundamentals + Attack Labs

## 🎯 Purpose
This repository is a comprehensive, attack-informed knowledge base for understanding and explaining:
- Data Loss Prevention (DLP)
- Secure Web Gateway (SWG)

Includes labs, examples, policies, evasion tactics, and architecture references to showcase deep applied knowledge of both domains.

## 📚 Topics Covered

### 🔐 DLP (Data Loss Prevention)
- Core types: Endpoint, Network, Cloud
- Sensitive data matching (regex, keywords, fingerprinting)
- Policy examples: PII, PCI, code secrets
- Exfil vectors: screenshots, copy-paste, USB
- Evasion: Base64, image embedding, cloud sync bypass

### 🌐 SWG (Secure Web Gateway)
- Core function: Filter, inspect, enforce
- SSL decryption flow
- Category-based filtering and tunneling detection
- Extension-based abuse scenarios
- Policy coverage for shadow IT and risky apps

## ⚔️ Attack Simulations
- Obfuscated data leaks
- Web tunneling and protocol masquerading
- SSL inspection evasion
- Unicode + MIME manipulation
- Browser-based steganography labs

## 🗂️ Folder Guide
- `dlp_basics/`: Core concepts, examples, and bypass methods
- `swg_basics/`: How SWGs enforce policy, where they fail
- `attack_labs/`: Proof-of-concept scripts and walkthroughs
- `artifacts/`: Payloads, simulated docs, and decoded results
- `diagrams/`: Architecture visuals for interviews and slides
- `references/`: Industry control maps and behavioral Q&A

## 🧠 Ideal Use Cases
- Blue team playbook development
- Red team TTP simulations
- Interview prep and whiteboard sessions
- Internal security architecture understanding

## ✅ To Do
- [ ] Add MITM proxy lab for SWG edge case testing
- [ ] Create YARA + regex hybrid match simulation
- [ ] Add AI/ML false positive simulation (for DLP tuning)
- [ ] Vendor detection fingerprinting (Zscaler headers, etc.)

## 📄 License
MIT
