#include <string>
#include <iostream>
#include <list>
#include <map>
using namespace std;

int main(){
    //int
    int x = 5;

    //string
    string testString = "This is a string.";
    cout << testString << endl;

    //floating-point number
    float number = 2.5;
    cout << "The floating number value is: " << number << endl;

    //boolean
    //note: the numeric value of true is 1 and the numeric value of false is 0 
    int x1 = 2, x2 = 4;
    bool num1, num2;
    num1 = x1 == x2;
    num2 = x1 < x2;

    cout << "Bool num1 is: " << num1 << endl;
    cout << "Bool num2 is: " << num2 << endl;

    //arrays
    //to declare an array you must specify the data type and the size of the array
    //arrays are zero-indexed, meaning the first element will use index 0, and then we increment by 1
    int array[2];
    array[0] = 5;
    int arrayNum = array[0];
    cout << "Our array value is: " << arrayNum << endl;

    //lists
    //lists are part of the C++ library, you can utilize this by adding '#include <list>' in the header
    list<int> nameList{1,2,3,4,5};
    for (auto i: nameList) {
        cout << i << ' ';
    }

    //dictionary
    //'maps' work just like dictionaries, they work like a container that stores values which have a unique key.
    //Each value within this container has a special key.
    //to use maps, you must add '#include <map>' in your header.
    
    //creating a map
    map<string, int> mapExample;
    mapExample["One"] = 1;
    mapExample["Two"] = 2;
    mapExample["Three"] = 3;

    //https://favtutor.com/blogs/cpp-dictionary
    return 0;
}

