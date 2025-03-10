Building Agentic Apps: ArangoDB, NVIDIA cuGraph, and NetworkX Hackathon (the “Hackathon”) Official Rules
NO PURCHASE OR PAYMENT NECESSARY TO ENTER OR WIN. A PURCHASE OR PAYMENT WILL NOT INCREASE YOUR CHANCES OF WINNING. 

SUBMISSION OF ANY ENTRY CONSTITUTES AGREEMENT TO THESE OFFICIAL RULES AS A CONTRACT BETWEEN ENTRANT (AND EACH INDIVIDUAL MEMBER OF ENTRANT), THE HACKATHON SPONSOR, AND DEVPOST.

 

1. Dates and Timing
*Updated March 7, 2025

Submission Period: Monday, February 10, 2025 (10:00 am Pacific Time) – Sunday, March 9, 2025 (11:45 pm Pacific Time) (“Submission Period”).

Public Voting Period: Monday, March 10, 2025 (10:00 am  Pacific Time) – Monday, March 17, 2025 (12:00 am Pacific Time) (“Public Voting Period”).

Judging Period: Monday, March 10, 2025 (10:00 am  Pacific Time) – Monday, March 17, 2025 (12:00 am Pacific Time) (“Judging Period”).

Winners Announced: On or around Thursday, March 20, 2025 (12:30 pm Pacific Time).

 

2. Sponsor and Administrator
Sponsor and Administrator: ArangoDB, 548 Market St, Suite 61436, San Francisco, CA, 94104, United States

 

3. Eligibility
The Hackathon IS open to: 

Individuals who are at least the age of majority where they reside as of the time of entry (“Eligible Individuals”); and
Teams of Eligible Individuals (“Teams”); 
(the above are collectively, “Entrants”)

An Eligible Individual may join more than one Team and an Eligible Individual who is part of a Team may also enter the Hackathon on an individual basis. If a Team is entering the Hackathon, they must appoint and authorize one individual (the “Representative”) to represent, act, and enter a Submission, on their behalf. By entering a Submission on behalf of a Team you represent and warrant that you are the Representative authorized to act on behalf of your Team.

The Hackathon IS NOT open to: 

Individuals who are residents of, domiciled in, a country, state, province or territory where the laws of the United States or local law prohibits participating or receiving a prize in the Hackathon (including, but not limited to, Brazil, Quebec, Russia, Crimea, Cuba, Iran, North Korea, Syria and any other country designated by the United States Treasury's Office of Foreign Assets Control) 
Employees, representatives and agents** of such Promotion Entities, and all members of their immediate family or household*
Any other individual involved with the design, production, promotion, execution, or distribution of the Hackathon, and each member of their immediate family or household*
Any Judge (defined below), or company or individual that employs a Judge
Any other individual whose participation in the Hackathon would create, in the sole discretion of the Sponsor and/or Administrator, a real or apparent conflict of interest 
*The members of an individual’s immediate family include the individual’s spouse, children and stepchildren, parents and stepparents, and siblings and stepsiblings. The members of an individual’s household include any other person that shares the same residence as the individual for at least three (3) months out of the year. 

**Agents include individuals that in creating a Submission to the Hackathon, are acting on behalf of, and at the direction of, a Promotion Entity through a contractual or similar relationship.

 

4. How To Enter 
Entrants may enter by visiting arangodbhackathon.devpost.com (“Hackathon Website”) and following the below steps:

Register for the Hackathon on the Hackathon Website by clicking the “Join Hackathon” button. To complete registration, sign up to create a free Devpost account, or log in with an existing Devpost account. This will enable you to receive important updates and to create your Submission.
Entrants will obtain access to the required developer tools/platform and complete a Project described below in Project Requirements. Use of the developer tools will be subject to the license agreement related thereto. Entry in the Hackathon constitutes consent for the Sponsor and Devpost to collect and maintain an entrant’s personal information for the purpose of operating and publicizing the Hackathon.
Entrants can use the ArangoDB Community Edition or access a 30-day free trial of the ArangoGraph managed service by visiting https://arangodb.com/arangograph-trial/
Note: Submissions must be made within 30 days of the date when the participant/team signs up for the 30-day ArangoGraph free trial, and must be completed before March 9, 2025.
Complete and enter all of the required fields on the “Enter a Submission” page of the Hackathon Website (each a “Submission”) during the Submission Period and follow the requirements below.
Project Requirements

What to Create: Entrants must create a working Agentic Application that:

Data Source:
a) Utilizes public or open-source datasets relevant to specific industries or use cases (e.g., social networks, healthcare, transportation).
b) Alternatively, use one of the datasets provided by ArangoDB.
Data Preparation:
a) Converts datasets into a graph format (if not already) before loading into NetworkX.
Technologies:
a) ArangoDB: Persists graph data using the ArangoDB NetworkX Integration. [ArangoDB NetworkX Integration Guide]
b) LangChain: Processes natural language queries using LangChain Integration. [LangChain ArangoDB Integration]
c) LangGraph: Building stateful, multi-actor applications with LLMs, used to create agent and multi-agent workflows. 
d) NetworkX: Structures and processes graph data before executing GPU-accelerated analytics. Used for pre-processing, graph transformations, and algorithm execution when GPU acceleration is not required. [NetworkX Documentation]
e) NVIDIA cuGraph: Performs GPU-accelerated graph analytics (e.g., centrality measures, clustering) on large-scale graphs. [by way of cuGraph Backend to NetworkX]
Functionality:
a) Accepts natural language queries.
b) Dynamically determines whether to:
        - Generate and execute Dynamic AQL Queries for graph traversal.
        - Execute cuGraph/NetworkX algorithms for advanced analytics.
        - Hybrid query (combining AQL, NetworkX/cuGraph)
        - OPTIONAL - use other tools to enhance the query response
