day 6 learnings

linter:
it scans the code for errors or bad practices like that
formatter:
it just checks how the code looks like and format it properly like spacing indentation things like that

ruff:
it is a python linter and it does both the works

some rules of ruff :
it checks if the lines length is greater than 88 chars it will give a warning
it check if we have not imported a library it will give a warning
also the migrations are excluded as they are automatically generated codes so its just waste of time to check for errors in them 