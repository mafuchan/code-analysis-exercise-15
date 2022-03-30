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
|{dogs: [{name: "Steve"}]}, "Steve" | undefined | 
|{dogs: [{name: "Ein"}]}, "Ein" |  {name : "Ein"}    | 
|{dogs: [{name: "Clancy"}]}, "Clancy" |  {name : "Clancy"} | 
|{dogs: [{name: "Fido"}]}, "Fido" |  {name : "Fido" }  | 
|{dogs: [{name: "Kyle"}]}, "Kyle" | undefined |
<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function compares the name provided within the array and if the person has a name that is equal to the dog, which then the dog's name is returned. Otherwise, it is undefined since there is no else statement to return a value.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
