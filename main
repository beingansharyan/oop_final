#include <bits/stdc++.h>

using namespace std;

void divide(int,int);
void divide(int x,int y)
{
    try
    {
        if(y==0)
        {
            throw y;
        }
        else if(y<0)
        {
            throw 1.0;
        }
        else if(y>x)
        {
            throw 'y';
        }
    }
    catch(int y)
    {
        cout << "dividing by zero " << endl;

    }
    catch(double y)
    {
        cout << "y is negative " << endl;
    }
    catch(char y)
    {
        cout << "y is greater than x" << endl;
    }
}
class task
{
public:
    int a1,b1;
    friend istream& operator >> (istream &,task&);
    friend ostream& operator << (ostream &,task&);
};
istream& operator >> (istream& in,task& t1)
{
    cout << "enter a &b values " << endl;
    in >> t1.a1;
    in >> t1.b1;
    return in;
}
ostream& operator << (ostream& out,task& t2)
{
    out << "a = " << t2.a1 << endl;
    out << "b= " << t2.b1 << endl;
    return out;
}

template <typename T> class Array {
private:
    T* ptr;
    int size;

public:
    Array(T arr[], int s);
    void print();
};

template <typename T> Array<T>::Array(T arr[], int s)
{
    ptr = new T[s];
    size = s;
    for (int i = 0; i < size; i++)
        ptr[i] = arr[i];
}

template <typename T> void Array<T>::print()
{
    for (int i = 0; i < size; i++)
        cout << " " << *(ptr + i);
    cout << endl;
}
class alpha
{
private:
    int x,y;
public:
    alpha() // default and dynamic constructor
    {
        x=0;
        y=0;
    }
    alpha(int a,int b) // parameterized and dynamic  constructor
    {
        x=a;
        y=b;
    }
    void dialpha()
    {
        cout << "x= " << x << "& y=" << y << endl;
    }
    ~alpha()
    {
        cout << "destructors called " << endl;
    }
};
class tsk{
private:
    int x,y;
public:
    void input()
    {
        cout << "enter x and y" << endl;
        cin >> x >> y;
    }
    void display()
    {
        cout << "res = " << endl;
        cout << "x= " << x << " y= " << y << endl;
    }
    friend tsk addf(tsk,tsk);
};
tsk addf(tsk ob1,tsk ob2)
{
    tsk ob3;
    ob3.x=ob1.x+ob2.x;
    ob3.y=ob1.y+ob2.y;
    return ob3;
}
class fact
{
private:
 static int n;
public:
    static void getdata()
    {
        cout << "enter n " << endl;
        cin >> n;
    }
    static void output()
    {
        int f=1;
        for(int i=1;i<=n;i++)
        {
            f*=i;
        }
        cout << f;
    }
};
struct student
{
    int grades;//grades of  students of a particular class
    string name;
    int roll_n0;
};
void display(student s1)
{
    cout << "enter the details of the student" << endl;
    cout << "Students grades " << s1.grades << endl;
    cout << "students name = " << s1.name << endl;
    cout << "students roll no = " << s1.roll_n0 << endl;
 }
 void add(int a,int b=20,int c=100);
void add(int a,int b,int c)
{
    cout << a+b+c << endl;
}
void swap(int *x, int *y)
{
    int swap;
    swap=*x;
    *x=*y;
    *y=swap;
}
void swap(int x,int y)
{
    int temp;
    temp=x;
    x=y;
    y=temp;
}
inline void subt(int a,int b)
{
    cout << a-b;
}
void myFunc( int counter)
{
    if(counter == 0)

        return;
    else
    {
        myFunc(--counter);
        cout<<counter<<endl;
    }
}
void myFunc2( int counter)
{
    if(counter == 0)

        return;
    else
    {
        cout<<counter<<endl;
        myFunc(--counter);
    }
}
void mtp(int a, int b)
{
    cout << "multiplication = " << (a*b);
}

void mtp(double a, double b)
{
    cout << endl << "multiplication =" << (a*b);
}
class A {
public:
    void display() {
        cout<<"Base class content.";
    }
};

class B : public A {};

class C : public B {};

class Mammal {
public:
    Mammal() {
        cout << "Mammals can give direct birth." << endl;
    }
};

class WingedAnimal {
public:
    WingedAnimal() {
        cout << "Winged animal can flap." << endl;
    }
};

class Bat: public Mammal, public WingedAnimal {};

