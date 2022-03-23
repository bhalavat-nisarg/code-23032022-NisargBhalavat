# BMI Calculator

This application can calculate any person's BMI using their Weight (in kg) and Height (in cm). In addition to this the application can also provide an information regarding the BMI Category and Health risk based on the calculated BMI.

## BMI Ranges (kg/m<sup>2</sup>)

-   18.4 and below
-   18.5 - 24.9
-   25 - 29.9
-   30 - 34.9
-   35 - 39.9
-   40 and above

## BMI Category and Health Risk

| BMI Range      | BMI Category        | Health Risk       |
| -------------- | ------------------- | ----------------- |
| 18.4 and below | Underweight         | Malnutrition risk |
| 18.5 - 24.9    | Normal weight       | Low risk          |
| 25 - 29.9      | Overweight          | Enhanced risk     |
| 30 - 34.9      | Moderately Obese    | Medium risk       |
| 35 - 39.9      | Severely Obese      | High risk         |
| 40 and above   | Very Severely Obese | Very High risk    |

---

## Requirements

To run this application on your location system, the following installations are needed:

1. Node.Js
2. NPM Module
3. MongoDB

## How to use

-   Clone the repository
-   Add your MongoDB localhost path in **.env.example** and rename it to **.env**
-   Run `npm run setup-app`

    -   This is will do a clean installation of all the node modules and setup your MongoDB database with sample documents which can be used to calculate BMI.

-   Either run `npm run dev` to start the server in Development mode
-   Or run `npm run start` to start the server in Production mode
