//***********************************ARRANGE**********************************************// 
int val2 = 8;
int val1 = 4;

String str4 = "Colombia";
String str5 = "Colombia";

String str3 = null;

byte[] expectedArray = "trial".getBytes(); 
byte[] resultArray = "trial".getBytes(); 

Boolean str1=true;
Boolean str2=true;

//****************************************ACT*********************************************// 
String text1= new String("Hola Mundo");
String text2= new String("Hola Mundo");

//***************************************ASSERT********************************************// 

//Comprueba que dos objetos son iguales

assertEquals(str1,str2);

//Comprueba que una condición es verdadera
 
assertTrue(val1<val2);

//Comprueba que una condición es falsa

assertFalse(val1>val2);

//Comprueba que un objeto no es nulo

assertNotNull(country1);

//Comprueba que un objeto es nulo

assertNull(str3);

//Comprueba si dos referencias apuntan al mismo objeto

assertSame(str4,str5);

//Comprueba que dos referencias no apuntan al mismo objeto

//assertNotSame(str1,str3);

//Comprueba que dos arrays son iguales.

assertArrayEquals(expectedArray,resultArray);
