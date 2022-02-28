# OOP-58002
def personal_informations():
    name, age = "Joash Miguel G. Dolor", 19
    course = "Computer Engineering"
    print("Name: {}\nAge: {}\nCourse: {}".format(name, age, course))

personal_informations()




class Student:
    student_name = 'Joash Miguel G. Dolor'
    student_id = '202114104'
    student_age = '19'
    student_school = 'Adamson University'
    student_course = 'Computer Engineering'
    def display():
        print(f'{Student.student_name}\nStudent id: {Student.student_id}\nStudent Age: {Student.student_age}\nStudent School: {Student.student_school}\nStudent Course: {Student.student_course}')
print("Student Attributes:")
Student.display()


class Person:
  def __init__(self,student,number,age,school,course):
    self.student = student
    self.number = number
    self.age = age
    self.school = school
    self.course = course
  
  def myFunction(self):
    print("I am ",self.student)
    print("To prove that i study in this school my student number is", self.number)
    print("I am ,self.age years old")
    print("I study in",self.school)
    print("My course is",self.course)
  
    p1 = Person("Joash Miguel Dolor", 202114104, 19, "Adamson University", "Computer Engineering")
    p1.myFunction()    
