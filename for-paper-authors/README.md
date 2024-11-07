# SC25 Guidelines for Paper Authors

Here, we compile a list of frequently asked questions concerning the AD/AD Appendices.

## Stick to the Template

- Ensure the subsequent **two lines are commented out** prior to submitting the appendix! Ensure all text is in black; remove any blue text.
  ```latex
  %\usetag{explanation}
  %\usetag{example}
  ```

- Use the provided LaTeX template!

- Do not alter the template, i.e., do not add author names, affiliations, etc.

- Do not misuse the AD/AE Appendices to include additional information apart from the artifacts. Do not include mathematical proofs in these appendices.

## Anonymity of AD/AE Appendices

The Reproducibility committee works on Linklings in a single-anonymous manner, which means that authors can reveal their identity on GitHub or Zenodo or other platforms.

IMPORTANT: When **submitting the AD Appendix** (as well as the AE Appendix later), authors **do not have to hide their identity**. We ensure that authors' names are not revealed to the Papers committee, which works dual-anonymously, which is different from the Reproducibility committee.

After paper acceptance, authors can request badges by providing an AE Appendix. The AE Appendix can be thought of
showing the Reproducibility reviewers that your artifact, described in the AD Appendix,  is indeed complete, functional, or reproducible. The AE Appendix evaluation will be conducted in a double-open manner, simplifying the process for authors to grant access to specific hardware required by Reproducibility reviewers.

## Do I need to a (Zenodo) DOI in the AD Appendix?

In general, the AD Appendix should contain an artifact that is publishable, as authors don't have the obligation to update the AD Appendix after acceptance.

However, numerous authors have concerns that a DOI would make the source code of possibly rejected papers public, which is undesirable.

To make things simpler, you may either:
1. reference a GitHub/Gitlab repo in the AD Appendix and create DOIs later in the AE stage, or
2. include a link to a private repository. Since the AD appendix will only be accessible by members of the Reproducibility committee, it will neither be public nor shared with the Papers committee. You will have to create a public DOI once the paper is accepted.

## Is access to Chameleon required for submitting the AD Appendix?

No, the computational artifact(s) in the AD Appendix should be described in a general manner.

Chameleon is only needed when requesting badges (when submitting the AE Appendix). Then, authors need to show in the AE Appendix that their description from the AD Appendix is indeed exercisable.

## Can authors reference figures or tables from the AD/AE Appendices in the paper?

No, a paper should be self-consistent, as reviewers assess solely the manuscript.
Accordingly, authors should avoid forward referencing figures or tables in the AD/AE Appendices.

Authors can incorporate a "conventional" appendix into their manuscript, which will count towards the 10-page limit, ensuring it is integrated into the main document.

In contrast, the AD/AE Appendices should only be used to describe the computational artifacts (AD)
and how to execute them by example on a designated computational platform (AE).

## How to deal with proprietary code or other legal constraints?

After submitting a paper to SC25 via [https://submissions.supercomputing.org/](https://submissions.supercomputing.org/), author have the option to upload an AD Appendix.


In certain cases, authors might be unable to share the full computational artifact accompanying a paper. Under these circumstances, they have two alternatives.

1. On [https://submissions.supercomputing.org/](https://submissions.supercomputing.org/), authors may choose not to submit an AD Appendix, such as in cases of proprietary code restrictions. If authors opt-out, they must provide a detailed explanation on why
an AD Appendix could not be provided. This explanation will be entered directly in the submission system (i.e., the explanation is not part of the AD Appendix).
2. (preferred) Even in scenarios where the disclosure of source code is not feasible, authors are still encouraged to compile an Artifact Description (AD) Appendix, encapsulating all other important information of the computationl artifact.
Authors should follow the provided AD/AE template and fill in as much information as can be shared.
For instance, if a Digital Object Identifier (DOI) for a computational artifact cannot be provided, authors may simply enter "N/A" or "N/A (proprietary)" in the corresponding section of the AD Appendix.
