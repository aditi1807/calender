# calender
my first repository
import calendar
y=int(input("enter the year"))
m=1
print("\n*****CALENDAR*****")
Cal=calendar.TextCalendar(calendar.MONDAY)
i=1
while i<=12:
    Cal.prmonth(y,i)
    print()
    i+=1