c) Visualizes results clearly and intuitively, returning them to a natural language interface.
Development Environment:
a) Utilizes Python 3.10.
b) CUDA-compatible GPU to leverage cuGraph acceleration is encouraged.
c) Access to ArangoGraph 30-day trial (or the ArangoDB Community edition).
d) Develops an executable Jupyter Notebook demonstrating the workflow, dataset handling, query execution, and visualization.
Functionality: The Project must function as described in the Hackathon Overview.
New Apps Only: Projects must be newly created by the Entrant during the Submission Period.
Note: Submissions must be made within 30 days of the date when the participant/team signs up for the 30-day ArangoGraph free trial, and must be completed before March 9, 2025. You can also use the ArangoDB Community Edition which has no time limit.
Third Party Integrations: If a Project integrates any third-party SDK, APIs and/or data, Entrant must be authorized to use them in accordance with any terms and conditions or licensing requirements of the tool.
Submission Requirements 

Submissions to the Hackathon must meet the following requirements:

Include an executable Jupyter Notebook (stored in a Github Repo) with clear inline documentation explaining each step.
Include a text explanation/description that should explain the features and functionality of your Project.
Include a walkthrough video of your Project. The video portion of the Submission:
should be 5-10 minutes. Judges are not required to watch beyond 10 minutes.
should explain the dataset, methodology, and application functionality.
should include the dataset selection, workflow explanation, and code implementation and results
Screen capture/recording with talk track going over the design process and the application
must be uploaded to and made publicly visible on YouTube, and a link to the video must be provided on the submission form on the Hackathon Website; and
must not include third party trademarks, or copyrighted music or other material unless the Entrant has permission to use such material.
Include a URL to a public Github Repo.
Multiple Submissions 

An Entrant may submit more than one Submission, however, each Submission must be unique and substantially different from each of the Entrant’s other Submissions, as determined by the Sponsor and Devpost in their sole discretion.

Submission ownership

Be the original work of the Entrant, be solely owned by the Entrant, and not violate the IP rights of any other person or entity.

Testing 

Access must be provided to an Entrant’s working Project for judging and testing by providing a link to a website, functioning demo, or a test build. If Entrant’s website is private, Entrant must include login credentials in its testing instructions. The Entrant must make the Project available free of charge and without any restriction, for testing, evaluation and use by the Sponsor, Administrator and Judges until the Judging Period ends. Judges are not required to test the Project and may choose to judge based solely on the text description, images, and video provided in the Submission.

Access can be provided to the Sponsor and Administrator by providing a URL to ArangoGraph and your Python Notebook. 

If the Project includes software that runs on proprietary or third party hardware that is not widely available to the public, including software running on devices or wearable technology other than smartphones, tablets, or desktop computers, the Sponsor and/or Administrator reserve the right, at their sole discretion, to require the Entrant to provide physical access to the Project hardware upon request.  

Language Requirements

All Submission materials must be in English or, if not in English, the Entrant must provide an English translation of the demonstration video, text description, and testing instructions as well as all other materials submitted. 

Team Representation

