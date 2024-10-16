# Hey Day

## A Simple Script for October the Sixteenth 

### First, add your shebang line

```bash
#!/bin/bash
```


### Then, the command will ask the user for their name
```bash
echo "What is your name?"
```
### read -s will allow the user to add their name without seeing their input on the STDOUT.
```bash
read -s name
```
### Lastly, echo will greet the user
```bash
echo "Hey, $name! Did you know today is Hey Day?!"
```