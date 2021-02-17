# Tarea 2: Depuración.

#### 1. En la función1...¿Qué hacen estas líneas de código?

    String string2 = "string2";
    
    string2= string2.substring(0, string2.length()-1);
    
    string2=string2+"1";
    
*Al string2 le quitan uno y pasa a ser string1*

#### 2. ¿Qué valen las variables string1 y stgring2 antes de ejecutar el código de comprobación siguiente?

    if(string1 == string2 ) {

        System.out.println("SON IGUALES " + a);

    }
    
    else {
        System.out.println("SON DIFERENTES");
    }
    
*String1 vale "string1" y String2 vale "string1".*

#### 3. ¿Por qué no funciona el operador==? ¿Qué operador se debe usar en su lugar de este?

*No funciona porque no es valido para este caso, habría que usar un .equals().*

#### 4. La función2() está declarada como sigue:
    public void funcion2() {
        System.out.println("--------------------");
        System.out.println("Esta es la función 2");
        System.out.println("Cómo hago la llamada para que
    funcione????");
    }
    
*Hay que poner static en el public void funcion2() y en la clase main hay que llamarlo con "funtion2();*
    
