# JavaScript-Roadmap
Learning JavaScript step by step in 2024

New Features in ES2024

# Object.groupBy()
# Map.groupBy()
# Temporal.PlainDate()
# Temporal.PlainTime()
# Temporal.PlainMonthDay()
# Temporal.PlainYearMonth()

JavaScript Object.groupBy()
const fruits = [
  {name:"apples", quantity:300},
  {name:"bananas", quantity:500},
  {name:"oranges", quantity:200},
  {name:"kiwi", quantity:150}
];

// Callback function to Group Elements
function myCallback({ quantity }) {
  return quantity > 200 ? "ok" : "low";
}

// Group by Quantity
const result = Object.groupBy(fruits, myCallback);


JavaScript Map.groupBy()
// Create an Array
const fruits = [
  {name:"apples", quantity:300},
  {name:"bananas", quantity:500},
  {name:"oranges", quantity:200},
  {name:"kiwi", quantity:150}
];

// Callback function to Group Elements
function myCallback({ quantity }) {
  return quantity > 200 ? "ok" : "low";
}

// Group by Quantity
const result = Map.groupBy(fruits, myCallback);

JavaScript Temporal.PlainDate()
const date = Temporal.PlainDate(2024, 5, 1);

JavaScript Temporal.PlainTime()
const date = new Temporal.PlainTime(10, 30);

JavaScript Temporal.PlainMonthDay()
const date = new Temporal.PlainMonthDay(5, 1);

JavaScript Temporal.YearMonth()
const date = new Temporal.PlainYearMonth(2024, 5);




