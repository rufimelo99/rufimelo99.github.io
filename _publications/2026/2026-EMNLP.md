---
title:          "When Models Know but Can't Linearly Say: Relational Encoding Limits Linear Vulnerability Classification in Code LLMs"
date:           2026-08-23 00:01:00 +0800
selected:       true
pub:            "EMNLP 2026 Findings <span class='badge badge-pill badge-publication badge-success'>A*</span>"
pub_post:       'Accepted'
pub_date:       "2026"
abstract: >-
  Large language models can detect vulnerable code, yet the form of vulnerability encoding in their representations remains unclear. We analyze 8 code models spanning 6.7B-15B parameters on C programs using three datasets (DeltaSecommits, SVEN, and PreciseBugs), comparing two diagnostic tasks on the same representations: identifying what patterns the code instantiates, and determining whether it is vulnerable. Models encode the first with high fidelity. Under the studied paired C-code datasets and linear-probing setup, vulnerability information is more accessible as a paired relational signal—whether code A is riskier than code B—than as a globally separable categorical label. This structural difference has implications for classification: the model reliably ranks which code is riskier but standard classifiers on isolated samples achieve limited accuracy because vulnerable and secure samples form overlapping distributions in representation space.
cover:          /assets/images/covers/arxiv.png
authors:
  - Rui Melo
  - Andre Catarino
  - Claudia Mamede
  - Rui Abreu
  - Corina Pasareanu
links:
  Preprint: /preprints/2026_EMNLP_When_Models_Know_but_Can_t_Say__Relational_Encoding_Limits_Vulnerability_Classification_in_Code_LLMs.pdf
---
