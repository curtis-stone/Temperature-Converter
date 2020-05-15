# Temperature-Converter
Takes the temperature in Fahrenheit and returns it in both Celsius and Kelvin

// tempScale function holds an object w/ each conversion

 function tempScale(farenheit) {
    return {
        farenheit: farenheit,
        celsius: (farenheit - 32) * (5/9),
        kelvin: (farenheit + 459.67) * (5/9)
    }
}
let temps = tempScale(80) // sets temoerature to 80 degrees Farenheit
console.log(temps) // prints the tempScale object with a list of each temperature value
