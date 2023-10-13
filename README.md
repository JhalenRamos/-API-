# API Name
 -API-

## API
Description
  API is a robust RESTful web service that empowers developers to perform essential CRUD (Create, Read, Update, Delete) operations on a MySQL database. This API is specifically designed for managing personal names efficiently and is suited for a wide range of applications, from user management systems to contact databases. It offers a comprehensive set of endpoints and features to interact with and manipulate name data seamlessly.

## API
Endpoints

API provides the following endpoints, each serving a distinct purpose:
POST /postName: This endpoint allows users to create and add new name records to the database.
GET /getName: Users can retrieve existing name records from the database using this endpoint.
POST /updateName: This endpoint facilitates the modification of name records, enabling users to update first and last names.
POST /deleteName: Users can remove name records from the database using this endpoint, providing a means for efficient data management.

## Request
Payload

{
	“lname”: “hortizuela”,
	“fname”:”manny”
}

## Response

{“status”:”success”,”data”:{{“lname”; “hortizuela”, “fname”:”manny”}}}
 


## Usage
Developers can utilize the NameManager API by making HTTP requests to the respective endpoints, allowing for easy integration with their applications. This API simplifies the management of name data within a MySQL database.

## License
No license

## Contributors
 Sir manny hortizuela

## Contact
Information


Include contact
information for inquiries or support.
For inquiries and support, please contact at jhalen.ramos@student.dmmmsu.edu.ph
