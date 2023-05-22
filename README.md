# F.Repository

JavaScript Kelvin and Newton Weather

// This is Kelvin nowdays//
const kelvin = 150;

// This command coverts Kelvin to Celsius//
const celsius = kelvin - 273;

// This command convert Celsius to Newtown//
let newtown = celsius * (33/100);
newtown = Math.floor(newtown);
console.log(`The temperature is ${newtown} degrees Newtown`)

// This method converts Celsius to Faranheits//
let farenheit = celsius * (9/5) + 32;
farenheit = Math.floor(farenheit);
console.log(`The temperature is ${farenheit} degrees Fahrenheit.`);
