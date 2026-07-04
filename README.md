# Salary-Lookup-System
A simple Python program using dictionaries to search for employee salaries by name. Supports male and female data

# Employee-Salary-Lookup V1.0
# برنامج بسيط للبحث عن راتب الموظف بالاسم

women = {"sara": 4500, "mona": 5000, "noor": 4700, "dalia": 6800, "reem": 6000, "amna": 5200}

men = {"ali": 5000, "ahmed": 6200, "omar": 4800, "khalid": 5500, "mohamed": 7000, "yousif": 5300}

name = input("ادخل الاسم الذي تريده: ")

if name in women:
    print(name, "her salary is", women[name])
elif name in men:
    print(name, "his salary is", men[name])
else:
    print("لا يوجد اسم", name)