If a team is entering the Hackathon, they must appoint and authorize one individual (the “Representative”) to represent, act, and enter a Submission, on their behalf. The Representative must meet the eligibility requirements above. By entering a Submission on the Hackathon Website on behalf of a team you represent and warrant that you are the Representative authorized to act on behalf of your team.

Intellectual Property 

Your Submission must: (a) be your (or your Team’s) original work product; (b) be solely owned by you, your Team, with no other person or entity having any right or interest in it; and (c) not violate the intellectual property rights or other rights including but not limited to copyright, trademark, patent, contract, and/or privacy rights, of any other person or entity. An Entrant may contract with a third party for technical assistance to create the Submission provided the Submission components are solely the Entrant’s work product and the result of the Entrant’s ideas and creativity, and the Entrant owns all rights to them. An Entrant may submit a Submission that includes the use of open source software or hardware, provided the Entrant complies with applicable open source licenses and, as part of the Submission, creates software that enhances and builds upon the features and functionality included in the underlying open source product. By entering the Hackathon, you represent, warrant, and agree that your Submission meets these requirements.

Financial or Preferential Support 

A Project must not have been developed, or derived from a Project developed, with financial or preferential support from the Sponsor or Administrator. Such Projects include, but are not limited to, those that received funding or investment for their development, were developed under contract, or received a commercial license, from the Sponsor or Administrator any time prior to the end of Hackathon Submission Period. The Sponsor, at their sole discretion, may disqualify a Project, if awarding a prize to the Project would create a real or apparent conflict of interest.

 

5. Submission Modifications
Draft Submissions 

Prior to the end of the Submission Period, you may save draft versions of your submission on Devpost to your portfolio before submitting the Submission materials to the Hackathon for evaluation. Once the Submission Period has ended, you may not make any changes or alterations to your Submission, but you may continue to update the Project in your Devpost portfolio.

Modifications

After the Submission Period. The Sponsor and Devpost may permit you to modify part of your Submission after the Submission Period for the purpose of adding, removing or replacing material that potentially infringes a third party mark or right, discloses personally identifiable information, or is otherwise inappropriate. The modified Submission must remain substantively the same as the original Submission with the only modification being what the Sponsor and Devpost permits. 

 

6. Judges & Criteria
Eligible submissions will be evaluated by a panel of judges selected by the Sponsor (the “Judges”). Judges may be employees of the sponsor or third parties, may or may not be listed individually on the Hackathon Website, and may change before or during the Judging Period. Judging may take place in one or more rounds with one or more panels of Judges, at the discretion of the sponsor. 

Stage One) The first stage will determine via pass/fail whether the ideas meet a baseline level of viability, in that the Project reasonably fits the theme and reasonably applies the required APIs/SDKs featured in the Hackathon.

Stage Two) All Submissions that pass Stage One will be evaluated in Stage Two based on the following equally weighted criteria (the “Judging Criteria”):

Entries will be judged on the following equally weighted criteria, and according to the sole and absolute discretion of the judges:

Innovation

How creative and original is the solution

Does the application introduce novel use cases or solve a meaningful problem?

Functionality 

Does the application correctly interpret and execute natural language queries depending on query type?

Does the app effectively execute hybrid queries?

Bonus if other agent tools are added

Technical Excellence

Effective use of AQL, LangChain, and cuGraph for traversal and analytics.

Proper handling of large-scale datasets and GPU acceleration.


Usability

Is the application user-friendly and intuitive?

Are the results presented clearly and effectively (e.g., through visualizations and not just chatbot)?

Documentation and Presentation

Is the code well-documented and easy to follow?

Is the walkthrough video comprehensive and does it provide an overview of the solution?

The scores from the Judges will determine the potential winners of the applicable prizes. The Entrant(s) that are eligible for a Prize, and whose Submissions earn the highest overall scores based on the applicable Judging Criteria, will become potential winners of that Prize.

Tie Breaking 

For each Prize listed below, if two or more Submissions are tied, the tied Submission with the highest score in the first applicable criterion listed above will be considered the higher scoring Submission. In the event any ties remain, this process will be repeated, as needed, by comparing the tied Submissions’ scores on the next applicable criterion. If two or more Submissions are tied on all applicable criteria, the panel of Judges will vote on the tied Submissions.

Public Choice Voting 

During the Voting Period, eligible Submissions will be posted on the Hackathon Website for community members to submit their votes. Voting results will not be displayed publicly. The winners of the Public Choice Prize will be selected based on the highest number of verified votes received during the Voting Period. Verified vote counts will be determined by Devpost. Participation and use of Public Voting is subject to the Devpost Terms of Service which include the below:

