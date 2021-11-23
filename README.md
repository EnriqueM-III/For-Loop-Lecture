# For-Loop-Lecture


## Lift Off
    #include <iostream>
    using namespace std;
    int main()

    {
    for (int x = 0; x >= 10; x--) {
        cout << x << "\n";


        if (x == 1)
            cout << "We have lift-off!";;
    }

    }

## Descending 5 Stars

    #include <iostream>
    using namespace std;
    int main()
    {

    for (int i = 1; i < 5; i++)
    {
        for (int j = i; j < 5; j++)
        {
            cout << "*";
        }
        cout << endl;
    }
    }
    
## Odd and Even For Loop
    #include <iostream>
    using namespace std;
    int main()

    {
    for (int i = 20; i < 24; i++)
    {
        if (i % 2 == 0){
            cout << i << "Even \n";
        }
        else {
            cout << i << "Odd \n";
        }

    }
    }
    
    
## 7 Star Square
    #include <iostream>
    using namespace std;
    int main()

    {


    for (int i = 0; i < 7; i++)
    {
        for (int j = 0; j < 7; j++)
        {
            cout << "*";
        }
        cout << endl;
    }
    }

## 9s (LECTURE 10)

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
	int x = 0;
	int sum = 0;
	do
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << " ";
			sum = sum + x;
			x++;
		}

	} while (x <= 200);
	cout << endl;
	cout << "\nThe sum is " << sum << endl;
    }
    
    

##
