# API call demonstration

//Using play framework, the task aims to simulate API calls using using HTTP Methods for RESTful Services

To add, do POST
curl -X POST -H "Content-Type: application/json" -d "{"""firstName""":"""Logan""","""lastName""":"""Thiru""","""age""":26}" http://localhost:9000/

To delete, do DELETE
curl -X DELETE http://localhost:9000/0 

To update, do PUT
curl -X PUT -H "Content-Type: application/json" -d "{"""firstName""":"""Logan""","""lastName""":"""Doe""","""age""":26,"""id""": 0}" http://localhost:9000/

To list all, do 
curl -X GET http://localhost:9000/
