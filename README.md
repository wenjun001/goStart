### This project illustrate project struction for go language. 
src is code folder.
and there are 2 folder one is main folder named sored and other is algorithm that is for bubble and quick sort implment. 

How to run this code:

1. set $GOPATH for this project 
2. go build algorithm/qsort
3. go build algorithm/bubblesort
4. go test algorithm/qsort
5. go test algorithm/bubblesort
6. go install algorithm/qsort
7. go install algorithm/bubblesort
8. go build sorter
9. go install sorter

Finally run it 

````bath
./sorter -i unsorted.dat -o sorted.dat -a qsort

unsorted.dat contains some data such as:

12
2
34
44
232
23
33
````
