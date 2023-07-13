# Anton Hryts
#### Junior Front-End Developer

#### Contacts
* **Location:** Minsk, Belarus
* **Phone:** +375 (29) 381-98-66 
* **Email:** <antongric558@gmail.com>
* **Telegram:** [@anton_gric](https://t.me/anton_gric)
* **GitHub:** [antongrits](https://github.com/antongrits)

---

#### Brief information about me:
I have always been interested in the IT field. Therefore, I decided to enroll in the best university in the country - BSU for the specialty of web programming.
My strengths are enthusiasm, reliability, creativity, determination and others. I am also a good team worker, I have interpersonal communication skills. 
My goal is to become a good Front-End developer. 
I never stop there, I develop myself, take courses, read programming literature. And then I want to learn a lot of new things and improve my skills.

---

#### Skills and Proficiency:
* HTML, CSS
* JavaScript (Basics)
* C++
* Git, GitHub
* VS Code, Visual Studio, Adobe Dreamweaver
* Figma

---

#### Code example:
```
class RailwayCar {
    #weight;
    #cargoUnits;
    constructor(weight, cargoUnits) {
        if (weight < 0) {
            this.displayError("Wrong weight");
            cargoUnits = 0;
            this.#weight = "No cargo";
        }
        else if (weight === 0 && cargoUnits !== 0) {
            this.displayError("The weight is 0 and the number of items is a positive number");
            cargoUnits = 0;
            this.#weight = weight;
        }
        else this.#weight = weight;
        if (cargoUnits < 0) {
            this.displayError("Invalid number of items");
            this.zeroWeight();
            this.#cargoUnits = "No cargo";
        }
        else if (cargoUnits === 0 && weight !== 0) {
            this.displayError("The number of product units is 0 and the weight is a positive number");
            this.zeroWeight();
            this.#cargoUnits = cargoUnits;
        }
        else this.#cargoUnits = cargoUnits;
    }
    get weight() {
        return this.#weight;
    }
    get cargoUnits() {
        return this.#cargoUnits;
    }
    displayError(errorMessage) {
        document.write("Error: " + errorMessage);
        document.write("<br><br>");
    }
    toString() {
        document.write("<br>Weight: " + this.weight);
        document.write("<br>Quantity of product units: " + this.cargoUnits);
    }
    zeroWeight(){
        this.#weight = 0;
    }
    zeroUnits() {
        this.#cargoUnits = 0;
    }
}
```

---

#### Educational projects:
* [Theater website landing page](https://github.com/antongrits/theater) (HTML, CSS)
* [class Railway](https://github.com/antongrits/railway_class) (HTML, JS)
* [lists](https://github.com/antongrits/lists) (C++)