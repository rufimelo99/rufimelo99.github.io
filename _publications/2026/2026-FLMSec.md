---
title:          "SEVRA-BENCH: Social Engineering of Vulnerabilities in Review Agents"
date:           2026-10-08 00:01:00 +0800
selected:       true
pub:            "NeurIPS 2026 FLMSec Workshop (non-archival)"
pub_post:       'Accepted'
pub_date:       "2026"
abstract: >-
  Large language models (LLMs) are increasingly deployed in automated code-review systems, where their approvals can determine which code is merged into shared repositories. However, it is unclear whether review agents can detect vulnerability-introducing code when an attacker controls both the code change and the persuasive Pull Request (PR) narrative designed to mask it. We introduce SEVRA-BENCH (Social Engineering of Vulnerabilities in Review Agents), a benchmark that measures how often a review agent approves such adversarial PRs. Each PR in SEVRA-BENCH is built from a historical commit that fixed a vulnerability. We automatically reverse that fix to extract the original vulnerable code, and submit the resulting code change as a PR wrapped in one of 15 social-engineering framings. To test review-agent resilience to narrative manipulation, these framings vary dimensions such as supporting evidence, conveyed urgency, signals of prior approval, and appeals to authority. SEVRA-BENCH evaluates a retained challenge split of roughly 1000 adversarial PRs drawn from publicly disclosed vulnerability fixes across the top 10 entries of the MITRE's 2025 most dangerous software weaknesses. Evaluating 8 review agents against this benchmark, we reveal that review agents are susceptible to narrative manipulation, exposing a significant gap in security capabilities.
cover:          /assets/images/covers/NIPS.png
authors:
  - Rui Melo
  - Riccardo Fogliato
  - Sean Zhou
  - Pratiksha Thaker
  - Zhiwei Steven Wu
links:
  Preprint: https://arxiv.org/abs/2606.13757
  Workshop Version: /preprints/2026_NIPS_FLMSec_SEVRA_BENCH__Social_Engineering_of_Vulnerabilities_in_Review_Agents.pdf
---
