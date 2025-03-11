# Act-lab-4

def boyet(score):
    if score < 0:
        print("Invalid score! Please enter a value between 0 and 100.")
         
    elif score <= 60:
        print("You got an F!")        
    elif score <= 69:
        print("You got an D!")        
    elif score <= 79:
        print("You got an C!")        
    elif score <= 89:
        print("You got an B!")        
    elif score <= 100:
        print("You got an A!")
    else: 
        print("Failed.")
       
print("Assigning Grades")

while True:
    try:
        budoy = input("State you Grade: ")
        boyet(int(budoy))        
    except ValueError:
        print("Invalid score! Please enter a value between 0 and 100!")
        break
