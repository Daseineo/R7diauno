Reto 1 - 7
donde los operadores de igualdad entre valores hacen que el código, tenga las salidas esperadas en la consola. 
Porque dependiendo de cómo escribas tu código, JavaScript hará una conversión de tipo a un tipo booleano de manera 
implícita (automática), y esto afectará a variables que eran Strings, Numbers, Object, etc.

Esto causa algunos comportamientos extraños, como todos estos ejemplos a continuación que retornan true:

console.log( false == '0' );
console.log( null == undefined );
console.log( " \t\r\n" == 0 );
console.log( ' ' == 0 );
