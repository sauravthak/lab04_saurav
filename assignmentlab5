class Employee:
    def __init__(self, emp_id, name, age, salary):
        self.emp_id = emp_id
        self.name = name
        self.age = age
        self.salary = salary

    def __str__(self):
        return f"{self.emp_id} {self.name} {self.age} {self.salary}"

def sort_employees(employees, key):
    if key == 1:  # Sort by Age
        employees.sort(key=lambda emp: emp.age)
    elif key == 2:  # Sort by Name
        employees.sort(key=lambda emp: emp.name)
    elif key == 3:  # Sort by Salary
        employees.sort(key=lambda emp: emp.salary)

def print_employee_data(employees):
    for emp in employees:
        print(emp," ")


employees = [
    Employee("161E90", "Raman", 41, 56000),
    Employee("161F91", "Himadri", 38, 67500),
    Employee("161F99", "Jaya", 51, 82100),
    Employee("171E20", "Tejas", 30, 55000),
    Employee("171G30", "Ajay", 45, 44000),
]

while True:
    print("Choose a sorting parameter:")
    print("1. Age")
    print("2. Name")
    print("3. Salary")
    print("4. Quit")
   
    choice = int(input("Enter your choice: "))
   
    if choice == 4:
        break
   
    sort_employees(employees, choice)
    print("Sorted Employee Data:")
    print_employee_data(employees)