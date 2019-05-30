Poderes judiciales - Causas no penales
======================================

En este conjunto de datos se presentan los datos obtenidos a partir de datos primarios remitidos por los poderes judiciales provinciales, correspondientes a causas no penales, siguiendo el [Protocolo Técnico de Datos y de Procesos](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf), en el marco del [Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf). Abarca las materias que no son penales, como civil, familia, comercial, contencioso administrativo, tributario, laboral, etc.

http://datos.jus.gob.ar/dataset/poderes-judiciales-causas-no-penales

Características
---------------

-   **Fecha de Primera Publicación:** 10/05/2019

-   **Tags o Etiquetas:** Buenos Aires, Catamarca, Chaco, Chubut, Ciudad Autónoma de Buenos Aires, Corrientes, Córdoba, Entre Ríos, Formosa, Jujuy, La Pampa, La Rioja, Mendoza, Misiones, Neuquén, Río Negro, Salta, San Juan, San Luis, Santa Cruz, Santa Fe, Santiago del Estero, Tierra del Fuego, Tucumán, causas, código penal, instituciones, poderes judiciales,

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Justicia y Política Criminal. Programa Justicia Abierta

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Justicia y Política Criminal. Programa Justicia Abierta

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Justicia y Política Criminal. Programa Justicia Abierta

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Poderes Judiciales - causas no penales

-   **Nombre:** poderes-judiciales-causas-no-penales.zip

-   **Descripción del contenido:** Contiene los archivos con los datos elaborados a partir de datos primarios remitidos por los poderes judiciales, correspondientes a causas no penales.

-   **Formato:** ZIP

-   **Nombre de los archivos contenidos:** poderes-judiciales-causas-no-penales-AAAA.csv

-   **Rango temporal:** causas no penales iniciadas en el año AAAA

-   **Observación:** la estructura de los archivos contenidos en este zip está descripta en el recurso "Poderes Judiciales - Causas no penales - muestreo"

### Poderes judiciales - Causas no penales - Muestreo

-   **Nombre:** poderes-judiciales-causas-no-penales-muestreo.csv

-   **Descripción del contenido:** Muestreo de 1000 datos, obtenidos a partir de datos primarios remitidos por los poderes judiciales provinciales, correspondientes a causas no penales. Los datos completos están publicados en formato zip.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** muestreo de causas no penales iniciadas en el último año informado por la provincia

### Campos del recurso

-   **provincia_id (string):** código de provincia del Poder Judicial en que se inició la causa, según la codificación implementada por INDEC

-   **provincia_nombre (string):** nombre de provincia del Poder Judicial en que se en que se inició la causa

-   **causa_id (string):** código que identifica la causa. Cada provincia usa su propio formato de identificación de causa. Si se repiten los números de causa en diferentes unidades de una institución se arma un nuevo identificador concatenando la unidad, un guión y el número de causa remitido, a fin de generar una clave única de causa por provincia.

-   **materia_id (string):** identificador de la materia que le corresponde a la causa, según lo informado por la institución. Algunas provincias informan la materia según los identificadores propuestos en el [Protocolo Técnico de Datos y de Procesos](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf), por ejemplo:
	- CP - Civil Patrimonial (incluye minería)
	- FP - Civil-Familia: personas
	- LA - Laboral, etc.
Algunas provincias informan el código de materia según figura en sus sistemas.

-   **materia_descripcion (string):** descripción de la materia que le corresponde a la causa

-   **materia_estadistica (string):** agrupación efectuada con fines estadísticos, a partir de la materia informada

-   **circunscripción_id (string):** identificador de la circunscripción a la que pertenece la unidad en que se inició la causa. La circunscripción es la unidad territorial en que se divide la provincia a fin de la administración de justicia.

-   **circunscripción_descripcion (string):** descripción de la circunscripción a la que pertenece la unidad en que se inició la causa

-   **unidad_id (string):** identificador de la unidad operativa del sistema de justicia en que se inició la causa

-   **unidad_descripcion (string):** descripción de la unidad operativa del sistema de justicia en que se inició la causa

-   **causa_fecha_inicio (date):** fecha de inicio de la causa

-   **objeto_litigio_id (string):** identificador del objeto de litigio que da inicio a la causa. Algunos ejemplos son: Amparo/Cobro de honorarios/Violencia familiar/Daños y perjuicios, etc.

-   **objeto_litigio_descripcion (string):** descripción del objeto que da inicio a la causa.

-   **objeto_litigio_estadistico (string):** agrupación efectuada con fines estadísticos, a partir del objeto de litigio informado

-   **parte_tipo (string):** indica el rol procesal de las partes. Puede tomar los valores:
  	- Actor
	- Demandado
	- Citado en garantía

-   **persona_tipo (string):** indica el tipo de persona. Puede tomar los valores:
	- Persona física
	- Persona jurídica

