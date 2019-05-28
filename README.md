# AIML
Artificial Intelligence Lab template information that VA Researchers and Project Teams will find useful, including key principles
OFFICE OF 
INFORMATION 
AND TECHNOLOGY
Artificial Intelligence (AI) in Clinical Applications
Enterprise Design Patterns (EDP)

AI Lab in Microsoft (MS) Azure - Proof of Concept
May 2019 | Demand Management Division 
 
Table of Contents
1	Context	3
2	Challenge	3
3	AI Lab Deployment Template in Cloud	3
4	Key Practices	5
Appendix A: References	6


Table 1: Change Matrix
Version	Date	Description of Updates
0.1	02/01/2019	AI ML Proof of Concept – initial draft
0.2	04/30/2019	Updated draft to include Azure Cloud Template details
0.3	05/20/2019	Updated with Dr. Mazen Zawaideh input
0.4	TBD	Generate AIML code from Azure Lab environment and upload to GitHub


 
1	Context
Artificial Intelligence (AI) and Machine Learning (ML) are expanding rapidly and are revolutionizing the health care industry. AI applications cover major disease areas like cancer, neurology and cardiology, and drug research and discovery. 
AI and ML offer unique strength in drawing insights from unstructured data such as images (computer vision) and free text (natural language processing). There is interest in the health care community in the areas of radiomics, quantitative imaging, automated triage of medical imaging studies, and advanced multi-modal research utilizing rich data sources such as patient imaging, genomics, and free text clinical reports. Using these techniques brings promise to VA for more precise patient diagnosis, treatment planning, and treatment response follow-up for a broad range of conditions. 
One important aspect of where AI can be applied in clinical applications is in medical image processing. In general computer processing of medical images, such as X-rays, requires large compute resources and is ideal for leveraging VA cloud computing resources. The industry best practice for leveraging cloud compute resources involve designing a deployment template for AI project in clinical application
2	Challenge
 Key challenges in implementing AI and ML techniques into the research and clinical workflows are the absence of systematic processes to:
1.	Curate and label relevant data in a format appropriate for AI/ML model ingestion. 
2.	Procure and correctly use the hardware and software infrastructure needed for AI/ML model development, training, refinement, and clinical validation. 
The above challenges are addressed by a phased sprint approach that includes 
•	A preliminary Lab development environment to demonstrate proof of concept of applying ML to medical image classification.
•	Once POC is demonstrated, researchers can move to VAEC to apply the techniques to real clinical data and then scale up. 
In addition, training clinical and research staff in how to use the above techniques and VAEC Cloud resources will be addressed separately.   Information related to Azure Resources such as Azure N-Series VMs, NVIDIA GPUs and BLOB Storage can be accessed through the relevant tags.
3	AI Lab Deployment Template in Cloud
This template provides information to assist VA researchers set up a lab environment in MS Azure for proof of concept studies in AI in clinical applications.  
Researchers should first obtain access to the azure lab environment.  Instructions on how to get access is provided in < document name > <location>
The template consists of the following:
•	Detailed step by step guidance to set up the AI POC lab environment
•	Code packages 
•	Images 
•	README which is this document.
 
 
4	Key Practices
•	All AI research Projects should leverage MS Azure Sandbox to demonstrate POC
•	Ensure that project teams follow ECSO’s Pre-configuration process and guidelines 
 

Appendix A: References 
•	DEA User Stories: https://vaww.portal2.va.gov/sites/asd/TechStrat/IPTS/SitePages/Home.aspx 
•	FISMA User Stories: https://vaww.portal2.va.gov/sites/asd/AERB/FISMASecurityCompliance/SitePages/Home.aspx 
•	TRM: http://trm.oit.va.gov/ 
•	NIST 800-63-3: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-3.pdf 
•	VA 6500.3: http://vaww.va.gov/vapubs/viewPublication.asp?Pub_ID=733&FType=2 
•	VA 6510 (under revision): http://vaww.va.gov/vapubs/viewPublication.asp?Pub_ID=823&FType=2 
Disclaimer: This document serves both internal and external customers. Links displayed throughout this document may not be viewable to all users outside the VA domain. This document may also include links to websites outside VA control and jurisdiction. VA is not responsible for the privacy practices or the content of non-VA websites. We encourage you to review the privacy policy or terms and conditions of those sites to fully understand what information is collected and how it is used.
Statement of Endorsement: Reference herein to any specific commercial products, process, or service by trade name, trademark, manufacturer, or otherwise, does not necessarily constitute or imply its endorsement, recommendation, or favoring by the United States Government, and shall not be used for advertising or product endorsement purposes.
