---
layout: page
permalink: /submissions/
title: Call for Contributions
description:
nav: true
nav_order: 3
---

## **Call for Extended Abstracts**

We invite submissions of **extended abstracts (2–4 pages, excluding references)** that advance the field of constrained learning (deadline: ~~Aug 21, 2025~~ **Aug 28, 2025 (AOE)**.
Final versions will be posted on the [Papers tab](/papers) but **will not be part of formal proceedings**.
Accepted abstracts will be presented at the workshop during two poster sessions, with selected contributions invited to give a **short talk** (see [Contributed Talks](#contributed-talks) for details).

**Scope**: We welcome submissions on constrained optimization and its application to enforcing properties on machine learning models, with a focus on work that develops or leverages *tailored* constrained optimization techniques. In general, this excludes approaches that impose properties via penalties or regularization—that is, by augmenting the loss with a linear penalty term and minimizing the resulting unconstrained objective. (See this [Position Paper](https://arxiv.org/abs/2505.20628) for a discussion of why such methods are typically not principled in the context of constrained optimization.)

We particularly encourage contributions in the following areas:

- **Algorithms**: Fundamental algorithms for constrained optimization, especially those suited to constrained deep learning problems—i.e., differentiable, large-scale, non-convex, and stochastic settings. We welcome approaches that offer favorable efficiency-complexity tradeoffs and hyperparameter robustness in real-world applications.

- **Constraint Regularization**: Techniques that improve constraint satisfaction on unseen data.

- **Learning Theory**: Statistical learning theory for constrained problems, including results on constraint generalization, convergence, and stability.

- **Continuous Relaxations**: Techniques for solving discrete constrained problems via continuous relaxations.

- **Learning to Optimize** approaches applied to solving constrained learning problems.

- **Applications**: Practical applications of constrained optimization in deep learning. We particularly encourage submissions that highlight the crucial role of constraints in safety-critical domains (e.g., autonomous vehicles, medical diagnosis) or trustworthy AI (e.g., fairness, robustness, interpretability). *We also welcome applications that expose methodological gaps and motivate new research directions*.

- **Software**: Libraries and tools that support constrained deep learning workflows.

Submissions on both constrained minimization and constrained game formulations are welcome.

### Submission Guidelines

- Please format your submission using the modified NeurIPS style file available here: [coml_styles.zip](/assets/files/coml_styles.zip).
  (*This is the NeurIPS 2025 style file with an updated footer indicating submission or acceptance at this workshop rather than the main conference*).
- Submissions should be **2–4 pages long, excluding references and appendices**.
- Appendices are accepted but discouraged; the reviewers will not be required to read the appendices.
- Submissions will be managed through the [OpenReview portal](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/COML).

Please note the following **requirements**:
- Submissions must be **original work in progress not previously published** in peer-reviewed conferences or journals (see [Dual Submissions and Previously Published Work](#dual-submissions-and-previously-published-work) below for details).
- At least **one author is expected to attend the workshop in person**, and we encourage all authors to participate.
- Submissions are not required to include a checklist.

Submissions will be reviewed by a panel of 3 reviewers. The review process will be double-blind, and authors should ensure that their submissions do not reveal their identities.

To better understand the criteria reviewers will use when evaluating your submission, please refer to the [Reviewer Guidelines](/reviewers).

### Dual Submissions and Previously Published Work

Following the [NeurIPS 2025 workshop policies](https://neurips.cc/Conferences/2025/CallForWorkshopsGuidance), submissions must be **original work in progress not previously published** in peer-reviewed conferences or journals. Submissions found to have been previously published will be **desk-rejected**. Note that work presented at prior non-archival workshops is permitted.

**Dual submissions are allowed**, provided the other venue is either (i) non-archival (e.g., another workshop), or (ii) archival with a publication date *after* the COML notification date (September 22, 2025). If you are submitting to another venue, please ensure that your COML submission complies with that venue’s dual submission policy.

### Contributed Talks

Four extended abstracts will be selected for a **short contributed talk** at the workshop. Selection will be based on the quality and relevance of the abstract to the workshop themes.
To promote a diverse set of contributions, we aim to select one talk from each of the following categories:

- Best **fundamental** (theoretical or algorithmic) contribution,
- Best **application**,
- Best **overall** contribution,
- Best **negative results** contribution.

However, the final selection may deviate from these categories depending on the quality of submissions.

Each talk will be **10 minutes long**, followed by a **5-minute Q&A session**, and must be delivered **in person**.
Oral presenters will be notified by **Sep 29, 2025**.

### Important Dates

As per [OpenReview guidelines](https://docs.openreview.net/getting-started/frequently-asked-questions/why-does-it-take-two-weeks-to-moderate-my-profile), please ensure that you create an account at least two weeks before the submission deadline to avoid any delays.

* [**Submission deadline**](https://openreview.net/group?id=NeurIPS.cc/2025/Workshop/COML): ~~Aug 21, 2025~~ Aug 28, 2025 (AOE)
* **Author notification**: Sep 22, 2025
* **Oral selection notification**: Sep 29, 2025
* **Camera-ready version**: Oct 31, 2025 (AOE)

Please note there will be **no discussion period**; reviews and decisions will be final.

### Code of Conduct

COML authors are expected to adhere to the [NeurIPS 2025 Code of Conduct](https://neurips.cc/Conferences/2025/CodeOfConduct) and the [NeurIPS 2025 LLM Policy for Authors](https://neurips.cc/Conferences/2025/LLM). In particular, while LLMs may be used to assist in writing submissions, authors remain fully responsible for the content, which must not be entirely generated by an LLM.

## Questions?

Contact us at [constrainedml@gmail.com](mailto:constrainedml@gmail.com).