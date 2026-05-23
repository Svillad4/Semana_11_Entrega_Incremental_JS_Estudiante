# CHANGELOG - Incremento Semana 11

Completa este archivo antes de entregar.

## Nombre del proyecto
Incremento funcional: Inscripcion a talleres comunitarios

## Integrantes
Santiago villada,Wilmar herrera,Arlex valente

## Version entregada
Semana 11 entrega incremental js

## Funcionalidad agregada o ajustada
Describe el incremento semanal implementado.
Durante la mejora del proyecto se implementó un modo oscuro funcional para mejorar la comodidad visual del usuario y darle una apariencia más moderna al sistema. Esta mejora permite cambiar entre modo claro y oscuro sin afectar las funcionalidades ya existentes. Además, la preferencia queda guardada automáticamente usando localStorage, por lo que el sistema recuerda el tema seleccionado incluso al recargar la página

También se agregó una confirmación antes de eliminar registros. Ahora, cuando el usuario presiona el botón “Eliminar”, el sistema muestra un mensaje de confirmación para evitar borrar datos accidentalmente. Esto mejora la seguridad y la experiencia del usuario dentro de la aplicación

## Archivos modificados
- [ ] index.html
- [ ] css/styles.css
- [ ] js/app.js
- [ ] docs/03_checklist_requisitos.md
- [ ] docs/04_matriz_pruebas.md
- [ ] docs/05_bitacora_depuracion.md

## Validaciones implementadas
- [ ] Nombre obligatorio y minimo de caracteres.
- [ ] Edad numerica y mayor o igual a 12.
- [ ] Telefono de 10 digitos.
- [ ] Correo con formato valido.
- [ ] Seleccion de taller.
- [ ] Confirmacion de datos.

## Errores corregidos durante la depuracion
Resume los errores mas importantes corregidos.
Se corrigieron varios errores importantes relacionados con el funcionamiento del formulario y las validaciones del sistema. Algunos elementos de JavaScript tenían IDs diferentes a los del HTML, lo que impedía que ciertas funciones trabajaran correctamente

También se solucionó el problema donde el formulario recargaba la página al enviarse y el botón de limpiar no ejecutaba correctamente su función

En las validaciones se corrigieron errores lógicos relacionados con edad, teléfono, correo y aceptación de términos, mejorando el control de datos ingresados por el usuario

Además, se arregló un problema en el guardado de información en localStorage y un error en el recorrido de datos que generaba elementos undefined en la tabla

Finalmente, se agregó el caso faltante para la opción web dentro de la función de descripción de talleres, permitiendo mostrar correctamente la información correspondiente

## Pruebas realizadas
Resume las pruebas manuales y automaticas ejecutadas.
Se realizaron pruebas manuales utilizando Live Server y la consola del navegador con Ctrl + Shift + J para identificar errores en la página. Durante las pruebas se ingresaron diferentes datos en los formularios y se verificó el funcionamiento de botones, validaciones y cálculos

A medida que aparecían errores en consola o fallos en el funcionamiento, estos fueron corregidos progresivamente hasta lograr que el sistema respondiera correctamente

También se ejecutaron pruebas automáticas mediante las validaciones integradas en JavaScript, comprobando restricciones como campos obligatorios, validación de datos y bloqueo de números negativos

## Reflexion tecnica
 Explica que aprendiste sobre depuracion, control de flujos e integracion correcta.

Durante esta actividad aprendí la importancia de la depuración y el control de errores dentro de una página web. Al revisar la consola pude identificar problemas relacionados con IDs incorrectos, validaciones y funciones mal conectadas entre HTML y JavaScript

También comprendí mejor cómo controlar el flujo de los formularios para evitar errores como recargas innecesarias o datos inválidos. Además, aprendí que una buena integración entre HTML y JavaScript es fundamental para que el sistema funcione correctamente sin afectar otras partes del proyecto 

