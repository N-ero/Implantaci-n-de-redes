## UT1 Teoría de Redes
<hr>
Esta UT1 está enfocada a profundizar en el concepto de redes, tipos de redes, tipos de codificación y en explicar la teoría de señales que existen que intervienen en los diferentes sistemas de redes. En este repositorio encontrarás toda la teoría necesaria y ejercicios para poner en práctica todos tus conocimientos. También se incluye un modelo de examen resuelto para prepararos previamente antes de un examen.

Un saludo.

**N-ero**.
<hr>

### Parte 1: Concepto de red
``` 
Una red es un sistema de comunicación que enlaza más de un equipo informático entre sí.
```
El objetivo de una red es:

    1. Compartir información de forma instantánea.
    2. Compartir la carga de trabajo.
    3. Ahorrar recursos.
    4. Establecer comunicación.

Pero obviamente, establecer una red supone una cantidad de problemas, que a su vez, generan preguntas básicas que hay que responder:
    
    1. ¿Qué medio de transmisión se va a utilizar?
    2. ¿Qué tipo de señal y modulación se va a emplear?
    3. ¿Cómo es la transmisión?
    4. ¿Qué sucede cuando hay equipos que transmiten más rápido que otros?
    5. ¿Habrán errores de transmisión?
    6. ¿Cómo se tratan dichos errores?
    7. ¿Cómo se indica a quien van dirigidos los datos?
    8. ¿Cómo se unen redes para crear más grandes?

Todas y cada una de estas preguntas se van a ir respondiendo a lo largo de esta UT.
<hr>

### Elementos de la comunicación en un sistema de redes

Los elementos de la comunicación cotidianos también se pueden comparar con los que intervienen en una red.

1. <b>El emisor:</b> Se trata del equipo informático que transmite datos y comparte información con el receptor, utilizando un medio adecuado para ello.
2. <b>El receptor:</b> Se trata de quien recibe los datos y la información del emisor, a través de un medio común. 
3. <b>El medio:</b> El medio es el canal por donde fluye la información entre el emisor y el receptor. Pueden ser conformados por cableado, o tal vez pueden ser ondas de radio.

Todos estos elementos actúan con el rol que ostentan, pero, la comunicación es un proceso un poco más complejo. La transmisión de datos puede ser de tres tipos, atendiendo a si la comunicación es recibida unidireccional o bidireccional:

1. <b>Simplex:</b> La transmisión es unidireccional. El emisor manda datos al receptor, y este último no responde de vuelta. Por ejemplo, la televisión.
2. <b>Half-duplex:</b> La transmisión es bidireccional pero no pueden fluir datos en sentidos opuestos de forma simultánea. Esto es, por ejemplo, un programa de radio, donde los comunicadores transmiten información y con un "cambio y corto" cambian roles de emisor y receptor.
3. <b>Half-duplex:</b> Las comunicaciones fluyen al mismo tiempo en ambos sentidos. Por ejemplo, establecer comunicación con una página web, donde el usuario y el servidor se envían datos de forma simultánea.
