// void main() { hello(5,5,3);
//             }
// dynamic hello(var sub1, var sub2, var sub3){
//    var total = sub1 + sub2 + sub3;
//    print(total);


// void main(){
// //   var car1 = Car();
// //   car1.name = "Civic";
// //   car1.abc();
  
// //   var car2 = Car();
// //   car2.name = "Prius";
// //   car2.abc();
   
// // }

// // class Car{
// //   var name = "";
  
// //   dynamic abc(){
// //     print('This car is ${name}');
// //   }
  

// }

void main(){
  var obj = Circle();
  obj.dis();
  obj.cir();
  
  var obj1 = Square();
  obj1.dis();
  obj1.sq();
}

class Shape{
  dynamic dis(){
    print("Parent Class");
  }
}

class Circle extends Shape{
  dynamic cir(){
    print("Circle (child) class");
  }
}

class Square extends Shape{
  dynamic sq(){
    print("Square (child) class");
  }
}
