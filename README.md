# Control Flow

# Conditional statements

# Control Flow
# if, else and elif
# Conditional statements are used to control the flow of our program

# As a user i would like to sell tickets according to the age of user
# and catagory of the movie
# age = 12a, PG, universal(U), 15 and 18
# user input to let us know whether to sell ticket or not
# casting implemented
# display the age back to the user with appropriate message

# user_age = input("How old are you? ")
#
#
# #If the user is above the age of 15 let him buy ticket
#
# if user_age >= 15: # If condition is met then print statement will execute
#     print("Thakyou please proceed to your purchase")
#
#     #If user is under 15 do not allow
# elif user_age < 15:
#     print("Sorry you are under age to watch this movie")
# #else block gets executed if none of the above conditions are met
# else:
#     print("Something went wrong")


#Ensure your git hub README doc for todayss lessons are up to date







user_age = input("How old are you? ")
user_age = int(user_age)
U_rating = ["Pokemon", "Ice Age", "Madagascar"]
PG_rating = ["DragonBallZ", "Garfield"]
rating_12 = ["James Bond", "Die Hard", "Mission Impossible"]
rating_15 = ["Justice League", "Avengers", "Dark Knight"]
rating_18 = ["Saw", "Paranormal Activity", "Scream"]


if user_age < 12:
    print("Thank you, Please proceed to your selection")
    print(U_rating, PG_rating)
elif user_age >= 12:
    print("Thank you, Please proceed to your selection")
    print(U_rating, PG_rating, rating_12)
elif user_age >= 15:
    print("Thank you, Please proceed to your selection")
    print(U_rating, PG_rating, rating_12, rating_15)
elif user_age > 18:
    print("Thank you, Please proceed to your selection")
    print(U_rating, PG_rating, rating_12, rating_15, rating_18)
else:
    print("Sorry, Something went wrong")
