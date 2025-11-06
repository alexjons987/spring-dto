# Spring DTO
## Task 1: DTO from Query Parameters
Requirements:
* Create a GET endpoint that accepts multiple @RequestParam (e.g. name,
category, minprice, maxprice).
* Return the DTO as a JSON response.
* Handle missing parameters with required = false where appropriate.
## Task 2: DTO from PathVariable and RequestParam
Requirements:
* Create a GET endpoint where @PathVariable is used for an id and
@RequestParam is used for filtering or sorting information.
* Build a DTO that combines both types of data.
* Return the DTO in the response as JSON.
* Use a reasonable defaultValue for @RequestParam if no value is passed.
## Task 3: Entity to DTO Conversion
Requirements:
* Create a simple User entity with fields such as id, email, and role.
* Create the corresponding UserDto for data transfer to the client.
* Implement a mapper class that converts between entity and DTO.
* Use a service class that returns UserDto via the controller.
## Task 4: Simple manual validation of DTO data
Requirements:
* Create a GET endpoint that accepts parameters for email and age.
* Manually check in the controller that email contains @ and that age is between
18–99.
* Return a text message indicating whether the data is valid or not.
* Create a simple DTO to hold the values
## Task 5: DTO in ResponseEntity
Requirements:
* Create a GET endpoint that returns a `ResponseEntity<SimpleResponseDto>`.
* The DTO should contain fields such as message, timestamp, and success.
* Return status code 200 OK on successful operation, and 400 BAD_REQUEST on
failure.
* Set the timestamp to the current time and adapt the message depending on
the result.