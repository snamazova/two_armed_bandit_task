# 🏆 2-Armed Bandit Task

This script defines a **2-Armed Bandit Task** for decision-making experiments. Participants must choose between two "bandits" (options), each with a different probability of giving rewards. The goal is to study learning and decision-making strategies.

---

## ✨ How It Works

- There are **25 trials** where a participant must choose **Bandit 1 (Orange) or Bandit 2 (Blue)**.
- Each bandit has a **90% chance of giving a reward** and a **10% chance of failure (reward = 0)**.
- **Bandit 1** generally has higher rewards than Bandit 2.
- The rewards per trial are randomized based on probability.

### **Reward Structure**
| Bandit  | Success Probability | Possible Rewards |
|---------|--------------------|-----------------|
| **Bandit 1 (Orange)** | 90% | **5 - 10** (higher avg reward) |
| **Bandit 2 (Blue)** | 90% | **1 - 10** (more variable) |
| Failure (for both) | 10% | **0 (no reward)** |

---