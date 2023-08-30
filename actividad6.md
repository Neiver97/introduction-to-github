
//Comprueba que dos objetos son iguales

assertEquals("Validar que dos objetos son iguales",str1,str2);

//Comprueba que una condición es verdadera
 
assertTrue("Valida condición verdadera",val1<val2);

//Comprueba que una condición es falsa

assertFalse("Valida condición falsa",val1>val2);

//Comprueba que un objeto no es nulo

//assertNotNull("Valida objeto <> null",country1);

//Comprueba que un objeto es nulo

assertNull("Valida que un objeto es nulo",str3);

//Comprueba si dos referencias apuntan al mismo objeto

assertSame("Validar si dos referencias apuntan al mismo objeto",str4,str5);

//Comprueba que dos referencias no apuntan al mismo objeto

//assertNotSame("Diferente instancia de objectos",str1,str3);

//Comprueba que dos arrays son iguales.

assertArrayEquals("Validar si dos array son iguales",expectedArray,resultArray);
