# Codebook: Annotation Guidelines and Definitions

## Purpose
This codebook provides explicit definitions and decision rules for consistently applying the annotation taxonomy to research papers on Web3 punishment mechanisms.

## Core Definitions

### 1. Punishment Types

**Social Penalties (SP):** Any non-monetary sanction that affects a participant's reputation, standing, or ability to participate without direct financial cost.

**Monetary Punishments (MP):** Sanctions that impose direct financial costs, including loss of assets, fines, or temporary asset freezes.

**Hybrid Punishments (HP):** Mechanisms that combine elements of both social and monetary penalties, where both types of sanctions are integral to the proposed system.

### 2. Domain Contexts

**Consensus:** Protocols and mechanisms related to blockchain validation, block production, or network security (PoW, PoS, etc.).

**DAO Governance:** Decentralized Autonomous Organizations, including voting systems, proposal mechanisms, and community management.

**Marketplace:** Digital asset exchanges, NFT platforms, DeFi protocols, and other trading environments.

### 3. Mechanism-Specific Definitions

#### Social Penalties (SP)
- **SP-Ban/Removal:** Complete or temporary exclusion from system participation
- **SP-Reputation:** Quantitative or qualitative reduction in social standing
- **SP-Warning:** Formal notification of violation without immediate penalty
- **SP-Blacklist:** Permanent, public exclusion list
- **SP-Whitelist:** Allow-list granting exclusive access privileges
- **Law Enforcement:** Formal legal actions, regulations, or compliance requirements

#### Monetary Punishments (MP)
- **MP-Financial Costs:** Direct monetary fines or fees
- **MP-Forfeits:** Permanent loss of staked or deposited assets
- **MP-Freeze:** Temporary immobilization of assets
- **MP-Slashing:** Protocol-mandated reduction of validator stake

#### Hybrid Punishments (HP)
- **[Social]+[Monetary]:** Combination tags indicate both components are present
- **HP-Ban/Removal+Fine:** Exclusion with concurrent financial penalty
- **HP-Blacklist+Financial Fine:** Permanent exclusion with monetary cost
- **HP-Reputation+Financial Fine:** Reputation damage plus fine
- **HP-Legal+Fines:** Regulatory actions with financial penalties

## Decision Rules

### Rule 1: Primary Type Assignment
Assign the primary punishment type based on the paper's **main contribution**:
- If paper proposes/enhances a monetary mechanism → MP
- If paper focuses on reputation/social systems → SP  
- If paper explicitly combines both → HP
- If unclear, default to most emphasized mechanism

### Rule 2: Domain Assignment
Papers may receive multiple domain tags if they:
1. Propose mechanisms applicable to multiple domains
2. Compare mechanisms across domains
3. Present general frameworks with domain examples

### Rule 3: Mechanism Tagging
- Tag **all** mechanisms discussed in detail
- Do not tag mechanisms only mentioned in passing
- Use most specific applicable tag
- Add "Law Enforcement" tag if legal frameworks are substantive component

### Rule 4: Edge Cases

**Case A:** Paper discusses monetary penalties in passing but focuses on social system
- **Decision:** Primary = SP, add MP-related domain tag if relevant

**Case B:** Paper compares SP and MP but doesn't combine them
- **Decision:** Tag both SP and MP, but HP only if integration is proposed

**Case C:** General governance paper with punishment examples
- **Decision:** Tag by example domains/mechanisms

## Quality Assurance Checks

### Consistency Checks
1. No paper should have only domain tags without mechanism tags
2. HP papers must have at least one SP and one MP mechanism tag
3. Law Enforcement tag should co-occur with at least one other mechanism tag

### Completeness Checks  
1. All 107 papers must have at least one primary type tag
2. All papers must have at least one domain tag
3. Mechanism tags should cover the paper's main contributions

## Examples with Rationale

### Example 1: Pure Slashing Paper
- **Paper:** "Game-Theoretic Analysis of Ethereum Slashing"
- **Tags:** MP, Consensus-MP, MP-Slashing, MP-Forfeits
- **Rationale:** Focuses exclusively on monetary penalties in consensus

### Example 2: DAO Reputation System
- **Paper:** "Decentralized Reputation for DAO Governance"
- **Tags:** SP, DAO-SP, DAO-governance, SP-Reputation, SP-Warning
- **Rationale:** Social penalties in DAO context with multiple mechanisms

### Example 3: Marketplace Anti-Fraud System
- **Paper:** "Hybrid Penalties for NFT Market Fraud"
- **Tags:** HP, Marketplace-HP, HP-Reputation+Financial Fine, HP-Blacklist+Financial Fine
- **Rationale:** Combines social (reputation, blacklist) and monetary (fines) penalties

## Version History

- **v1.0** (Initial): Basic taxonomy based on Zotero tags
- **v1.1** (Current): Added decision rules and examples
- **Future:** Will expand based on intercoder reliability testing
