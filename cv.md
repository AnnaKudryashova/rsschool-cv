# [rsschool-cv](https://github.com/AnnaKudryashova/rsschool-cv)

# Anna Kudriashova

## Software Developer


## Contact information:

* **Location:** Vilnius, Lithuania
* **Phone:** +370 660 44 55 4
* **E-mail:** anna_kudriashova@epam.com
* [Trailhead](https://www.salesforce.com/trailblazer/akudriashova)
* [Linkedin](https://www.linkedin.com/in/anna-kudriashova/)

## About Me

 Certified Salesforce Developer with 3+ years of experience developing custom solutions with a wide range of technologies in Sales Cloud and Service Cloud within Health Care domain.

## Skills
* Administration and configuration: Data Model, Validation rules, Workflows, Process Builder, Flows
* Security model
* Apex triggers and Unit tests
* Asynchronous Apex
* Salesforce UI: Visualforce, Aura, LWC
* Conga Composer
* Salesforce REST integration
* Data migration using Data Loader
* Ant migration tool, Salesforce CLI
* HTML, CSS, JS

## Code Example

**KATA from CODEWARS:** *If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in.
Additionally, if the number is negative, return 0.
Note: If the number is a multiple of both 3 and 5, only count it once.*

```
function solution(number) {
    if (number <= 0) return 0;
    let array = [];
    let sum = 0;
    for (let i = 1; i < number; i++) {
        if (i % 3 == 0 && i % 5 == 0) {
            array.push(i);
        } else if (i % 3 == 0 || i % 5 == 0) {
            array.push(i);
        }
    }
    for (let i = 0; i < array.length; i++) {
        sum += array[i];
    }
    return sum;
}
```

## Experience
### EPAM Systems
**2021-current time**
* Software Engineer

## Education
### European Humanities University
**2023-current time** 
* Computer Science

## Languages

* Russian - native
* English - C1
* German - A2

