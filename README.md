# Assignmentcos2
print("Hi user! Here are 5 physics formulas to solve your problem:")

print("1. Speed = Distance / Time")
print("2. Force = Mass * Acceleration")
print("3. Density = Mass / Volume")
print("4. Pressure = Force / Area")
print("5. Work = Force * Distance")

choice = input("Pick a formula number (1-5): ")

if choice == "1":
    d = float(input("Enter distance: "))
    t = float(input("Enter time: "))
    print("Speed =", d/t)
elif choice == "2":
    m = float(input("Enter mass: "))
    a = float(input("Enter acceleration: "))
    print("Force =", m*a)
elif choice == "3":
    m = float(input("Enter mass: "))
    v = float(input("Enter volume: "))
    print("Density =", m/v)
elif choice == "4":
    f = float(input("Enter force: "))
    A = float(input("Enter area: "))
    print("Pressure =", f/A)
elif choice == "5":
    f = float(input("Enter force: "))
    d = float(input("Enter distance: "))
    print("Work =", f*d)
else:
    print("Invalid choice!")
