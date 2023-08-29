---
layout: default
title: Data Migration
description: Available graduate positions in the data migration project
---

## An intelligent and dynamic planner for adaptive migration of big data systems (1 PhD position available)

### a. Project Description

   Migration of data between two different systems can become a rather complex process. The process of migration usually involves unloading the source data, passing it through a middleware that may process the data (compress it, convert it to the target data format, encrypt it etc.) and eventually loading it to the target system. In practice, the challenge does not lie only on transferring and possibly reformatting the data for the new system. On one hand, the migration requires resources that need to be allocated optimally, so that we reduce costs and migration time and avoid downtime as much as possible. In this scenario, the middleware can be a critical component of the migration. To facilitate and accelerate the process, we can split the source data in streams and parallelize the data transfer. As such, the middleware may require making multiple read and write requests to the source and target systems and deploy a MapReduce like architecture to unload, process and reload the data. Depending on the size of data, the constraints in time and budget and the availability of resources, the middleware needs to make intelligent decisions by solving complex multi-dimensional problems. On the other hand, we need to assume that other aspects of complexity may be present, including that the source, target and middleware systems may not reside in the same infrastructure or may not belong to the same proprietor. In this case, the different migration phases (unloading, reformatting, compression, encryption, reloading) may have to be deployed on different parts of the infrastructure depending on the availability of resources and in order to reduce transmission costs for larger data streams. The final requirement is that the middleware needs to be adaptive. The conditions of the migration process and infrastructure may vary during the actual migration. This variation may occur due to multi-tenancy and sharing of the resources with other applications, due to reliability issues (i.e., migration nodes failing), or due to suboptimal original planning because of uncertainty. The objective of this project is to build a decision-support system to optimize the parameters of the migration and of the infrastructure and a self-adaptive migration middleware that will be able to monitor the migration and adapt its configuration at runtime.

### b. Tasks and responsibilities

   The hired student will work towards the development of a prototype tool for a self-adaptive data migration mechanism. The student will develop the theoretical foundation as well as the implementation for such mechanism. The student will aim to publish in top-tier journals, including IEEE Transactions on Cloud Computing, IEEE Transaction on Big Data, IEEE Transactions on Knowledge and Data Engineering, ACM Transactions on Autonomous and Adaptive Systems, and conferences, such as SEAMS, ACSOS, ICSE, ICPC and others. The student will also be responsible for supervising and mentoring MSc and BSc students working on the project. The position is open for Winter, Summer or Fall 2024.

### c.	Required Skills

   The student will be asked to demonstrate adequate understanding or expertise in the following topics through relevant courses (on undergraduate or graduate level) or through relevant publications in international conferences or journals. The student should consider applying if they have the expert-level skills and at least 50% of the good-level skills.
    
   * Expert programming skills, preferably in python.
   * Expert knowledge on cloud computing and distributed systems.
   * Good knowledge in any of these optimization techniques: linear programming OR dynamic programming OR control theory.
   * Good knowledge on database systems, including relational databases, NoSQL databases, distributed file systems.
   * Good knowledge on distributed data analytics systems, such as MapReduce.
   * Good knowledge on container technology, such as Docker or Kubernetes.
   * Adequate knowledge on machine learning models and methods.
   * Adequate knowledge on simulation methods, like Monte Carlo, and benchmarking techniques.
   * Adequate knowledge on statistical methods and tests.

### d. Application process

   Upon contacting the professor to inquire for the position, the student is also asked to submit the following documents:
   
   * A copy of the most recent version of their CV or Resume.
   * A copy of the transcripts of their undergraduate and master studies.
   * The aforementioned documents are also required by the EECS application process for the PhD program (along with a statement of purpose). The candidate student is highly encouraged to complete the EECS application in parallel to contacting the professor. More information about the EECS application can be found here: https://lassonde.yorku.ca/eecs/academics/graduate/future-students/#phd 
   * The names and contact information of 3 referees.
   * A review for one of the three following articles. The review (maximum one page) should contain a summary of the paper, its strengths and weaknesses and comments about the improvement or extension of the work presented in the paper.
     
     + Ahmad, N., Naveed, Q.N. and Hoda, N., 2018, November. Strategy and procedures for Migration to the Cloud Computing. In 2018 IEEE 5th International Conference on Engineering Technologies and Applied Sciences (ICETAS) (pp. 1-5). IEEE.
     + Jamshidi, P., Ahmad, A. and Pahl, C., 2013. Cloud migration research: a systematic review. IEEE transactions on cloud computing, 1(2), pp.142-157.
     + Hao, W., Yen, I.L. and Thuraisingham, B., 2009, July. Dynamic service and data migration in the clouds. In 2009 33rd annual IEEE international computer software and applications conference (Vol. 2, pp. 134-139). IEEE.
       
   * An example of a proposal (as evidence of writing) written by the student for a research project relevant to the position or of a topic selected by the student. The proposal should include background, motivation, methodology and a plan for evaluation. The proposal should be maximum 2 pages.
   * The candidate student should submit these documents by email to the professor with the subject “Data Migration PhD 2024”. **__No email will be considered unless it has this subject and the required attachments (CV, transcripts, review, proposal)__**. In the email, the student should express their interest to the position and provide the corresponding evidence to the required skills as this appears in the attached documents.


_yay_

[back](./)
