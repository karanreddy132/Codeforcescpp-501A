# Codeforcescpp-501A
#include <bits/stdc++.h>

using namespace std;

int main()
{
  int a,b,c,d;
  cin >> a >> b >> c >> d;
  int misha_p = max(3*a/10,a-(a/250)*c);
  int vasya_p = max(3*b/10,b-(b/250)*d);
  if(misha_p > vasya_p)
    cout << "Misha";
  else if (misha_p < vasya_p)
    cout << "Vasya";
  else
    cout << "Tie";
  return 0;
}
