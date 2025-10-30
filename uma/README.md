# ARG25 Project Submission Template

Welcome to Invisible Garden- ARG25.

Each participant or team will maintain this README throughout the program.  
You’ll update your progress weekly **in the same PR**, so mentors and reviewers can track your journey end-to-end.



##  Project Title
UMA delta-hedged carry 

## Team
- Team/Individual Name: Structured Products
- GitHub Handles: mcmoodoo, LeeMarreros, kavehtehrani
- Devfolio Handles: Defiant, LeeMarreros, kwar13

## Project Description
UMA (probably most well known for being used by polymarket as source of truth) has a staking and voting mechanism that earns ~14-17% APR. Coupled with a short leg (e.g. in perps) you can make a delta-neutral structured yield product that earns the APR while being hedged the underlying volatility in UMA price itself, effectively stripping out the yield on the token.


## Tech Stack

Smart Contract 
* Solidity for deposit vaults enabling the users to deposit/withdraw/claim rewards

Hedging engine
* Off-chain hedging engine to deep the vault delta hedged periodically, likely in python

User interface
* Frontend to interact with the protocol, likely in Next.js


## Objectives

Deploy the vault + hedging engine at least on the testnet for a proof-of-concept to show that the yield while variable can be effectively captured on a periodical basis


## Weekly Progress

### Week 1 (ends Oct 31)
**Goals:**

**Progress Summary:**  


### Week 2 (ends Nov 7)
**Goals:**  
 
**Progress Summary:**  


### 🗓️ Week 3 (ends Nov 14)
**Goals:**  

**Progress Summary:**  



## Final Wrap-Up
_After Week 3, summarize your final state: deliverables, repo links, and outcomes._

- **Main Repository Link:**  
- **Demo / Deployment Link (if any):**  
- **Slides / Presentation (if any):**



## 🧾 Learnings
_What did you learn or improve during ARG25?_



## Next Steps
_If you plan to continue development beyond ARG25, what’s next?_



_This template is part of the [ARG25 Projects Repository](https://github.com/invisible-garden/arg25-projects)._  
_Update this file weekly by committing and pushing to your fork, then raising a PR at the end of each week._
