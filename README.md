# Automatic-AC-using-Arduino

Se ha realizado un sistema de temperatura completamente automático, de forma que el AC se ajuste solo
Uno de los problemas que surgen en todas las viviendas es el gran gasto de electricidad, para solventar esto proponemos el ajuste automático del AC en base a la captación de la temperatura y humedad interior y exterior. Al variar la temperatura periódicamente evitamos que el AC trabaje a baja temperatura durante un largo tiempo haciendo que consuma más energía.
Para evitar el ajuste manual de la temperatura, hemos automatizado este proceso utilizando un sensor DHT22, este sensor leerá la temperatura actual y se enviará al AC mediante infrarrojos (IR Blaster) simulando el mando a distancia del mismo AC.
