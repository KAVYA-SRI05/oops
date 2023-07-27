# oops concets in python
1.class
2.object
3.inheritence
4.polymorphism
5.abstraction
6.encapsulation

#//classes and object
class student:
      def __init__(Self,name,age):
          self.name=name
          self.age=age
      def display(Self):
          print('name:',self.name)
          print('age:',self.age)
obj=student('kavya',20)
obj.display()

output://kavya
         20
#//inheritence
#single inheritence
class parent:
      def fun1(self):
          print('i am parent class')
class child(parent):
      def fun2(self):
          print('i am child class')
obj=child()
obj.fun1()
obj.fun2()

#//output i am parent class
          i am child class

#multilevel inheritence
class father:
       def fun1(self):
            print('this is father')
class child(father):
      def fun2(self): 
          print('this is child class')
class grandchild(child):
      def fun3(self):
          print('this is grandchild')
obj=grandchild()
obj.fun1()
obj.fun2()
obj.fun3()
#//output:this is father
          this is child class
          this is grand child


#//multiple inheritence
class father:
       def fun1(self):
           print('this is father')
class mother:
      def fun2(self):
          print('this is mother')
class child(father,mother):
      def fun3(self):
          print('this is child')
obj=child()
obj.fun1()
obj.fun2()
obj.fun3()


#/hierarchial inheritence
class parent:
      def fun1(self):
           print('parent')
class child(parent):
      def fun2(self):
          print('child')
class child2(parent):
      def fun3(self):
          print9'child2')
obj=child2()
obj.fun1()
obj.fun3()




