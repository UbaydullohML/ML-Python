# Python-Kaggle

## Table of contents
* [Intro-Programming](#intro-programming)
* [Python](#python)
  
## Intro-Programming

Arithmetic and Variables

    print(((1+3)*(9-2)/2)**2)

    # In general, Python follows the PEMDAS rule when deciding the order of operations.

    # Create variables
    num_years = 4
    days_per_year = 365 
    hours_per_day = 24
    mins_per_hour = 60
    secs_per_min = 60
    # Calculate number of seconds in four years
    total_secs = secs_per_min * mins_per_hour * hours_per_day * days_per_year * num_years
    print(total_secs)

    
Functions 

![image](https://github.com/UbaydullohML/Python-Kaggle/assets/75980506/acd4b041-e13c-4250-8aee-3a8a5b1bef91)

    def add_threee=(input_var):
        output_var = input_var + 3
        return output_var

    new_number = add_three(10)
    print(new_number)


    def get_pay(n_hours)
        pretax = n_hours * 15
        aftertax = pretax * (1-.12)
        return aftertax

    pay = get_pay(40)
    print(pay)
    pay = get_pay(32)
    print(pay) 

    def get_pay_with_more_inputs(num_hours, hourly_wage, tax_bracket):
        # Pre-tax pay
        pay_pretax = num_hours * hourly_wage
        # After-tax pay
        pay_aftertax = pay_pretax * (1 - tax_bracket)
        return pay_aftertax

    higher_pay_aftertax = get_pay_with_more_inputs(40, 24, .22)
    print(higher_pay_aftertax)

    # Define the function with no arguments and with no return
    def print_hello():
        print("Hello, you!")
        print("Good morning!")
    
    # Call the function
    print_hello()


Data types

    
