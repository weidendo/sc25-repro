# SC25 Guidelines for Paper Authors

Clone this repository. Use the style and template in this directory. See the attached PDF as example.

### Procedure

For each paper, it is mandatory to submit an AD (artifact description) appendix (see deadlines on SC25 web site).
For this, remove the 2nd part (AE) of the template and fill out the required information matching your paper as short and precise as possible.
If you cannot provide such information, add a justification instead.

In a 2nd stage, authors can optionally request badges by providing  an AE (artifact evaluation) appendix.
Submission of the AE appendix happens after acceptance notification.
The AE Appendix can be thought of showing the Reproducibility reviewers that your artifact, described in the AD Appendix,  is indeed complete, functional, or reproducible.

### Generic hints

Make sure you provide enough information in the AE appendix to make the job of evaluation as easy as possible.
An evaluation should be possible in less than 8 hours.
To increase the probability for getting the badges for your effort, you will have the chance of submitting a revised AE after a first check by a reviewer.
In addition, a reviewer may contact you via Linklings. For this, it is the decision of the reviewer to disclose her/his identity. Thus, it is fine for the AE evaluation to become double-open.

# Frequently Asked Questions

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

The AE Appendix evaluation will usually be conducted in a double-open manner (decision of the reviewer), simplifying the process for authors to grant access to specific hardware required by Reproducibility reviewers.

## Do I need a (Zenodo) DOI in the AD Appendix?

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
