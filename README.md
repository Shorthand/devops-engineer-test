# Service Deployment

## A take-home challenge for DevOps / Cloud Engineers

### Background

A new web-based service needs to be deployed into production such that it is accessible from the internet by the general public. The service itself consists of a docker container containing the core service logic, a set of static html/css/js/etc files, and requires access to an existing hosted database.
The deployment is expected to handle at least 1000 concurrent users at launch, with the ability to scale up or down as required
by demand, and remain highly available in the face of server or network failures, or deliberate DoS. The service will need to be
updated from time-to-time, with minimal downtime.

### Challenge

Your challenge is two-fold:

1. Design appropriate deployment infrastructure for this service that meets the above requirements, including relevant deployment diagrams. The design may make use of any AWS or non-AWS services that you deem suitable for a production system.
   Please explicitly state any assumptions that you need to make as part of this design, as well as any expectations of the provided service container.
2. Implement this design using AWS CDK (preferred) or an equivalent deployment technology. An example Dockerfile of an (extremely) simple API endpoint container is provided in the 'api' folder of this repository that you may use.

### Criteria

Assuming that you submit a viable solution, we are then first and foremost interested to see _how_ you solve the problem. That is our top criterion below:

1. Elegance/simplicity of your solution
2. Elegance/maintainability of your code (note: this is very distinct from the first criterion!)
3. Design documentation + comments.

### Submitting your solution

Clone this repository and set up your own, new private repository as the origin remote.

Once your remote repository is ready, add @ckortekaas and let us know that you've completed the challenge.

---

Your comments go here.
