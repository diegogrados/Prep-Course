Las variables son una forma de almacenar un valor de algo, para usarlo mas adelante. En el cual para
crealo en JS se debe ingresar var seguido de un espacio y el nombre que le pondremos, a continuacion 
un = y el valor. Un ejemplo seria: var canasta = 5.

Un string es un bloque de texto, los cuales siempre seran definidos entre comillas y pueden ser `simples`
o "dobles".

Las funciones son muy importantes en la programacion y sobre todo en JS. Ya que es una forma de llamar a una accion que se vaya a realizar. Por ejemplo: function Bolas (){}.
Un argumento es una variable que se puede usar dentro de una funcion, y pueden ser mas de una.
ejemplo de ello seria: function Bolas (cant, color){}.
El return es una declaracion que usamos, para que en vez de usar otra funcion llamada console.log
nos regrese los valores que hayamos especificado.
Por ejemplo: 
function Bolas (cant, color){
     var caja = cant + color;
      return caja;}

La declaracion IF es una estructura de control utilizada para tomar decisiones. Es un condicional que sirve para realizar unas u otras operaciones en función de una expresión. Funciona de la siguiente manera, primero se evalúa una expresión, si da resultado positivo se realizan las acciones relacionadas con el caso positivo.
ejemplo 
function puedeManejar(edad) {
    if (edad > 18) {
        return true;
    }

    return false;
}

Los valores booleanos True y False son para verificar la autenticidad de la funcion que estamos empleando, un buen ejemplo de ello seria:
function puedeManejar(edad) {
    if (edad > 18) {
        return true;
    }

    return false;
}

puedeManejar(22); // true
