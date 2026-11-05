# Baja California: law history in git

The law of the State of Baja California (Estado Libre y Soberano de Baja California, Mexico) in Spanish, with one file per provision and dated versions in git. Historical changes identify their decree; current consolidated baselines identify the official publisher.

This state corpus belongs at `mx-bcn/` in [lexifina/global-law](https://github.com/lexifina/global-law). Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

## What this repository holds

165 ordenamientos with 1960 versions: the state constitution, four codes and state laws. The SCJN historical record contains 143 acts and 1936 versions. This corpus adds 22 current-text acts and two later versions from Congreso del Estado de Baja California. Earlier versions of those 22 additional acts are not included. Regulations and the complete set of repealed laws are outside this record.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 193 | as first published, then each reform: 1953-08-16 to 2026-09-05 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE BAJA CALIFORNIA | 133 | as first published, then each reform: 1974-03-02 to 2026-10-24 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE BAJA CALIFORNIA | 66 | as first published, then each reform: 1974-03-02 to 2018-12-01 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE BAJA CALIFORNIA | 22 | as first published, then each reform: 1989-01-01 to 2024-03-16 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE BAJA CALIFORNIA | 243 | as first published, then each reform: 1989-09-19 to 2026-08-29 |
| `ley-contra-la-delincuencia-organizada/` | LEY CONTRA LA DELINCUENCIA ORGANIZADA PARA EL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 2004-01-03 to 2015-05-25 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE BAJA CALIFORNIA | 42 | as first published, then each reform: 2008-06-26 to 2026-06-23 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2023-03-04 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS PARA EL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 2002-10-19 to 2024-03-09 |
| `ley-de-agricultura-urbana-sustentable/` | LEY DE AGRICULTURA URBANA SUSTENTABLE PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2023-07-08 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2022-10-22 |
| `ley-de-aranceles/` | LEY DE ARANCELES PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 1977-03-11 to 2018-12-01 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 19 | as first published, then each reform: 2002-10-26 to 2026-03-14 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2014-08-23 to 2018-12-01 |
| `ley-de-atencion-y-prevencion-de-la-violencia-familiar/` | LEY DE ATENCION Y PREVENCION DE LA VIOLENCIA FAMILIAR PARA EL ESTADO DE BAJA CALIFORNIA | 13 | as first published, then each reform: 2003-07-05 to 2025-06-28 |
| `ley-de-atencion-y-proteccion-a-personas-con-autismo/` | LEY DE ATENCION Y PROTECCION A PERSONAS CON AUTISMO PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2016-10-24 to 2025-09-06 |
| `ley-de-capacitacion-en-materia-de-genero-de-prevencion-y-err/` | LEY DE CAPACITACION EN MATERIA DE GENERO, DE PREVENCION Y ERRADICACION DE LA VIOLENCIA HACIA LAS MUJERES PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2025-02-08 to 2025-07-24 |
| `ley-de-centros-de-atencion-cuidado-y-desarrollo-integral-inf/` | LEY DE CENTROS DE ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 2015-05-30 to 2022-12-03 |
| `ley-de-compatibilidad-de-funciones-empleos-y-comisiones/` | LEY DE COMPATIBILIDAD DE FUNCIONES, EMPLEOS Y COMISIONES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 1967-07-21 to 2002-02-23 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE BAJA CALIFORNIA | 12 | as first published, then each reform: 1988-01-03 to 2026-05-23 |
| `ley-de-cultura-fisica-y-deportes/` | LEY DE CULTURA FISICA Y DEPORTES DEL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 2015-01-01 to 2024-06-01 |
| `ley-de-derechos-y-cultura-indigena/` | LEY DE DERECHOS Y CULTURA INDIGENA DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2007-11-10 to 2016-03-19 |
| `ley-de-desarrollo-agropecuario/` | LEY DE DESARROLLO AGROPECUARIO DEL ESTADO DE BAJA CALIFORNIA | 11 | as first published, then each reform: 2010-10-09 to 2025-10-11 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 2010-05-01 to 2026-03-14 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 2016-02-29 to 2026-03-14 |
| `ley-de-desarrollo-urbano/` | LEY DE DESARROLLO URBANO DEL ESTADO DE BAJA CALIFORNIA | 31 | as first published, then each reform: 1994-07-24 to 2025-03-15 |
| `ley-de-edificaciones/` | LEY DE EDIFICACIONES DEL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 1994-06-25 to 2025-04-12 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE BAJA CALIFORNIA | 27 | as first published, then each reform: 2020-12-29 to 2026-06-23 |
| `ley-de-energias-renovables/` | LEY DE ENERGIAS RENOVABLES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2012-06-23 to 2020-11-28 |
| `ley-de-entrega-y-recepcion-de-los-asuntos-y-recursos-publico/` | LEY DE ENTREGA Y RECEPCION DE LOS ASUNTOS Y RECURSOS PUBLICOS PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 1998-08-08 to 2025-02-15 |
| `ley-de-estimulo-fiscal-a-la-creacion-y-expresion-artistica-p/` | LEY DE ESTIMULO FISCAL A LA CREACION Y EXPRESION ARTISTICA PARA BAJA CALIFORNIA | 1 | as first published: 2019-01-19 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2003-06-14 to 2026-04-18 |
| `ley-de-firma-electronica/` | LEY DE FIRMA ELECTRONICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2009-11-07 to 2013-02-15 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 8 | as first published, then each reform: 2017-08-12 to 2026-10-10 |
| `ley-de-fomento-a-la-competitividad-y-desarrollo-economico/` | LEY DE FOMENTO A LA COMPETITIVIDAD Y DESARROLLO ECONOMICO PARA EL ESTADO DE BAJA CALIFORNIA | 18 | as first published, then each reform: 2005-06-11 to 2026-06-06 |
| `ley-de-fomento-a-la-cultura-del-cuidado-del-agua/` | LEY DE FOMENTO A LA CULTURA DEL CUIDADO DEL AGUA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2017-01-19 to 2020-05-13 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2012-10-20 to 2024-04-06 |
| `ley-de-fomento-a-la-produccion-artesanal/` | LEY DE FOMENTO A LA PRODUCCION ARTESANAL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 2012-01-21 to 2025-03-29 |
| `ley-de-fomento-a-la-proveeduria/` | LEY DE FOMENTO A LA PROVEEDURIA DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2018-04-21 to 2026-03-28 |
| `ley-de-fomento-a-las-actividades-de-bienestar-y-desarrollo-s/` | LEY DE FOMENTO A LAS ACTIVIDADES DE BIENESTAR Y DESARROLLO SOCIAL PARA EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 2001-03-03 to 2026-07-04 |
| `ley-de-fomento-cooperativo/` | LEY DE FOMENTO COOPERATIVO PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2024-03-16 |
| `ley-de-fomento-para-el-uso-de-la-bicicleta-y-proteccion-al-c/` | LEY DE FOMENTO PARA EL USO DE LA BICICLETA Y PROTECCION AL CICLISTA PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2017-04-08 |
| `ley-de-fondo-auxiliar-para-la-administracion-de-justicia/` | LEY DE FONDO AUXILIAR PARA LA ADMINISTRACION DE JUSTICIA DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 1989-04-01 to 2013-02-16 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE BAJA CALIFORNIA | 80 | as first published, then each reform: 1973-01-01 to 2026-07-18 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE BAJA CALIFORNIA | 44 | as first published, then each reform: 1954-01-03 to 2024-11-05 |
| `ley-de-impulso-a-la-eficiencia-energetica/` | LEY DE IMPULSO A LA EFICIENCIA ENERGETICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2012-06-16 to 2015-03-28 |
| `ley-de-impulso-al-conocimiento-cientifico-tecnologico-y-a-la/` | LEY DE IMPULSO AL CONOCIMIENTO CIENTIFICO, TECNOLOGICO Y A LA INNOVACION PARA EL DESARROLLO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2020-03-21 to 2024-06-29 |
| `ley-de-indulto-para-los-reos-del-fuero-comun/` | LEY DE INDULTO PARA LOS REOS DEL FUERO COMUN DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 1 | as first published: 1960-09-01 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE BAJA CALIFORNIA PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 3 | as first published, then each reform: 2025-12-26 to 2026-07-18 |
| `ley-de-ingresos-del-municipio-de-playas-de-rosarito-baja-cal/` | LEY DE INGRESOS DEL MUNICIPIO DE PLAYAS DE ROSARITO, BAJA CALIFORNIA PARA EL EJERCICIO FISCAL DEL 2026 | 1 | as first published: 2026-01-02 |
| `ley-de-ingresos-del-municipio-de-san-quintin-baja-california/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN QUINTIN, BAJA CALIFORNIA, PARA EL EJERCICIO FISCAL DEL 2026 | 4 | as first published, then each reform: 2026-01-01 to 2026-09-01 |
| `ley-de-obras-publicas-equipamientos-suministros-y-servicios/` | LEY DE OBRAS PUBLICAS, EQUIPAMIENTOS, SUMINISTROS Y SERVICIOS RELACIONADOS CON LA MISMA DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2001-08-18 to 2025-10-04 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2011-08-06 to 2026-03-28 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2016-10-29 to 2024-05-08 |
| `ley-de-prevencion-mitigacion-y-adaptacion-del-cambio-climati/` | LEY DE PREVENCION, MITIGACION Y ADAPTACION DEL CAMBIO CLIMATICO PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 2012-06-02 to 2026-03-14 |
| `ley-de-prevencion-tratamiento-y-control-de-las-adicciones/` | LEY DE PREVENCION, TRATAMIENTO Y CONTROL DE LAS ADICCIONES PARA EL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 2016-10-29 to 2026-03-28 |
| `ley-de-proteccion-a-la-maternidad/` | LEY DE PROTECCION A LA MATERNIDAD PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2013-10-19 to 2015-11-21 |
| `ley-de-proteccion-a-los-animales-domesticos/` | LEY DE PROTECCION A LOS ANIMALES DOMESTICOS DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 1997-12-09 to 2026-06-10 |
| `ley-de-proteccion-al-ambiente/` | LEY DE PROTECCION AL AMBIENTE PARA EL ESTADO DE BAJA CALIFORNIA | 48 | as first published, then each reform: 2001-12-01 to 2026-06-23 |
| `ley-de-proteccion-al-empleo/` | LEY DE PROTECCION AL EMPLEO PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2011-12-24 to 2018-12-01 |
| `ley-de-proteccion-civil-y-gestion-integral-de-riesgos/` | LEY DE PROTECCION CIVIL Y GESTION INTEGRAL DE RIESGOS DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2017-09-09 to 2026-06-23 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-de-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DE TABACO DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2013-09-21 to 2023-12-02 |
| `ley-de-proteccion-de-datos-personales-para-el-sector-publico/` | LEY DE PROTECCION DE DATOS PERSONALES PARA EL SECTOR PUBLICO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2025-10-01 to 2026-10-10 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL PARA EL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2007-10-08 to 2026-06-06 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE BAJA CALIFORNIA | 10 | 9 historical versions retained; additional current Congreso text in force from 2026-10-24 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 2018-02-24 to 2026-03-28 |
| `ley-de-salud-publica/` | LEY DE SALUD PUBLICA PARA EL ESTADO DE BAJA CALIFORNIA | 102 | as first published, then each reform: 2001-11-10 to 2026-03-28 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR DEL ESTADO DE BAJA CALIFORNIA | 9 | as first published, then each reform: 2012-10-06 to 2026-07-04 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 1954-12-10 to 1957-12-03 |
| `ley-de-transparencia-acceso-a-la-informacion-publica-y-apert/` | LEY DE TRANSPARENCIA, ACCESO A LA INFORMACION PUBLICA Y APERTURA INSTITUCIONAL PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2025-10-01 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 2009-04-04 to 2026-03-14 |
| `ley-de-urbanizacion/` | LEY DE URBANIZACION DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 1981-08-21 to 2026-04-25 |
| `ley-de-valuacion/` | LEY DE VALUACION DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2012-01-26 to 2016-03-12 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 2018-10-30 to 2024-03-16 |
| `ley-de-zonas-metropolitanas/` | LEY DE ZONAS METROPOLITANAS DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2013-03-16 to 2019-04-13 |
| `ley-del-calendario-civico/` | LEY DEL CALENDARIO CIVICO PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2016-03-12 |
| `ley-del-catastro-inmobiliario/` | LEY DEL CATASTRO INMOBILIARIO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 1994-09-03 to 2026-04-18 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2020-11-14 |
| `ley-del-ejercicio-de-las-profesiones/` | LEY DEL EJERCICIO DE LAS PROFESIONES PARA EL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 2002-09-07 to 2025-05-10 |
| `ley-del-impuesto-sobre-alcoholes-y-bebidas-alcoholicas/` | LEY DEL IMPUESTO SOBRE ALCOHOLES Y BEBIDAS ALCOHOLICAS | 5 | as first published, then each reform: 1969-04-11 to 1979-01-01 |
| `ley-del-instituto-de-seguridad-y-servicios-sociales-de-los-t/` | LEY DEL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL GOBIERNO Y MUNICIPIOS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2015-02-18 to 2023-07-15 |
| `ley-del-muro-en-honor-a-las-mujeres-destacadas-en-el-estado/` | LEY DEL MURO EN HONOR A LAS MUJERES DESTACADAS EN EL ESTADO DE BAJA CALIFORNIA -- ANTES LEY DEL MURO DE HONOR PARA HONRAR A LAS MUJERES, EN EL PODER LEGISLATIVO DEL ESTADO DE BAJA CALIFORNIA -- | 5 | as first published, then each reform: 2012-12-29 to 2026-03-14 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 2001-09-15 to 2026-09-05 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE BAJA CALIFORNIA | 8 | as first published, then each reform: 1992-11-11 to 2026-10-10 |
| `ley-del-procedimiento-para-los-actos-de-la-administracion-pu/` | LEY DEL PROCEDIMIENTO PARA LOS ACTOS DE LA ADMINISTRACION PUBLICA DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2004-01-03 to 2015-11-21 |
| `ley-del-regimen-municipal/` | LEY DEL REGIMEN MUNICIPAL PARA EL ESTADO DE BAJA CALIFORNIA | 38 | as first published, then each reform: 2001-10-18 to 2026-02-28 |
| `ley-del-registro-publico-de-la-propiedad-y-de-comercio/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD Y DE COMERCIO PARA EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2005-12-03 to 2016-12-31 |
| `ley-del-servicio-civil-de-los-trabajadores-al-servicio-de-lo/` | LEY DEL SERVICIO CIVIL DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES DEL ESTADO Y MUNICIPIOS DE BAJA CALIFORNIA -ANTES LEY DEL SERVICIO CIVIL DE LOS TRABAJADORES AL SERVICIO DE LOS PODERES DEL ESTADO, MUNICIPIOS E INSTITUCIONES DESCENTRALIZADAS DE BAJA CALIFORNIA- | 20 | as first published, then each reform: 1989-10-21 to 2026-09-03 |
| `ley-del-servicio-de-administracion-tributaria/` | LEY DEL SERVICIO DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2020-08-15 |
| `ley-del-servicio-profesional-docente/` | LEY DEL SERVICIO PROFESIONAL DOCENTE DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2014-03-14 to 2014-03-28 |
| `ley-del-sistema-estatal-anticorrupcion-de-baja-california/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2017-08-08 to 2024-01-27 |
| `ley-del-sistema-estatal-de-seguridad-ciudadana-de-baja-calif/` | LEY DEL SISTEMA ESTATAL DE SEGURIDAD CIUDADANA DE BAJA CALIFORNIA -- ANTES LEY DE SEGURIDAD PUBLICA DEL ESTADO DE BAJA CALIFORNIA -- | 16 | as first published, then each reform: 2020-12-29 to 2026-02-28 |
| `ley-del-sistema-integral-de-justicia-para-adolescentes/` | LEY DEL SISTEMA INTEGRAL DE JUSTICIA PARA ADOLESCENTES DEL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 2014-08-08 to 2015-05-25 |
| `ley-del-tribunal-de-justicia-electoral/` | LEY DEL TRIBUNAL DE JUSTICIA ELECTORAL DEL ESTADO DE BAJA CALIFORNIA | 4 | as first published, then each reform: 2015-06-13 to 2023-09-02 |
| `ley-del-tribunal-estatal-de-justicia-administrativa-de-baja/` | LEY DEL TRIBUNAL ESTATAL DE JUSTICIA ADMINISTRATIVA DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2021-06-19 to 2026-09-01 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE BAJA CALIFORNIA | 14 | as first published, then each reform: 2015-06-13 to 2026-09-01 |
| `ley-en-materia-de-declaracion-especial-de-ausencia-para-pers/` | LEY EN MATERIA DE DECLARACION ESPECIAL DE AUSENCIA PARA PERSONAS DESAPARECIDAS DEL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2020-07-11 |
| `ley-general-de-administracion-documental/` | LEY GENERAL DE ADMINISTRACION DOCUMENTAL PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2003-07-12 to 2018-12-01 |
| `ley-general-de-bienes/` | LEY GENERAL DE BIENES DEL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 1973-07-31 to 2023-04-22 |
| `ley-organica-de-la-defensoria-publica/` | LEY ORGANICA DE LA DEFENSORIA PUBLICA DEL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 2010-04-23 to 2024-11-23 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 2019-10-31 to 2025-12-27 |
| `ley-organica-de-la-universidad-autonoma/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DEL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 1957-03-03 to 2010-09-11 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO DEL ESTADO DE BAJA CALIFORNIA | 11 | 10 historical versions retained; additional current Congreso text in force from 2026-01-01 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE BAJA CALIFORNIA | 56 | as first published, then each reform: 1995-10-05 to 2026-09-01 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE BAJA CALIFORNIA | 67 | as first published, then each reform: 2002-06-26 to 2026-09-07 |
| `ley-organica-del-registro-civil/` | LEY ORGANICA DEL REGISTRO CIVIL DEL ESTADO DE BAJA CALIFORNIA | 15 | as first published, then each reform: 1983-05-11 to 2025-11-08 |
| `ley-para-el-desarrollo-y-proteccion-social-de-los-periodista/` | LEY PARA EL DESARROLLO Y PROTECCION SOCIAL DE LOS PERIODISTAS DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2012-10-06 to 2018-12-01 |
| `ley-para-fomentar-la-donacion-altruista-en-materia-alimentar/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA EN MATERIA ALIMENTARIA EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 1998-02-07 to 2023-07-29 |
| `ley-para-la-atencion-proteccion-de-los-derechos-y-apoyo-a-la/` | LEY PARA LA ATENCION, PROTECCION DE LOS DERECHOS Y APOYO A LAS PERSONAS MIGRANTES DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2021-03-21 to 2025-12-13 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE BAJA CALIFORNIA -- ANTES LEY PARA LA IGUALDAD DE TRATO Y OPORTUNIDADES ENTRE MUJERES Y HOMBRES -- | 14 | as first published, then each reform: 2015-11-14 to 2025-07-22 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2014-09-20 to 2026-02-28 |
| `ley-para-la-prevencion-gestion-integral-y-economia-circular/` | LEY PARA LA PREVENCION, GESTION INTEGRAL Y ECONOMIA CIRCULAR DE LOS RESIDUOS DEL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2021-04-25 to 2026-03-14 |
| `ley-para-la-promocion-fomento-y-desarrollo-de-la-industria-c/` | LEY PARA LA PROMOCION, FOMENTO Y DESARROLLO DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2010-09-21 to 2023-02-11 |
| `ley-para-la-proteccion-y-defensa-de-los-derechos-de-ninas-ni/` | LEY PARA LA PROTECCION Y DEFENSA DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE BAJA CALIFORNIA | 27 | as first published, then each reform: 2015-04-18 to 2026-07-04 |
| `ley-para-la-venta-almacenaje-y-consumo-publico-de-bebidas-al/` | LEY PARA LA VENTA, ALMACENAJE Y CONSUMO PUBLICO DE BEBIDAS ALCOHOLICAS DEL ESTADO DE BAJA CALIFORNIA | 18 | as first published, then each reform: 2001-11-12 to 2026-01-31 |
| `ley-para-las-personas-con-discapacidad-en-el-estado-de-baja/` | LEY PARA LAS PERSONAS CON DISCAPACIDAD EN EL ESTADO DE BAJA CALIFORNIA | 16 | as first published, then each reform: 2010-10-16 to 2025-05-14 |
| `ley-para-prevenir-y-erradicar-el-acoso-escolar/` | LEY PARA PREVENIR Y ERRADICAR EL ACOSO ESCOLAR PARA EL ESTADO DE BAJA CALIFORNIA | 7 | as first published, then each reform: 2014-09-22 to 2026-07-04 |
| `ley-para-prevenir-y-erradicar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ERRADICAR LA DISCRIMINACION EN EL ESTADO DE BAJA CALIFORNIA | 11 | as first published, then each reform: 2012-09-01 to 2025-10-04 |
| `ley-para-prevenir-erradicar-los-delitos-en-materia-de-trata/` | LEY PARA PREVENIR, ERRADICAR LOS DELITOS EN MATERIA DE TRATA DE PERSONAS Y PARA LA PROTECCION Y ASISTENCIA A LAS VICTIMAS DE ESTOS DELITOS EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2013-10-17 to 2026-03-14 |
| `ley-para-prevenir-investigar-y-sancionar-los-delitos-en-mate/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR LOS DELITOS EN MATERIA DE EXTORSION PARA EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2025-12-27 |
| `ley-que-crea-el-centro-de-justicia-para-las-mujeres/` | LEY QUE CREA EL CENTRO DE JUSTICIA PARA LAS MUJERES DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2017-06-30 to 2023-10-07 |
| `ley-que-crea-el-organismo-descentralizado-denominado-institu/` | LEY QUE CREA EL ORGANISMO DESCENTRALIZADO DENOMINADO INSTITUTO DE SERVICIOS EDUCATIVOS Y PEDAGOGICOS DE BAJA CALIFORNIA | 2 | as first published, then each reform: 1992-12-12 to 2023-05-29 |
| `ley-que-crea-el-premio-estatal-de-periodismo/` | LEY QUE CREA EL PREMIO ESTATAL DE PERIODISMO DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2012-09-22 to 2018-12-01 |
| `ley-que-crea-la-comision-estatal-del-sistema-penitenciario-d/` | LEY QUE CREA LA COMISION ESTATAL DEL SISTEMA PENITENCIARIO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2020-04-30 to 2025-11-29 |
| `ley-que-establece-las-bases-de-operacion-de-la-justicia-tera/` | LEY QUE ESTABLECE LAS BASES DE OPERACION DE LA JUSTICIA TERAPEUTICA PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2019-01-16 to 2019-02-22 |
| `ley-que-establece-las-bases-de-operacion-de-las-casas-de-emp/` | LEY QUE ESTABLECE LAS BASES DE OPERACION DE LAS CASAS DE EMPEÑO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2010-08-28 to 2018-12-01 |
| `ley-que-establece-las-bases-minimas-para-el-control-de-la-ex/` | LEY QUE ESTABLECE LAS BASES MINIMAS PARA EL CONTROL DE LA EXPLOTACION DE APARATOS MECANICOS, ELECTRONICOS, ELECTROMECANICOS Y MUSICALES PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 1994-02-22 to 2013-01-12 |
| `ley-que-instituye-el-primer-sabado-del-mes-de-septiembre-de/` | LEY QUE INSTITUYE EL PRIMER SABADO DEL MES DE SEPTIEMBRE DE CADA AÑO, COMO DIA ESTATAL DEL DATIL, A EFECTO DE ESTABLECER LA RUTA TURISTICA DEL DATIL Y RECONOCER A ESTA ESPECIE DE LA FLORA, SU CONTRIBUCION AL DESARROLLO SOCIOECONOMICO Y NUTRICIONAL DEL ESTADO | 1 | as first published: 2024-04-06 |
| `ley-que-instituye-la-medalla-de-honor-del-congreso/` | LEY QUE INSTITUYE LA MEDALLA DE HONOR DEL CONGRESO DEL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2007-10-20 to 2016-05-28 |
| `ley-que-otorga-ayuda-economica-a-los-pensionados-del-sistema/` | LEY QUE OTORGA AYUDA ECONOMICA A LOS PENSIONADOS DEL SISTEMA EDUCATIVO FEDERAL QUE PRESTARON SUS SERVICIOS EN EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 1980-08-01 |
| `ley-que-reglamenta-el-servicio-de-agua-potable-en-el-estado/` | LEY QUE REGLAMENTA EL SERVICIO DE AGUA POTABLE EN EL ESTADO DE BAJA CALIFORNIA | 6 | as first published, then each reform: 2017-01-19 to 2026-04-25 |
| `ley-que-reglamenta-las-candidaturas-independientes-en-el-est/` | LEY QUE REGLAMENTA LAS CANDIDATURAS INDEPENDIENTES EN EL ESTADO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2015-06-13 to 2026-01-02 |
| `ley-que-regula-a-los-trabajadores-que-refiere-la-fraccion-i/` | LEY QUE REGULA A LOS TRABAJADORES QUE REFIERE LA FRACCION I, APARTADO B, DEL ARTICULO 99 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA, EN MATERIA DE SEGURIDAD SOCIAL | 1 | as first published: 2015-02-18 |
| `ley-que-regula-a-los-trabajadores-que-refiere-la-fraccion-ii/` | LEY QUE REGULA A LOS TRABAJADORES QUE REFIERE LA FRACCION II, APARTADO B, DEL ARTICULO 99 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA, EN MATERIA DE SEGURIDAD SOCIAL | 2 | as first published, then each reform: 2015-02-18 to 2016-03-12 |
| `ley-que-regula-el-funcionamiento-y-operacion-de-yonkes-recic/` | LEY QUE REGULA EL FUNCIONAMIENTO Y OPERACION DE YONKES, RECICLADORAS Y CENTROS DE ACOPIO DE MATERIALES METALICOS PARA EL ESTADO DE BAJA CALIFORNIA | 3 | as first published, then each reform: 2013-08-27 to 2025-02-08 |
| `ley-que-regula-el-uso-de-la-fuerza-publica-en-el-estado-de-b/` | LEY QUE REGULA EL USO DE LA FUERZA PUBLICA EN EL ESTADO DE BAJA CALIFORNIA | 1 | as first published: 2018-07-16 |
| `ley-que-regula-el-uso-y-fomento-del-escudo-y-canto/` | LEY QUE REGULA EL USO Y FOMENTO DEL ESCUDO Y CANTO DEL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2010-10-09 to 2013-04-27 |
| `ley-que-regula-las-actividades-de-los-agentes-profesionales/` | LEY QUE REGULA LAS ACTIVIDADES DE LOS AGENTES PROFESIONALES INMOBILIARIOS DEL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2014-11-29 to 2018-12-01 |
| `ley-que-regula-los-financiamientos-y-obligaciones-para-la-di/` | LEY QUE REGULA LOS FINANCIAMIENTOS Y OBLIGACIONES PARA LA DISCIPLINA FINANCIERA DEL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 3 | as first published, then each reform: 2018-04-21 to 2024-11-05 |
| `ley-que-regula-los-servicios-de-control-vehicular-en-el-esta/` | LEY QUE REGULA LOS SERVICIOS DE CONTROL VEHICULAR EN EL ESTADO DE BAJA CALIFORNIA | 17 | as first published, then each reform: 2010-10-09 to 2025-04-12 |
| `ley-reglamentaria-de-la-federal-de-tierras-ociosas-del-23-de/` | LEY REGLAMENTARIA DE LA FEDERAL DE TIERRAS OCIOSAS DEL 23 DE JUNIO DE 1920 | 1 | as first published: 1960-09-01 |
| `ley-sobre-desaparicion-y-busqueda-de-personas/` | LEY SOBRE DESAPARICION Y BUSQUEDA DE PERSONAS PARA EL ESTADO DE BAJA CALIFORNIA | 2 | as first published, then each reform: 2024-08-10 to 2025-12-27 |
| `ley-sobre-el-regimen-de-propiedad-en-condominio-de-inmuebles/` | LEY SOBRE EL REGIMEN DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO LIBRE Y SOBERANO DE BAJA CALIFORNIA | 5 | as first published, then each reform: 2004-06-19 to 2017-04-29 |
| `estatuto-territorial-de-los-municipios/` | ESTATUTO TERRITORIAL DE LOS MUNICIPIOS DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2023-07-20; earlier versions not included |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2024-11-23; earlier versions not included |
| `ley-de-instituciones-de-asistencia-social-privada-para-ninas-ninos-y-adolescentes/` | LEY DE INSTITUCIONES DE ASISTENCIA SOCIAL PRIVADA PARA NIÑAS, NIÑOS Y ADOLESCENTES PARA EL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2024-02-10; earlier versions not included |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-02-14; earlier versions not included |
| `ley-de-la-comision-de-arbitraje-medico/` | LEY DE LA COMISIÓN DE ARBITRAJE MÉDICO DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2024-06-29; earlier versions not included |
| `ley-de-la-comision-estatal-de-los-derechos-humanos-de-baja-california/` | LEY DE LA COMISIÓN ESTATAL DE LOS DERECHOS HUMANOS DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2025-02-15; earlier versions not included |
| `ley-de-la-familia/` | LEY DE LA FAMILIA PARA EL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2023-12-09; earlier versions not included |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-03-14; earlier versions not included |
| `ley-de-la-policia-estatal-de-seguridad-y-custodia-penitenciaria-de-baja-california/` | LEY DE LA POLICIA ESTATAL DE SEGURIDAD Y CUSTODIA PENITENCIARIA DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2018-10-20; earlier versions not included |
| `ley-de-la-policia-estatal-preventiva-de-baja-california/` | LEY DE LA POLICÍA ESTATAL PREVENTIVA DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2013-06-29; earlier versions not included |
| `ley-de-la-procuraduria-de-proteccion-al-ambiente/` | LEY DE LA PROCURADURÍA DE PROTECCIÓN AL AMBIENTE PARA EL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2023-09-09; earlier versions not included |
| `ley-de-las-comisiones-estatales-de-servicios-publicos/` | LEY DE LAS COMISIONES ESTATALES DE SERVICIOS PÚBLICOS DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-04-25; earlier versions not included |
| `ley-de-los-derechos-proteccion-e-integracion-de-las-personas-adultas-mayores-en-el-estado/` | LEY DE LOS DERECHOS, PROTECCIÓN E INTEGRACIÓN DE LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-07-04; earlier versions not included |
| `ley-de-mejora-regulatoria-y-sus-municipios/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 1 | current consolidated text, in force from 2025-05-31; earlier versions not included |
| `ley-de-movilidad-sustentable-y-transporte/` | LEY DE MOVILIDAD SUSTENTABLE Y TRANSPORTE DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2025-10-04; earlier versions not included |
| `ley-de-partidos-politicos/` | LEY DE PARTIDOS POLÍTICOS DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2023-09-02; earlier versions not included |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES PARA EL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2024-05-08; earlier versions not included |
| `ley-de-poblacion/` | LEY DE POBLACIÓN DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2013-10-19; earlier versions not included |
| `ley-de-preservacion-del-patrimonio-cultural/` | LEY DE PRESERVACIÓN DEL PATRIMONIO CULTURAL DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2025-06-21; earlier versions not included |
| `ley-de-presupuesto-y-responsabilidad-hacendaria-y-sus-municipios/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE BAJA CALIFORNIA Y SUS MUNICIPIOS | 1 | current consolidated text, in force from 2026-10-10; earlier versions not included |
| `ley-para-la-deteccion-y-tratamiento-oportuno-e-integral-de-cancer-en-la-infancia-y-la-adol/` | LEY PARA LA DETECCIÓN Y TRATAMIENTO OPORTUNO E INTEGRAL DE CÁNCER EN LA INFANCIA Y LA ADOLESCENCIA DEL ESTADO DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-10-24; earlier versions not included |
| `ley-para-la-proteccion-y-fomento-de-la-industria-vitivinicola-de-baja-california/` | LEY PARA LA PROTECCIÓN Y FOMENTO DE LA INDUSTRIA VITIVINÍCOLA DE BAJA CALIFORNIA | 1 | current consolidated text, in force from 2026-06-06; earlier versions not included |

## Reading the record

| Question | Command |
| --- | --- |
| Which text applies on a date? | `python tools/on.py YYYY-MM-DD ACT` |
| What changed in an article? | `git log -p -- ACT/art-NNN.md` |
| Which decree or publisher supplied a paragraph? | `git blame ACT/art-NNN.md` |
| What are the versions and their sources? | Read `data/versions.json` and the act's README. |

An act folder contains its articles, heading and transitorios. Article identifiers use `art-NNN`, with suffixes such as `-bis`. Reform transitorios are separated by their publication dates. Textual annexes, notes and signatures remain in the source text.

## Dates and attribution

`In-force` is the date the text took effect under the source's commencement provision. Publication dates and source URLs remain recorded separately. The executive-organic law's additional version includes changes whose stated commencement is 2026-01-01. Current consolidated text is dated by its latest applicable reform, rather than its original enactment.

Historical law commits name the decree behind the change when the source identifies it. A current baseline marked “oldest version available” is credited to its official publisher. Line attribution follows whole paragraphs; a line can contain wording from more than one amendment. A consolidated source can contain editorial changes whose legislative attribution is not identified.

## Official sources

Historical versions: Suprema Corte de Justicia de la Nación, Legislación, https://legislacion.scjn.gob.mx/. These versions and their history are retained.

Additional current consolidated texts and the two later versions: Congreso del Estado de Baja California, https://www.congresobc.gob.mx/TrabajoLegislativo/Leyes. Each version records its official document URL. Source coverage was checked on 2026-11-05.

The additional record is incomplete: six annual fiscal texts require PDF/table/image validation, and three listed rows require reconciliation of their current normative status. A national execution-law reference belongs to federal legislation. These outstanding rows are not represented as additional current acts here.

## Verification and reproducibility

The repository's text is taken from the official sources. It is not rewritten by a language model. The added current texts use native Word text; no OCR-derived law text is included. The checked added documents contain decorative coats of arms and no omitted normative image content.

`tools/check_repo.py` checks the dated repository files against the corpus input. `REPRODUCE.md` records the sources, data digest and build decisions. Rebuild comparisons check determinism; independent comparisons with official documents check source fidelity. Existing published history is retained when later versions are appended.

## Licence

Legislative texts are not protected by copyright in Mexico: Ley Federal del Derecho de Autor, artículo 14, fracción VIII. Official-source attribution is retained. Source and repository licence details are in `LICENSE`.

## Español

Este repositorio contiene 165 ordenamientos y 1960 versiones de la legislación de Baja California. Conserva las versiones históricas de la SCJN y añade 22 textos vigentes y dos versiones posteriores del Congreso del Estado. Las fechas corresponden a la entrada en vigor indicada por la fuente. No incluye todas las leyes abrogadas ni las versiones anteriores de los 22 textos adicionales.
