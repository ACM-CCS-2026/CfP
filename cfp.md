# Call for Papers

The 33rd ACM Conference on Computer and Communications Security (CCS) seeks submissions presenting novel contributions related to all real-world aspects of computer security and privacy. Theoretical papers must make a convincing case for the relevance of their results to practice. Authors are encouraged to write the abstract and introduction of their paper in a way that makes the results accessible and compelling to a general computer-security researcher. In particular, authors should bear in mind that anyone on the program committee may be asked to review any paper.

CCS has two review cycles in 2026. For each submission, one of the following decisions will be made:

+ __Accept__: Papers in this category will be accepted for publication in the proceedings and presentation at the conference, possibly after making minor changes with the oversight of a shepherd.
+ __Minor revision__: Papers in this category are considered to be promising but need some minor additional work (e.g., minor experiments, proofs to minor lemmas). Authors will be given the opportunity to resubmit such papers, with appropriate revisions, in which case they should clearly explain in a separate note how the revisions address the comments of the reviewers. The revised paper will then be re-evaluated, and either accepted or rejected.
+ __Reject__: Papers in this category are declined for inclusion in the conference. Papers rejected from the first review cycle may not be submitted again (even in revised form) to the second review cycle.
Authors of each accepted paper must ensure that at least one author registers for the conference, and that their paper is presented in-person at the conference if at all possible.

## Paper Submission Information

All submissions must be received by 11:59 PM AoE (UTC-12) on the day of the corresponding deadline. Submitted papers must not substantially overlap with papers that have been published or accepted for publication, or that are simultaneously in submission to a journal, conference, or workshop with published proceedings. All submissions should be properly anonymized. Papers should avoid revealing authors' identity in the text. When referring to their previous work, authors are required to cite their papers in the third person, without identifying themselves. In the unusual case in which a third-person reference is infeasible, authors can blind the reference itself. Papers not properly anonymized may be rejected without review. __Authors may submit up to a maximum of 7 papers at each cycle.__

All submitted papers will be evaluated based on their merits, particularly their importance to practical aspects of computer and communications security and privacy, novelty, quality of execution, and presentation. Note that CCS does not accept SoK or survey papers.

