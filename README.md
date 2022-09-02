- 👋 Hi, I’m @Abraao8levi
- 👀 I’m interested in Programação Web HTML5, Javascript e CSS 
- 🌱 I’m currently learning C++ 

- 📫 How to reach me @Abraao8levi 
https://instagram.com/abraao8levi?igshid=YmMyMTA2M2Y=
<!---
Meu primeiro programa em C++
#include <iostream>
using namespace std;

int main() {
    int capacidade {};
    cin>>capacidade;
    int pess {};
    int qnt = 0;
    
    
    while (true) {
        cin>>pess;
        qnt +=pess;
        
        if (qnt==0) {
            cout<<"vazio"<<endl;
        }else if (qnt<capacidade) {
            cout<<"ainda cabe"<<endl;
        }else if (qnt>=capacidade*2) {
            cout<<"hora de partir"<<endl;
            break;
        }else if (qnt>=capacidade) {
            cout<<"lotado"<<endl;
        }
    }
}
Meu 2° Projeto em C++

#include <iostream>

using namespace std;

int main(){ 

    int heli,pol,fug,dir;

    cin >> heli >> pol >> fug >> dir;

    if(dir == 1){
        
        while(true){
            if(fug == pol){
                cout << "N\n";
                break; 
            }

            if(fug == heli){
                cout << "S\n";
                break; 
            }



            if(fug == 15){
                fug = 0;
            }else{
                fug++;
            } 
        }
    }else{
        while(true){

             if(fug == pol){
                cout << "N\n";
                break; 
            }

            if(fug == heli){
                cout << "S\n";
                break; 
            }



            if(fug == 0){
                 fug = 15;
            }else{
                fug--;
            }

        }
    }
    

    return 0;
}



