# DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models

## Overview (C)

## Question1 (C)


## Question2 (S)
### "What makes GPT-4 more vulnerable to generating toxic or biased outputs in adversarial contexts compared to GPT-3.5, and what specific prompt types can lead to such behaviors?"
- Key Reasons for GPT-4’s Increased Vulnerability

- **Enhanced Instruction Following:** 
  - GPT-4 has improved capabilities to follow instructions precisely, which is beneficial for most tasks but makes it more susceptible to adversarial prompts that guide it toward toxic or biased outputs.
  - *Because GPT-4 is better at following instructions, it is more likely to produce harmful outputs if prompted with carefully crafted, misleading instructions.*

- **Sensitivity to Adversarial Prompts:**
  - The paper shows that GPT-4 responds to certain adversarial prompt types—like “role-playing” or “straightforward instructions” that bypass content filters—by following them more rigorously than GPT-3.5.
  - This increased sensitivity makes it easier for adversaries to manipulate GPT-4 into generating undesirable content.

- **Complex Prompt Interpretation:** 
  - GPT-4 can interpret complex prompts with intricate context, which inadvertently makes it more responsive to nuanced adversarial instructions that encourage biased or toxic content.

### Supporting Figures from the Paper


- **Figure 2: *Examples of Undesirable Responses of GPT-4 Given Adversarial System Prompts***
  - This figure showcases specific examples where adversarial prompts lead GPT-4 to produce toxic or offensive content.
  - *These examples illustrate how GPT-4’s improved instruction-following ability can lead to undesirable outputs when adversarial prompts are introduced.*

- **Figure 7: *Toxicity of GPT-3.5 and GPT-4 Given Diverse System Prompts***
  - This figure compares the average toxicity scores for GPT-3.5 and GPT-4 across various adversarial prompts.
  - It highlights that GPT-4 has consistently higher toxicity scores than GPT-3.5, especially when straightforward or role-playing prompts are used.
  - *By analyzing this figure, the audience can see that certain adversarial prompt types are particularly effective at provoking toxic outputs from GPT-4.*




## Architecture overview (C)

## Critical Analysis (S)


## Impacts (S)


## Resource links ()


## Code demo

## Citation for paper