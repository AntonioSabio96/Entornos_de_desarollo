***TASCA 1\.***

Donat el projecte IntelliJ adjunt, comproveu mitjançant depuració del sistema:

1\. En la función1… Què fan aquestes línies de codi?  
String string2 \= "string2";  
string2= string2.substring(0, string2.length()-1);  
string2=string2+"1";

- crea una variable string

2\. Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?  
if(string1 \== string2 ) {  
System.out.println("SÓN IGUALS " \+ a );.  
} else {  
System.out.println("SÓN DIFERENTS");  
}

- crea una subcadena para eliminar la ultima letra

3\. Per què no funciona l'operador \== ? Quin operador s'ha d'usar en lloc d'aquest?

- no funciona porque la variable strintg solo compara las memorias de texto no el contenido  
- para que funcione debemos usar .equals

4\. La función2() està declarada com segueix:  
public void funcion2() {  
System.out.println("--------------------");  
System.out.println("Aquesta és la funció 2");  
System.out.println("Com faig la crida perquè funcione????");  
}

Aquesta funció com l'he de cridar des del mètode MAIN perquè funcione. Existeixen 2  
possibilitats. Explica-les.

- Porque  no es estatico, le faltaria la palabra clave "static". Funcion2 pertenece a un objeto, por eso no es posible llamarlo directamente de main  
    
- Llamar desde main  
    
  Tengo dos soluciones   
    
  Public static void funcion2  
    
  ED\_Debug obj \= new  ED\_Debug();


  
