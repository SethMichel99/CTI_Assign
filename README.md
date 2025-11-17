# CTI Assign

# Task 3

| Vertex | Description |
|--------|-------------|
| **Adversary** | UNC6229 — financially motivated threat actor based in Vietnam. Impersonates recruiters, builds fake companies, communicates professionally, targets credentials and corporate ad/social accounts. |
| **Infrastructure** | Fake recruiter emails, fake job-posting websites, phishing login/MFA pages, impersonated company profiles, CRM/SaaS email tools, password-protected ZIP attachments, cloud-hosted phishing servers, messaging platforms. |
| **Capabilities** | Remote Access Trojans (RATs), credential phishing, MFA & login bypass workflows, social engineering via faking recruitment and fake offers, malware hidden in ZIPs, impersonation, cloud service abuse to appear legitimate. |
| **Victim** | Digital marketers, social media managers, online advertising workers, remote job seekers; organizational targets include corporate ad accounts, social-media accounts, credentials, and MFA tokens. |


# Task 5 

The threat actor I analyzed is a financially motivated group based out of Vietnam, they go by "UNC6229". According to Googles Threat report - this group mainly targets people working in digital marketing or advertising like social media related roles or accounts. The main method of attack involves creating fake job postings and prenting to be recruiters/HR reps. Their capable of building convincing company profiles and imitating real professional company looks, they can replicate proffesional looking ads/emails and can appear as if they are a real legitimate company.

The groups initial access is usually gain by exploiting social engineering techniques, victims can be sent forms or assesments to fill and file back in the form of ZIP files which carry and contain malware. If files are downloaded and opened they usually deploy RATS or constant redirects to phishing pages designed for credential exploitation. Lots of there methods involve replication of login portals and capture MFA.

The reason for the group targeting who they target is because they want access to the potential monetization the account may bring, if its a high traffic page - its valuable. Which is why digital marketers, people who may have access to high traffic media accounts and such fit the role perfectly. If the scammers gain access, they can exploit that traffic for monetization, they can set up there ad fraud schemes and have an army of "company" accounts that are actually just revenue generators for the scammers - no one knows a thing - (for a while atleast).





# Task 6 

The diamond model helped me break the report down into more clear sections, I was able to understand each individual peice a bit better and understand how everything works together. Who the attacker is, what they do - what tools and knowledge they have, and who they are targetting. This made the whole diagram, report and everything else easier to understand because the model actually forces you to seperate each part and see how they can connect.

The biggest challenge was figuring out what counted as infrastructure versus capabilities - as some things seem to kind of overlap.. another challenge was that the report didn’t really label an “adversary” or “victim,” so I had to do a bit of interpretation on where things went.. It took a bit of reading and re-reading to pull out the right points and summarize them properly.

Using this model helps defenders spot the patterns. When you know and understand the infastructure of the threat actor and what they rely on, the tools they use and how they pick victims - its easier to build detections and do the necesarry implementations of planning a form of "defense" against the enemy. The model helps turn the threat into something anticipatable and even actionable.



