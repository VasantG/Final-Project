# **CODE**

### [Home](ReadMe.md)--[Projects](Projects.md)--[Facts](Page3.md)--[Cars](Page4.md) --[Code](Page5.md)

---

## Python
```python
while (True):
      try:
           initial_position = float(input("Enter the object's initial position: "))
           initial_velocity = float(input("Enter the object's initial velocity: "))
           acceleration = float(input("Enter the object's acceleration: "))
           time_elapsed = float(input("Enter the time that has elapsed: "))
           if (time_elapsed < 0):
                print("Negative time elapsed are not allowed.")
                continue
          # Final Position
           final_position = initial_position + initial_velocity * time_elapsed + 0.5 * acceleration * time_elapsed ** 2

          # Output the final position
           print("\nThe objects's final position is", final_position)
      except ValueError:
           print("The value you entered is invalid. Only numerical values are valid.")
      else:
             print(" Good job! You entered a valid value.")
             break
do_calculation = True
while (do_calculation):
	# get input from user
	# perform the calculation
	# output the result
	another_calculation = input("Do you want to perform another calculation? (y/n): ")
	if (another_calculation != "n"):
		do_calculation = False
while (True):
      try:
           initial_position = float(input("Enter the object's initial position: "))
           initial_velocity = float(input("Enter the object's initial velocity: "))
           acceleration = float(input("Enter the object's acceleration: "))
           time_elapsed = float(input("Enter the time that has elapsed: "))
           if (time_elapsed < 0):
                print("Negative time elapsed are not allowed.")
                continue
          # Final Position
           final_position = initial_position + initial_velocity * time_elapsed + 0.5 * acceleration * time_elapsed ** 2

          # Output the final position
           print("\nThe objects's final position is", final_position)
      except ValueError:
           print("The value you entered is invalid. Only numerical values are valid.")
      else:
             print(" Good job! You entered a valid value.")
             break
```

---

## Credits: ##

- ### Images: [*Unsplash*](https://unsplash.com/)

---
