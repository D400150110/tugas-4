#include <conio.h>
#include <stdio.h>
#include <iostream.h>
#include <math.h>

int main(){
float a,b,c,D,x1,x2;      //deklarasi variabel

cout<<"Menentukan akar persamaaan"<<endl;
ulang:
cout<<"Masukan a : ";cin>>a; //untuk inputan
cout<<"Masukan b : ";cin>>b;
cout<<"Masukan c : ";cin>>c;
if(a>0){
D=pow(b,2)-(4*a*c);  //proses menghitung nilai determinan
cout<<"nilai D : "<<D<<endl;
    if(D>=0){
      x1=(-b+sqrt(D))/(2*a);
      x2=(-b-sqrt(D))/(2*a);
      cout<<"Nilai x1 : "<<x1;
      cout<<endl;
      cout<<"Nilai x2 : "<<x2;
               }
   else{
   cout<<"Akar Imaginer"<<endl;
           }
    }
 else if(a<0){
 goto ulang;
 }  //tutup if
else{
cout<<"Salah Entry"<<endl;
    }
getch();
return 0;
}  //tutup program
