# day_8
    ___Инструкция if___


const weather = "дождь"; 

if (weather === "дождь") {
  console.log("Не забудь взять зонт!");
}
if (weather === "солнце") {
  console.log("Не забудь взять панаму!");
}

const weather = "дождь"; 
const isRain = weather === "дождь"; // заранее вычислим есть дождь или нет

if (isRain) { // используем результат вычислений для условного ветвления 
  console.log("Не забудь взять зонт!");
};
   
    ___Логическое преобразование___
   
    
const count = 5;

if (count) {
  console.log("У нас есть несколько яблок!"); // Сработает, так как count не 0
}

const name = "";

if (name) {
  console.log("Привет, " + name); // Не сработает, так как name - пустая строка
}

    ___Использование else и else if___

const time = 10;

if (time < 7) {
  console.log("Слишком рано, еще спим...");
} else if (time < 12) {
  console.log("Доброе утро!");
} else {
  console.log("Скорее всего, уже день.");
}

    ___Тернарный оператор___


const age = 27;

const isAdult = age >= 16;
const ageCategory = isAdult ? "Взрослый" : "Ребенок";
console.log(ageCategory); // Взрослый

const score = 85;
const grade = score > 90 ? 'A' : score > 75 ? 'B' : score > 60 ? 'C' : 'D';
console.log(grade); // Выведет 'B'





