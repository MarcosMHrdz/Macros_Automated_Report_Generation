![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Macros Generación automatizada de informes

- En esta práctica de laboratorio, utilizará el archivo `deduction_import_raw.xlsx`. El archivo se proporciona en la carpeta `files_for_lab`. Este es el archivo de datos sin procesar que se importa desde el servidor.

### Escenario

El equipo de nómina de tu empresa recibe información de tu cliente en un formato específico. Luego, el equipo de nómina necesita manipular la información en un formato que pueda cargarse directamente en el software de procesamiento de nómina. El software sólo puede leer la información en un formato específico. Su tarea es automatizar este proceso, lo que ahorrará mucho tiempo al equipo de nómina y hará que el proceso sea más sólido.

Aquí hay una instantánea de cómo se ve el formato inicial del archivo entregado al equipo de nómina: [enlace a la imagen - Formato de datos sin procesar en excl](https://education-team-2020.s3-eu-west-1 .amazonaws.com/data-analytics/6.9-raw_data_payroll.png)

Así es como debería verse el resultado final: [enlace a la imagen - Resultado final](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.9-final_output. png)

### Instrucciones

- No se requieren encabezados.
- La primera columna consta de números de seguro social sin guiones.
- La segunda columna consta de un valor constante `EE_DDUCT`
- La tercera columna consta de valores de la columna AG, es decir, "Beneficio". Solo necesitaríamos las primeras tres letras de esta columna (si hay un valor en esa columna que tenga más de tres letras)
- La cuarta columna consta del valor numérico de la columna "Costo EE" seguido de "|" (barra vertical repetida seis veces)	