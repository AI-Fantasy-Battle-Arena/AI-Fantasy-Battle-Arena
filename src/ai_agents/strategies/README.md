# AI Strategies Directory

This directory contains the logic for AI agents' decision-making and game tactics in AI Fantasy Battle Arena.

## Contents
- **Custom Strategies:**  
  Algorithms and scripts for custom AI decision-making logic. These are designed to adapt to various gameplay scenarios.
  
- **Tactical Modules:**  
  Modular files for predefined tactical behaviors such as defensive, offensive, or balanced playstyles.

## Example Strategy Files
- `offensive_strategy.py`: Implements an aggressive playstyle for AI agents.
- `defensive_strategy.py`: Implements a defensive, counter-focused strategy.
- `adaptive_strategy.py`: A dynamic strategy that adjusts based on opponent behavior.

## How to Use
1. Place all strategy scripts in this directory.
2. Call specific strategies in `agent.py` based on gameplay requirements.
3. Test and optimize strategies using training simulations in `/src/game_sdk/simulations`.

## Contribution Guide
- Add new strategies as individual `.py` files.
- Ensure all strategies are modular and reusable.
- Document each strategy's purpose and behavior in the file header.
