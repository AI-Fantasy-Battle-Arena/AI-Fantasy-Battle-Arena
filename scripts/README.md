# Scripts Directory

This directory contains deployment, automation, and maintenance scripts for the AI Fantasy Battle Arena platform. These scripts are used to manage blockchain contracts, perform token buybacks, and automate routine tasks.

## Structure Overview

```
/scripts
│── /deployment # Scripts for deploying smart contracts │ 
├── deploy_contracts.js # Deploy all blockchain contracts │
├── deploy_tokenomics.js # Deploy tokenomics-related contracts 
│── /maintenance # Scripts for ecosystem maintenance │
├── burn_tokens.js # Perform token burns periodically │
├── staking_rewards.js # Distribute staking rewards 
│── README.md # Documentation for scripts usage
```


## Key Components
1. **Deployment Scripts:**  
   Scripts to deploy blockchain contracts to various networks, ensuring proper initialization of $BATTLE tokens and in-game contracts.

2. **Maintenance Scripts:**  
   Automate tasks such as token burning, staking rewards distribution, and other ecosystem management functions.

## How to Run Scripts
1. Install dependencies for blockchain scripts:  
   ```bash
   npm install

node scripts/deployment/deploy_contracts.js

node scripts/maintenance/burn_tokens.js




