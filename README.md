# Assignmentcos2
print("Hi user! Here are 5 physics formulas to solve your problem:")

print("- Speed")
print("- Force")
print("- Density")
print("- Pressure")
print("- Work")

choice = input("Type the formula name you want to use: ").lower()

if choice == "speed":
    d = float(input("Enter distance: "))
    t = float(input("Enter time: "))
    print("Speed =", d/t)
elif choice == "force":
    m = float(input("Enter mass: "))
    a = float(input("Enter acceleration: "))
    print("Force =", m*a)
elif choice == "density":
    m = float(input("Enter mass: "))
    v = float(input("Enter volume: "))
    print("Density =", m/v)
elif choice == "pressure":
    f = float(input("Enter force: "))
    A = float(input("Enter area: "))
    print("Pressure =", f/A)
elif choice == "work":
    f = float(input("Enter force: "))
    d = float(input("Enter distance: "))
    print("Work =", f*d)