// base class
class Animal {
public:
    void info() {
        cout << "I am an animal." << endl;
    }
};
// derived class 1
class Dog : public Animal {
public:
    void bark() {
        cout << "I am a Dog. Woof woof." << endl;
    }
};
// derived class 2
class Cat : public Animal {
public:
    void meow() {
        cout << "I am a Cat. Meow." << endl;
    }
};
class vehicle
{
public:
    vehicle()
    {
        cout<< "This is a vehicle\n";
    }
};
class Car: public vehicle
{
public:
    Car()
    {
        cout<< "This is a car\n";
    }
};
class Racing
{
public:
    Racing()
    {
        cout<< "This is for Racing\n";
    }
};
class Ferrari: public Car, public Racing
{
public:
    Ferrari()
    {
        cout<< "Ferrari is a Racing Car\n";
    }
};
int main() {

    cout << "Some of the features of OOP I  have discussed and written here, You can choose a value between 1-10 to "
            "get access to OOP features" << endl;
    int choice;
    cout << "enter your choice \n";
    cin >> choice;
    switch (choice) {
        case 1: {
            cout << "STRUCTURES \n";//structures ,passing structures in functions
            //created one structures called student with two names s1 and s2 and initialized their data, grades,name,roll no
            student s2;
            student s1;
            s1.name = "ABc";
            s2.name = "BAc";
            s1.roll_n0 = 2345;
            s2.roll_n0 = 3456;
            s1.grades = 98;
            s2.grades = 98;
            //displaying the contents of both the students s1 and s2
            cout << "the details of 1st student " << endl;
            display(s1);
            cout << "the details of 2nd student " << endl;
            display(s2);
            break;
        }
        case 2: {
            cout << "BITWISE OPERATORS" << endl;
            /*all about bitwise operators, AND,OR XOR, BITWISE SHIFT LEFT,BITWISE SHIFT RIGHT */
            int d = 1001;
            int d2 = 1111;
            int bit_0, bit_1, bx, bnd, bor;
            bit_0 = d >> 1;
            bit_1 = d << 1;
            bx = d ^ d2; //XOR
            bnd = d & d2; //AND
            bor = d || d2; //OR
            cout << "binary and operator " << bnd << endl;
            cout << "binary or operator " << bor << endl;
            cout << "xor operator " << bx << endl;
            cout << "binary right shift " << bit_0 << endl;
            cout << "binary left shift " << bit_1 << endl;
            break;
        }
        case 3: {
            cout << "everything about strings " << endl;
            //String class,its functions to find length concat,substring , copy and iterators//
            string s1 = "computer";
            string s2 = "science";
            int len = s1.length();
            int len2 = s2.length();
            //substring
            string s3 = s2.substr(0, 4);
            cout << "substring of s2 " << s3 << endl;
            // Inserting a character
            s1.push_back('s');
            cout << s1 << endl;
            //deleting a character
            s1.pop_back();
            cout << "after popping " << s1 << endl;
            //swapping a string
            swap(s1, s2);
            cout << "after swapping " << "s1= " << s1 << "& s2= " << s2 << endl;
            break;
        }
        case 4: {
            cout << "FUNCTIONS " << endl;
            //FUNCTIONS-default arguments,call by value,reference, inline ,function overloading,recursive function//
            cout << "default arguments " << endl;

            add(10, 2);
            add(3, 4, 6);
            add(1);
            cout << "call by value, call by reference " << endl;
            cout << "call by reference " << endl;
            int x = 500, y = 100;
            swap(&x, &y);  // passing value to function
            cout << "Value of x is: " << x << endl;
            cout << "Value of y is: " << y << endl;
            cout << "call by value " << endl;
            int a = 20, b = 30;
            swap(a, b);
            cout << "value of a is " << a << endl;
            cout << "value of b is " << b << endl;
            cout << "inline function " << endl;
            subt(10, 20);
            cout << "recursive functions " << endl;
            cout << "head recursive funciton " << endl;
            myFunc(5);
            cout << "non-head recursion " << endl;
            myFunc2(6);
            cout << "FUNCTION OVERLOADING" << endl;
            //addition of numbers
            mtp(10, 20);
            mtp(10.14, 23.34);
            break;
        }
        case 5: {
            cout << "CLASSES AND OBJECTS" << endl;
            cout << "addition using friend function " << endl;
            tsk ob1, ob2, ob3;
            ob1.input();
            ob2.input();
            ob3 = addf(ob1, ob2);
            ob3.display();
            /* */
            cout << "CONSTRUCTORS AND DESTRUCTORS " << endl;
            alpha ob;
            alpha ab8(2, 3);
            //outputting the value of a and b
            ab8.dialpha();
            break;
        }
        case 6: {
            cout << "INHERITANCE " << endl;
            cout << "multilevel inheritance  " << endl;
            C obj;
            obj.display();
            cout << "multiple inheritance " << endl;
            Bat b1;
            cout << "herarchial inheritance " << endl;
            // Create object of Dog class
            Dog dog1;
            cout << "Dog Class:" << endl;
            dog1.info();  // Parent Class function
            dog1.bark();

            // Create object of Cat class
            Cat cat1;
            cout << "\nCat Class:" << endl;
            cat1.info();  // Parent Class function
            cat1.meow();

            cout << "HYBRID INHERITANCE " << endl;
            Ferrari f;
            break;
        }
        case 7: {
            cout << "OPERATOR OVERLOADING " << endl;
            cout << "overloading extraction and insertion operator " << endl;
            //overloading extraction and insertion operator//
            task t1;
            cout << "enter objects " << endl;
            cin >> t1;
            cout << t1;
            break;
        }
        case 8: {
            cout << "exception handling " << endl;
            divide(10, 0);//to divide the number by zero ,throwing 0 catching 0
            divide(10, -2);//throwing 1.0 catching double y
            divide(10, 20);//performing simple division
            divide(20, 2);//throwing 'y' catching char y
            break;
        }
        case 9: {
            cout << "TEMPLATES " << endl;
            //class templates created of DM- array,its size and parameterized constructor and printing the array elements//
            int arr[5] = {1, 2, 3, 4, 5};
            Array<int> a(arr, 5);
            a.print();
            break;
        }
        case 10: {
            // Creation of ofstream class object
            ofstream fout;
            string line;
            // by default ios::out mode, automatically deletes
            // the content of file. To append the content, open in ios:app
            // fout.open("a1.txt", ios::app)
            fout.open("a1.txt");
            while (fout) {
                getline(cin, line);
                if (line == "-1")
                    break;
                fout << line << endl;
                fout.close();
                ifstream fin;
                fin.open("a1.txt");
                while (getline(fin, line)) {
                    cout << line << endl;
                }
                fin.close();
                break;
            }
        }
            return 0;
    }
}
