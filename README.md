# 1st-demo
its my first repository.
<br>
authrer me nasir.
<br>




<br>
#include <iostream>
using namespace std;

class animal{
public:
    void eat(){
        cout<< "an ganimal is eating" <<endl;
    }
};

class dog : public animal{
public:
    void bark(){
        cout<< "dog is barking" <<endl;
    }
};
int main(){
    dog d;
    d.eat();
    d.bark();
    return 0;
}

