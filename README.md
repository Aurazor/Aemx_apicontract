# Aemx ApiContract
## Project Description:

Aemx-Apicontract is a Java library that provides functionality to generate Java models and API interfaces from an OpenAPI schema. It includes a feature to map variables to Java models, adapting them to MongoDB entities using the repository pattern. This library allows you to easily create and manage Java models based on the defined API endpoints in the OpenAPI schema and seamlessly save and retrieve data in a MongoDB database.

## Key Features:

Generate Java models and API interfaces from an OpenAPI schema.
Map variables to Java models adapted for MongoDB entities using the repository pattern.
Save and retrieve data in MongoDB with ease using the provided repository.

## Prerequisites:
* Ensure you have Java 11 or later installed on your system.

## Clone the project
    git clone https://github.com/Aurazor/Aemx_apicontract.git
## Build the project
    cd Aemx_apicontract
    mvn clean install
## Usage
* Add the dependency and build your project.

        <dependency>
            <groupId>com.nikhilaukhaj</groupId>
            <artifactId>aemx-apicontract</artifactId>
            <version>1.0.8-SNAPSHOT</version>
        </dependency>
## Person REST
* Person API interface (**PersonApi**)

        public class RestPerson implements PersonApi {}
* Person API models (**PersonDetailsFull**) repository

      @ApplicationScoped
      public class PersonModelRepository implements PanacheMongoRepository<PersonDetailsFull> {}
         




    




