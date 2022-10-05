# dmoney-api-jmx

## Technology and Tool used

- Jmeter
- Java jdk

## Scenario of this project

- Creating a jmx file from this following Postman Collection: **https://www.getpostman.com/collections/a8f908e0ee1d77cb6f85**
- Adding following requests:

1. Login to user
2. Get user list
3. Create a user
4. Search the newly created user by id
5. Search the newly created user by phone number
6. Search the newly created user by email
7. Update the user phone number
8. Check User Details After Phone Number Update
9. Delete the user

## How to run this project

- Download the jmx file and keep in bin folder in path\apache-jmeter-5.5\apache-jmeter-5.5\bin
- Run the file in Jmeter 
- To generate report,open gitbash in the bin folder and run following command: 
 ``jmeter -n -t Dmoney.jmx -l Dmoney.csv -e -o Reports``

## prerequisites
**You must have jdk and jmeter installed in your system**


## Output

![jmeter](https://user-images.githubusercontent.com/54511128/194085460-65ac3dc6-6f90-42ac-99b9-a227a1486e0f.PNG)
![Report](https://user-images.githubusercontent.com/54511128/194085481-c599edf1-1bd1-4caa-a35a-bc64c87fd321.PNG)
