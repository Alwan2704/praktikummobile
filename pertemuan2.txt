// class Hewan{
//    String nama="Hewan";


//   // Hewan(){
//   //   print("ini constructor");
//   // }

//   void makan(){
//     print("Makan");
//   }

// }
// class Mamalia extends Hewan{
//   @override
//   void makan(){
//     print("karnivora");
//   }
// }

// class Unggas extends Hewan{
//   @override
//   void makan(){
//     print("obnivora");
//   }

// }

// void main(){
//   // Hewan h = Hewan();
//   // print(h.nama);
//   // h.makan();
//   Hewan m = Mamalia();
//   Hewan m2 = Unggas();
//   m.makan();
//   m2.makan();
// }

// abstract class Hewan {
//   void makan (){
//     print("Makan");
//   }
// }


// class Mamalia implements Hewan{
//   void makan(){
//     print("karnivora");
//   }
// }
// class Unggas extends Hewan{
//   void makan(){
//     print("omnivora");
//   }
// }

class Hewan<T>{
  T value;
  Hewan(this.value);
  T getValue(){
    return value;

  }
  void makan(){
    print("rumput");
  }
}

void main(){
Hewan<String> kambing = Hewan<String>("kambing makan dengan");

print(kambing.getValue());
kambing.makan();
}