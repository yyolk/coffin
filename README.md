[![Build Status](https://secure.travis-ci.org/yyolk/coffyn.png)](http://travis-ci.org/yyolk/coffyn) [![bitHound Overalll Score](https://www.bithound.io/github/yyolk/coffyn/badges/score.svg)](https://www.bithound.io/github/yyolk/coffyn)

# Coffyn

## [Nayls](https://github.com/yyolk/nayls)

### Run coffin with Docker container
```
docker build -t coffin . 
docker run -ti --rm -v $(pwd)/examples:/data print demo.coffin
```

---
_new_
## Commands


### `coffyn dig <new_stack>`
Initiate a project at folder.
Or when within a current stack, add stack within stack.

### `coffyn nail <resource_type>`
Add a resource to the project

### `coffyn plot`
Validate and build the template.

### `coffyn bury`
Launch the stack

### `coffyn memorial <stack_name>`
Diff a stack to current project
Diff a stack to it's original template (Audit trail?, based on cloudtrail?)

### `coffyn mourn [<stack_name>]`
Describe stack(s)

### `coffyn exhume <stack_name>`
Tear down a stack
#### options
- `--disinterment`
    + tear down all stacks based on a `[tag]` arg?
    + 

### `coffyn entomb <stack_name> <new_stack_name>`
Copy a stack?

### `coffyn crypt[s]`
- ???
- _single-crypt_

### `coffyn mausoleum`
??? Describe all stacks ???

### `coffyn ease[ment]`
- The printed contract and agreement made between cemetery staff and the individual purchasing the rights of interment.

### `coffyn grave`
???

### `coffyn urn`
???

### `coffyn headstone`
???

### `coffyn frame <basic_resource>`
- a collection of basic resources that are reusable
- a one time run at the beginning of a project
- more like yo i guess

## Project Structure

    /project
    |