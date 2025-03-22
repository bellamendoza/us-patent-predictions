# Research

## Overarching Topics
- Impact of federal funding on innovation
- Bias of federal funding
    - Do tier 1 schools recieve more support than MSI? Does it hinder MSI ability to innovate?
- Forcasting trends of "successful" R&D that is federally funded
    - if successful means patented
- Predict patent's funding agency, maybe predict most effective agencies for innovation
- Predict the probability of a patent being approved for federally funded R&D
    - see if there is a difference of federally funded R&D vs private
- Compare the impact of federally funded patents vs non-federally funded patents


## Data Sources
- USPTO PatentsView
    - inventors, institutions, citations
- USASpending
- Might want to zoom in on NSF, NIH awards data: https://reporter.nih.gov/
- IPEDS (Integrated Postsecondary Education Data System)


## Future ideas
- Predicting when a less cited patent will become a heavily cited patent
- Classifying patents as for genuine innovation vs for suing other companies
    - could involve nlp, case documents

## Notes
- Maybe "sucessful innovation" is measured by number of citations a patent has rather than whether or not the work is patented, or maybe it is both.
- cited by examiner vs cited by applicant.
    - by examiner: used to in attempt to disprove that the invention is novel in the official review process.
    - by applicant: used to show that their invention is novel or to show they are aware of existing technologies.
    -  both are important, but maybe we can argue that the examiner citations hold more weight bc an applicant might be less inclined to    
    include citations that prove their inventions are not original
    - only utility patents have cpc assignments on patentview (https://patentsview.org/forum/7/topic/537)
        - Non-utility patents must include a prefix: 'D' for design patents, 'PP' for plant patents, 'RE' for reissue patents, 'T' for defensive publications, and 'H' for SIRs
    - There are different types of patents:
        - Utility patents: new inventions, have Cooperative Patent Classification (CPC) to classify invention based on technical field, 20 yr protection from filing date
    - Design patents (D): protect the ornamental design of an item, no CPC because focused on aesthetics, 15 yr protection
    - Plant Patent (PP): new asexually reproduced plant varieties (e.g., hybrids or genetically unique plants), has their own classifcation system (PLT), 20 yrs protection
    - Reissue Patents (RE): Issued to correct errors in an existing patent without changing the original invention (often to broaden or narrow claims), same expiration as original patent
    - Defensive Publication (T): Disclose an invention to prevent others from patenting it while not seeking exclusive rights, not technically a patent, no CPC assignment required
    - Statutory Invention Registrations (SIRs, H, Obsolete): Allowed inventors to publish inventions without seeking patent protection (abolished in 2013)



### Follow-up
- learn more about the test extraction proccess: https://patentsview.org/government-interest
- no data dictionary for g_cpc_at_issue



