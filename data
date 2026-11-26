import re
from datetime import datetime

def project_deadline():
    project = input("Enter Project Name: ")
    month = input("Enter the Month of Its Deadline: ")
    day = input("Enter the Day of Its Deadline: ")
    year = input("Enter the Year of Its Deadline: ")
    print(f"Project Name: {project.upper()}")
    print(f"Deadline: {datetime.strftime(month, "%B"), day, year}")
project_deadline()
reset = input("Do you want to Reset the Date? ")
while re.fullmatch(reset, "yes", re.IGNORECASE):
    project_deadline()