“You may not use any manual or automated vote process or methods, or multiple e-mail addresses, to circumvent the one-vote limit per person per Submission. Doing so will subject all of your votes to disqualification. The Administrator may also disqualify an entrant, if the entrant receives multiple or irregular votes from the same user or users, receives votes in a manner that indicates manual, automated, or other vote manipulation, or attempts to compensate voters.”

 

7. Intellectual Property Rights
All Submissions remain the intellectual property of the individuals that developed them. By submitting an entry, entrants agree that the Sponsor will have a fully paid, non-exclusive license to use such entry for judging the entry. Entrants agree that the sponsor and Devpost shall have the right to promote the Submission and use the name, likeness, voice and image of all individuals contributing to a Submission, in any materials promoting or publicizing the Hackathon and its results, during the Hackathon Period and for three years thereafter.  Some Submission components may be displayed to the public. Other Submission materials may be viewed by the sponsor, Devpost, and judges for screening and evaluation. By submitting an entry or accepting any prize, entrants represent and warrant that (a) submitted content is not copyrighted, protected by trade secret or otherwise subject to third party intellectual property rights or other proprietary rights, including privacy and publicity rights, unless entrant is the owner of such rights or has permission from their rightful owner to post the content; and (b) the content submitted does not contain any viruses, Trojan horses, worms, spyware or other disabling devices or harmful or malicious code.

 

8. Prizes


Winner

Prize

Qty

Eligible Submissions 

Overall Prizes

First Place

$15,000 in USD
Feature on ArangoDB Blog
Social Media Promotion

1

All eligible submissions

Second Place

$7,500 in USD
Feature on ArangoDB Blog
Social Media Promotion

1

All eligible submissions

Third Place

$5,000 in USD
Feature on ArangoDB Blog
Social Media Promotion

1

All eligible submissions

Honorable Mention

$750 in USD
Feature on ArangoDB Blog
Social Media Promotion

2

All eligible submissions

Public Choice Prizes

Public Choice

$750 in USD
Feature on ArangoDB Blog
Social Media Promotion

1

All eligible submissions

IMPORTANT NOTES ON MULTIPLE PRIZE ELIGIBILITY:
Each individual Project is eligible to receive one (1) Overall prize and one (1) Public Choice prize.

A. Substitutions & Changes: Prizes are non-transferable by the winner. Sponsor in its sole discretion has the right to make a prize substitution of equivalent or greater value. Sponsor will not award a prize if there are no eligible Submissions entered in the Hackathon, or if there are no eligible Entrants or Submissions for a specific prize.

B. Verification Requirement: THE AWARD OF A PRIZE TO A POTENTIAL WINNER IS SUBJECT TO VERIFICATION OF THE IDENTITY, QUALIFICATIONS AND ROLE OF THE POTENTIAL WINNER IN THE CREATION OF THE SUBMISSION. No Submission or Entrant shall be deemed a winning Submission or winner until their post-competition prize affidavits have been completed and verified, even if prospective winners have been announced verbally or on the competition website. The final decision to designate a winner shall be made by the Sponsor and/or Administrator. 

C. Prize Delivery: Prizes will be payable to the Entrant, if an individual; or to the Entrant’s Representative, if a Team. It will be the responsibility of the winning Entrant’s Representative to allocate the Prize among their Team’s participating members, as the Representative deems appropriate. A monetary Prize will be mailed to the winning Entrant’s address (if an individual) or the Representative’s address (if a Team), or sent electronically to the Entrant, Entrant’s Representative’s bank account, only after receipt of the completed winner affidavit and other required forms (collectively the “Required Forms”), if applicable. The deadline for returning the Required Forms to the Administrator is ten (10) business days after the Required Forms are sent. Failure to provide correct information on the Required Forms, or other correct information required for the delivery of a Prize, may result in delayed Prize delivery, disqualification of the Entrant, or forfeiture of a Prize. Prizes will be delivered within 60 days of the Sponsor or Devpost’s receipt of the completed Required Forms.

