let word1 = prompt("Enter the first word:");
let word2 = prompt("Enter the second word:");

// Log to the console the original strings and the reversed strings

function reverseString(str) {
  return str.split("").reverse().join("");
}

let reversedWord1 = reverseString(word1);
let reversedWord2 = reverseString(word2);

console.log("Original word 1:", word1);
console.log("Reversed word 1:", reversedWord1);
console.log("Original word 2:", word2);
console.log("Reversed word 2:", reversedWord2);

// Log to the console by returning the truth value if the original string is equivalent to the reversed string.

console.log("Is word 1 a palindrome?", word1 === reversedWord1);
console.log("Is word 2 a palindrome?", word2 === revers
 ...
