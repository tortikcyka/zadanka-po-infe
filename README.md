console.log("hola es mi trabajo");

let answer = "";

// Крок 1: Вимагаємо "!hi!"
while (answer !== "!hi!") {
  answer = prompt("Write '!hi!' to continue");
  if (answer !== "!hi!") {
    console.log("You didn't write '!hi!'. Please try again.");
  }
}

console.log("That’s some about me");

// Крок 2: Вимагаємо "w"
answer = "";
while (answer !== "w") {
  answer = prompt("Write 'w' to continue");
  if (answer !== "w") {
    console.log("You didn't write 'w'. Please try again.");
  }
}

console.log("My name is Mykyta Redka. I'm from Ukraine. I'm 16 years old.");

// Крок 3: Знову вимагаємо "w"
answer = "";
while (answer !== "w") {
  answer = prompt("Write 'w' to continue");
  if (answer !== "w") {
    console.log("You didn't write 'w'. Please try again.");
  }
}

console.log("I was born in Kherson and study at school №31 on Kazatsky.");



