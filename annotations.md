# Systematic Review: Punishment Mechanisms in Web3 - Annotation Taxonomy

This document outlines the classification taxonomy used to annotate the 107 papers reviewed in our systematic survey "Deterring Dishonesty in Web3: A Systematic Review of Punishment Mechanisms in Decentralized Networks."

## Annotation Process Methodology

The annotation process followed a systematic two-step approach:

### Step 1: Keyword-Based Initial Tagging
We began with keyword searches across the collected papers to identify initial patterns. The search terms were organized by punishment type:

**Social Penalties (SP) Keywords:**  
`DAO-governance`, `social sanctions`, `reputation systems`, `banning`, `blacklisting`, `warnings`, `whitelisting`, `law enforcement`, `community penalties`

**Monetary Punishments (MP) Keywords:**  
`financial penalties`, `fines`, `forfeiture`, `slashing`, `staking penalties`, `asset freezing`, `economic sanctions`, `deposit loss`

**Hybrid Punishments (HP) Keywords:**  
`combined penalties`, `reputation+fine`, `blacklist+forfeit`, `legal+financial`, `multi-layered sanctions`, `escalation mechanisms`

### Step 2: Manual Content Analysis and Refinement
After initial keyword tagging, we conducted manual content analysis to:
- Verify keyword matches were contextually appropriate
- Identify papers that discussed punishment types
- Refine tags based on the paper's primary contribution
- Resolve ambiguous cases through consensus review
- Ensure consistent application of the taxonomy across all 107 papers

This combined approach ensured both systematic coverage (via keywords) and nuanced accuracy (via manual analysis) in our classification.

## Result: PAPER_INDEX.md
The outcome of this annotation process is documented in the companion file [PAPER_INDEX.md](PAPER_INDEX.md), which provides a comprehensive index of all 107 papers organized by their assigned tags, primary punishment type, and application domain. This index serves as the foundational dataset for our quantitative analysis and cross-domain comparisons.

## Core Classification Schema

All papers were categorized using a hierarchical tagging system with three primary dimensions:

1. **Punishment Type** (Primary Category)
2. **Application Scenario** (Domain Context)
3. **Enforcement Mechanism** (Enforcement approach)

## 1. Punishment Type Categories

### 1.1 Social Penalties (SP)
*Non-monetary sanctions targeting reputation or participation*

- **SP-Ban/Removal**: Complete or partial exclusion from system participation
- **SP-Reputation**: Credit score reduction, reputation damage
- **SP-Warning**: Formal notices or alerts prior to escalation
- **SP-Blacklist**: Permanent exclusion from all network interactions
- **SP-Whitelist**: Allow-list based access control (inverse of blacklisting)
- **SP-Other**: Unique social mechanisms (e.g., public shaming)
- **Law Enforcement**: Formal legal actions integrated with social penalties

### 1.2 Monetary Punishments (MP)
*Financial sanctions involving direct economic costs*

- **MP-Financial Costs**: Fines, fees, or direct monetary penalties
- **MP-Forfeits**: Permanent loss of staked or deposited assets
- **MP-Freeze**: Temporary immobilization of assets
- **MP-Slashing**: Protocol-mandated reduction of staked collateral

### 1.3 Hybrid Punishments (HP)
*Combinations of social and monetary sanctions*

- **HP-Ban/Removal+Fine**: Exclusion combined with financial penalties
- **HP-Blacklist+Financial Fine**: Permanent exclusion with monetary costs
- **HP-Blacklist+Forfeit Deposit**: Exclusion with asset forfeiture
- **HP-Legal+Fines**: Formal legal actions with financial penalties
- **HP-Reputation+Financial Fine**: Reputation damage with monetary costs
- **HP-Reputation+Forfeit Deposit**: Reputation loss with asset forfeiture
- **HP-Reputation+Freeze**: Reputation damage with asset freezing

## 2. Application Scenario Tags

### 2.1 Social Penalties by Domain
- **DAO-SP**: Social penalties applied in DAO governance contexts
- **Marketplace-SP**: Social penalties in digital asset marketplaces
- **Consensus-SP**: Social penalties in blockchain consensus mechanisms
- **DAO-governance**: Governance-specific social penalty mechanisms

### 2.2 Monetary Punishments by Domain
- **Consensus-MP**: Monetary penalties in consensus protocols
- **DAO-MP**: Monetary penalties in DAO governance
- **Marketplace-MP**: Monetary penalties in digital asset marketplaces

### 2.3 Hybrid Punishments by Domain
- **Consensus-HP**: Hybrid mechanisms in consensus protocols
- **DAO-HP**: Hybrid mechanisms in DAO governance
- **Marketplace-HP**: Hybrid mechanisms in digital asset marketplaces

## 3. Cross-Cutting Tags

- **Smart contract based enforcement Punishments**: 
- **Community voting based enforcement**: 

## Annotation Guidelines

1. **Primary Tag Selection**: Each paper receives at least one punishment type tag (SP/MP/HP)
2. **Domain Tagging**: All papers receive one or more domain tags
3. **Enfocement based**: Papers are tagged with the most specific enforcement mechanism tags
4. **Multi-tagging**: Papers addressing multiple mechanisms receive multiple tags

