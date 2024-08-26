# COSC55 Final Project
## Due August 27th, at 11:59 PM

Welcome To Sri and Warren's repository  + wiki for our COSC 55 Final project! This ReadMe will act as a guide for the wiki.

## Structure of Repo
All of our documentation is through the wiki feature; click the wiki, then select the relevant page. We have pages for each module, a initial source which we used to guide our research, and a final resources page of articles we used to guide our implementations for security for module 4. Check the wiki for the details on the project, including a security implementation walkthrough and such.

## In a Nutshell:
- 12 Distinct AWS Resources used
- 15 hours spent on implementation
- 2 hours spent agonizing on why IAM would not work
- 2 students with a now in-depth understanding of AWS
- 2 Happy faces when the project was finished

## Summary of Project
First, some background on the hypothetical organization: they are a small company that develops software, about 60-80 people large. They have an "employee directory", which is the focus of this project. This employee directory has application server(s) that serve curious employees a directory of their fellow coworkers, their contact photos, and contact information, and a database server that stores this information. A s3 bucket is used store employee pictures, and another will be used to store logs. Our project is implementing security on this


Our project initially started off as a project focusing on encryption, where we would primarily be using Amazon KMS and IAM to ensure strict user roles and employ encryption at rest and transit through various AWS services, and use CloudWatch and CloudTrail for logging and monitoring purposes among other resources. We initially wanted to have a load balancer as well. However, as we started module 3, we realized that a load balancer would not be useful/make sense for our implementation, and pivoted away from it. An obstacle we ran into was our learner acounts could not use the IAM interface to create roles and such, which ended up restricting the scope of initial project even more. However, at this point, we decided to expand the initial scope of the project and dive deep into all the various offerings AWS could provide us, with the objective to learn the most, even if we were blocked off from using certain features. We ended up using the following resources either hypothetically(because lack of permissions), or in actual practice: AWS Lambda, Rekognition, EC2, Systems Manager(Fleet Manager, Incident Manager), VPC, CloudWatch, CloudTrail, Firewall Manager, IAM, KMS, S3, and GuardDuty. 

Into the Implementation:
We had a VPC, where the hypothethical organization would have their cloud environemnt live. There would be a public subnet and a private subnet. THe private subnet would have a database server to store data on the 

## Project Reflection

Looking back on our project, it was disappointing that we couldn’t use IAM, which was a major focus for us. We had planned on using IAM for managing user permissions and security, and its absence felt like a big setback. We were initially bummed out because it seemed like we were missing a crucial part of our setup. Despite this, our team rallied together and used the challenge as a chance to get creative. We quickly shifted our approach and used other AWS services to build a solution that ended up being even better than what we had originally planned. This experience taught us that being flexible and adapting to new circumstances can lead to great results, sometimes even exceeding our initial goals. If we had the opportunity to tackle this project again, using our own AWS accounts would be something that we would do. Having direct control over individual AWS accounts would allow us to fully experiment with and implement IAM roles and policies as originally intended, and all the services that relied on them. This would provide us with a deeper understanding of how to manage permissions, set up security measures, and troubleshoot real-world issues, all of which are crucial for building a secure and efficient system. Additionally, managing our own AWS accounts would give us a hands-on opportunity to explore billing and cost management features in real-time. We could monitor and optimize resource usage more effectively, learning valuable lessons about cost control and budgeting in the cloud. Overall, having personal AWS accounts would not only enrich our technical skills but also offer a more comprehensive learning experience, enabling us to apply our knowledge and make more informed decisions in future projects.

Through this project, we've gained significant experience with AWS, an industry standard that is widely used across the technology sector. Mastering AWS has provided us with practical skills and knowledge in cloud computing, which are highly valued in the field of computer science. Understanding how to deploy, manage, and secure cloud resources prepares us for real-world challenges and enhances our readiness for careers in tech. This hands-on experience not only builds our technical expertise but also gives us a competitive edge in the job market, as proficiency with AWS is a key asset for many roles in computer science and related fields. With a solid understanding of AWS, we’re well-prepared to deploy and host our own applications, in conjunction with our previous knowledege of Docker and containerization. AWS provides a range of tools and services that make it easy to scale, manage, and secure applications, which is crucial for side projects that might grow in complexity. Whether it's hosting a web application, managing databases, or automating workflows, our newfound expertise with AWS enables us to build, deploy, and maintain projects efficiently and effectively, opening up new possibilities for innovation and experimentation in our personal endeavors.

## Project Conclusion

This project has been an invaluable learning experience, significantly expanding our understanding security within cloud computing scenarios. Through hands-on work with AWS services, we’ve gained practical skills in deploying, managing, and securing cloud-based applications. Our ability to adapt and overcome challenges, such as the inability to use IAM as initially planned, has strengthened our problem-solving capabilities and deepened our technical knowledge. The insights gained from working with AWS have not only enhanced our current project but also prepared us for future endeavors in the tech industry. Additionally, this project has prepared us well for our own side projects. The skills we’ve acquired will be essential as we continue to explore new technologies and work on diverse projects in the future.

Thank you Professor Adam Goldstein! His informative lectures and detailed explanations provided us with a solid foundation in AWS and cloud computing. Professor Goldstein’s ability to break down complex concepts into manageable and comprehensible parts made it easier for us to grasp the intricacies of AWS, which isnt exactly the most user friendly in terms of design. Professor Goldstein’s insights and feedback not only helped us overcome obstacles but also inspired us to approach challenges with a solution-oriented mindset. Thank you, Professor Goldstein, for your dedication and for providing us with the tools and knowledge to succeed in this project and beyond!






