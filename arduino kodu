# erdinc51



// BİLGİ PAYLAŞTIKÇA GÜZEL HERKEZE BAŞARILAR 

#include <Servo.h>

Servo myservo;  // SERVOYA İSİM VERİLDİ

// AC09-GX GİRİŞ PİNLERİ 
const int A=2; 
const int B=3; 
const int C=4; 
const int D=5; // ortak uç  
const int E=6; 
const int F=7; 

//AC09-GX PİNLERİ OKUMAK İÇİN BİR BİTLİK DEGİŞKENLER
bool a=0;
bool b=0;
bool c=0; 
bool d=0; // ortak uç 
bool e=0; 
bool f=0; 


float pozisyon = 0;    // SERVO POZİSYONU İÇİN DEGİŞKEN 
byte  konum ; 


void setup()
{
Serial.begin(9600); 
myservo.attach(9);  
Serial.println("AC09-GX ARDUİNO İLE KULLANIMI"); 
delay(1000); 
}
void loop() 
{ 
  switch_oku(); 
  delay(1); 
  konum_bul(); 
  myservo.write(pozisyon);
  delay(1);
  
}

void switch_oku()
{
 // Serial.println("swich okunuyor"); 
  a=digitalRead(A); 
  b=digitalRead(B); 
  c=digitalRead(C); 
  d=digitalRead(D); 
  e=digitalRead(E); 
  f=digitalRead(F);
  delay(5);
}

void  konum_bul()
{
//------> KONUM : 0 <------------------------------------
 if(a==0 && b==0 && c==0 && d==1 && e==0 && f==0) 
 {
  Serial.print("Switch konumu >> 0 pozisyon : "); 
  delay(100);
  konum=0;
  pozisyon=0;
  Serial.println(pozisyon); 
 }
//-------------------------------------------------------


//------> KONUM : 1 <------------------------------------
 if(a==1 && b==0 && c==1 && d==1 && e==0 && f==0) 
 {
  Serial.print("Switch konumu >> 1 pozisyon : "); 
delay(15);
  konum=1;
  pozisyon=16.3;
  Serial.println(pozisyon); 
 }
//-------------------------------------------------------

//------> KONUM : 2 <------------------------------------
 if(a==1 && b==0 && c==0 && d==1 && e==0 && f==1) 
 {
  Serial.print("Switch konumu >> 2 pozisyon : "); 
delay(15);
  konum=2;
  pozisyon=32.7; 
  Serial.println(pozisyon); 
 }
//-------------------------------------------------------

//------> KONUM : 3 <------------------------------------
 if(a==0 && b==0 && c==1 && d==1 && e==0 && f==1) 
 {
  Serial.print("Switch konumu >> 3 pozisyon : "); 
delay(15);
  konum=3;
  pozisyon=49.09; 
  Serial.println(pozisyon); 
 }
//-------------------------------------------------------
 
 
//------> KONUM : 4 <------------------------------------
 if(a==0 && b==1 && c==0 && d==1 && e==0 && f==1) 
 {
  Serial.print("Switch konumu >> 4 pozisyon : "); 
delay(15);
  konum=4;
  pozisyon=65.45;
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------


//------> KONUM : 5 <------------------------------------
 if(a==1 && b==1 && c==1 && d==1 && e==0 && f==1) 
 {
  Serial.print("Switch konumu >> 5 pozisyon : "); 
  delay(100);
  konum=5; 
  pozisyon=81.81; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------


//------> KONUM : 6 <------------------------------------
 if(a==1 && b==1 && c==0 && d==1 && e==0 && f==0) 
 {
  Serial.print("Switch konumu >> 6 pozisyon : "); 
  delay(100);
  konum=6; 
  pozisyon=98.18; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------


//------> KONUM : 7 <------------------------------------
 if(a==0 && b==1 && c==1 && d==1 && e==0 && f==0) 
 {
  Serial.print("Switch konumu >> 7 pozisyon : "); 
  delay(100);
  konum=7; 
  pozisyon=114.54; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------



//------> KONUM : 8 <------------------------------------
 if(a==0 && b==1 && c==0 && d==1 && e==1 && f==0) 
 {
  Serial.print("Switch konumu >> 8 pozisyon : "); 
delay(15);
  konum=8;
  pozisyon=130.90; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------

//------> KONUM : 9 <------------------------------------
 if(a==1 && b==1 && c==1 && d==1 && e==1 && f==0) 
 {
  Serial.print("Switch konumu >> 9 pozisyon : "); 
delay(15);
  konum=9;
  pozisyon=147.27; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------

//------> KONUM : 10 <------------------------------------
 if(a==1 && b==1 && c==0 && d==1 && e==1 && f==1) 
 {
  Serial.print("Switch konumu >> 10 pozisyon : "); 
delay(15);
  konum=10;
  pozisyon=163.63; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------

//------> KONUM : 11 <------------------------------------
 if(a==0 && b==1 && c==1 && d==1 && e==1 && f==1) 
 {
  Serial.print("Switch konumu >> 11 pozisyon : "); 
delay(15);
  konum=187;
  pozisyon=180; 
  Serial.println(pozisyon); 
 }
 //-------------------------------------------------------


}