-   **persona_fisica_edad (string):** edad de la persona física vinculada a la causa. Toma valor cuando se trata de una persona física. Si el denunciado es mayor de 65 años toma el valor 65+

-   **persona_fisica_genero (string):** género de la persona física vinculada a la causa. Toma valor cuando se trata de una persona física. Toma los valores "M" para masculino y "F" para femenino

-   **persona_juridica_tipo (string):** tipo de persona jurídica. Toma valor cuando se trata de una persona jurídica. Algunas provincias informan el tipo de persona jurídica según la clasificación propuesta en el [Protocolo Técnico de Datos y de Procesos](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf), por ejemplo:
	- Estado Nacional
	- Estado Provincial
	- Entes descentralizados Estado Nacional
	- Entes descentralizados Estado Provincial
	- Asociación Civil
	- Asociación Sindical
	- Fundación
	- Sociedad Comercial
	- Municipalidad
	- Consorcio de Propietarios
	- Otros
Algunas provincias informan el tipo de persona jurídica clasificada según figura en sus sistemas

-   **persona_juridica_cuit (string):** número de cuit de la persona jurídica. Toma valor cuando se trata de una persona jurídica.

-   **fecha_envio (string):** fecha en que la institución remitió el paquete de datos al Ministerio de Justicia y Derechos Humanos de la Nación

### Poderes Judiciales - provincias y años disponibles - causas no penales

-   **Nombre:** poderes-judiciales-provincias-y-anios-disponibles-causas-no-penales.csv

-   **Descripción del contenido:** Índice de provincias y años disponibles publicados

-   **Formato:** CSV delimitado por comas, codificado en UTF-8 BOM

-   **Rango temporal:** cada uno de los años informados para cada provincia

### Campos del recurso

-   **provincia_id (string):** código de provincia del Poder Judicial en que se inicia la causa, según la codificación implementada por INDEC

-   **provincia_nombre (string):** nombre de provincia del Poder Judicial en que se inició la causa

-   **institucion (string):** nombre de la institución que publica

-   **anio (string):** año de las causas o de los actos procesales informados

-   **publica_causas_iniciadas (string):** indica si la institución publica datos correspondientes a causas iniciadas (contenidos en el recurso "Poderes Judiciales - Causas no penales"). Toma los valores S: Sí, N: No

-   **publica_actos_procesales (string):** indica si la institución publica datos correspondientes a actos procesales (contenidos en el recurso "Poderes Judiciales - Actos Procesales de causas no penales"). Toma los valores S: Sí, N: No

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión I](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)

[Código Penal de la Nación Ley - 11.179](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm)