D. Fees & Taxes: Winners (and in the case of Team, all participating members) are responsible for any fees associated with receiving or using a prize, including but not limited to, wiring fees or currency exchange fees. Winners (and in the case of Team, all participating members) are responsible for reporting and paying all applicable taxes in their jurisdiction of residence (federal, state/provincial/territorial and local). Winners may be required to provide certain information to facilitate receipt of the award, including completing and submitting any tax or other forms necessary for compliance with applicable withholding and reporting requirements. United States residents may be required to provide a completed form W-9 and residents of other countries may be required to provide a completed W-8BEN form. Winners are also responsible for complying with foreign exchange and banking regulations in their respective jurisdictions and reporting the receipt of the Prize to relevant government departments/agencies, if necessary. The Sponsor, Devpost, and/or Prize provider reserves the right to withhold a portion of the prize amount to comply with the tax laws of the United States or other Sponsor jurisdiction, or those of a winner’s jurisdiction.

 

9. Entry Conditions and Release
A. By entering the Hackathon, you (and, if you are entering on behalf of a Team, each participating members) agree(s) to the following:

The relationship between you, the Entrant, and the Sponsor and Administrator, is not a confidential, fiduciary, or other special relationship.
You will be bound by and comply with these Official Rules and the decisions of the Sponsor, Administrator, and/or the Hackathon Judges which are binding and final in all matters relating to the Hackathon.
You release, indemnify, defend and hold harmless the Promotion Entities, and their respective parent, subsidiary, and affiliated companies, the Prize suppliers and any other organizations responsible for sponsoring, fulfilling, administering, advertising or promoting the Hackathon, and all of their respective past and present officers, directors, employees, agents and representatives (hereafter the “Released Parties”) from and against any and all claims, expenses, and liabilities (including reasonable attorneys’ fees), including but not limited to negligence and damages of any kind to persons and property, defamation, slander, libel, violation of right of publicity, infringement of trademark, copyright or other intellectual property rights, property damage, or death or personal injury arising out of or relating to a Entrant’s entry, creation of Submission or entry of a Submission, participation in the Hackathon, acceptance or use or misuse of the Prize (including any travel or activity related thereto) and/or the broadcast, transmission, performance, exploitation or use of the Submission as authorized or licensed by these Official Rules. 
B. Without limiting the foregoing, the Released Parties shall have no liability in connection with: 

Any incorrect or inaccurate information, whether caused by the Sponsor or Administrator’s electronic or printing error, or by any of the equipment or programming associated with or utilized in the Hackathon; 
Technical failures of any kind, including, but not limited to malfunctions, interruptions, or disconnections in phone lines, internet connectivity or electronic transmission errors, or network hardware or software or failure of the Hackathon Website;
Unauthorized human intervention in any part of the entry process or the Hackathon; 
Technical or human error which may occur in the administration of the Hackathon or the processing of Submissions; or 
Any injury or damage to persons or property which may be caused, directly or indirectly, in whole or in part, from the Entrant’s participation in the Hackathon or receipt or use or misuse of any Prize.
The Released Parties are not responsible for incomplete, late, misdirected, damaged, lost, illegible, or incomprehensible Submissions or for address or email address changes of the Entrants. Proof of sending or submitting the aforementioned will not be deemed to be proof of receipt by the Sponsor or Administrator. If for any reason any Entrant’s Submission is determined to have not been received or been erroneously deleted, lost, or otherwise destroyed or corrupted, the Entrant’s sole remedy is to request the opportunity to resubmit its Submission. Such a request must be made promptly after the Entrant knows or should have known there was a problem and will be determined at the sole discretion of the Sponsor.

 

10. Publicity
By participating in the Hackathon, Entrant consents to the promotion and display of the Entrant’s Submission, and to the use of personal information about themselves for promotional purposes, by the Sponsor, Administrator, and third parties acting on their behalf. Such personal information includes, but is not limited to, your name, likeness, photograph, voice, opinions, comments and hometown and country of residence. It may be used in any existing or newly created media, worldwide without further payment or consideration or right of review, unless prohibited by law. Authorized use includes but is not limited to advertising and promotional purposes. 

 

