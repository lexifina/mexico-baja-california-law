# Baja California: law history in git

The law of the State of Baja California (Estado Libre y Soberano de Baja California, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-bcn/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

143 ordenamientos with 1936 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 193 | as first published, then each reform: 16 August 1953 to 5 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE BAJA CALIFORNIA | 133 | as first published, then each reform: 2 March 1974 to 24 October 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE BAJA CALIFORNIA | 66 | as first published, then each reform: 2 March 1974 to 1 December 2018 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE BAJA CALIFORNIA | 22 | as first published, then each reform: 1 January 1989 to 16 March 2024 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE BAJA CALIFORNIA | 243 | as first published, then each reform: 19 September 1989 to 29 August 2026 |
| `ley-contra-la-delincuencia-organizada/` | LEY CONTRA LA DELINCUENCIA ORGANIZADA PARA EL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 3 January 2004 to 25 May 2015 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE BAJA CALIFORNIA | 42 | as first published, then each reform: 26 June 2008 to 23 June 2026 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 4 March 2023 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS PARA EL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 19 October 2002 to 9 March 2024 |
| `ley-de-agricultura-urbana-sustentable/` | LEY DE AGRICULTURA URBANA SUSTENTABLE PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 8 July 2023 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 22 October 2022 |
| `ley-de-aranceles/` | LEY DE ARANCELES PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 11 March 1977 to 1 December 2018 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 19 | as first published, then each reform: 26 October 2002 to 14 March 2026 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 23 August 2014 to 1 December 2018 |
| `ley-de-atencion-y-prevencion-de-la-violencia-familiar/` | LEY DE ATENCION Y PREVENCION DE LA VIOLENCIA FAMILIAR PARA EL ESTADO DE BAJA CALIFORNIA | 13 | as first published, then each reform: 5 July 2003 to 28 June 2025 |
| `ley-de-atencion-y-proteccion-a-personas-con-autismo/` | LEY DE ATENCION Y PROTECCION A PERSONAS CON AUTISMO PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 24 October 2016 to 6 September 2025 |
| `ley-de-capacitacion-en-materia-de-genero-de-prevencion-y-err/` | LEY DE CAPACITACION EN MATERIA DE GENERO, DE PREVENCION Y ERRADICACION DE LA VIOLENCIA HACIA LAS MUJERES PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 8 February 2025 to 24 July 2025 |
| `ley-de-centros-de-atencion-cuidado-y-desarrollo-integral-inf/` | LEY DE CENTROS DE ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 30 May 2015 to 3 December 2022 |
| `ley-de-compatibilidad-de-funciones-empleos-y-comisiones/` | LEY DE COMPATIBILIDAD DE FUNCIONES, EMPLEOS Y COMISIONES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 21 July 1967 to 23 February 2002 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE BAJA CALIFORNIA | 12 | as first published, then each reform: 3 January 1988 to 23 May 2026 |
| `ley-de-cultura-fisica-y-deportes/` | LEY DE CULTURA FISICA Y DEPORTES DEL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 1 January 2015 to 1 June 2024 |
| `ley-de-derechos-y-cultura-indigena/` | LEY DE DERECHOS Y CULTURA INDIGENA DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 10 November 2007 to 19 March 2016 |
| `ley-de-desarrollo-agropecuario/` | LEY DE DESARROLLO AGROPECUARIO DEL ESTADO DE BAJA CALIFORNIA | 11 | as first published, then each reform: 9 October 2010 to 11 October 2025 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 1 May 2010 to 14 March 2026 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 29 February 2016 to 14 March 2026 |
| `ley-de-desarrollo-urbano/` | LEY DE DESARROLLO URBANO DEL ESTADO DE BAJA CALIFORNIA | 31 | as first published, then each reform: 24 July 1994 to 15 March 2025 |
| `ley-de-edificaciones/` | LEY DE EDIFICACIONES DEL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 25 June 1994 to 12 April 2025 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE BAJA CALIFORNIA | 27 | as first published, then each reform: 29 December 2020 to 23 June 2026 |
| `ley-de-energias-renovables/` | LEY DE ENERGIAS RENOVABLES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 23 June 2012 to 28 November 2020 |
| `ley-de-entrega-y-recepcion-de-los-asuntos-y-recursos-publico/` | LEY DE ENTREGA Y RECEPCION DE LOS ASUNTOS Y RECURSOS PUBLICOS PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 8 August 1998 to 15 February 2025 |
| `ley-de-estimulo-fiscal-a-la-creacion-y-expresion-artistica-p/` | LEY DE ESTIMULO FISCAL A LA CREACION Y EXPRESION ARTISTICA PARA BAJA CALIFORNIA | 1 | as first published: 19 January 2019 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 14 June 2003 to 18 April 2026 |
| `ley-de-firma-electronica/` | LEY DE FIRMA ELECTRONICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 7 November 2009 to 15 February 2013 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 8 | as first published, then each reform: 12 August 2017 to 10 October 2026 |
| `ley-de-fomento-a-la-competitividad-y-desarrollo-economico/` | LEY DE FOMENTO A LA COMPETITIVIDAD Y DESARROLLO ECONOMICO PARA EL ESTADO DE BAJA CALIFORNIA | 18 | as first published, then each reform: 11 June 2005 to 6 June 2026 |
| `ley-de-fomento-a-la-cultura-del-cuidado-del-agua/` | LEY DE FOMENTO A LA CULTURA DEL CUIDADO DEL AGUA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 19 January 2017 to 13 May 2020 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 20 October 2012 to 6 April 2024 |
| `ley-de-fomento-a-la-produccion-artesanal/` | LEY DE FOMENTO A LA PRODUCCION ARTESANAL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 21 January 2012 to 29 March 2025 |
| `ley-de-fomento-a-la-proveeduria/` | LEY DE FOMENTO A LA PROVEEDURIA DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 21 April 2018 to 28 March 2026 |
| `ley-de-fomento-a-las-actividades-de-bienestar-y-desarrollo-s/` | LEY DE FOMENTO A LAS ACTIVIDADES DE BIENESTAR Y DESARROLLO SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 3 March 2001 to 4 July 2026 |
| `ley-de-fomento-cooperativo/` | LEY DE FOMENTO COOPERATIVO PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 16 March 2024 |
| `ley-de-fomento-para-el-uso-de-la-bicicleta-y-proteccion-al-c/` | LEY DE FOMENTO PARA EL USO DE LA BICICLETA Y PROTECCION AL CICLISTA PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 8 April 2017 |
| `ley-de-fondo-auxiliar-para-la-administracion-de-justicia/` | LEY DE FONDO AUXILIAR PARA LA ADMINISTRACION DE JUSTICIA DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 1 April 1989 to 16 February 2013 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE BAJA CALIFORNIA | 80 | as first published, then each reform: 1 January 1973 to 18 July 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE BAJA CALIFORNIA | 44 | as first published, then each reform: 3 January 1954 to 5 November 2024 |
| `ley-de-impulso-a-la-eficiencia-energetica/` | LEY DE IMPULSO A LA EFICIENCIA ENERGETICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 16 June 2012 to 28 March 2015 |
| `ley-de-impulso-al-conocimiento-cientifico-tecnologico-y-a-la/` | LEY DE IMPULSO AL CONOCIMIENTO CIENTIFICO, TECNOLOGICO Y A LA INNOVACION PARA EL DESARROLLO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 21 March 2020 to 29 June 2024 |
| `ley-de-indulto-para-los-reos-del-fuero-comun/` | LEY DE INDULTO PARA LOS REOS DEL FUERO COMUN DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 1 | as first published: 1 September 1960 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE BAJA CALIFORNIA PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 3 | as first published, then each reform: 26 December 2025 to 18 July 2026 |
| `ley-de-ingresos-del-municipio-de-playas-de-rosarito-baja-cal/` | LEY DE INGRESOS DEL MUNICIPIO DE PLAYAS DE ROSARITO, BAJA CALIFORNIA PARA EL EJERCICIO FISCAL DEL 2026 | 1 | as first published: 2 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-quintin-baja-california/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN QUINTIN, BAJA CALIFORNIA, PARA EL EJERCICIO FISCAL DEL 2026 | 4 | as first published, then each reform: 1 January 2026 to 1 September 2026 |
| `ley-de-obras-publicas-equipamientos-suministros-y-servicios/` | LEY DE OBRAS PUBLICAS, EQUIPAMIENTOS, SUMINISTROS Y SERVICIOS RELACIONADOS CON LA MISMA DEL ESTADO DE BAJA CALIFORNIA | 3 | oldest version available, then each reform: 18 August 2001 to 4 October 2025 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE BAJA CALIFORNIA | 5 | oldest version available, then each reform: 6 August 2011 to 28 March 2026 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE BAJA CALIFORNIA | 2 | oldest version available, then each reform: 29 October 2016 to 8 May 2024 |
| `ley-de-prevencion-mitigacion-y-adaptacion-del-cambio-climati/` | LEY DE PREVENCION, MITIGACION Y ADAPTACION DEL CAMBIO CLIMATICO PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 2 June 2012 to 14 March 2026 |
| `ley-de-prevencion-tratamiento-y-control-de-las-adicciones/` | LEY DE PREVENCION, TRATAMIENTO Y CONTROL DE LAS ADICCIONES PARA EL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 29 October 2016 to 28 March 2026 |
| `ley-de-proteccion-a-la-maternidad/` | LEY DE PROTECCION A LA MATERNIDAD PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 19 October 2013 to 21 November 2015 |
| `ley-de-proteccion-a-los-animales-domesticos/` | LEY DE PROTECCION A LOS ANIMALES DOMESTICOS DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 9 December 1997 to 10 June 2026 |
| `ley-de-proteccion-al-ambiente/` | LEY DE PROTECCION AL AMBIENTE PARA EL ESTADO DE BAJA CALIFORNIA | 48 | as first published, then each reform: 1 December 2001 to 23 June 2026 |
| `ley-de-proteccion-al-empleo/` | LEY DE PROTECCION AL EMPLEO PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 24 December 2011 to 1 December 2018 |
| `ley-de-proteccion-civil-y-gestion-integral-de-riesgos/` | LEY DE PROTECCION CIVIL Y GESTION INTEGRAL DE RIESGOS DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 9 September 2017 to 23 June 2026 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-de-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DE TABACO DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 21 September 2013 to 2 December 2023 |
| `ley-de-proteccion-de-datos-personales-para-el-sector-publico/` | LEY DE PROTECCION DE DATOS PERSONALES PARA EL SECTOR PUBLICO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 1 October 2025 to 10 October 2026 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA | 5 | as first published, then each reform: 8 October 2007 to 6 June 2026 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 10 August 2017 to 1 September 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 24 February 2018 to 28 March 2026 |
| `ley-de-salud-publica/` | LEY DE SALUD PUBLICA PARA EL ESTADO DE BAJA CALIFORNIA | 102 | as first published, then each reform: 10 November 2001 to 28 March 2026 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR DEL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 6 October 2012 to 4 July 2026 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 10 December 1954 to 3 December 1957 |
| `ley-de-transparencia-acceso-a-la-informacion-publica-y-apert/` | LEY DE TRANSPARENCIA, ACCESO A LA INFORMACION PUBLICA Y APERTURA INSTITUCIONAL PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 1 October 2025 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 4 April 2009 to 14 March 2026 |
| `ley-de-urbanizacion/` | LEY DE URBANIZACION DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 21 August 1981 to 25 April 2026 |
| `ley-de-valuacion/` | LEY DE VALUACION DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 26 January 2012 to 12 March 2016 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 30 October 2018 to 16 March 2024 |
| `ley-de-zonas-metropolitanas/` | LEY DE ZONAS METROPOLITANAS DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 16 March 2013 to 13 April 2019 |
| `ley-del-calendario-civico/` | LEY DEL CALENDARIO CIVICO PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 12 March 2016 |
| `ley-del-catastro-inmobiliario/` | LEY DEL CATASTRO INMOBILIARIO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 3 September 1994 to 18 April 2026 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 14 November 2020 |
| `ley-del-ejercicio-de-las-profesiones/` | LEY DEL EJERCICIO DE LAS PROFESIONES PARA EL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 7 September 2002 to 10 May 2025 |
| `ley-del-impuesto-sobre-alcoholes-y-bebidas-alcoholicas/` | LEY DEL IMPUESTO SOBRE ALCOHOLES Y BEBIDAS ALCOHOLICAS | 5 | as first published, then each reform: 11 April 1969 to 1 January 1979 |
| `ley-del-instituto-de-seguridad-y-servicios-sociales-de-los-t/` | LEY DEL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL GOBIERNO Y MUNICIPIOS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 18 February 2015 to 15 July 2023 |
| `ley-del-muro-en-honor-a-las-mujeres-destacadas-en-el-estado/` | LEY DEL MURO EN HONOR A LAS MUJERES DESTACADAS EN EL ESTADO DE BAJA CALIFORNIA -- ANTES LEY DEL MURO DE HONOR PARA HONRAR A LAS MUJERES, EN EL PODER LEGISLATIVO DEL ESTADO DE BAJA CALIFORNIA -- | 5 | as first published, then each reform: 29 December 2012 to 14 March 2026 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 15 September 2001 to 5 September 2026 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 11 November 1992 to 10 October 2026 |
| `ley-del-procedimiento-para-los-actos-de-la-administracion-pu/` | LEY DEL PROCEDIMIENTO PARA LOS ACTOS DE LA ADMINISTRACION PUBLICA DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 3 January 2004 to 21 November 2015 |
| `ley-del-regimen-municipal/` | LEY DEL REGIMEN MUNICIPAL PARA EL ESTADO DE BAJA CALIFORNIA | 38 | as first published, then each reform: 18 October 2001 to 28 February 2026 |
| `ley-del-registro-publico-de-la-propiedad-y-de-comercio/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD Y DE COMERCIO PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 3 December 2005 to 31 December 2016 |
| `ley-del-servicio-civil-de-los-trabajadores-al-servicio-de-lo/` | LEY DEL SERVICIO CIVIL DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA -ANTES LEY DEL SERVICIO CIVIL DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES DEL ESTADO, MUNICIPIOS E INSTITUCIONES DESCENTRALIZADAS DE BAJA CALIFORNIA- | 20 | as first published, then each reform: 21 October 1989 to 3 September 2026 |
| `ley-del-servicio-de-administracion-tributaria/` | LEY DEL SERVICIO DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 15 August 2020 |
| `ley-del-servicio-profesional-docente/` | LEY DEL SERVICIO PROFESIONAL DOCENTE DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 14 March 2014 to 28 March 2014 |
| `ley-del-sistema-estatal-anticorrupcion-de-baja-california/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE BAJA CALIFORNIA | 3 | as first published, then each reform: 8 August 2017 to 27 January 2024 |
| `ley-del-sistema-estatal-de-seguridad-ciudadana-de-baja-calif/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD CIUDADANA DE BAJA CALIFORNIA -- ANTES LEY DE SEGURIDAD PUBLICA DEL ESTADO DE BAJA CALIFORNIA -- | 16 | as first published, then each reform: 29 December 2020 to 28 February 2026 |
| `ley-del-sistema-integral-de-justicia-para-adolescentes/` | LEY DEL SISTEMA INTEGRAL DE JUSTICIA PARA ADOLESCENTES DEL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 8 August 2014 to 25 May 2015 |
| `ley-del-tribunal-de-justicia-electoral/` | LEY DEL TRIBUNAL DE JUSTICIA ELECTORAL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 13 June 2015 to 2 September 2023 |
| `ley-del-tribunal-estatal-de-justicia-administrativa-de-baja/` | LEY DEL TRIBUNAL ESTATAL DE JUSTICIA ADMINISTRATIVA DE BAJA CALIFORNIA | 2 | as first published, then each reform: 19 June 2021 to 1 September 2026 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 13 June 2015 to 1 September 2026 |
| `ley-en-materia-de-declaracion-especial-de-ausencia-para-pers/` | LEY EN MATERIA DE DECLARACION ESPECIAL DE AUSENCIA PARA PERSONAS DESAPARECIDAS DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 11 July 2020 |
| `ley-general-de-administracion-documental/` | LEY GENERAL DE ADMINISTRACION DOCUMENTAL PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 12 July 2003 to 1 December 2018 |
| `ley-general-de-bienes/` | LEY GENERAL DE BIENES DEL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 31 July 1973 to 22 April 2023 |
| `ley-organica-de-la-defensoria-publica/` | LEY ORGANICA DE LA DEFENSORIA PUBLICA DEL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 23 April 2010 to 23 November 2024 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 31 October 2019 to 27 December 2025 |
| `ley-organica-de-la-universidad-autonoma/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DEL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 3 March 1957 to 11 September 2010 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO DEL ESTADO DE BAJA CALIFORNIA | 10 | as first published, then each reform: 9 December 2021 to 1 October 2025 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE BAJA CALIFORNIA | 56 | as first published, then each reform: 5 October 1995 to 1 September 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE BAJA CALIFORNIA | 67 | as first published, then each reform: 26 June 2002 to 7 September 2026 |
| `ley-organica-del-registro-civil/` | LEY ORGANICA DEL REGISTRO CIVIL DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 11 May 1983 to 8 November 2025 |
| `ley-para-el-desarrollo-y-proteccion-social-de-los-periodista/` | LEY PARA EL DESARROLLO Y PROTECCION SOCIAL DE LOS PERIODISTAS DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 6 October 2012 to 1 December 2018 |
| `ley-para-fomentar-la-donacion-altruista-en-materia-alimentar/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA EN MATERIA ALIMENTARIA EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 7 February 1998 to 29 July 2023 |
| `ley-para-la-atencion-proteccion-de-los-derechos-y-apoyo-a-la/` | LEY PARA LA ATENCION, PROTECCION DE LOS DERECHOS Y APOYO A LAS PERSONAS MIGRANTES DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 21 March 2021 to 13 December 2025 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE BAJA CALIFORNIA -- ANTES LEY PARA LA IGUALDAD DE TRATO Y OPORTUNIDADES ENTRE MUJERES Y HOMBRES -- | 14 | as first published, then each reform: 14 November 2015 to 22 July 2025 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 20 September 2014 to 28 February 2026 |
| `ley-para-la-prevencion-gestion-integral-y-economia-circular/` | LEY PARA LA PREVENCION, GESTION INTEGRAL Y ECONOMIA CIRCULAR DE LOS RESIDUOS DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 25 April 2021 to 14 March 2026 |
| `ley-para-la-promocion-fomento-y-desarrollo-de-la-industria-c/` | LEY PARA LA PROMOCION, FOMENTO Y DESARROLLO DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 21 September 2010 to 11 February 2023 |
| `ley-para-la-proteccion-y-defensa-de-los-derechos-de-ninas-ni/` | LEY PARA LA PROTECCION Y DEFENSA DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE BAJA CALIFORNIA | 27 | as first published, then each reform: 18 April 2015 to 4 July 2026 |
| `ley-para-la-venta-almacenaje-y-consumo-publico-de-bebidas-al/` | LEY PARA LA VENTA, ALMACENAJE Y CONSUMO PUBLICO DE BEBIDAS ALCOHOLICAS DEL ESTADO DE BAJA CALIFORNIA | 18 | as first published, then each reform: 12 November 2001 to 31 January 2026 |
| `ley-para-las-personas-con-discapacidad-en-el-estado-de-baja/` | LEY PARA LAS PERSONAS CON DISCAPACIDAD EN EL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 16 October 2010 to 14 May 2025 |
| `ley-para-prevenir-y-erradicar-el-acoso-escolar/` | LEY PARA PREVENIR Y ERRADICAR EL ACOSO ESCOLAR PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 22 September 2014 to 4 July 2026 |
| `ley-para-prevenir-y-erradicar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ERRADICAR LA DISCRIMINACION EN EL ESTADO DE BAJA CALIFORNIA | 11 | as first published, then each reform: 1 September 2012 to 4 October 2025 |
| `ley-para-prevenir-erradicar-los-delitos-en-materia-de-trata/` | LEY PARA PREVENIR, ERRADICAR LOS DELITOS EN MATERIA DE TRATA DE PERSONAS Y PARA LA PROTECCION Y ASISTENCIA A LAS VICTIMAS DE ESTOS DELITOS EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 17 October 2013 to 14 March 2026 |
| `ley-para-prevenir-investigar-y-sancionar-los-delitos-en-mate/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR LOS DELITOS EN MATERIA DE EXTORSION PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 27 December 2025 |
| `ley-que-crea-el-centro-de-justicia-para-las-mujeres/` | LEY QUE CREA EL CENTRO DE JUSTICIA PARA LAS MUJERES DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 30 June 2017 to 7 October 2023 |
| `ley-que-crea-el-organismo-descentralizado-denominado-institu/` | LEY QUE CREA EL ORGANISMO DESCENTRALIZADO DENOMINADO INSTITUTO DE SERVICIOS EDUCATIVOS Y PEDAGOGICOS DE BAJA CALIFORNIA | 2 | as first published, then each reform: 12 December 1992 to 29 May 2023 |
| `ley-que-crea-el-premio-estatal-de-periodismo/` | LEY QUE CREA EL PREMIO ESTATAL DE PERIODISMO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 22 September 2012 to 1 December 2018 |
| `ley-que-crea-la-comision-estatal-del-sistema-penitenciario-d/` | LEY QUE CREA LA COMISION ESTATAL DEL SISTEMA PENITENCIARIO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 30 April 2020 to 29 November 2025 |
| `ley-que-establece-las-bases-de-operacion-de-la-justicia-tera/` | LEY QUE ESTABLECE LAS BASES DE OPERACION DE LA JUSTICIA TERAPEUTICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 16 January 2019 to 22 February 2019 |
| `ley-que-establece-las-bases-de-operacion-de-las-casas-de-emp/` | LEY QUE ESTABLECE LAS BASES DE OPERACION DE LAS CASAS DE EMPEÑO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 28 August 2010 to 1 December 2018 |
| `ley-que-establece-las-bases-minimas-para-el-control-de-la-ex/` | LEY QUE ESTABLECE LAS BASES MINIMAS PARA EL CONTROL DE LA EXPLOTACION DE APARATOS MECANICOS, ELECTRONICOS, ELECTROMECANICOS Y MUSICALES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 22 February 1994 to 12 January 2013 |
| `ley-que-instituye-el-primer-sabado-del-mes-de-septiembre-de/` | LEY QUE INSTITUYE EL PRIMER SABADO DEL MES DE SEPTIEMBRE DE CADA AÑO, COMO DIA ESTATAL DEL DATIL, A EFECTO DE ESTABLECER LA RUTA TURISTICA DEL DATIL Y RECONOCER A ESTA ESPECIE DE LA FLORA, SU CONTRIBUCION AL DESARROLLO SOCIOECONOMICO Y NUTRICIONAL DEL ESTADO | 1 | as first published: 6 April 2024 |
| `ley-que-instituye-la-medalla-de-honor-del-congreso/` | LEY QUE INSTITUYE LA MEDALLA DE HONOR DEL CONGRESO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 20 October 2007 to 28 May 2016 |
| `ley-que-otorga-ayuda-economica-a-los-pensionados-del-sistema/` | LEY QUE OTORGA AYUDA ECONOMICA A LOS PENSIONADOS DEL SISTEMA EDUCATIVO FEDERAL QUE PRESTARON SUS SERVICIOS EN EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 1 August 1980 |
| `ley-que-reglamenta-el-servicio-de-agua-potable-en-el-estado/` | LEY QUE REGLAMENTA EL SERVICIO DE AGUA POTABLE EN EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 19 January 2017 to 25 April 2026 |
| `ley-que-reglamenta-las-candidaturas-independientes-en-el-est/` | LEY QUE REGLAMENTA LAS CANDIDATURAS INDEPENDIENTES EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 13 June 2015 to 2 January 2026 |
| `ley-que-regula-a-los-trabajadores-que-refiere-la-fraccion-i/` | LEY QUE REGULA A LOS TRABAJADORES QUE REFIERE LA FRACCION I, APARTADO B, DEL ARTICULO 99 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA, EN MATERIA DE SEGURIDAD SOCIAL | 1 | as first published: 18 February 2015 |
| `ley-que-regula-a-los-trabajadores-que-refiere-la-fraccion-ii/` | LEY QUE REGULA A LOS TRABAJADORES QUE REFIERE LA FRACCION II, APARTADO B, DEL ARTICULO 99 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA, EN MATERIA DE SEGURIDAD SOCIAL | 2 | as first published, then each reform: 18 February 2015 to 12 March 2016 |
| `ley-que-regula-el-funcionamiento-y-operacion-de-yonkes-recic/` | LEY QUE REGULA EL FUNCIONAMIENTO Y OPERACION DE YONKES, RECICLADORAS Y CENTROS DE ACOPIO DE MATERIALES METALICOS PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 27 August 2013 to 8 February 2025 |
| `ley-que-regula-el-uso-de-la-fuerza-publica-en-el-estado-de-b/` | LEY QUE REGULA EL USO DE LA FUERZA PUBLICA EN EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 16 July 2018 |
| `ley-que-regula-el-uso-y-fomento-del-escudo-y-canto/` | LEY QUE REGULA EL USO Y FOMENTO DEL ESCUDO Y CANTO DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 9 October 2010 to 27 April 2013 |
| `ley-que-regula-las-actividades-de-los-agentes-profesionales/` | LEY QUE REGULA LAS ACTIVIDADES DE LOS AGENTES PROFESIONALES INMOBILIARIOS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 29 November 2014 to 1 December 2018 |
| `ley-que-regula-los-financiamientos-y-obligaciones-para-la-di/` | LEY QUE REGULA LOS FINANCIAMIENTOS Y OBLIGACIONES PARA LA DISCIPLINA FINANCIERA DEL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 3 | as first published, then each reform: 21 April 2018 to 5 November 2024 |
| `ley-que-regula-los-servicios-de-control-vehicular-en-el-esta/` | LEY QUE REGULA LOS SERVICIOS DE CONTROL VEHICULAR EN EL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 9 October 2010 to 12 April 2025 |
| `ley-reglamentaria-de-la-federal-de-tierras-ociosas-del-23-de/` | LEY REGLAMENTARIA DE LA FEDERAL DE TIERRAS OCIOSAS DEL 23 DE JUNIO DE 1920 | 1 | as first published: 1 September 1960 |
| `ley-sobre-desaparicion-y-busqueda-de-personas/` | LEY SOBRE DESAPARICION Y BUSQUEDA DE PERSONAS PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 10 August 2024 to 27 December 2025 |
| `ley-sobre-el-regimen-de-propiedad-en-condominio-de-inmuebles/` | LEY SOBRE EL REGIMEN DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 19 June 2004 to 29 April 2017 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Tijuana, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