Submissions must be a PDF file in double-column [ACM format](https://www.acm.org/publications/proceedings-template) using "sigconf" 2-column format, no more than 12 pages long, excluding the bibliography, well-marked appendices, and supplementary material. Note that reviewers are not required to read the appendices or any supplementary material. Authors should not change the font or the margins of the ACM format. The CCS information, such as concepts, keywords, or rights management information (e.g., DOI and ISBN), must be retained. The teaser figure is optional. Please refer to the sample-sigconf.tex and sample-sigconf.pdf in the ACM package (also mirrored [here](https://www.overleaf.com/latex/templates/association-for-computing-machinery-acm-sig-proceedings-template/bmvfhcdnxfty)) as an example. Submissions not following the required format may be rejected without review.

Submitted papers may be rejected for being out of scope, at the discretion of the PC chairs. Authors who have questions about whether their paper is in scope are encouraged to ask the PC chairs in advance. No modifications to the author list on a paper may be made after submission.

## Ethical Considerations

Authors are expected to consider the ethical implications and potential societal impact of their work. Papers that raise ethical concerns, such as those involving human subjects, user data, or real-world vulnerability analysis, must include a dedicated "__Ethical Considerations__" section. This section should discuss the balance of risks vs. benefits and the steps taken to minimize potential harm (e.g., responsible disclosure, data anonymization). Note that institutional (IRB/ERB) approval is neither strictly necessary nor always sufficient to demonstrate ethical conduct; we expect authors to reason about the ethics of their work beyond ensuring institutional compliance. For detailed guidance on community standards, we follow the [USENIX Security'26 Ethics Policy](https://www.usenix.org/conference/usenixsecurity26/call-for-papers#ethics). This discussion section will not count toward the page limit.

## Open Science Policy

This edition of ACM CCS adopts an Open Science policy to strengthen the transparency, reproducibility, and long-term impact of published research. Authors are expected to share the artifacts underlying their results (such as code, datasets, models, scripts, and documentation) whenever legally, ethically, and practically possible.

Each submitted paper **must include an “Open Science” appendix** that:
- Enumerates all artifacts needed to evaluate the paper’s core contributions (e.g., code, datasets, models, configuration files, scripts, documentation, benchmarks).  
- Clearly describes how the program committee can access each artifact during double-blind review (including anonymous URLs or credentials, where applicable). 
- Explicitly justifies any artifact that **cannot** be shared (e.g., due to licensing restrictions, responsible disclosure concerns, safety or privacy of study subjects, or deployment risks if adversarial methods are released prematurely). When full sharing is not possible, authors are encouraged to provide partial, synthetic, or redacted artifacts that still allow reviewers to assess the methodology.

Artifacts listed in the Open Science appendix are considered part of the submission and will be used in the review process. If a claimed contribution depends on an artifact that is not available and not convincingly justified, reviewers may judge that the contribution cannot be adequately evaluated, which can negatively affect the final decision.

## Providing Artifacts at Submission Time

Artifacts are **required** for submissions whose contributions fundamentally rely on an implementation, experimental evaluation, system, tool, or dataset. This includes, but is not limited to, papers that:

1. Introduce a new system, library, or tool.  
2. Present experimental results derived from an implementation.  
3. Propose a new benchmark, dataset, or data collection methodology.

If reviewers determine that a central contribution cannot be properly evaluated without accessing artifacts that are neither provided nor convincingly justified in the Open Science appendix, the paper may be rejected.

All artifacts will be treated with the same strict confidentiality as the manuscript. Access is restricted to the assigned PC members, who may use artifacts **only** for the purpose of evaluating the paper. Any unauthorized use, sharing, or downloading for personal or professional purposes constitutes a serious ethical violation and may result in removal from the PC and additional sanctions (such as bans on future service or submissions).

To preserve anonymity in the double-blind review process:

- Authors **must** host artifacts on anonymous hosting services (e.g., <https://anonymous.4open.science>) that do not record identifying access logs (such as reviewer IP addresses).  
- General-purpose platforms like Zenodo, Figshare, or non-anonymized GitHub repositories do **not** provide sufficient anonymization and must not be used for submission-time hosting.  
- Anonymous URLs should be included directly in the submitted paper (e.g., in the Open Science appendix), not entered separately into the submission system.

For large artifacts that cannot feasibly be hosted anonymously (e.g., datasets > 1 GB), authors may provide a representative subset (such as a “toy” or validation dataset) sufficient to verify the methodology and core claims. In these cases, the Open Science appendix must explain why the full artifact cannot be shared anonymously and describe how the subset preserves the integrity and representativeness of the evaluation.

After acceptance, authors are encouraged to de-anonymize or replace the anonymous links with stable, citable repositories, consistent with the Open Science policy above, and to register their artifacts for optional Artifact Evaluation.


## Optional Artifact Evaluation

Beyond basic availability, ACM CCS offers an **optional Artifact Evaluation (AE)** process to recognize artifacts that are functional and support the reproducibility of the paper’s results.

Authors of accepted papers (including shepherd-approved and minor-revision papers) will have the option to submit their artifacts to the AE Committee for in-depth evaluation. The AEC will assess, as applicable:

- Whether the artifact is functional (e.g., code runs, scripts execute, datasets load).  
- Whether the artifact supports reproducing, within reasonable effort, the key results or claims in the paper.

A separate call for artifacts will be issued after paper acceptance, detailing submission instructions, evaluation criteria, and timelines. Artifacts that successfully pass AE may receive a corresponding recognition (e.g., badges) in the conference proceedings and on the paper’s web page.


## Policy on the Use of Generative AI and LLMs

ACM CCS follows the ACM Policy on Authorship regarding the use of generative AI tools. Authors and reviewers must adhere to the following guidelines when using Large Language Models (LLMs) and other generative AI tools (e.g., ChatGPT, Claude, Copilot).

### 1. Guidelines for Authors

The use of generative AI tools to assist in preparing submissions is permitted, provided that human authors retain full responsibility for the accuracy, originality, and integrity of the work. Generative AI tools cannot be listed as authors. By submitting to ACM CCS, authors affirm that they have critically reviewed all AI-assisted content as if they had written it themselves, including all text, figures, code, experimental data, and citations.

#### Hallucinations, Fabrication, and Falsification

Authors must carefully verify that all AI-generated content is accurate and supported by evidence. Submissions that contain hallucinated citations (e.g., references to non-existent or fabricated works), falsified or fabricated data, experiments, or results, or other invented claims presented as fact may be **desk rejected**. Such practices are treated as research misconduct (fabrication and falsification). In serious cases, suspected misconduct may be reported to the authors’ institutions and/or referred to relevant ACM bodies (such as the ACM Publications Board or ethics committees) for investigation, which may result in further sanctions, including bans on future submissions, retractions, or other disciplinary actions in accordance with ACM policy.

#### Mandatory Disclosure of Generative AI Usage

In accordance with ACM policy, all uses of generative AI tools must be disclosed.

If AI tools were used only for minor editorial improvements (e.g., grammar, spelling, or light style polishing) a brief statement in the __Acknowledgement Section__ is sufficient, such as:  “This paper was edited for grammar using [Tool Name].”

If AI tools were used to generate or substantially rewrite substantive content (e.g., sentences or paragraphs in the main text, code, data, or detailed descriptions of experiments), authors must include a dedicated **“Generative AI Usage”** paragraph at the end of the paper, before the references. This paragraph should name the tools used, describe which parts of the paper were generated or heavily assisted (for instance, drafting portions of the introduction or producing an initial code skeleton), and explain how the authors validated the AI-generated content (for example, by manual verification, re-running experiments, or cross-checking citations). This paragraph does **not** count toward the page limit.

### 2. Guidelines for Reviewers

To protect the integrity and confidentiality of the peer-review process, reviewers must not upload any part of a submitted manuscript to public generative AI tools or LLM services. Under the ACM Peer Review Policy, submissions are confidential; providing the manuscript (or any portion of it, including abstract, figures, equations, tables, or code) to a third-party AI service is prohibited, as such systems may store, index, or train on the input without the authors’ consent.

Reviewers who choose to use AI tools to assist in drafting their reviews (for example, for grammar checking of their own text) may do so only if they refrain from including any content from the submission itself.

Violations of this policy are treated as serious breaches of confidentiality. Reviewers found to have uploaded submission content to public generative AI tools will be immediately removed from the Program Committee and reported to the ACM Publications Board or other relevant ACM bodies for investigation as an ethical misconduct matter. Potential consequences include bans on future reviewing or committee service, restrictions on future submissions, and other sanctions consistent with ACM policies and procedures.

By serving on the Program Committee or submitting a paper to ACM CCS, all participants agree to comply with this policy on the use of generative AI and LLMs.

## Withdrawing Policy

Withdrawal of a paper is prohibited at any point prior to the official notification of the final decision (acceptance or rejection) being sent to the authors. By submitting a paper, authors commit to seeing the submission through the full review process. 
 
## Conference Tracks

Like last year, the ACM CCS Conference features a multi-track format. Each track operates as a separate mini-conference, with its own Track Chairs and Track Program Committee. The overall process is managed by the Program Chairs (Véronique Cortier and Zhiqiang Lin). At the time of submission, authors must select one track, which should be the most relevant to the topic of the paper. We understand that some papers might span multiple topics. In specific cases, PC members might be asked to provide reviews for papers outside their track, in an effort to provide the best possible reviews to the authors. The chairs may decide to move a paper to another track.

## Program Co-Chairs ✉ccs26-pc-chairs@acm.org

+ Véronique Cortier (CNRS, Loria)
+ Zhiqiang Lin (The Ohio State University, USA)

## Track Chairs

+ Software Security ✉ccs26-software-track@acm.org
  - Zhiyun Qian (University of California, Riverside, USA)
  - Vasileios P. Kemerlis (Brown University, USA)
+ Web Security ✉ccs26-web-track@acm.org
  - Limin Jia (CMU, USA)
+ Network Security ✉ccs26-netsec-track@acm.org
  - Christian Rossow (CISPA, Germany)
+ Security Usability and Measurement ✉ccs26-usablesec-track@acm.org
  - Mainack Mondal (IIT Kharagpur, India)
  - Michelle Mazurek (University of Maryland, USA)
+ Security and Privacy of Machine Learning ✉ccs26-mlsec-track@acm.org
  - Shiqing Ma (UMass Amherst, USA)
  - Lea Schönherr (CISPA, Germany)
  - Fabio Pierazzi (University College London, UK)
+ Formal Methods and Programming Languages ✉ccs26-formal-track@acm.org
  - Toby Murray (University of Melbourne, Australia)
+ Hardware, Side Channels, and Cyber Physical Systems ✉ccs26-hardware-track@acm.org
  - Christopher Fletcher (University of California, Berkeley, USA)
  - Alvaro Cardenas (University of California, Santa Cruz, USA)
+ Applied Cryptography ✉ccs26-crypto-track@acm.org
  - Dominique Schroeder (TU Wien, Austria)
  - Foteini Baldimtsi (George Mason University, USA)
+ Blockchain and Distributed Systems ✉ccs26-distributed-track@acm.org
  - Kartik Nayak (Duke University, USA)
+ Privacy and Anonymity ✉ccs26-privacy-track@acm.org
  - Thorsten Strufe (Karlsruhe Institute of Technology, Germany)


## Track Justification Statement (Required)

Each submission must include a brief statement (e.g., 200 words) in the appropriate section of HotCRP addressing:

+ __Track selection justification:__ Why is your selected track the best match for your work?
  
With this measure, we want to ensure that submissions are clearly aligned with the intended CCS track. For work spanning multiple tracks, simply choose the best fit and briefly explain your reasoning, and mention any fitting alternative tracks in your statement.

## Special note for Machine Learning papers submitting to CCS

Machine learning has become pervasive across security and privacy research. To ensure papers are directed to the most appropriate tracks and to clarify what constitutes a good fit for CCS, we provide the following guidelines.

### Categorization of ML-Related Papers

__ML for Security and Privacy Problems:__ If ML is used to solve a security or privacy issue, submit the paper in the track that better aligns with the __primary field of the problem being addressed__, _not_ "Security and Privacy of Machine Learning".

_Examples:_

+ [Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis](https://dl.acm.org/doi/pdf/10.1145/3658644.3670272) - uses ML for website fingerprinting, fits the "Privacy and Anonymity" track
+ [Rules Refine the Riddle: Global Explanation for Deep Learning-Based Anomaly Detection in Security Applications](https://dl.acm.org/doi/pdf/10.1145/3658644.3670375) covers a couple of "ML for security" domains, which can be motivated as a fit for the "Network Security" track
+ [Exposing Privacy Risks in Anonymizing Clinical Data: Combinatorial Refinement Attacks on k-Anonymity Without Auxiliary Information](https://arxiv.org/abs/2509.03350) focuses on k-anonymity (Privacy and Anonymity Track)
+ [Analyzing PDFs like Binaries: Adversarially Robust PDF Malware Analysis via Intermediate Representation and Language Model](https://arxiv.org/pdf/2506.17162) is primarily focused on the definition of a more robust malware detection system (Software Security Track)
+ [Securely Training Decision Trees Efficiently](https://dl.acm.org/doi/pdf/10.1145/3658644.3670268), which is primarily focused on privacy-preserving ML with a heavy cryptographic component (Applied Cryptography)

__Security and Privacy of Machine Learning:__ If your work directly addresses the security or privacy of ML itself, the Security and Privacy of Machine Learning track is the right fit. This must also be stated in the Track Justification Statement, clarifying the authors' decision not to submit to a domain-specific track (e.g., Web Security, Software Security).

Relevant work investigates novel attacks (e.g., data poisoning, backdoors, adversarial examples, prompt injection, model inversion, membership inference) or defenses (e.g., attack detection, secure training methods, post-attack forensics) throughout the ML lifecycle under plausible threat models that could occur in practice, not based on unrealistic assumptions or unlikely scenarios.

All papers submitted to this track must provide a threat model that clearly articulates the (i) envisioned attacker(s), (ii) threat surfaces (e.g., system components including but not limited to the underlying machine learning algorithm), (iii) generality (e.g., demonstrating that the attack is not limited to a specific model but generalizes across model architectures or families.), and (iv) practicality of the attack. __If the authors believe they still fit the "Security and Privacy of Machine Learning" track without the need for a threat model, they need to explicitly justify this in the Track Justification Statement.__

The paper evaluation needs to be linked to the threat model and scenario motivating the paper. Strong submissions produce generalizable contributions such as frameworks for risk assessment, attack patterns that generalize across models, systematic problem characterizations, or principled defenses with clear justification. Papers that present collections of examples or trial-and-error probes, or approaches lacking methodical rigor, will be considered out of scope.

Purely theoretical ML works without actionable security insights are out of scope, as are papers focusing on generic ML properties (e.g., robustness to natural noise) that lack clear security implications.

_Examples of suitable papers:_

+ "[Beowulf: Mitigating Model Extraction Attacks Via Reshaping Decision Regions](https://dl.acm.org/doi/10.1145/3658644.3670267)" - addresses model extraction attacks with practical defense, fits the "Machine Learning and Security" Track
+ "[Membership Inference Attacks Against In-Context Learning](https://dl.acm.org/doi/10.1145/3658644.3690306)" - focuses on the privacy of LLMs, fits the "Machine Learning and Security" Track
+ "[Membership Inference Attacks as Privacy Tools: Reliability, Disparity and Ensemble](https://arxiv.org/pdf/2506.13972)" focuses primarily on analyzing evaluations of membership inference attacks, and fits the "Machine Learning and Security" track.
+ "[Watch Out! Simple Horizontal Class Backdoor Can Trivially Evade Defense](https://dl.acm.org/doi/10.1145/3658644.3670361)" focuses on the security of MLs, proposing a new type of backdoor with a realistic threat model, which fits the "Machine Learning and Security" track

## Conflicts of Interest

The conference requires cooperation from both authors and program committee members to ensure a fair review process. For this purpose, authors must report all program-committee members who, in their opinion, have a conflict of interest and therefore may not be able to provide an unbiased review. Mandatory declared conflicts of interest include current or former doctoral advisor/advisee, members of the same institution, close family members, and recent co-authors (within the past 2 years). For any other declared conflict, authors are required to explain the nature of the conflict Program Chairs and the Track Chairs. The chairs reserve the right to request further explanation and can remove non-mandatory conflicts at their discretion.

Track Chairs are not allowed to submit papers in their own track but they may submit any number of papers in other tracks, subject to a maximum of 7 papers per cycle.

Program-committee members who have a genuine conflict of interest with a paper, including the Program Chairs and the Track Chairs, will be excluded from evaluation and discussion of that paper. When a Track Program Chair has a conflict, the paper will be handled by the Program Chairs. When a Program Chair is conflicted, the other Co-Chair will be responsible for managing that paper. When both Program Chairs are in conflict, a committee member will be appointed to handle the paper. Program Chairs are not allowed to be authors or co-authors of any submissions.

## Policy for Peer-Review Integrity

All SIGSAC sponsored conferences and workshops are required to follow ACM policies against harassment activities (https://www.acm.org/about-acm/policy-against-harassment) and ACM Code of Ethics and Professional Conduct (https://www.acm.org/code-of-ethics). Also all authors, PC members and non-PC reviewers are required to follow ACM Publications Policies (https://www.acm.org/publications/policies/toc). Particularly, we require all reviewers to uphold the integrity of the peer review process and avoid conflict of interest of any form (e.g., reviewer collusion ring). Those who violate these policies will be penalized according to ACM policies (https://www.acm.org/publications/policies/penalties-for-publication-violations). If you would like to report a violation, please contact program chairs of your conferences/workshops or SIGSAC officers. We are committed to protecting the confidentiality of your communication.

## Important Dates

### First Review Cycle

- **Abstract submission deadline**  
  Jan 7, 2026 *(Mandatory: all papers must have an abstract submitted by this date)*

- **Full paper submission deadline**  
  Jan 14, 2026

- **Notification of early-rejection papers**  
  Feb 18, 2026

- **Author rebuttal period**  
  Mar 16–19, 2026

- **Rebuttal deadline**  
  Mar 19, 2026

- **Author notification**  
  Apr 9, 2026

- **Minor revision approval deadline**  
  June 5, 2026

- **Camera ready deadline**  
  August 21, 2026

 
### Second Review Cycle

- **Abstract submission deadline**  
  Apr 22, 2026 *(Mandatory: all papers must have an abstract submitted by this date)*

- **Full paper submission deadline**  
  Apr 29, 2026

- **Notification of early-rejection papers**  
  June 1, 2026

- **Author rebuttal period**  
  June 23–26, 2026

- **Rebuttal deadline**  
  June 26, 2026

- **Author notification**  
  July 17, 2026

- **Minor revision approval deadline**  
  Sept 6, 2026

- **Camera ready deadline**  
  Sept 17, 2026
 

## Submission Site

- First review cycle: <https://ccs2026a.hotcrp.com/>  
- Second review cycle: <https://ccs2026b.hotcrp.com/>

**Please Note:** The official publication date is the first day of the conference. The official publication date affects the deadline for any patent filings related to published work.


## Community Standards & Anti-Harassment

ACM CCS is committed to promoting diversity and inclusion in our community. If you have suggestions, concerns, or complaints related to biases or sexual harassment, we encourage you to reach out to the Program Chairs. We are committed to protecting the anonymity of such reports and helping to address your concerns. We value your feedback and ideas to help us all build a healthier and more welcoming community.

We encourage the authors to be mindful of not using language or examples that further the marginalization, stereotyping, or erasure of any group of people, especially historically under-represented groups (URGs) in computing. Of course, exclusionary treatment can arise unintentionally. Be vigilant and actively guard against such issues in your writing. Reviewers will also be empowered to monitor and demand changes if such issues arise in your submissions. Please check the link for more information.

## Agreements

By submitting your article to an ACM Publication, you are hereby acknowledging that you and your co-authors are subject to all [ACM Publications Policies](https://www.acm.org/publications/policies), including [ACM's new Publications Policy on Research Involving Human Participants and Subjects](https://www.acm.org/publications/policies/research-involving-human-participants-and-subjects). Alleged violations of this policy or any ACM Publications Policy will be investigated by ACM and may result in a full retraction of your paper, in addition to other potential penalties, as per ACM Publications Policy.

Please ensure that you and your co-authors [obtain an ORCID ID](https://orcid.org/register), so you can complete the publishing process for your accepted paper. ACM has been involved in ORCID from the start and we have recently made a [commitment to collect ORCID IDs from all of our published authors](https://authors.acm.org/author-resources/orcid-faqs). We are committed to improve author discoverability, ensure proper attribution and contribute to ongoing community efforts around name normalization; your ORCID ID will help in these efforts.

## <u>Important update on ACM's new open access publishing model for 2026 ACM Conferences!</u>

Starting January 1, 2026, ACM will fully transition to Open Access. All ACM publications, including those from ACM-sponsored conferences, will be 100% Open Access. Authors will have two primary options for publishing Open Access articles with ACM: the ACM Open institutional model or by paying Article Processing Charges (APCs). With over 1,800 institutions already part of ACM Open, the majority of ACM-sponsored conference papers will not require APCs from authors or conferences (currently, around 70-75%).

Authors from institutions not participating in ACM Open will need to pay an APC to publish their papers, unless they qualify for a financial or discretionary waiver. To find out whether an APC applies to your article, please consult the list of [participating institutions](https://libraries.acm.org/acmopen/open-participants) in ACM Open and review the [APC Waivers and Discounts Policy](https://www.acm.org/publications/policies/policy-on-open-access-apc-waivers-and-discounts). Keep in mind that waivers are rare and are granted based on specific criteria set by ACM.

Understanding that this change could present financial challenges, ACM has approved a temporary subsidy for 2026 to ease the transition and allow more time for institutions to join ACM Open. The subsidy will offer:
+ $250 APC for ACM/SIG members
+ $350 for non-members

This represents a [65% discount](https://www.acm.org/publications/openaccess), funded directly by ACM. Authors are encouraged to help advocate for their institutions to join ACM Open during this transition period.

This temporary subsidized pricing will apply to all conferences scheduled for 2026.
