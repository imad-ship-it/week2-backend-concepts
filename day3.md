day 3 learnings

ORM:
it is used instead of sql queries so that we can writte python code instead of sql queries to interact with the database as database only understand sql so orm converts the python code into sql queries and in this wat we can interact with the db

foreign key and cascade:
foreign key is used when we create a relationship btw 2 tables like in this app there can be multiple tasks of a user so those taasks will have the user id as a foreign key and cascade means that if one thing is deleted all the things that are related to taht will be deleted like if we delete a uuser all of its task will also be deleted

filter() and get()
filter is used when we need multiple tasks and a list is returned while get is used when we need a specific task

django-filter:
it is a library that makes filtering easier like if we were to filter with priority date then without this we would have to write if else codes in views that would make it much more difficult

searchfields and orderingfields:
search field is just like the google search it searches the data in the fields whereas ordering fields is used to order the data in simple sort it

