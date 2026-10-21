Class :
     - A class is a blueprint for creating objects, it defines properties and methods that the created objects(instance) will have 
     - to craete a class we use the keyword: class
     - always the 1st letter of the class name should be capital , e.g: class Student{}


Object: An object is an instance of the class

# Program to understand class and object
class Laptop{
  String brand='';
  int price=0;
}
  
void main()
{ 
  Laptop l1 = Laptop();  //l1 is the object name 
  l1.brand='hp';
  l1.price=175000;
  
  Laptop l2 = Laptop();
  l2.brand='Dell';
  l2.price=100000;

  print(l1.brand);
  print(l2.brand);
}

o/p: hp
     dell



# program on class and object 
class Animal {
  String name = '';
  String animalSound = '';

  void sound(String s) {
    animalSound = s;
  }

  void display() {
    print("Name of the animal: $name");
    print("Sound: $animalSound");
  }
}

void main() {
  Animal dog = Animal();
  dog.name = "Dog";
  dog.sound('bow');
  dog.display();

  Animal lion = Animal();
  lion.name = "Lion";
  lion.sound('fahhhhhh');
  lion.display();
}


o/p:
Name of the animal: Dog
Sound: bow
Name of the animal: Lion
Sound: fahhhhhh

