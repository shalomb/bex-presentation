---

### PaaS Portfolio

- Backups as a Service (BUaaS)
  - File Level
  - VM/Tenant Level
- Monitoring as a Service (MonaaS)
- Databases as a Service
  - SQLaaS
  - NoSQLaaS
- Load-Balancers as a Service (LBaaS - L7)
- License Management as a Service (LMaaS*)
- File Sharing (ARCaaS)
- Functions as a Service (FaaS)

---

### Backups as a Service (BUaaS)

- Service for NatCo Services as well as IT
- Plays into backup/restore/disaster recovery stories
- 2 Parts - File Level and VM/Tenant Level

---

### Backups as a Service (BUaaS - File Level)

- Provided by Restic
- Cross Platform, Open Source (BSD Licensed)
- Agent based, integrates into customers requirements as they see fit
- Portal provisions
  - Backup Targets (Openstack GR Ceph), Credentials
  - Configuration
- Customer deploys as required

---

### Backups as a Service (BUaaS - VM Level)

- Provided by Trilio™ ("Openstack Raksha")
- Protection for full tenant workloads
- Openstack native integration "data protection"
  - Agentless - Openstack performs backups to schedules
  - "Forever" Scalable
- Portal provisions TrilioVault particulars
  - Storage, Credentials, NetworkAccess

---

### Monitoring as a Service (Monaas)

- To be defined by customer demand and wider architectural concerns
- Start with exposing existing Openstack functionality
  - Ceilometer/Datalake
- Extend with Openstack Monasca
  - Provides both monitoring and log pipelines
  - POC carried out by NFVI Monitoring

---

### Databases as a Service

- Allow customers to offload setup and management complexity of DBs
- 2 Parts
  - SQLaaS for RDBMS DB
  - NoSQLaaS for NoSQL DB

---

### Databases as a Service (SQLaaS)

- Support relational database workloads
- Provided by Postgresql
- Opensource, highly scalable
- Feature Partity with Oracle™
- Open Questions around deployment/consumption models
  - In-tenant deployment vs hosted multi-tenant service
  - Or both?

---

### Databases as a Service (NoSQLaaS)

- Support non-relational database workloads
- Provided by Apache Cassandra
- Highly scalable, durable
- Similar deployment/consumption model to SQLaaS

---

### License Management as a Service (LMaaS)

- Provided by Optisam
- Inventory of licenses allocation/usage
- TBD

---

### File Sharing (ARCaaS)

File sharing platform

- Provided by Pydio
- Similar in concept to Google Drive/Dropbox - easy to use
- Collaboration model - workspaces/cells
- Hosted multi-tenant service
- TBD

---

### Functions as a Service (FaaS)

Allow customers to develop/run/manage "Serverless" applications
- with minimal complexity
- Simply push code into FaaS

- Based on Apache Openwhisk
- Event driven function execution
- Provides for many Pan-Net internal engineering needs
  - Infrequent background jobs
  - CI/CD, Deployments, Maintenance, etc
- TBD

