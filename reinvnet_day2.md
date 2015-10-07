## 10/6/2015 - AWS re:Invent (Day 2)

### Global Partner Summet (Terry Wise)

The keynote for Global Partners.

#### AWS Marketplace 2015

- AWS customers using 143 million hours of Amazon EC2 for AWS Marketplace software
products.

- More to come including Chef, Splunk, etc.

- AWS Quick Starts: reference deployments for rapidly deploying popular software
  with AWS best practices (MondoDB, Sharepoint, etc.)

#### Growth

- In 2014 absolute growth of IaaS workloads surpassed the growth of on-premise
  workloads (Gartner)

- Customer success from many different fields (entertainment, startups,
  manufacturing, finance, gaming, etc.)

- Over 2000 gov agencies, 5000 educational institutions, 17500 nonprofits
  utilizing AWS products

#### What are customers asking for?

- Security/governance, backup/disaster recovery, managed services, DevOps, etc.

- Expanding current services

#### AWS Developer and Management Tools

- Not just a transformation of **where**, but also a transformation of **how**
  their developers work

- Customers want to combine AWS services with other partner services - build AWS
  tools around seamless compatibility with partner services

- Full service support

##### Moving faster, safely

- Big monolithic apps to microservers
- Large teams to small teams
- Discipline silos to DevOps teams
- Infrequent releases to continuous releases

- This adds up to Massive number of deployments

#### Announcing DevOps competency

- AWS partners who offer powerful DevOps tools
- Continuous Integration
- Config management
- etc.

#### BYOL Windows License

- Customers can use their own licenses on EC2 dedicated hosts (Windows, SQL,
  SUSE Linux Enterprise, etc.)

- Allow customers to reuse investments in software.


### EC2 Deep Dive

Q&A session

Q. Whats happening with networking?
A. Many limits based on what the kernel was built to support. Working on scaling
that out.

Q. Inter-region peering.
A. It's coming.

Q. Customer looking for ephemeral storage on c4.
A. It wasn't being used by anyone, but we'd love to know of the use cases.

Q. What will Redshift deploy with?
A. i2s only. Need to resolve an issue with other instance types.

Q. Add more net interfaces without larger instances?
A. Noted. Its a limited resource at the moment.

Q. Availability of g2s in "our" region?
A. We need the right signals and we can dive in.

NOTE: d2s will not launch with Redshift

Q. More memory/processing power?
A. New 2TB ram availability coming.

Q. Any plans to retire older instance types?
A. Not yet. Considering that for the ones nobody is using anymore.

#### General Comments

- Gov moves slow - we just want to know ahead of time whats going to be
  available.

- Committed to GPU improvements.

