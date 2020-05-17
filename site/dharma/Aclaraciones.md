Aclaraciones

///// Como ya estan al tanto, aclaro que el tablero en Trello lo creamos pero no lo utilizamos debido a los inconvenientes que se presentaron de los cuales ya están informados. A los dos se lo compartimos, de todas formas acá les dejo el link:

Trello: https://trello.com/b/UcWqTu6b

1) Generales
- El footer tiene ese ancho porque de esa manera evito que el botón fixed tape el número de la central.
- El logo no me terminó de convencer cómo quedó. Pensé en ponerle fondo blanco al header pero eso queda peor. Asique lo dejé así porque no se me ocrruió mejor forma de colocarlo ni de hacerlo más "amigable" a la vista.
- En el anclaje de carrito dentro del header me gustaría poder poner un número con la cantidad de productos que vas seleccionando. Sería un ícono muy chiquito pegado al ícono del carro como para indicar cuántos cursos tenés cargados.
- El logo es un anclaje que siempre va a llevar a la home.
- En el registro y, obviamente, en la carga de productos hay muchos tipos de input. Lo que no estaba seguro es si los anclajes de comprar también deberían ser inputs asique por ahora los dejé como anclajes
- Agregué distintos hover a algunos anclajes para que se vea más linda la interacción.
- Casi nunca sé cuanto hay que ponerle de ancho al body. Las páginas quedaron bien, pero no estoy seguro si ese dato está bien aplicado. Además, para hacer el responsive de celulares en la carga de productos, dejé todo igual y únicamente cambié el ancho del body, lo que generó que las fuentes y todo lo que esta adentro se mantenga igual y se perfecto. 
- El button del buscador no pude acomodarlo de otra manera que no sea con position absolute. Sé que está mal hecho aunque se vea bien, pero no pude encontrar la manera de incluirlo dentro del input de buscador sin usar absolute.
- El div que contiene al buscador tiene un espacio a la derecha, como un márgen. No sé por qué está ahí ni de donde salió pero me impidió dejar el mismo espacio a ambos lados del buscador. 

2) Index
- El responsive para tablets lo dejé igual que para pc porque considero que se ve bien y claro, además no hay nada que pueda cambiar de posición porque tendría que agrandarlo y quedaría demasiado grande en relación a todo lo demás o sino centrarlo y quedaría muy vacía por los bordes toda la página, asique lo dejé así. 
- El banner de mercado liebre quería que fuera un carrusel. El problema es que sólo sabemos hacerlo copiándolo de Bootstrap y no me gusta nada usar esta plataforma porque intenté varias veces pero siempre me desconfigura otras cosas dentro de la página. Asique por el momento pensé en dejar el banner y más adelante cuando conozcamos más herramientas, agregar un carrusel sin copiarlo de Bootstrap.
- A los cursos que podés seleccionar en la home les agregué transform para que se pase el mousse por encima y se entienda que podés clickearlos porque no se me ocurría otra manera de hacer notar que son links. Igualmente creo que quedó bastante bien.
- La idea sería que en un futuro haya un video nuestro hablando brevemente sobre la institución pero por el momento sólamente dejé un video vacío como para posicionarlo y que quede acomodado en la home y así más adelante poder agregar uno grabado.
- Me pareció copado agregar el boton fixed para tener acceso siempre a mandarnos un mail y recibir información sobre lo que esté buscando el cliente. Al clickearlo le abre la aplicación predeterminada que el cliente tenga para enviar mails, la idea es que ese botón nos envíe algo similar al quiero recibir más info.
- En el footer agregué un anclaje de whatsapp que directamente te lleva a las llamadas en tu pc o celular y puedas llamarnos o agregarnos a whatsapp.
- Cuando el Sprint pide un resumen de la oferta de productos yo agregué los anclajes a los distintos cursos. Al principio no pretendíamos ponerlos, sino que tenías que ir a la sección productos para poder ver esa información. Pero los agregué a la home porque el Sprint lo pide, lo que no entendí es si es necesario agregar una breve descripción de cada producto junto con su precio. En este caso sería casi como poner una pestaña de productos dentro de la home. No sé si eso esta bueno, asique por eso lo dejé así, que se vean los cursos pero sin el precio.

3) Detalle del producto
- En la sección que está en el medio con plan de estuidos, descripción, etc la idea es que al clickear alguno de estos enlaces, se abra y brinde la información. Me imaginaba por ejemplo clickear fechas de inicio y que el fondo gris que tiene esa sección se agrande y aparezcan las fechas con las sedes y así con el resto de enlaces.
- El tema del banner es el mismo caso que en la home.
- La idea con el anclaje de descargar programa en pdf en un futuro es poder cargar un pdf hecho por nosotros para que al clickearlo, efectivamente se descargue ese archivo.

4) Registro
- Saqué todos los enlaces del header porque considero que no son necesarios dentro de esta sección pero los del footer los dejé porque pueden llegar a ser útiles. Además dejé el logo porque te lleva a la home.
- Los inputs los hice acordes a lo que piden para que no se vean las contraseñas y el mail si o si requiera un @.
- Cuando le agreguemos JS al html me gustaría poder poner la función que no te permite copiar y pegar la contraseña.
- No estoy del todo seguro si el botón de crear cuenta es un input de tipo submit para enviar al servidor la información que el cliente colocó o de tipo anclaje con un input submit dentro para que envíe la información pero también te mande a otra página mostrándote el típico mensaje "Casi está listo, solo resta que revises tu mail para confirmar la cuenta".

5) Carga de producto admin
- En el header dejé esos 3 enlaces porque considero que son los únicos tres que me pueden llegar a servir luego de crear un producto nuevo y el footer le dejé únicamente el color de fondo porque no necesito la información ni los enlaces que normalmente brinda.
- En el Sprint pide aclarar qué campos son obligatorios pero como necesito toda la información que pido, directamente me pareció mas cómodo y menos invasivo poner una aclaración al principio.
- No sé cómo hacer para que el formulario me diga que hay algun input sin completar o algun checkbox sin marcar. Es la última consigna del Sprint. Pero no sé como hacerla.