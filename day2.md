day 2 learnings

crud operations:
the basic 4 functions which is used to control data

patch put post:
patch  is used when we have to update some part of the data
whereas post is used for new data and put is used to update the whole data

status codes:
200 ok
201 created
400 bad request
401 unauthorized
404 not found
500 internal server error

updated serialization concept:
serialization works like both tojson and fromjson and when it gets the data from user and want to store it in database it runs a validation check then it goes in the database but converted in the format the data is stored in db

415 error:
i also encountered 415 error when i used the body as text instead of json it came in put or post request
this means that the data type should be  in json so that the server understands it