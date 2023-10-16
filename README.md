# SurveyForm
Some of the Key Properties of this Form
 1)Validated every field
 2)shows the stringified JSON Form data in alert msg after submitting the form
 3)Validation - atleast one character and only alphabets allowed for fields like
   - FirstName
   - LastName
   - Profession
 4)validation for email - aplhaNumerics and special characters like (".","_","%","+","-") followed by
   "@" symbol and aplhaNumerics along with (".","-") followed by "." and two or more alphabets.
   Regex : "^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$"
 5)Validation for mobile number: only numberss allowed, no more or less that 10 digits allowed.
