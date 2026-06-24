mDay 1 learnings


django and drf:
django is a python web framework for backend development and
drf is a python package that extends django to create web APIs

models:
models connect the database and the code in such a way that we wont need to open the database and do things manually
we use models which helps accessing  database tables easily same like i did in laravel in (web course this sem) but with a little difference

serializer:
serrializer converts data from database into json so that different frameworks can work together just like the tojson function used in flutter dart which converts the dart objects to json

viewsets:
viewsets are used to perform crud operations on models
it stores all the logic for the crud operations at one place in this way we dont need to write separate codes for each function
it is same like resourcecontrollers in laravel