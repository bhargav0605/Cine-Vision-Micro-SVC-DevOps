## Tasks:

- Separate these projects first:
BackEnd:
Micro Services:
1. Movie Service
2. User Service

Helper Services:
1. Email Service

FrontEnd:
1. React Service

Database:
1. Postgres
2. MongoDB
3. Kafka & Zookeeper
4. KeyCloak
5. Zipkin
6. Redis

######## TASKS for v0.1.0 ########
- [x] Take all the services out first.
- [ ] Make all URLs and secrets(not secure but it is v0.1.0) used in these services hard coded in environment variables.
- [X] Create Docker Images for all these micro services.
- [ ] Make Jenkins/GitHub action workflow to deploy all these docker images and security of it.
- [ ] Create K8 files for all these micro services and make these secrets and URLs in configmap(still hard coded and not secure).
- [ ] Integrate the Vault to store all the secrets and update micro services to use this.
- [ ] Deploy this on K8.
- [ ] Testing
