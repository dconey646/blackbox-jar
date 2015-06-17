# Person-service
Welcome to the Person Service! Created by TerribleCode co. As part of this service, there are three endpoints for which you can use. Please find them below!

#Get the list of all the people
GET Request
/person
Should return a list of people. Example response:
[
  {
    "name":"Ben"
    }
]

#Add a person to the list
POST request
/person
Will add a person to the list of people in the service. Example of the data to send:
{
  "name":"Ben"
}

#Delete a person from the list
DELETE request
/person/{index}
Will delete the person in the corresponding index. Example request:
/person/0

Please report any issues to the support team!
