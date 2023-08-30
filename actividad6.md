//***********************************ARRANGE**********************************************// 
Int a = 8;
Int b = 4;

String country1 = "Colombia";
String country2 = "Colombia";

String aux = null;

byte[] expected = "trial".getBytes(); 
byte[] actual = "trial".getBytes(); 

Boolean flag=true;
Boolean flag2=true;

//****************************************ACT*********************************************// 
InstanceA instanceA = new InstanceA("Pepito","Perez");

String text1= new String("Hola Mundo");
String text2= new String("Hola Mundo");

//***************************************ASSERT********************************************// 


//Comprueba que dos objetos son iguales

assertEquals("Validar que dos objetos son iguales",flag,flag2);

//Comprueba que una condición es verdadera
 
assertTrue("Valida condición verdadera",b < a);

//Comprueba que una condición es falsa

assertFalse("Valida condición falsa",b > a);

//Comprueba que un objeto no es nulo

assertNotNull("Valida objeto <> null",instanceA);

//Comprueba que un objeto es nulo

assertNull("Valida que un objeto es nulo",aux);

//Comprueba si dos referencias apuntan al mismo objeto

assertSame("Validar si dos referencias apuntan al mismo objeto",country1,country2);

//Comprueba que dos referencias no apuntan al mismo objeto

assertNotSame("Diferente instancia de objectos",str1,str3);

//Comprueba que dos arrays son iguales.

assertArrayEquals("Validar si dos array son iguales",expected,actual);
