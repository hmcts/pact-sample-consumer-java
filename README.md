# Testing a Spring Boot REST API Consumer against a Contract with Pact


## Getting Started

* run `./gradlew build` in this project to create a pact and run the consumer test
* afterwards, find the pact contract file in the folder `target/pacts` 
* use the docker-pactbroker-compose.yml file to bring up a local pact broker if one isnt't running already
* publish the pact using the pactPubish task in gradle
