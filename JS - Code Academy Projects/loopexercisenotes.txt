const rapperArray = ["Lil' Kim", "Jay-Z", "Notorious B.I.G.", "Tupac"];

// Write your code below
for (let i=0; i < rapperArray.length; i++) {
    console.log(rapperArray[i])
  console.log(i)
  if (rapperArray[i]=='Notorious B.I.G.')//Remember to write == as = is 'equal' and replace the var; == is 'is equal to' for comparision in for/while condition
  {
  console.log(rapperArray[i])
    break;
  }
}
console.log('And if you don\'t know, now you know.')

