# Taller integrador individual - Edward Sánchez

## Hallazgos de la auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
|---|---|---|
| Nombres de archivo con espacios/mayúsculas | No sigue convención de nombres de archivo | Renombrados a index.html y estilos.css |
| Título de pestaña "pagina" | No describe el contenido de la página | Cambiado a "Calculadora de Promedio" |
| Variable x | No indica qué almacena | Renombrada a cantidadNotas |
| Variable TempValue2 | Nombre confuso y arbitrario | Renombrada a promedio |
| Variable data1 sin uso | Código muerto | Eliminada |
| Parámetros a, b, c | No descriptivos | Renombrados a nota1, nota2, nota3 |
| IDs n1, n2, n3, r, r2 | Poco descriptivos | Renombrados a nota1, nota2, nota3, resultadoPromedio, resultadoEstado |
| Función calc() | Nombre poco claro | Renombrada a calcularPromedio() |
| Función calcularAntiguo comentada | Código muerto sin uso | Eliminada |
| console.log de depuración | No debe quedar en producción | Eliminados |