{
  "title": "Distributed tracing of transactions for an existing financial transaction processing pipeline",
  "date": "2018-02-11T12:41:05-05:00",
  "image": "/img/circleci-workflow.png",
  "link": "https://github.com/eddiewebb/bosh-bamboo",
  "image": "",
  "description": "This is distributed tracing mechanism for tracing Microsoft's financial transaction flowing through multiple subsidiaries and making them available to the stakeholders through a UI powered by REST API",
  "tags": ["DevOps","BOSH", "Java", "Atlassian Ecosystem", "monit", "python", "xml/xslt", "bash/shell","REST APIs"],
  "fact": "",
  "featured":true
}

•	Worked in a team to design and develop a distributed tracing mechanism for tracing Microsoft’s financial transactions flowing through multiple sub-systems.
•	Enhanced the design to support tracing of batched transactions which can further split into multiple discrete transactions and multiple batched transactions and so on such that each final discrete transaction can be traced individually.
•	Developed a service to track the failed transactions and trace it back to its previous hop.
•	Developed a tool to onboard new clients (existing Lines Of Business with financial transactions) onto the tracking system and streamlined the onboarding process.
•	Implemented additional key features of the tracing system including correlation of transaction with acknowledgements at various stages and associating arbitrary contextual information at each hop of the transaction.
•	A UI powered by a REST API provided stakeholders to query the progress of each individual transactions.  Worked on the API part to implement the search functionality based on various properties of transactions.

