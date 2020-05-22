# javascript-snippets
Overview for JavaScript Array Methods

## forEach methode

const = numbers = [1, 2, 3, 4, 5];

numbers.forEach(printItem);

function printItem(item, index, arr) {
  console.log('item number' + index + 'has value of' + item)
}

----

can also be written with a arrow function

====

numbers.forEach((item, index, arr) => {
    console.log('item number' + index + 'has value of' + item)
}