11. General Conditions 
Sponsor and Administrator reserve the right, in their sole discretion, to cancel, suspend and/or modify the Hackathon, or any part of it, in the event of a technical failure, fraud, or any other factor or event that was not anticipated or is not within their control.
Sponsor and Administrator reserve the right in their sole discretion to disqualify any individual or Entrant if it finds to be actually or presenting the appearance of tampering with the entry process or the operation of the Hackathon or to be acting in violation of these Official Rules or in a manner that is inappropriate, unsportsmanlike, not in the best interests of this Hackathon, or a violation of any applicable law or regulation.
Any attempt by any person to undermine the proper conduct of the Hackathon may be a violation of criminal and civil law. Should the Sponsor or Administrator suspect that such an attempt has been made or is threatened, they reserve the right to take appropriate action including but not limited to requiring an Entrant to cooperate with an investigation and referral to criminal and civil law enforcement authorities.
If there is any discrepancy or inconsistency between the terms and conditions of the Official Rules and disclosures or other statements contained in any Hackathon materials, including but not limited to the Hackathon Submission form, Hackathon Website, or advertising, the terms and conditions of the Official Rules shall prevail.
The terms and conditions of the Official Rules are subject to change at any time, including the rights or obligations of the Entrant, the Sponsor and Administrator. The Sponsor and Administrator will post the terms and conditions of the amended Official Rules on the Hackathon Website. To the fullest extent permitted by law, any amendment will become effective at the time specified in the posting of the amended Official Rules or, if no time is specified, the time of posting.
If at any time prior to the deadline, an Entrant or prospective Entrant believes that any term in the Official Rules is or may be ambiguous, they must submit a written request for clarification. 
The Sponsor or Administrator’s failure to enforce any term of these Official Rules shall not constitute a waiver of that provision. Should any provision of these Official Rules be or become illegal or unenforceable in any jurisdiction whose laws or regulations may apply to an Entrant, such illegality or unenforceability shall leave the remainder of these Official Rules, including the Rule affected, to the fullest extent permitted by law, unaffected and valid. The illegal or unenforceable provision shall be replaced by a valid and enforceable provision that comes closest and best reflects the Sponsor’s intention in a legal and enforceable manner with respect to the invalid or unenforceable provision.
Excluding Submissions, all intellectual property related to this Hackathon, including but not limited to copyrighted material, trademarks, trade-names, logos, designs, promotional materials, web pages, source codes, drawings, illustrations, slogans and representations are owned or used under license by the Sponsor and/or Administrator. All rights are reserved. Unauthorized copying or use of any copyrighted material or intellectual property without the express written consent of its owners is strictly prohibited. Any use in a Submission of Sponsor or Administrator’s intellectual property shall be solely to the extent provided for in these Official Rules.
 

12. Limitations of Liability
By entering, all Entrants (including, in the case of a Team, all participating members) agree to release the Released Parties from any and all liability in connection with the Prizes or Entrant’s participation in the Hackathon. Provided, however, that any liability limitation regarding gross negligence or intentional acts, or events of death or body injury shall not be applicable in jurisdictions where such limitation is not legal.

 

13. Disputes
A. Except where prohibited by law, as a condition of participating in this Hackathon, Entrant agrees that:

Any and all disputes and causes of action arising out of or connected with this Hackathon, or any Prizes awarded, shall be resolved individually, without resort to any form of class action lawsuit, and exclusively by final and binding arbitration under the rules of the American Arbitration Association and held at the AAA regional office nearest the contestant;
The Federal Arbitration Act shall govern the interpretation, enforcement and all proceedings at such arbitration; and
Judgment upon such arbitration award may be entered in any court having jurisdiction.
B. Under no circumstances will Entrant be permitted to obtain awards for, and Entrant hereby waives all rights to claim, punitive, incidental or consequential damages, or any other damages, including attorneys’ fees, other than contestant’s actual out-of-pocket expenses (i.e., costs associated with entering this Hackathon), and Entrant further waives all rights to have damages multiplied or increased.

C. All issues and questions concerning the construction, validity, interpretation and enforceability of these Official Rules, or the rights and obligations of the Entrant and Sponsor in connection with this Hackathon, shall be governed by, and construed in accordance with, the substantive laws of the State of New York, USA without regard to New York choice of law rules.

SOME JURISDICTIONS DO NOT ALLOW THE LIMITATIONS OR EXCLUSION OF LIABILITY FOR INCIDENTAL OR CONSEQUENTIAL DAMAGES, SO THE ABOVE LIMITATIONS OF LIABILITY MAY NOT APPLY TO YOU.

 

14. Additional Terms
Please review the Devpost Terms of Service at https://info.devpost.com/terms for additional rules that apply to your participation in the Hackathon and more generally your use of the Hackathon Website. Such Terms of Service are incorporated by reference into these Official Rules, including that the term "Poster" in the Terms of Service shall mean the same as "Sponsor" in these Official Rules." If there is a conflict between the Terms of Service and these Official Rules, these Official Rules shall control with respect to this Hackathon only.

 

15. Entrant’s Personal Information
Information collected from Entrants is subject to Devpost’s Privacy Policy, which is available at https://info.devpost.com/privacy.

For questions, send an email to support@devpost.com.