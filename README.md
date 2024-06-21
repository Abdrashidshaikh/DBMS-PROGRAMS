ADT PROGRAM TO CREATE A CLASS STUDENT.

class student:
 marks = []
 def getdata(self, rn, name,m1,m2,m3):
 student.rn=rn
 student.name=name
 student.marks.append(m1)
 student.marks.append(m2)
 student.marks.append(m3)
 def displaydata(self): 
 print("Roll Number is: ", student.rn)
 print("Name is : ", student.name)
 print("Marks are : ", student.marks)
 print("Total Marks are : ", self.total())
 print("Average Marks are : ",self.average())
 def total(self):
 return(student.marks[0]+student.marks[1]+student.marks[2])
 def average(self):
 return((student.marks[0]+student.marks[1]+student.marks[2])/3)


r=int(input("Enter the roll number : "))
name = input("Enter the name : ")
m1 = int (input("Enter First Subject Marks : "))
m2 = int (input("Enter Second Subject Marks : "))
m3 = int (input("Enter Third Subject Marks : "))
s1 = student()
s1.getdata(r,name,m1,m2,m3)
s1.displaydata()
