# maxHelp
אני צריכה עזרה
let answer: (message: String?, errorMessage: String?) = ("Sababa!",  nil)

if answer.message != nil {
    print("\(answer.message!)")
} else {
    print("Error")
}

if answer.errorMessage != nil {
   print("\(answer.errorMessage!)")
} else {
    print("Error")
}

var student: (name: String?, car: Int?, exam: Int?) = (nil, nil, nil)

student.name  = "Bob"
var name1 = student.name
student.car = 2938475
var car1 = student.car
student.exam = 3
var exam1 = student.exam


student.name  = "Vova"
var name2 = student.name
student.car = nil
var car2 = student.car
student.exam = nil
var exam2 = student.exam

student.name = "Max"
var name3 = student.name
student.car = 45356677
var car3 = student.car
student.exam = 5
var exam3 = student.exam

print(" Student name: \(name1!), car: \(car1!), exam: \(exam1!)")
print(" Student name: \(name2!), car: \(car2), exam: \(exam2)")
print(" Student name: \(name3!), car: \(car3!), exam: \(exam3!)")
