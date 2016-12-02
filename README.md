This project illustrate project struction for go language. 
src is code folder.
and there are 2 folder one is main folder named sored and other is algorithm that is for bubble and quick sort implment. 

How to run this code:

set $GOPATH for this project 

go build algorithm/qsort
go build algorithm/bubblesort
go test algorithm/qsort
go test algorithm/bubblesort
go install algorithm/qsort
go install algorithm/bubblesort
go build sorter
go install sorter

Finally run it 

./sorter -i unsorted.dat -o sorted.dat -a qsort

unsorted.dat contains some data such as:

12
2
34
44
232
23
33
