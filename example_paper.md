---
title: The Optica Journals Template
authors:
    - name: Sander Senhorst
      corresponding: true
      email: s.senhorst@tudelft.nl
      orcid: 0009-0005-9069-9584
      affiliations: ['TU Delft']
affiliations:
    - id: TU Delft
      institution: Delft University of Technology
      department: Department of Imaging Physics
      address: Lorentzweg 1
      postal_code: 2628 CJ Delft
      country: The Netherlands
exports:
  - format: tex+pdf
    template: ./
bibliography:
  - manual_references.bib
numbering:
  figure:
    template: Fig. %s
  table:
    template: Table %s
  equation:
    template: Eq. (%s)
---

+++ {"part": "abstract"}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
+++

## Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.{cite:p}`newton1687`

```{math}
G(\vec{r}) = \frac{\exp[jk|\vec{r}|]}{4\pi|\vec{r}|}
```

+++ {"part":"funding"}
Funding notice is optional, it will be replaced by the PRISM system later on.
+++

+++{"part": "acknowledgement"}
Additional information crediting individuals who contributed to the work being reported, clarifying who received funding from a particular source, or other information that does not fit the criteria for the funding block may also be included; for example, 'K. Flockhart thanks the National Science Foundation for help identifying collaborators for this work.'
+++

+++ {"part": "disclosures"}
Disclosures should be listed in a separate nonnumbered section at the end of the manuscript. List the Disclosures codes identified on the [Conflict of Interest policy page](https://opg.optica.org/submit/review/conflicts-interest-policy.cfm).
+++

+++ {"part": "data_availability"}
  
- When datasets are included as integral supplementary material in the paper, they must be declared (e.g., as "Dataset 1" following our current supplementary materials policy) and cited in the DAS, and should appear in the references.
- When datasets are cited but not submitted as integral supplementary material, they must be cited in the DAS and should appear in the references.
- If the data generated or analyzed as part of the research are not publicly available, that should be stated. Authors are encouraged to explain why (e.g. the data may be restricted for privacy reasons), and how the data might be obtained or accessed in the future.
- If no data were generated or analyzed in the presented research, that should be stated.
- Data availability statements are not required for preprint submissions.

+++

+++{"part": "supplemental"}
A supplemental document must be called out in the back matter so that a link can be included. For example, “See Supplement 1 for supporting content.” Note that the Supplemental Document must also have a callout in the body of the paper.
+++
