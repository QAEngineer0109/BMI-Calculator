# BMI-Calculator
Java BMI calculator app
---

# **BMI Calculator (Java Console Program)**

This project is a simple Java console application that calculates a user's **Body Mass Index (BMI)** based on their weight (in pounds) and height (in meters). After calculating the BMI, the program categorizes the user's weight status according to standard BMI ranges.

---

## **Features**

* Prompts the user for:

  * Weight in **pounds**
  * Height in **meters**

* Converts weight from **pounds to kilograms**

* Calculates BMI using the formula:

  [
  \text{BMI} = \frac{\text{weight (kg)}}{\text{height (m)}^2}
  ]

* Classifies the BMI into:

  * Underweight
  * Healthy weight
  * Overweight
  * Obese

---

## **How It Works**

1. The program uses a `Scanner` to read user input from the console.

2. Weight in pounds is converted to kilograms using:

   ```
   weightInKg = weightInPounds * 0.453592
   ```

3. The BMI is calculated and displayed.

4. Based on the BMI value, the program prints the corresponding weight category.

---

## **BMI Categories Used**

| BMI Range      | Category       |
| -------------- | -------------- |
| Below 18.5     | Underweight    |
| 18.5 – 24.9    | Healthy weight |
| 25.0 – 29.9    | Overweight     |
| 30.0 and above | Obese          |

---

## **Example Run**

```
Enter your weight in Pounds:
150
Enter your height in meters:
1.70
Your BMI is: 23.408
You are Healthy weight
```

---

## **Requirements**

* Java Development Kit (JDK) 8 or higher

---

## **How to Run**

1. Save the file as `BMICalculator.java` inside the `day4` package.
2. Compile the code:

   ```
   javac day4/BMICalculator.java
   ```
3. Run the program:

   ```
   java day4.BMICalculator
   ```



