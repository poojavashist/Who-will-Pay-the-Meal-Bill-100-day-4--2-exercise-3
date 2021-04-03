# Who-will-Pay-the-Meal-Bill-100-day-4--2-exercise-3
import random  names_string = input("Give me everybody's names, separated by a comma.  ")  names = names_string.split(",")  num_item = len(names)   random_choice = random.randint(0, num_item -1) who_pay_bill = names[random_choice]  print(who_pay_bill+ "\nTodays bill will pay by ! :" )
