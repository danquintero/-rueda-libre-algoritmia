
1. El cliente llega al local.
2. El empleado lo saluda y le pregunta qué necesita.
3. El cliente indica que quiere alquilar una bicicleta.
4. El empleado le pide un documento de identidad.
5. El empleado verifica que el documento sea válido.
6. El empleado le pregunta por cuánto tiempo la necesita.
7. El empleado le informa el precio según el tiempo.
8. Si el cliente acepta el precio, continúa; si no, el proceso termina.
9. El cliente paga el alquiler.
10. El empleado registra los datos del cliente y la hora de salida.
11. El empleado le entrega una bicicleta en buen estado.
12. El empleado le entrega el casco.
13. El empleado le entrega el candado.
14. El cliente revisa que tenga los tres elementos.
15. El cliente sale del local con la bicicleta, el casco y el candado.

##2 ## 2. Ambigüedades encontradas por el compañero
1. Paso 5: no dice qué documentos son válidos ni qué pasa si no lo es.
2. Paso 8: no dice qué pasa si el cliente no acepta el precio.
3. Paso 11: "buen estado" no dice cómo se verifica.

## 3. Versión corregida
INICIO
1. El cliente llega al local.
2. El empleado lo saluda y pregunta qué necesita.
3. El cliente pide alquilar una bicicleta.
4. El empleado pide la cédula.
5. Si la cédula no es válida, ir al FIN.
6. El empleado pregunta por cuánto tiempo la necesita.
7. El empleado informa el precio total.
8. Si el cliente no acepta el precio, ir al FIN.
9. El cliente paga.
10. El empleado registra los datos y la hora de salida.
11. El empleado revisa frenos y llantas de la bicicleta.
12. El empleado entrega la bicicleta, el casco y el candado.
13. El cliente sale del local con los tres elementos.
FIN

## 4. Características del algoritmo
- **Precisión:** "El empleado pide la cédula" dice exactamente qué documento.
- **Finitud:** termina en el paso 13, o antes en el FIN si hay rechazo.
- **Orden:** el cliente paga (9) antes de recibir la bicicleta (12).
- **Determinismo:** con la misma situación, siempre pasa lo mismo: "Si la cédula no es válida, ir al FIN".
- **Efectividad:** cada paso es realizable, como "El empleado revisa frenos y llantas".



