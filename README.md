# gRPC - test

let’s develop an student onboarding system using three Node.JS micro services for inter-microservice communication let’s make use of gRPC

### Main microservice (primary)

This microservice accepts a student onbording request via a RESTful API endpoint, then communicates with our two secondary microservices to process the onbording. The RESTful API also offers an endpoint to check the status of an onbording request

### Degree selector microservice (secondary)

The main microservice communicates with this microservice and searches for degree details

### onBoarding processor microservice (secondary)

This microservice accepts an onboarding request and provides the current onboarding status based on the onboarding status change events
