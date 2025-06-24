// Welcome message
alert("👋 Welcome to the JavaScript Trivia Bot!");

let score = 0; // Initialize score

// Question 1
let answer1 = prompt("Q1: What does HTML stand for?");
if (answer1 && answer1.toLowerCase() === "hypertext markup language") {
  alert("✅ Correct!");
  score++;
} else {
  alert("❌ Oops! The correct answer is 'HyperText Markup Language'.");
}

// Question 2
let answer2 = prompt("Q2: Which symbol is used for comments in JavaScript?");
if (answer2 && (answer2 === "//" || answer2.toLowerCase() === "double forward slash")) {
  alert("✅ Correct!");
  score++;
} else {
  alert("❌ The correct answer is // (double forward slash).");
}

// Question 3
let answer3 = prompt("Q3: What keyword is used to declare a variable in JavaScript?");
if (answer3 && (answer3.toLowerCase() === "let" || answer3.toLowerCase() === "var" || answer3.toLowerCase() === "const")) {
  alert("✅ Correct! You picked one of the valid keywords.");
  score++;
} else {
  alert("❌ The correct answers could be: let, var, or const.");
}

// Final Score
alert("🎉 You scored " + score + " out of 3. Thanks for playing!");
