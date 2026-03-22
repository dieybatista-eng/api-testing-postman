# API Test Cases

## TC01 - Get Users

Endpoint:
GET https://reqres.in/api/users

Steps:
1. Send GET request
2. Validate response

Expected Result:
Status code 200 and list of users returned

---

## TC02 - Create User

Endpoint:
POST https://reqres.in/api/users

Body:
{
  "name": "Diey",
  "job": "QA"
}

Expected Result:
User created successfully (status 201)
