# Javascript Snippets
Overview for JavaScript Array Methods

Source:
https://www.youtube.com/playlist?list=PLgBH1CvjOA62PBFIDq55-S6Beivje30A2

## forEach method

```javascript
const = numbers = [1, 2, 3, 4, 5];

numbers.forEach(printItem);

function printItem(item, index, arr) {
  console.log('item number' + index + 'has value of' + item)
}

// Expected outcome
```

----

Can also be written with a arrow function.

----

```javascript
const = numbers = [1, 2, 3, 4, 5];

numbers.forEach((item, index, arr) => {
    console.log('item number' + index + 'has value of' + item)
}

// Expected outcome
```

----

So what does the 'arr' property do? Lets just see.

----


```javascript
const = numbers = [1, 2, 3, 4, 5];

numbers.forEach((item, index, arr) => {
    console.log(arr)
}

// Expected outcome
```

### UseCases
