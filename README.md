# student-details-using-if-else--python
name=input("enter student name:")
roll=input("Enter student roll no:")
course=input("enter student course:")
print("                            ")
print("Enter student marks")
s1=int(input("enter s1 marks:"))
s2=int(input("enter s2 marks:"))
s3=int(input("enter s3 marks:"))
s4=int(input("enter s4 marks:"))
s5=int(input("enter s5 marks:"))
print("                            ")
sum=s1+s2+s3+s4+s5
average=sum/5
percentage=(sum/500)*100
if percentage>=90:
    print("your grade is A")
elif percentage>=80:
    print("your grade is B")
elif percentage>=70:
    print("your grade is C")
elif percentage>=60:
    print("your grade is D")
else:
    print("you are fail")
print("                            ")
print("student name: ",name)
print("student roll: ",roll)
print("student course:",course)
print("                             ")
print("subject1 mark: ",s1)
print("subject2 mark: ",s2)
print("subject3 mark: ",s3)
print("subject4 mark: ",s4)
print("subject5 mark: ",s4)
print("                            ")
print("total: ",sum)
print("percentage:",percentage,"%")

output
enter student name:sri
Enter student roll no:45
enter student course:computer science
                            
Enter student marks
enter s1 marks:98
enter s2 marks:97
enter s3 marks:96
enter s4 marks:95
enter s5 marks:100
                            
your grade is A
                            
student name:  sri
student roll:  45
student course: computer science
                             
subject1 mark:  98
subject2 mark:  97
subject3 mark:  96
subject4 mark:  95
subject5 mark:  95
                            
total:  486
percentage: 97.2 %
