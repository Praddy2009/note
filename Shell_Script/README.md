[Click here! Code online](https://repl.it/languages/bash%23main.sh)

`#<Somecode>` : To comment your code
<br>
`var_name=var_value` : To store value in a variable
<br>
`read var_name` : To take input of variable
<br>
`$var_name` : To access value stored inside variable
<br>
To make a variable readonly
```
var_name=var_value
readonly var_name
``` 
`unset var_name` : To delete variable 
<br>
<br>
`arr_name=('val1' 'val2' 'val3')` : To create an array
<br>
`${arr_name[index]}` : To access the value at specific index
<br>
`${arr_name[@]}` & `${arr_name[*]}` : To access all the values of array in one go
<br>
<br>
[Chekout Operators](https://www.tutorialspoint.com/unix/unix-basic-operators.htm)
<br>
<br>
If statement
```
if [ condition ]
then
  Statement
fi  
```

If else statement
```
if [ condition ]
then
  Statement
else
  Statement
fi  
```

If elif else statement
```
if [ condition ]
then
  Statement
elif [ condition ]
then
  Statement
else
  Statement
fi  
```

Case statement
```
vehicle="UFO"

case $vehicle in
  "car" )
    echo "It's car" ;;
  "bus" )
    echo "It's bus" ;;
  "truck" )
    echo "It's truck" ;;
  * )
    echo "It's Unknown" ;; 
esac
```
<br>
<br>

For Loop
```
for (( i=0; i<5; i++ ))
do
  echo $i
done
```
<br>
<br>

While loop
```
i=1
while [ $i -lt 5 ]
do
  echo "hero"
  i=$(( i+1 ))
done
```
<br>
<br>

Until loop
```
i=1
until [ $i -eq 5 ]
do
  echo "hero"
  i=$(( i+1 ))
done
```
