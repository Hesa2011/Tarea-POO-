Enunciado:
Desarrollar una clase llamada Motor que tenga:
 Dos atributos privados de tipo int. El primero se llama litros_de_aceite
y el segundo potencia.
 Un Constructor con un parámetro de tipo int para la potencia. Los
litros de aceite por defecto serán 0.
 Un getter para cada atributo.
 Un setter para cada atributo.
Desarrollar una clase llamada Coche que tenga:
 Un atributo privado de tipo Motor, un atributo de tipo String para la
marca, otro de tipo String para el modelo y otro de tipo double para
guardar el precio acumulado de las averías.
 Un constructor con dos parámetros de tipo String que inicialicen la
marca y el modelo.
 Un getter para cada atributo
 Un método acumularAvería que incrementará el importe gastado en
averías.
Desarrollar una clase llamada Garaje que tenga:
 Tres atributos: un coche, un String con el nombre de la avería asociada
y el número de cochos que ha ido atendiendo.
 El garaje sólo podrá atender un coche en cada momento. Deberá
controlar esta premisa.
 Un método aceptarCoche que reciba un parámetro de tipo Coche y la
avería asociada. El garaje sólo podrá atender un coche en cada
momento. Si ya está atendiendo uno, deberá devolver un false.
 Un método devolverCoche que dejará al garaje en estado de aceptar
un nuevo coche.
Práctica de POO - Prof. Willis Polanco
Desarrollar una clase PracticaPOO que en su método main:
 Cree un garaje
 Cree 2 coches
 El garaje irá atendiendo los coches y devolviéndolos, acumulando un
importe aleatorio (Math.random()) de la avería tratada.
 Si la avería del coche es "aceite" incrementar en 10 la cantidad de litros
de aceite.
 Los coches entrarán al menos 2 veces al garaje.
 Mostrar información de los coches al final del método main.
