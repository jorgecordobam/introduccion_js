![LarnU](../_src/assets/00-PrimerosPasos/logo_LarnU.png)

<br>
<br>

# Desafío: HTML

## Instrucciones

Crear un nuevo archivo dentro de la carpeta `Clases` llamado `introduccion_js` donde deberás escribir a un costado los valores que tomaran los siguentes ejercicios:

6 / "3" = Se hace la operacion ya que toma el string como un entero 
"2" * "3" = se hace la operación toma los dos strings como enteros
4 + 5 + "px" se hace la operacion de los dos primeros enteros y luego concatena el string 
"$" + 4 + 5 todo lo toma como string y lo concatena 
"4" - 2 se realiza la operacion como si fueran dos enteros 
"4px" - 2 creo que da error por que no se puede concatenar ya que es resta y no tiene ningun string tipo entero
7 / 0 es infinito osea imprimira infinity 
{}[0] no se 
parseInt("09")  conviete en entero el string imprimiria 9
5 && 2  si no estoy mal se imprime el ultimo numero por la condición 
2 && 5  si no estoy mal se imprime el ultimo numero por la condición
5 || 0  si no estoy mal se imprime el primer numero por la condición 
0 || 5  si no estoy mal se imprime el primer numero por la condición 
[3]+[3]-[10] no se que pasaria 
3>2>1 no se
[] == ![] verdadero por que esta vacio y vacio y vacio negado da vacio 


Analiza cual sera el resultado de los console.log:

var profesor = "Jhoswe";
let teacher = "Jose";
if (true) {
    var profesor = "The Flash";
    let teacher = "Reverse Flash";
    console.log(profesor);
    console.log(teacher);
}
console.log(profesor);
console.log(teacher);


por ser var cambia la primer variable pero la segunda se mantiene ya que esta en un let dentro del condicional # introduccion_js
