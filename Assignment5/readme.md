To execute the assignment:

cd into the directory

run the command in the terminal:
	cat filename.txt | python mapper_name.py | sort | python reducer_name.py 

(use 'type' instead of 'cat' in Windows CMD)

for example, to run the question 1:

cat input.txt | python mapper1.py | sort | python reducer1.py

To write the results to a file

cat input.txt | python mapper1.py | sort | python reducer1.py > output.txt