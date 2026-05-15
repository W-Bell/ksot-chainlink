# KSOT — Crowd Sourced Observable Truth

**"See Truth"**

A Chainlink-native **visual consensus oracle** that turns public photos into reliable on-chain attestations for Real World Assets (RWAs) and real-world events.

![KSOT Banner](https://github.com/W-Bell/ksot-chainlink/blob/main/assets/ksot-banner.jpg)
---

## 🎯 What is KSOT?

Current Chainlink RWA tools are excellent at financial Proof of Reserve and structured data, but they lack **ongoing visual ground truth**.

KSOT solves this by letting **anyone** submit geo-tagged, timestamped photos of physical assets. Multiple submissions → AI analysis → decentralized consensus → tamper-proof on-chain attestation.

### Starting Use Cases
- **Graded Collectibles** (trading cards, comics, memorabilia) — dynamic condition updates
- Weather damage verification for insurance
- Concert / event proof-of-attendance
- Public monuments & cultural heritage
- Art provenance

---

## 🔧 How It Works

```mermaid
flowchart TD
    A[Public submits geo-tagged photo] --> B[IPFS Storage]
    B --> C[Chainlink Functions: AI Analysis]
    C --> D[Multiple Submissions → Consensus]
    D --> E[Chainlink Automation Trigger]
    E --> F[On-chain Attestation]
    F --> G[RWA Contract / NFT Metadata Update]
