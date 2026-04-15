# GitHub Copilot Plans & Subscription Model

> Reference: [github.com/features/copilot/plans](https://github.com/features/copilot/plans)

GitHub Copilot offers 5 subscription tiers — 3 for individuals and 2 for organizations — each with increasing capabilities, model access, and premium request quotas. 

---

## Understand the Plans

<img width="1144" height="362" alt="image" src="https://github.com/user-attachments/assets/ab7b27c1-6c85-40bb-9fcd-90454edda04e" />

### 1. What is the difference in Premium requests, Chat/agent mode and Code completions?

#### Code Completions (the inline text)
        You're typing in VS Code:
        
            def calculate_tax(income, rate): # ← you pause here
        
        Copilot shows grey text: return income * rate / 10
        
        You press Tab to accept. That's 1 code completion. This happens automatically as you type — no prompt needed. On Free plan,
        you get 2,000 of these/month. On paid plans, unlimited.

#### Chat/Agent Mode (conversations)

        You open Copilot Chat and type: 
        
            "Refactor this function to handle negative income and add unit tests"

        Copilot reads your code, generates a refactored version, writes tests, maybe edits multiple files. That's 1 chat/agent request.

#### Premium Requests (the cost layer)

        Premium requests = the currency that chat/agent interactions cost, based on the model:

            You open Copilot Chat and type: 
            
                "explain this code"
   
       Using GPT-5 mini (0x):   0 premium requests deducted  ← FREE on paid plans
       Using Sonnet 4.6 (1x):   1 premium request deducted
       Using Opus 4.6 (3x):     3 premium requests deducted  ← Expensive one

### 2. GitHub Copilot's billing is entirely request-based, not token-based:

<img width="837" height="204" alt="image" src="https://github.com/user-attachments/assets/bc131911-0418-442a-b87f-69b58b1509a3" />

### 3. What does Premium Request Multipliers mean:

<img width="809" height="245" alt="image" src="https://github.com/user-attachments/assets/3562b347-830d-4aea-a869-365f7c0a9f5a" />


### 4. How do I know which Copilot plan I am using:

  #### Go to https://github.com/settings/copilot/features

  <img width="1051" height="529" alt="image" src="https://github.com/user-attachments/assets/ac8ec151-b732-43dd-9004-afd12545989c" />
