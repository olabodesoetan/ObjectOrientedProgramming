# ObjectOrientedProgramming

# class Student:
#     name = "John Doe"
#     age = 23
#     course = "Computer Science"
#     grade = 100
#     sex = "Male"

# student1 = Student()

# print (student1.name)
# print (student1.age)
# print (student1.course)
# print (student1.grade)
# print (student1.sex)

# student2 = Student ()

# student2.name = "Olabode Soetan"
# student2.age = 29
# student2.course = "Applied Statistics"
# student2.grade = 100
# student2.sex = "Male"

# print (student2.name)
# print (student2.age)
# print (student2.course)
# print (student2.grade)
# print (student2.sex)

#TO CREATE A MEMORY RATHER THAN UPDATE ON AFTER THE OTHER, USE INITIALIZATION FXN
# class Student:
#     def __init__(self,name,age,course,grade,sex):
#         self.name = name
#         self.age = age
#         self.course = course
#         self.grade = grade
#         self.sex = sex

# student1 = Student("Franca Adelu", 24, "Nursing", 100, "Female")
# print (student1.name)
# print (student1.age)
# print (student1.course)
# print (student1.grade)
# print (student1.sex)

# student2 = Student("Olabode Soetan", 29, "Applied Statistics", 100, "Male")
# print (student2.name)
# print (student2.age)
# print (student2.course)
# print (student2.grade)
# print (student2.sex)

#TO MAKE IT A LITTLE SHORTER
class Student:

    def __init__(self,name,age,course,sex,grade = 80):
        self.name = name
        self.age = age
        self.course = course
        self.grade = grade
        self.sex = sex

    def print_student_details(self):
        print(f"The student's name is {self.name}, age is {self.age}, course is {self.course}, sex is {self.sex}, and grade is {self.grade}.")

student1 = Student("Franca Adelu", 24, "Nursing", "Female")
student1.print_student_details()

student2 = Student("Olabode Soetan", 25, "Applied Statistics", "Male", 100)
student2.print_student_details()
