Currency Converter

This is a simple currency converter program made using Python .
Main idea of the project is to take an amount in one currency and convert it into another currency. 
The project is built only with the basic concepts taught in class.

---

 1. Project Overview :

  This program allows the user to:
- Enter the amount of money you want to convert
- Select the currency you want to convert from
- Select the currency you want to convert into  
- Get the output immediately

array is used to store all the exchange rates, and the program uses simple indexing to fetch the correct value.

---

 2. Features :

- Supports only 8 currencies; 
  INR,USD,EUR,GBP,AUD,CAD,JPY,CNY  
- Uses a NumPy matrix for conversion  
- If you give wrong currency code, it will not proceed further  
- Negative or invalid input is not allowed

---

 3. Technologies Used :

- Python 
- NumPy
- Basic programming concepts:
   functions , loops , conditional statements , arrays 

 ---

 4. Steps to Install and Run the Project :

  - Install Python on your system
  - Create a file named main.py
  - Copy and paste the program code into main.py
  - Open terminal / command prompt in the project folder
  - Run the program using:
   " python main.py "

---

 5. How It Works :

  - User selects two currencies
  - Program detects the correct exchange rate using NumPy indexing
  - The amount you write is multiplied with the rate
  - Converted value is shown on the terminal

 ---

 6. Limitations :

  - Rates of the currency are fixed
  - There is no graphical interface
  - Only 8 currencies included

 ---

 7. Future Improvements :

  - Add live exchange rates using an API
  - Add a GUI using Tkinter
  - Add more currencies

 

 
 
 

 

