#include<iostream>
#include<iomanip>
#include<vector>
using namespace std;

int s[3] = {};
int i = 0;
int min(vector<vector<int>>array)
{
int mi = array[0][0];
for (int i = 0; i < 4; i++) {
 for (int j = 0; j < 3; j++) {
  if (array[i][j] < mi)
  {
   mi = array[i][j];
  }
 }
}
return mi;
}
int main()
{
int a, b, c, d, e, f, g, h, i, j, k, l;
cin >> a >> b >> c >> d >> e >> f >> g >> h >> i >> j >> k >> l;
int arr[4][3]
{ { a, b, c },
{ d, e, f },
{ g, h, i },
{ j, k, l },
};
vector<vector<int>> stu(4);
for (int i = 0; i < 4; i++)
{
 stu[i] = vector<int>(3);
 for (int j = 0; j < 3; j++)

 {
  stu[i][j] = arr[i][j];
 }
}
cout << "min: " <<min(stu);
system("pause");
return 0;
}
