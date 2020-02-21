# CrowFacts
A database of information about crows, both found within and outside of the United States, based on user input. Can be sorted by:
- Species
- Location
- Size
- Weight
- Conservation status

Partitioned on species.

There is a seperate storage table of general crow facts which will be randomly chosen and generated. Examples of randomly generated output includes:
- “Here’s a crow fact: After fledglings leave the nest, parents care for them for several months.”
- “Here’s a crow fact: Crows mate for life.”

Database will be accessible via a web-page built using an API backend microservice deployed as a container through AWS Fargate. Additional functionality will be added so the database information can be used within separate applications, or feed into FeelGood lambda project.
