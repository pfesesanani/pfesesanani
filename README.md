#include <iostream>
#include <cmath>


using namespace std;
int main() {
int d;
int h;
int angle;
int output;
cout<<"enter height in inches"<<endl;
cin>>h;
cout<<"enter distance in feet"<<endl;
cin>>d;
cout<<"ente angle in degrees"<<endl;
cin>>angle;
output=((h*0.883)+(d*tan(angle)));
cout<<"answer you looking for is:"<<output<<endl;

    return 0;
}
}
<!---
pfesesanani/pfesesanani is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
