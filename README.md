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
  
Snacks

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
        string snacks[3][4] = {
            {"Galaxy silk, ","Mars Bars, ","Snickers, ","Bounty"},
            {"Flavoured Yoghurt, ","Oman Chips, ","Oreo, ","Lays, "},
            {"Apple, ","Banana, ","Orange and ","Pear. "}
        };
        for (int i = 0;i < 3;i++)
        {
            for (int j = 0;j < 4;j++) {
                cout << snacks[i][j] << "";
            }
            cout << endl;
        }
    }
Art

    #include <iostream>
    #include<string>
    using namespace std;
    int main()
    {
        string art[5][1] =
        { {"-----"},
         {"-O-O-"},
         {"-@@@-"},
         {"-^^^-"},
         {"-vvv-"}
        };
        for (int i = 0;i < 5;i++) {
            for (int j = 0;j < 1;j++)
                cout << art[i][j] << endl;
        }
        cout << endl;
    }
