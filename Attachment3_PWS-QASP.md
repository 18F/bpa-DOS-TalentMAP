PERFORMANCE BASED QUALITY ASSURANCE SURVEILLANCE PLAN (QASP) 
=============================================================

Department of State TalentMAP
=============================

**General Services Administration (GSA)/Technology Transformation Service (TTS)**

**and**

**Department of State (DOS)**

**Issued by:**

**General Services Administration (GSA)/National Capital Region (NCR)**

**Federal Acquisition Service (FAS)/Assisted Acquisition Services (AAS)**

**January 2017**

**NCR AAS Project Number ID11XXXXXX**

INTRODUCTION
------------

This Quality Assurance Surveillance Plan (QASP) has been developed to evaluate Contractor actions while implementing [*the Performance Work Statement (**PWS**)*](https://docs.google.com/document/d/1SXuXrg-6JHJqYW6Y_Dj3IHoZYPikKfvJGs7dVNbEtMw/edit#heading=h.2et92p0). It is designed to provide an effective surveillance method of monitoring Contractor performance for each listed objective on the Performance Requirements Matrix in the Call Order. It also provides a systematic method to evaluate the services the Contractor is required to furnish.

STANDARD
--------

The Contractor is responsible for management and quality control actions to meet the terms of the Call Order. The role of the Contracting Officer’s Representative (COR**)/**Administrative Contracting Officer’s Representative (ACOR**)** is quality assurance to ensure Call Order standards are achieved. The Contractor shall perform all work required in a satisfactory manner in accordance with the requirements of the PWS. The COR/ACOR shall notify the Contracting Officer (CO) for appropriate action if it is likely that the Contractor does not anticipate successful delivery of the final software code in accordance with the performance objectives and Acceptable Quality Levels (AQLs) identified below.

The COR/ACOR for this Call Order is:

COR: Kirsten Green, GSA TTS, *kirsten.green@gsa.gov*

*ACOR: Do we have or need one?*

PERFORMANCE REQUIREMENTS MATRIX
-------------------------------

The COR/ACOR will evaluate the performance objectives through surveillance as reflected below by reviews and acceptance of work products and services. As indicated, the COR/ACOR will assess progress towards the final delivered software code. Note that the performance requirements listed below are required for the final deliverable. However, the sprints and incremental delivery of code will be assessed by the Government to ensure that the Contractor is on a path to successful final delivery.

Deliverable or Required Services Performance Standard(s):

| **Deliverable or Required Services** | **Performance Standard(s)**                                                                                                       | **Acceptable Quality Level (AQL)**                                                                                                                                                                                                                 | **Method of Surveillance**                                                                                                                                           |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tested Code                          | Code delivered under the order must have substantial test code coverage and a clean code base.                                    | Minimum of 90% test coverage of all relevant code                                                                                                                                                                                                  | Combination of manual review and automated testing, using agreed-upon publicly-available SaaS products                                                               |
| Accessible                           | Client-side rendering must conform with section 508 standards.                                                                    | 0 errors reported for 508 Standards using an automated scanner and 0 errors reported in manual testing                                                                                                                                             | [*http://squizlabs.github.io/HTML\_CodeSniffer/*](http://squizlabs.github.io/HTML_CodeSniffer/)or [*https://github.com/pa11y/pa11y*](https://github.com/pa11y/pa11y) |
| Deployed                             | Code must successfully build and deploy into staging environment at the Department of State.                                      | Successful build with a single command                                                                                                                                                                                                             | Combination of manual review and automatic testing                                                                                                                   |
| Documented                           | All dependencies (and licenses for dependencies) are listed and all major functions are documented.                               | All dependencies are listed and the licenses are documented. Software/source code is documented. System diagram is provided.                                                                                                                       | Combination of manual review and automatic testing                                                                                                                   |
| Available                            | Code must be stored in a version-controlled open-source repository.                                                               | All of the code needed to run the front end of the prototype must be available.                                                                                                                                                                    | TTS will assess code availability.                                                                                                                                   |
| Research                             | Research activities must be conducted at regular intervals throughout the development process (not just at the beginning or end). | During the first sprint, vendor shall establish a research plan in collaboration with GSA TTS and the Department of State. This plan must account for the use of an informed consent form, if necessary, and delivery of research-related records. 
                                                                                                                                                                                                                                                       
   In subsequent sprints, research-related records will be delivered in accordance with the aforementioned research plan.                                                                                                                              | TTS will cross-reference research-related records with other project documentation to ensure that research is properly accounted for and communicated.               |
| Secure                               | Code must be free of medium- and high-level static and dynamic security vulnerabilities                                           | Clean tests from a static testing SaaS, such as Gemnasium, and from OWASP ZAP, and/or documentation explaining any false positives.                                                                                                                | https://pages.18f.gov/before-you-ship/                                                                                                                               |

PROCEDURES
----------

The COR/ACOR, along with the GSA TTS Product Lead and the product owner, will inspect all tasks required by the Call Order to ensure Contractor compliance with the requirements at the conclusion of each sprint, which shall have a length of two weeks or less.

Delivery of code will occur by pull request from the Contractor’s repository to the GSA TTS repository. If inspection results are satisfactory, the pull request will be merged; otherwise, deficiencies will be noted in the pull request or through issues as described below. The COR/ACOR may find the delivery satisfactory even though further work is required, provided that the specific requirements of the sprint are met.

Unless otherwise agreed upon in writing, the Contractor shall deliver research-related records to the Department of State in accordance with a previously agreed upon research plan. The research plan shall be delivered during the first sprint.

At the conclusion of each sprint, the COR/ACOR, along with the GSA TTS Product Lead and the product owner, will review the completed user stories and related functionality. Incomplete or inadequate code and user stories will be noted in a mutually agreed-upon issue tracker, such as Trello or GitHub Issues, and links to each issue shared with the CO. The Contractor may respond in that tracker as appropriate, addressing the accuracy and validity of the defect as well as any planned corrective action (if not already noted). The Contractor’s team will discuss and document actions to prevent recurrence in their sprint retrospectives.

At the conclusion of the period of performance, a similar procedure will be followed to document discrepancies and to assess overall performance.

If any of the services do not conform to the Call Order requirements, the COR/ACOR may require the Contractor to perform the services again in conformity with Call Order requirements. Any user stories that are not accepted must be completed in the next sprint, unless the product owner and GSA TTS product manager agree to move it to a later sprint. The COR/ACOR shall not certify satisfactory performance for the Call Order until all defects have been corrected. When the defects in services cannot be corrected by re-performance, the Government may:

1.  Require the Contractor to take necessary action to ensure that future performance conforms to Call Order requirements; and,

2.  Reduce the Call Order price to reflect the reduced value of the services performed. The COR/ACOR shall, in addition to providing documentation to the CO, maintain a complete quality assurance file. The file will contain copies of all reports, evaluations, recommendations, and any actions relating to the Government’s performance of the quality assurance function, including originals of all surveillance activity checklists. All such records will be retained for the life of the Call Order. The COR/ACOR shall forward these records to the CO at completion or termination of the Call Order.

ACCEPTANCE OF SERVICES
----------------------

Acceptance of services shall be based upon compliance with performance standards described in the PWS and surveillance procedures described in this QASP. Before approving/certifying any Contractor invoices, the COR/ACOR will verify that all invoiced services have been performed in compliance with Call Order requirements. The COR/ACOR shall not certify satisfactory performance for the Call Order until all defects have been corrected.
