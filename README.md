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

 Advanced array-Codelab  
                          
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
Enter 5 values

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
        int userInputs[5]{};
        for (int i=0; i < 5; i++){
            cout << "Enter 5 values" << endl;
            cin >> userInputs[i];
            }
        for (auto userInput : userInputs) {
            cout << userInput;
        }
    }
    
