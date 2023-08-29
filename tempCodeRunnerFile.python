import pandas as pd

data = {
    "Employee ID": ["161E90", "161F91", "161F99", "171E20", "171G30"],
    "Name": ["Raman", "Himadri", "Jaya", "Tejas", "Ajay"],
    "Age": [41, 38, 51, 30, 45],
    "Salary(PM)": [56000, 67500, 82100, 55000, 44000],
}

df = pd.DataFrame(data)


print(
    """Enter the choice
1. Employee ID
2. Name
3. Age
4. Salary """
)
choice = int(input())
if choice == 1:
    query = input("Enter the query to be Employee ID ")
    print(df[df["Employee ID"] == query])
elif choice == 2:
    query = input("Enter the query to be Name ")
    print(df[df["Name"] == query])
elif choice == 3:
    query = input("Enter the query to be Age ")
    print(df[df["Age"] == query])
elif choice == 4:
    query = input("Enter the query to be Salary ")
    print(df[df["Salary"] == query])