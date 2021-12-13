# Desk
#include <iostream>
using namespace std;
#include <math.h>
#include <string>
char A;
float B; 
float C;
char Y;
float x1;
float x2;
float y;
float y2;
char T;
float ci;
char AR;
char VO;
char w;
char q;
int main() {
  while(true) {
  cout << endl << "\nWhat calculator do you want to use?\n Slope calculator-A\n Normal calculator-B\n Circumfrence/Radius Calculator-C\n Area Calculator-D\n Volume Calculator-E\n"<< endl;
cin >> Y;
if (Y=='D'){
  cout << "What do you want to find the area of?\n Triangle-A\n Rectangle/Square-B \n Circle-C\n Oval-D\n Hexagon-E\n Octogon-F\n Kite-G\n Trapezoid-H\n Pentagon-I\n ";
cin >> w;
  if (w=='A'){
float t;
float b;
cout << "Height=";
cin >> t;
cout << "Base=";
cin >> b;
cout << "Area= " << t*b/2;
  }if (w=='B'){
    float er;
    float th;
    cout << "Heaght=";
    cin >> er;
    cout << "Length";
    cin>> th;
    cout << "Area= " << er*th;
  }if (w=='C'){
    char qwq;
    char ty;
    cout << "Radius= ";
    cin >> qwq;
    ty=qwq*qwq;
    cout << "Area= " << ty*3.1415926535897;
  }if (w=='D'){
    char s;
    char e;
    cout << "a= ";
    cin >> s;
    cout << "b= ";
    cin >> e;
    cout << "Area= " << 3.1415926535897*s*e;
  }if (w=='E'){   
    cout << "Side= "; 
  float cf;
  float Pp;
  cin >> cf;
  Pp=cf*6;
    cout << "Area= " << cf*Pp/2;
  }if (w=='F'){
float aa;;
cout << "Side= ";
cin >> aa;
cout << "Area= " << 2*(1+sqrt(2))*pow(aa,2);
  }if (w=='G'){
  float no;
  float nO;
  cout << "Diagonal 1= ";
  cin >> no;
  cout << "Diagonal 2= ";
  cin >> nO;
  cout << "Area= " << (no*nO)/2;
  }if (w=='H'){
  float h;
  float bg;
  float pu;
  cout << "Base 1= ";
    cin>> h;
    cout << "Base 2= ";
    cin>> bg;
    cout << "Height= ";
    cin >> pu;
  cout << "Area= " << (h+bg)/2*pu;
  }if (w=='I'){
  float pe;
    cout << "Side= ";
  cin >> pe;
  cout << "Area= " << .25*sqrt(5*(5+2*(sqrt(5))))*pow(pe,2);}}
  if (Y=='E'){
cout << "What do you want to find the volume of?\n Triangular prism- A\n Rectangular prism-B\n Sphere-C\n Cylinder-D\n Pyramid-E\n Pentagonal prism-F\n Hexagonal prism-G\n";
cin >> q;
if (q=='A'){
float as;
float lk;
float jw;
cout << "Leangth= ";
cin >> as;
cout << "Width= ";
cin>> lk;
cout << "Height= ";
cin >> jw;
cout << "volume= " << (as*lk)/2*jw;
  }if(q=='B'){
  float Re;
  float Si;
  float Wi;
  cout << "Length= ";
  cin >> Re;
  cout << "Width= ";
  cin >> Si;
  cout << "Heighth= ";
  cin >> Wi;
  cout << "Volume= " << Re*Si*Wi;
  }if (q=='C'){
    float rA;
    cout << "Radius= ";
    cin >> rA;
    cout << "Volume= " << 1.33333333333
*3.1415926535897*pow(rA,3);
  }if (q=='D'){
    float o;
    float hp;
    cout << "Radius= ";
    cin >> o;
    cout << "Height= ";
    cin >> hp;
    cout << "Volume= " << 3.1415926535897*pow(o,2)*hp;
  }if (q=='E'){
    float lq;
    float le;
    float sv;
    cout << "Length= ";
    cin >> lq;
    cout << "Width= ";
    cin >> le;
    cout << "Height= ";
    cin >> sv;
    cout << "Volume= " << (lq*le*sv)/3;
  }if (q=='F'){
    float fgh;
    float jif;
    cout << "Side= ";
    cin >> fgh;
    cout << "Height= ";
    cin  >> jif;
    cout << "volume= " <<  (.25*sqrt(5*(5+2*(sqrt(5))))*pow(fgh,2))*jif;
  }if (q=='G'){
    float hE;
    float hII;
    cout << "Base Edge= ";
    cin >> hE;
    cout << "Height= ";
    cin >> hII;
    cout << "Volume= " <<  (3*sqrt(3))/2*pow(hE,2)*hII;
  }}
if (Y=='C'){
cout << "Radius=";
cin >> ci;
cout << ci*6.28318530718;}
if (Y=='A'){
cout << "X1=";
cin >> x1;
cout << "X2="; 
cin >> x2;
cout << "Y1=";
cin >> y;
cout << "Y2=";
cin >> y2;
float R;
R=y2-y;
float P;
P=x2-x1;
cout << "Slope= " << R/P;
}if (Y=='B'){
cout << " Calculator"<< endl;
cout << endl << " Multiplication-A \n Division-B \n Addition-C \n Subtraction-D" << endl;
cin >> A;
if(A=='A'){
  cout << "Okay, what numbers do you want to multiply?" << endl;
  cin >> B;
  cin >> C;
  cout << B*C;
}if (A=='B'){
  cout << "Okay, what numbers do you want to divide?"<< endl;
  cin >> B;
  cin >> C;
  cout << B/C;
}if(A=='C'){
  cout<< "Okay, what numbers do you want to add?"<< endl;
  cin >> B;
  cin >> C;
  cout << B+C;
}if(A=='D'){
  cout << "Okay, what numbers do you want to subtract?"<< endl;
   cin >> B;
  cin >> C;
  cout << B-C;
}}} }