[Código Procesal Penal de La Nación Ley - 23.984](http://www.saij.gob.ar/23984-nacional-codigo-procesal-penal-lns0003709-1991-08-21/123456789-0abc-defg-g90-73000scanyel)

[Código Procesal Penal de la provincia de Buenos Aires Ley - 11.922](http://www.saij.gob.ar/11922-local-buenos-aires-codigo-procesal-penal-provincia-buenos-aires-lpb0011922-1996-12-18/123456789-0abc-defg-229-1100bvorpyel)

[Código Procesal Penal de la provincia de Catamarca Ley - 5.097](http://www.saij.gob.ar/legislacion/ley-catamarca-5097-codigo_procesal_penal_catamarca.htm)

[Código Procesal Penal de la provincia de Córdoba Ley - 8.123](http://www.saij.gob.ar/8123-local-cordoba-codigo-procesal-penal-provincia-cordoba-lpo0008123-1991-12-05/123456789-0abc-defg-321-8000ovorpyel)

[Código Procesal Penal de la provincia de Corrientes Ley - 2.945](http://www.saij.gob.ar/2945-local-corrientes-codigo-procesal-penal-para-provincia-corrientes-lpw0002945-1971-02-19/123456789-0abc-defg-549-2000wvorpyel)

[Código Procesal Penal de la provincia de chaco Ley - 1.062](http://www.saij.gob.ar/legislacion/ley-chaco-1062-codigo_procesal_penal_provincia.htm)

[Código Procesal Penal de la provincia de Chubut Ley - XV - N° 9 (Antes Ley 5.478)](http://www.saij.gob.ar/9-local-chubut-codigo-procesal-penal-chubut-lpu1000009-2010-05-06/123456789-0abc-defg-900-0001uvorpyel?&o=13&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=104)

[Código Procesal Penal de la provincia de Entre Ríos Ley - 9.754](http://www.saij.gob.ar/9754-local-entre-rios-codigo-procesal-penal-entre-rios-nuevo-regimen-lpe0009754-2006-12-20/123456789-0abc-defg-457-9000evorpyel)

[Código Procesal Penal de la provincia de Formosa Ley - 696](http://www.saij.gob.ar/696-local-formosa-codigo-procesal-penal-formosa-lpp0000696-1987-10-21/123456789-0abc-defg-696-0000pvorpyel?)

[Código Procesal Penal de la provincia de Jujuy Ley - 3.584](http://www.saij.gob.ar/3584-local-jujuy-codigo-procesal-penal-jujuy-lpy0003584-1978-11-20/123456789-0abc-defg-485-3000yvorpyel)

[Código Procesal Penal de la provincia de La Pampa Ley - 2.617](http://www.saij.gob.ar/2617-local-pampa-modificando-articulos-ley-n-2287-codigo-procesal-penal-provincia-pampa-lpl0002617-2011-05-05/123456789-0abc-defg-716-2000lvorpyel)

[Código Procesal Penal de la provincia de La Rioja Ley - 1.574](http://www.saij.gob.ar/1574-local-rioja-codigo-procesal-penal-rioja-lpf0001574-1950-09-29/123456789-0abc-defg-475-1000fvorpyel)

[Código Procesal Penal de la provincia de Mendoza Ley - 6.730](http://www.saij.gob.ar/6730-local-mendoza-codigo-procesal-penal-mendoza-lpm1006730-1999-11-16/123456789-0abc-defg-037-6001mvorpyel)

[Código Procesal Penal de la provincia de Misiones Ley - XIV Nro. 13](http://www.saij.gob.ar/13-local-misiones-codigo-procesal-penal-provincia-misiones-lpn0005365-2013-10-10/123456789-0abc-defg-563-5000nvorpyel)

[Código Procesal Penal de la provincia de Neuquén Ley - 2.784](http://www.saij.gob.ar/2784-local-neuquen-codigo-procedimiento-penal-correccional-lpq0002784-2011-11-24/123456789-0abc-defg-487-2000qvorpyel)

[Código Procesal Penal de la provincia de Río Negro Ley - 5.192](http://www.saij.gob.ar/5192-local-rio-negro-modifica-ley-n-5020-codigo-procesal-penal-lpr1005192-2017-04-07/123456789-0abc-defg-291-5001rvorpyel?&o=22&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n/Local/R%EDo%20Negro%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley&t=1657)

[Código Procesal Penal de la provincia de Salta Ley - 7.690](http://inecip.org/wp-content/uploads/C%C3%B3digo-Procesal-Penal-Salta.pdf)

[Código Procesal Penal de la provincia de San Juan Ley - 754 - O](http://www.saij.gob.ar/754-local-san-juan-codigo-procesal-penal-provincia-san-juan-lpj1500754-2014-11-19/123456789-0abc-defg-457-0051jvorpyel?)

[Código Procesal Penal de la provincia de San Luis Ley - VI Nro. 152](http://www.saij.gob.ar/legislacion/ley-san_luis-152-codigo_procesal_criminal_provincia.htm)

[Código Procesal Penal de la provincia de Santa Cruz Ley - 2.424](http://www.saij.gob.ar/2424-local-santa-cruz-codigo-procesal-penal-provincia-santa-cruz-lpz0002424-1995-11-16/123456789-0abc-defg-424-2000zvorpyel)

[Código Procesal Penal de la provincia de Santa Fe Ley - 12.734](http://www.saij.gob.ar/12734-local-santa-fe-codigo-procesal-penal-santa-fe-nuevo-regimen-lps0012734-2007-08-16/123456789-0abc-defg-437-2100svorpyel?)

[Código Procesal Penal de la provincia de Santiago del Estero Ley - 6.941](http://www.jussantiago.gov.ar/jusnueva/Normativa/Ley6941.php)

[Código Procesal Penal de la provincia de Tucumán Ley - 6.203](http://www.saij.gob.ar/6203-local-tucuman-codigo-procesal-penal-tucuman-lpt0006203-2010-03-23/123456789-0abc-defg-302-6000tvorpyel?&o=12&f=Total%7CFecha%7CEstado%20de%20Vigencia/Vigente%2C%20de%20alcance%20general%7CTema%5B5%2C1%5D%7COrganismo%5B5%2C1%5D%7CAutor%5B5%2C1%5D%7CJurisdicci%F3n%5B5%2C1%5D%7CTribunal%5B5%2C1%5D%7CPublicaci%F3n%5B5%2C1%5D%7CColecci%F3n%20tem%E1tica%5B5%2C1%5D%7CTipo%20de%20Documento/Legislaci%F3n/Ley/C%F3digo&t=104)

[Código Procesal Penal de la provincia de Tierra del Fuego Ley - 168](http://www.saij.gob.ar/168-local-tierra-fuego-codigo-procesal-penal-provincia-tierra-fuego-antartida-islas-atlantico-sur-lpv0000664-1994-08-19/123456789-0abc-defg-466-0000vvorpyel)
