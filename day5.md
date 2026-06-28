day 5 learnings:

automated testing and how it is better than manual testing:
automated testing is when we write a code that run tests automatically on our code and it is better than manual testing because it is faster and can run anytime we dont need to test in postman again and again

unit test integration test and end to end test:
unit test: in this a function or a part of code is tested separately 
integration test: in this two or more functions or parts of code are tested together like code with db
end to end test: in this the whole application is tested from start to end just like how a user would use it

pytest fixture:
this is a function that provides mock data for the test like users tasks etc.

pytest django db:
this is used to test the database if we dont use it then the test will not have a db and hence all tests will fail as they will not be able to access the db

we have used apiclient to make requests to our api in the tests this is bcz it is easier to send data in json in this and also it is specially made for apis

also when a user tries to access another task the error tht returns is 404 no 403 this is because if 403 comes  the hacker or the unauthorized person trying to access will learn that there is a task like that in the db as it says forbidden thats why we give error 404 not found which means that there is no such task or file