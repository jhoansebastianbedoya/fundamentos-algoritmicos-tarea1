# fundamentos-algoritmicos-tarea1
Reto A: El Algoritmo de la Bóveda
Objetivo: Abrir la puerta sin que la alarma quede sonando.
Secuencia paso a paso:
1. Encender el interruptor A → activa la energía principal.  
   (La alarma no suena porque B está apagado en este momento).
2. Encender el interruptor B → ahora A y B están encendidos, pero la alarma se activa.  
3. Encender el interruptor C → apaga la alarma, ya que A está encendido.  
resultado: A y B encendidos, alarma apagada, puerta abierta.
 Reto B: Desactivando el Sistema (Evaluación)

Expresión a resolver:
NOT( (15 MOD 4) + 2 == 5 ) OR ( 10 * 2 > 15 AND NOT(8 / 4 <= 1) )

1. Operaciones aritméticas internas:
   - 15 MOD 4 = 3  
   - 3 + 2 = 5  
   - Evaluamos: 5 == 5 → Verdadero
2. Aplicar NOT al primer bloque:
   - NOT(Verdadero) = Falso
3. Segundo bloque:
   - 10 * 2 = 20  
   - 20 > 15 → Verdadero  
   - 8 / 4 = 2  
   - 2 <= 1 → Falso  
   - NOT(Falso) = Verdadero  
   - Entonces: Verdadero AND Verdadero = Verdadero
4. Unir ambos bloques con OR:
   - Falso OR Verdadero = Verdadero
   - Resultado final de la expresión: Verdadero
