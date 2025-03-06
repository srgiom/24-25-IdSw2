# Legibilidad

## Códigos

| Asignatura       | Enlace |
|------------------|--------|
| **Programación 1** | [Code1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java) |
| **Programación 1**          | [Code2](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoCCCF/CCCF_ampliado.java) |
| **Programación 1**          | [Code3](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoForIF/retoforif21.java) |
| **Programación 2**          | [Code4](https://github.com/srgiom/progra2-22-23/tree/041357bb57a1344885c79e200e0efc4bc923ae9e/ejercicios/entregas/sergioMoreno/EX001-PooStudent/src) |

## Errores

### Nombrado
- caracol_extendido debería ser CaracolExtendido (Usar PascalCase en nombres de clases) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L1)
- retoforif21 → El nombre de la clase no sigue la convención PascalCase en Java.
Corrección: public class RetoForIf21 [Code 3](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoForIF/retoforif21.java#L1)

### Errores de Formato
- while (vidaCaracol == true) (Uso innecesario de == true, debe ser while (vidaCaracol)) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L16)
- Se puede simplificar j = j + 1 y i = i + 1 a j++ y i++. [Code 3](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoForIF/retoforif21.java#L7)

### Comentarios
- alturaFinal = profundidadCaida + bajada - subida + caidaCoche; (Sin comentarios, puede generar confusión sobre el efecto de cada término) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L63)

### Consistencia
- Falta espacio entre i+1 y j< position.
Corrección: for (int j = i + 1; j < position; j++) [Code 4](https://github.com/srgiom/progra2-22-23/blob/041357bb57a1344885c79e200e0efc4bc923ae9e/ejercicios/entregas/sergioMoreno/EX001-PooStudent/src/Subject.java#L69)

### Código Muerto
- "A la caja 6 le quedan: " + caja6 + " items" → Mensajes repetidos en cada iteración, se puede reducir la repetición con una función que maneje todas las cajas. [Code 2](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoCCCF/CCCF_ampliado.java#L189)

### Don’t repeat yourself - DRY
- El código de las cajas (líneas 60-127) es repetitivo, se puede resumir en una función. [Code 2](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoCCCF/CCCF_ampliado.java#L109)
- Llamar orderStudents() dos veces es redundante.
Corrección: Eliminar una de las llamadas. [Code 4](https://github.com/srgiom/progra2-22-23/blob/041357bb57a1344885c79e200e0efc4bc923ae9e/ejercicios/entregas/sergioMoreno/EX001-PooStudent/src/Subject.java#L82)

### YAGNI (You Ain't Gonna Need It)
- (j - 11)² + (i - 11)² se calcula dos veces en la condición. [Code 3](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoForIF/retoforif21.java#L12)

