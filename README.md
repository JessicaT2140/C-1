# C-1
#include <iostream>
using std::cin;
using std::cout;
using std::endl;
int main()
{
	char alpha[26] = { 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z' };
	int i;

	for (i = 0; i < 26; i++)

	{

		if (alpha[i] % 2 == 0)

		{
			cout << "PRINTING CONTENTS OF ARRAY USING THE MOD Option " << endl;
				
				cout << "=====================================================" << endl;
		
			cout << "Even number element = " << (++i + 2) - 2 << " Contents of Element within Array is = " << alpha[i - 1] << endl;

		}
	}
	
	return 0;

}



