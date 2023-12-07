# python1
class Circle:
    def circlr_area(self,radius):
        return 3.14*radius**2
ob2=Circle()
print(ob2.circlr_area(5))

class Particle:
    x=5
    def show(self,x):
        print(x)
        x=30
        print(self.x)
        print(x)
ob=Particle()
ob.show(50)
