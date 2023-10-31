# bash_scripting
What is terminal and bash scripting. Standart functions, custom functions, conditions and loops

### Standart functions:
**echo** function used for get info from standart output *stdout*
### Custom functions:
Custom function used for reuse some piese of code.\
**Declare:**
```
print_some_text () {
  local text=$1
  echo "$text"
}
```
**Call function:**\
`print_some_text "some text for print"`
### if conditions
**if** condition used for choose one branch from few \
*example*
```
var1="13"
var2="14"
if [["$var1" == "$var2" ]]; then
  echo "$va1 equal $var2"
else
  echo "$var1 not equal $var2"
fi
```
### Loops:
**lops used for repeat some pies of code a few times** \
*example*
```
FILES="1.txt 2.txt 3.txt 4.txt 5.txt"
for FILE in $FILES; do
  echo "$FILE"
done
```
