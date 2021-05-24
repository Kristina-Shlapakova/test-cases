# Test-cases 

Environment: Windows 10, Google Chrome Версия 88.0.4324.182

# Summary: No validation for fields in section 4 "Contact data"

Precondition: 

1. Go to the page [testdrive](https://testdrive.andersenlab.com/)

3. Select  a car (S500 Cabriolet AMG)

4. Сlick "Сontinue"

6.  Select a technical characteristics (Engine:Gasoline 3.0, Transmission:Automatic)

7.  Сlick "Сontinue"

Steps :

1. On the page "Contact information" leave all fields blank 

2. Сlick "Сontinue"

Actual Result: navigation to the Data Confirmation Page

Expected result: Error message 


# Summary: Not  function to go to the previous page

Precondition: 

1. Go to the page [testdrive](https://testdrive.andersenlab.com/)

Steps :

1. Select  a car (S500 Cabriolet AMG)

2. Сlick "Сontinue"

3. There is no button to go to the previous page

Actual Result: there is no button "Back" to go to the previous page

Expected result: the  button "Back" is present
 
# Summary: The "Data confirmation" page displays the names of the variable fields that were not filled 

Precondition: 

1. Go to the page [testdrive](https://testdrive.andersenlab.com/)

3. Select  a car (S500 Cabriolet AMG)

4. Сlick "Сontinue"

6.  Select a technical characteristics (Engine:Gasoline 3.0, Transmission:Automatic)

7.  Сlick "Сontinue"

Steps :

1. On the page "Contact information" leave all fields blank 

2. Сlick "Сontinue"

Actual Result: The "Data confirmation" page displays the names of the variable fields (First name, last name, middle  name, full years, phone number) that were not filled  

Actual Result: Error Message

 # Summary: A grammatical error in the word "Тест драйв"

Steps :

1. Go to the page [testdrive](https://testdrive.andersenlab.com/)

2. Pay attention to the word "Тест драйв" in the upper left corner and on page 5 "Confirmation of data" 

Actual Result: "Тест драйв"

Actual Result: "Тест-драйв"
