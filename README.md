# Lesson-13
Advance array-Courses

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
      string courses[] = { "BSU CC","BSU BA","HNC CC","HND" };
      for (int i = 0;i < 4;i++) {
        cout << courses[i] << endl;
      }
      for (auto course : courses) {
        cout << course << endl;
      }
    }

 Advanced arrayCodelab  
                          
    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
      char letters[] = { 'C','o','d','e','L','a','b' };
        for (auto letter : letters) {
        cout << letter;
      }
    }
