const array1 = [2, 4, 1, 0, 2, -1];
const array2 = [20, 50, 12, 6, 14, 8];

function smallestNumberFromArray(array) {
  let smallestNumberSoFar = array[0];
  for (let i = 0; i < array.length; i++) {
    if (smallestNumberSoFar >= array[i]) {
      smallestNumberSoFar = array[i];
    }
  }
  return smallestNumberSoFar;
}

function biggestNumberFromArray(array) {
  let biggestNumberSoFar = array[0];
  for (let i = 0; i < array.length; i++) {
    if (biggestNumberSoFar <= array[i]) {
      biggestNumberSoFar = array[i];
    }
  }
  return biggestNumberSoFar;
}

function smallestAndLargestNumber(array) {
  let smallestAndLargestNumbers = [];
  smallestAndLargestNumbers.push(smallestNumberFromArray(array));
  smallestAndLargestNumbers.push(biggestNumberFromArray(array));

  return smallestAndLargestNumbers;
}

console.log(smallestAndLargestNumber(array1));
console.log(smallestAndLargestNumber(array2));
