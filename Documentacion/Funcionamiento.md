# Funcionamiento técnico de la línea

## Objetivo

Simular un proceso industrial automatizado, coordinando la lógica de un PLC Siemens con elementos de transporte, clasificación, manipulación y almacenamiento en Factory I/O, y supervisarlo mediante un HMI.

## Proceso de entrada

La línea incorpora alimentación de piezas, cintas transportadoras, sensores de presencia/posición y manipuladores Pick & Place. La memoria académica describe una estación virtual de mecanizado antes de que el producto avance a la etapa de salida.

## Proceso de salida

Los sensores simulados identifican bases por color/tipología (azul y verde, según la memoria), se canalizan a rutas diferenciadas y se manipulan mediante mecanismos XYZ para su colocación en palés. La instalación incluye transporte de palés y un almacén automático representado con grúa y estanterías.

## Modos y supervisión

Los documentos describen selección de modos manual/automático, secuencias de parada y reset, señales de estado y alarmas. El vídeo SCADA muestra el inicio de sesión con perfiles OPERARIO y JEFE y su diferente acceso al control; paneles separados de entrada y salida; cambios de marcha, paro y alarma; alternancia con Factory I/O para observar el comportamiento; y un visor del almacén que representa ubicaciones de palés.

## Documentación de control

En `GRAFCET/` hay seis diagramas, separados en secuencias de proceso y parada. `Esquemas/` contiene siete páginas de esquemas eléctricos y neumáticos. En `TIA Portal/` se conserva el proyecto original archivado de TIA Portal V17.

## Precisión técnica

- Los mecanismos y sensores de Factory I/O son parte de una **simulación virtual**.
- La detección por color descrita no equivale a haber desarrollado un algoritmo propio de visión artificial.
- Las señales de parada o alarma demostradas en simulación no constituyen una validación de seguridad funcional para una máquina real.
- La ejecución se ve en los vídeos de 2024, pero el programa no ha sido recompilado ni probado de nuevo en 2026.
