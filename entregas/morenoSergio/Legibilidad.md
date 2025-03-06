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

### Errores de Formato
- while (vidaCaracol == true) (Uso innecesario de == true, debe ser while (vidaCaracol)) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L16)

### Comentarios
- alturaFinal = profundidadCaida + bajada - subida + caidaCoche; (Sin comentarios, puede generar confusión sobre el efecto de cada término) [Code 1](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/caracol/caracol_extendido.java#L63)

### Código Muerto
- "A la caja 6 le quedan: " + caja6 + " items" → Mensajes repetidos en cada iteración, se puede reducir la repetición con una función que maneje todas las cajas. [Code 2](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoCCCF/CCCF_ampliado.java#L189)

### Don’t repeat yourself - DRY
- El código de las cajas (líneas 60-127) es repetitivo, se puede resumir en una función. [Code 2](https://github.com/srgiom/prg1-22-23/blob/8136a23dc0fcb7b62ec2a82121447e97e24f9a83/retos/entregas/sergioMoreno/retoCCCF/CCCF_ampliado.java#L109)
