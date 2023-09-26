# CORTEX-XSOA
THIS PROJECT helped me understanding the working of CORTEX XSOAR whicn is a comprehensive security orchestration, automation, and response (SOAR) platform developed by Palo Alto Networks It is designed to help organizations streamline and automate their security operations.
This project focussed on automating response to phishing using  CorteX XSOAR. Since, the above mentioned SIEM platform is paid, I performed the Lab project on Google cloud in a course provided by Google itself.
This project made me understood the functioning of cortex xsoar and how to react to phishing attacks.
In this simulation, a genuine spear phishing incident occurs within a fictional bank setting. The perpetrator gains unauthorized access to the "Galactic Ministry of Finance," specifically compromising the email server of their loan syndication division. Posing as the Assistant Vice President of the syndication group, the attacker targets the Executive Vice President of Corporate Banking at Bordeaux Bank with a phishing email during a crucial business period.

![start1](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/9282e1b3-2d2f-4504-93c8-f10a835e1d50)

A Spear Phishing attack is a type of phishing attack that targets specific individuals or organizations typically through malicious emails.


![step 0](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/d30b065b-e1cb-4f77-8689-ff7f59be77a5)

Since, it is a demo, I was already provided with a possible phishing email attack which was relfected on the SIEM platfrom.

![step 6](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/a4194540-498c-4ba8-b853-95217ac152ce)

I then selected the Phishing incident under 'New Incident'. One of the benefits of using a SIEM platform is that you are provided with playbooks and can also create custom playbooks . Here I was provided with a email phishing playbook.

**Email Phishing Playbook Description:** This is an automated playbook to investigate suspected Phishing attempts. It picks up the required information from the incident metadata as created by the mail listener.

I was able to see the details of the possible phished email under the CASE INFO tab.

![step 8](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/68953d1f-7fa8-488c-994c-fcb776dbec42)

Then inorder to observe the playbook, I selected the work plan tab where I was already given some automated steps in order to perform responses and provide remediation measures.

![step 9](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/8c264a0b-9bee-4f76-9c16-ab46f6f5a2ef)

**The following steps were to be manually performed -**
1. Manually inspect the email for anything suspicious.

2. Assign and involve appropriate personnel.
   
3. Assess severity.
   
4. Are the hostnames in the urls being misrepresented?
   
![step 9](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/207d170e-ad5e-49e9-b95d-70ef387b18f0)



![st10](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/705bf72c-3739-4cb8-bae2-9ffcee60b092)



![step 11](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/154e2ef9-c4e5-43f6-974b-13e2591c3f64)



![step 12](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/c659f0a6-a353-4963-8c7c-34371cebf818)


After closely investigating, the url had a bad reputation.

It is important to check Reputation of the URL as they can indicate if a URL is known for distributing malicious content.

![alert](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/ffcc9c29-4e4b-46f6-b8ec-650127be29c4)




Once I have completed all the tasks, under the WORK PLAN tab, I was able to see my steps which I took and I can review them also. I was also given a verdict for my investigation.

![step 13](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/65697b5f-a17d-4dfb-9f4c-d0b78629373a)




![step 14](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/c9954a51-26d9-4c4e-8044-cb3f70b5765e)





![verdict](https://github.com/shashwatchandra71/CORTEX-XSOAR/assets/126588278/bc772bd6-cbc9-42fd-89bc-d2a59896ec29)




**CONCLUSION :**
I was able to work on Cortex Xsoar and understood the working of a Security Analyst in defending againts Phishing Attacks.  I must say that Cortex XSOAR stands as a formidable asset in the battle against email phishing threats. Its automated response capabilities swiftly detect and neutralize phishing attempts, expediting incident resolution. The platform excels at triaging and prioritizing incidents based on their severity, ensuring that critical threats receive immediate attention. Through seamless orchestration of security tools and processes, Cortex XSOAR streamlines the response effort, reducing manual intervention and accelerating mitigation. Its integration with email security solutions fortifies defenses, drawing on real-time threat intelligence to adapt and strengthen protections. Moreover, Cortex XSOAR enables the execution of tailored playbooks, encompassing steps from isolating affected systems to launching comprehensive forensic investigations. With robust reporting and documentation features, it ensures compliance and furnishes vital insights for post-incident analysis. By fostering collaboration and communication among security teams, Cortex XSOAR empowers organizations to thwart phishing attacks with a unified and efficient response. Its adaptability allows for custom-tailored responses, further enhancing its effectiveness in safeguarding against evolving phishing threats.








