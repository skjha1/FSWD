```js
// // Object Def 
// let Car = {
//     brand: "Toyota",
//     model: "Camry",
//     year: 2020,

//     // Method definition
//     displyInfo: function() {
//         return `${this.brand} ${this.model} ${this.year}`
//     }
// }

// console.log(Car.brand);
// console.log(Car.model);
// console.log(Car.year);

// console.log(Car.displyInfo());

// console.log(Car);

// console.log(Car.brand); // Toyota
// Car.brand = 'Honda'
// console.log(Car.brand); // Honda

// // Object constructor
// function Car(brand, model, year) {
//     this.brand = brand;
//     this.model = model;
//     this.year = year;
// }

// let myCar = new Car("Ford", "Focus", 2018);


// Var 


// function exampleVar() {
//     if(true) {
//         var x = 10;
//     }
//     console.log(x); // Output: 10
// }

// exampleVar();
// console.log(x); // ReferenceError: x is not defined

// function exampleLet() {
//     if(true) {
//         let x = 10;
//         console.log(x); // ReferenceError: x is not defined
//     }
//     console.log(x); // ReferenceError: x is not defined
// }

// exampleLet();

// function exampleConst() {
//    const PI = 3.14; 
//  //  PI = 3.14159;  // TypeError: Assignment to constant variable.
//    console.log(PI);
// }

// exampleConst();


// Class Introduction
// class Animal {
//     constructor(name){
//         this.name = name;
//     }

//     sound() {
//         console.log("Animal makes a sound");
//     }
// }
// // Creating an instance of the animal class
// let dog = new Animal("Dog");
// dog.sound(); // Output : Animal makes a sound

// // Class inheritance

// class Dog extends Animal {
//     constructor(name, breed){
//         super(name);
//         this.breed = breed;
//     }
//     brak() {
//         console.log("woof! woof!");
//     }
// }


// // Creating an insatnce of Dog class
// let bulldog = new Dog("Bulldog", "Bulldog");
// bulldog.sound();  // Output : Animal makes a sound
// bulldog.brak(); // Output : woof! woof!


// // Class static 

// class MathUtility {
//     static square(x) {
//         return x * x;
//     }
// }

// // Accessing static method without creating an instance
// console.log(MathUtility.square(5)); 



```
