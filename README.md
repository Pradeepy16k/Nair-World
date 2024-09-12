# Nair-World
Just Making Things possible
import calendar
year = int(input("Enter year: "))
month = int(input("Enter month: "))
cal = calendar.TextCalendar(calendar.SUNDAY)  # Starting the week with Sunday
print(cal.formatmonth(year, month))
# Example: Create a Full Year Calendar
import calendar
year = int(input("Enter year: "))
print(calendar.TextCalendar().formatyear(year))