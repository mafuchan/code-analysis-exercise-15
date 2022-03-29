# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (let dog of person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input  | Output |
| -----  | ------ |
|"Steve" | undefined | 
| "Ein"  |  {dog.name : "Ein"}    | 
|"Clancy"|  {dog.name : "Clancy"} | 
| "Fido" |  {dog.name : "Fido" }  | 
| "Kyle" | undefined |
<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function compares the name provided within the object and if the dog.name is equal to petName then the variable dog is returned. Otherwise, it is undefined since there is no else statement to return a value.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
