#include <iostream>
#define n 3
using namespace std;
class Array {
private:
	int arr[n][n] = { {1, 2, 3}, {4, 5, 6}, {7, 8, 9} };
public:
	void function() {
		for (int i = 0; i < n; i++) {
			for (int j = 0; j < n; j++) {
				cout << arr[i][j] << " ";
			}
			cout << endl;
		}
		cout << endl;

		for (int i = 0; i < n; i++) {
			for (int j = i; j < n; j++) {

				swap(arr[i][j], arr[j][i]);
			}
		}
		for (int i = 0; i < n; i++) {
			reverse(arr[i], arr[i] + n);
		}
		for (int i = 0; i < n; i++) {
			for (int j = 0; j < n; j++) {
				cout << arr[i][j] << " ";
			}
			cout << endl;
		}
	}
};
int main() {
	Array arraytex;
	arraytex.function();
}
