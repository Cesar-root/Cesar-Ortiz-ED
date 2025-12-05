EJERCICIO 2 (35 puntos): RED DE COMPUTADORAS

Una oficina tiene la siguiente red:

- El Router principal conecta con: Servidor, Switch1, Switch2
- Switch1 conecta con: PC1, PC2, Impresora1
- Switch2 conecta con: PC3, PC4, Impresora2
- El Servidor conecta con: Router (ya mencionado)

Responde:
a) Dibuja el grafo de la red = ya subido

b) ¿Cuántos vértices y aristas tiene?

Son 10 vertices = (Router, Servidor, Switch1, Switch2, PC1, PC2, Impresora1, PC3, PC4, Impresora2)
Son 9 aristas (relaciones o conexiones)

c) ¿Es conexo? ¿Qué significa esto para la red?

Si, puedes llegar a cualquier vertice desde cualquier punto por medio de las aristas

d) ¿Es un árbol? Justifica

Si, ya que es conexo, no tiene ciclos y su relacion vertices/ariastas es apropiada a un arbol = (aristas = vertices - 1)

e) Si se desconecta el Router, ¿cuántas componentes conexas quedan?

3 = servidor, Switch1(PC1, PC2 , Impresora1) y Switch2(PC3, PC4, Impresora2)

f) ¿Cuál es el dispositivo más crítico de la red? (si falla, más dispositivos quedan aislados)

El router debido a que si se elimina deja incomunicado el grafo
