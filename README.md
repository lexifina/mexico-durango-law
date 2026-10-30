# Durango: law history in git

The law of the State of Durango (Estado Libre y Soberano de Durango, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-dur/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

128 ordenamientos with 1239 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE DURANGO | 148 | as first published, then each reform: 4 November 1917 to 1 June 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE DURANGO | 92 | as first published, then each reform: 21 February 1948 to 8 June 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE DURANGO | 22 | as first published, then each reform: 21 September 1948 to 1 June 2018 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE DURANGO | 14 | as first published, then each reform: 1 January 2000 to 1 January 2026 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL | 10 | as first published, then each reform: 21 March 1988 to 17 December 2021 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE DURANGO | 140 | as first published, then each reform: 17 June 2009 to 8 June 2026 |
| `ley-de-accesibilidad/` | LEY DE ACCESIBILIDAD PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 8 December 2017 to 21 May 2021 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES PARA EL ESTADO DE DURANGO | 4 | as first published, then each reform: 21 December 2009 to 7 April 2025 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL ESTADO DE DURANGO | 15 | as first published, then each reform: 1 January 1999 to 21 May 2025 |
| `ley-de-agua/` | LEY DE AGUA PARA EL ESTADO DE DURANGO | 13 | as first published, then each reform: 10 July 2005 to 8 June 2026 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE DURANGO | 1 | as first published: 5 July 2021 |
| `ley-de-arancel-de-los-notarios-publicos/` | LEY DE ARANCEL DE LOS NOTARIOS PUBLICOS DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 24 June 1988 to 7 November 1994 |
| `ley-de-aranceles-de-los-arquitectos/` | LEY DE ARANCELES DE LOS ARQUITECTOS | 2 | as first published, then each reform: 16 December 1988 to 6 March 2017 |
| `ley-de-aranceles-de-los-licenciados-en-derecho-arbitros-depo/` | LEY DE ARANCELES DE LOS LICENCIADOS EN DERECHO, ARBITROS, DEPOSITARIOS, INTERPRETES, TRADUCTORES Y PERITOS EN ASUNTOS JURIDICOS DE CUALQUIER NATURALEZA EN EL ESTADO DE DURANGO | 3 | as first published, then each reform: 24 June 1988 to 6 March 2017 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 8 April 2024 to 14 April 2024 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE DURANGO | 3 | as first published, then each reform: 3 June 2022 to 11 December 2023 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL | 8 | as first published, then each reform: 18 September 1996 to 3 January 2021 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 24 November 2017 to 18 August 2022 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 25 September 1980 to 16 May 2014 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE DURANGO | 9 | as first published, then each reform: 8 July 2013 to 31 October 2025 |
| `ley-de-caminos/` | LEY DE CAMINOS DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 12 March 1930 to 7 July 1997 |
| `ley-de-caminos-y-puentes/` | LEY DE CAMINOS Y PUENTES DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 17 November 2014 to 2 April 2023 |
| `ley-de-ciencia-y-tecnologia/` | LEY DE CIENCIA Y TECNOLOGIA DEL ESTADO DE DURANGO | 7 | as first published, then each reform: 27 October 2006 to 24 April 2025 |
| `ley-de-condominios/` | LEY DE CONDOMINIOS DEL ESTADO DE DURANGO | 5 | as first published, then each reform: 3 August 2013 to 21 November 2022 |
| `ley-de-consulta-indigena/` | LEY DE CONSULTA INDIGENA PARA EL ESTADO Y MUNICIPIOS DE DURANGO | 1 | as first published: 7 September 2015 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE DURANGO Y SUS MUNICIPIOS EN MATERIA DE PARTICIPACIONES | 2 | as first published, then each reform: 1 January 2026 to 1 January 2026 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE DURANGO | 9 | as first published, then each reform: 23 September 2016 to 20 March 2023 |
| `ley-de-cultura/` | LEY DE CULTURA PARA EL ESTADO DE DURANGO | 7 | as first published, then each reform: 8 June 2009 to 5 June 2023 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE DURANGO | 8 | as first published, then each reform: 14 June 2004 to 14 July 2019 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE PARA EL ESTADO DE DURANGO | 12 | as first published, then each reform: 1 January 2014 to 23 November 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE DURANGO | 11 | as first published, then each reform: 18 July 2005 to 19 December 2022 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE DURANGO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 20 May 2005 to 2 December 2024 |
| `ley-de-disciplina-financiera-y-de-responsabilidad-hacendaria/` | LEY DE DISCIPLINA FINANCIERA Y DE RESPONSABILIDAD HACENDARIA DEL ESTADO DE DURANGO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 26 June 2017 to 8 June 2026 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE DURANGO | 63 | as first published, then each reform: 30 June 1995 to 8 June 2026 |
| `ley-de-ejecucion-de-penas-y-medidas-de-seguridad/` | LEY DE EJECUCION DE PENAS Y MEDIDAS DE SEGURIDAD DEL ESTADO DE DURANGO | 7 | as first published, then each reform: 18 October 2009 to 1 April 2022 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE DURANGO | 8 | as first published, then each reform: 17 December 2004 to 9 January 2025 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION | 2 | as first published, then each reform: 11 August 1941 to 24 March 1960 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE DURANGO | 4 | as first published, then each reform: 4 June 2010 to 27 December 2024 |
| `ley-de-fiscalizacion-superior-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS PARA EL ESTADO DE DURANGO | 3 | as first published, then each reform: 13 September 2024 to 8 June 2026 |
| `ley-de-fomento-a-la-actividad-artesanal-en-el-estado-de-dura/` | LEY DE FOMENTO A LA ACTIVIDAD ARTESANAL EN EL ESTADO DE DURANGO | 2 | as first published, then each reform: 3 September 2009 to 7 September 2015 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE DURANGO | 1 | as first published: 1 January 2018 |
| `ley-de-fomento-economico/` | LEY DE FOMENTO ECONOMICO PARA EL ESTADO DE DURANGO | 28 | as first published, then each reform: 2 December 2015 to 3 July 2026 |
| `ley-de-fomento-y-cultura-de-la-paz/` | LEY DE FOMENTO Y CULTURA DE LA PAZ PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 15 May 2023 to 17 November 2025 |
| `ley-de-gestion-ambiental-sustentable/` | LEY DE GESTION AMBIENTAL SUSTENTABLE PARA EL ESTADO DE DURANGO | 21 | as first published, then each reform: 25 June 2010 to 25 May 2026 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 1 January 2026 to 1 January 2026 |
| `ley-de-hacienda-para-los-municipios/` | LEY DE HACIENDA PARA LOS MUNICIPIOS DEL ESTADO DE DURANGO | 14 | as first published, then each reform: 1 January 2007 to 1 January 2027 |
| `ley-de-igualdad-entre-mujeres-y-hombres/` | LEY DE IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE DURANGO | 8 | as first published, then each reform: 2 January 2009 to 17 November 2025 |
| `ley-de-imagen-institucional/` | LEY DE IMAGEN INSTITUCIONAL PARA EL ESTADO DE DURANGO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 1 September 2019 to 25 December 2022 |
| `ley-de-indulto/` | LEY DE INDULTO PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 17 November 2014 to 7 September 2015 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO LIBRE Y SOBERANO DE DURANGO PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-canelas-durango-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE CANELAS, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-cuencame-durango-para-el-ej/` | LEY DE INGRESOS DEL MUNICIPIO DE CUENCAME, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-durango-durango-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE DURANGO, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 19 December 2025 |
| `ley-de-ingresos-del-municipio-de-general-simon-bolivar-duran/` | LEY DE INGRESOS DEL MUNICIPIO DE GENERAL SIMON BOLIVAR, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-gomez-palacio-durango-para/` | LEY DE INGRESOS DEL MUNICIPIO DE GOMEZ PALACIO, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 8 June 2026 |
| `ley-de-ingresos-del-municipio-de-mapimi-durango-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE MAPIMI, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-ocampo-durango-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE OCAMPO, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-poanas-durango-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE POANAS, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-santa-clara-durango-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA CLARA, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-suchil-durango-para-el-ejer/` | LEY DE INGRESOS DEL MUNICIPIO DE SUCHIL, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-tlahualilo-durango-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE TLAHUALILO, DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE DURANGO | 16 | as first published, then each reform: 4 July 2014 to 5 June 2026 |
| `ley-de-integracion-territorial/` | LEY DE INTEGRACION TERRITORIAL PARA EL ESTADO DE DURANGO | 4 | as first published, then each reform: 5 April 2010 to 3 June 2022 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE DURANGO | 3 | as first published, then each reform: 7 August 2017 to 27 May 2022 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE DURANGO | 5 | as first published, then each reform: 17 July 2005 to 20 May 2022 |
| `ley-de-justicia-penal-restaurativa/` | LEY DE JUSTICIA PENAL RESTAURATIVA DEL ESTADO DE DURANGO | 4 | as first published, then each reform: 27 February 2009 to 9 May 2014 |
| `ley-de-la-comision-estatal-de-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 14 June 2024 to 17 November 2025 |
| `ley-de-la-junta-estatal-de-caminos-para-el-desarrollo/` | LEY DE LA JUNTA ESTATAL DE CAMINOS PARA EL DESARROLLO DEL ESTADO DE DURANGO | 1 | as first published: 16 January 1989 |
| `ley-de-la-procuraduria-de-proteccion-de-ninas-ninos-y-adoles/` | LEY DE LA PROCURADURIA DE PROTECCION DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE DURANGO | 6 | as first published, then each reform: 2 September 2016 to 21 November 2022 |
| `ley-de-las-mujeres-para-una-vida-sin-violencia/` | LEY DE LAS MUJERES PARA UNA VIDA SIN VIOLENCIA DEL ESTADO DE DURANGO | 39 | as first published, then each reform: 31 December 2007 to 17 November 2025 |
| `ley-de-las-y-los-jovenes/` | LEY DE LAS Y LOS JOVENES DEL ESTADO DE DURANGO | 5 | as first published, then each reform: 7 March 2003 to 19 November 2017 |
| `ley-de-los-derechos-de-las-jefas-de-familia/` | LEY DE LOS DERECHOS DE LAS JEFAS DE FAMILIA DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 8 May 2023 to 27 April 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE DURANGO | 52 | as first published, then each reform: 13 March 2015 to 10 June 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-tres-poderes/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS TRES PODERES DEL ESTADO DE DURANGO | 23 | as first published, then each reform: 25 July 1980 to 8 June 2026 |
| `ley-de-medios-de-impugnacion-en-materia-electoral-y-de-parti/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL Y DE PARTICIPACION CIUDADANA PARA EL ESTADO DE DURANGO | 8 | as first published, then each reform: 17 November 2008 to 13 August 2023 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA DEL ESTADO DE DURANGO | 1 | as first published: 7 June 2019 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL PARA EL ESTADO DE DURANGO | 3 | as first published, then each reform: 28 July 2023 to 24 October 2025 |
| `ley-de-obra-publica-y-servicios-relacionados-con-la-misma/` | LEY DE OBRA PUBLICA Y SERVICIOS RELACIONADOS CON LA MISMA PARA EL ESTADO DE DURANGO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 5 June 2023 to 7 July 2025 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 20 September 2012 to 8 July 2016 |
| `ley-de-pensiones/` | LEY DE PENSIONES DEL ESTADO DE DURANGO | 3 | as first published, then each reform: 6 December 2017 to 20 August 2021 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE DURANGO | 10 | as first published, then each reform: 4 February 1987 to 21 November 2022 |
| `ley-de-presupuesto-de-egresos/` | LEY DE PRESUPUESTO DE EGRESOS DEL ESTADO LIBRE Y SOBERANO DE DURANGO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-presupuesto-contabilidad-y-gasto-publico/` | LEY DE PRESUPUESTO, CONTABILIDAD Y GASTO PUBLICO DEL ESTADO DE DURANGO | 13 | as first published, then each reform: 29 August 1980 to 2 December 2024 |
| `ley-de-prevencion-de-la-violencia-y-la-delincuencia-en-el-es/` | LEY DE PREVENCION DE LA VIOLENCIA Y LA DELINCUENCIA EN EL ESTADO DE DURANGO | 1 | as first published: 1 April 2020 |
| `ley-de-prevencion-y-asistencia-para-la-atencion-de-las-adicc/` | LEY DE PREVENCION Y ASISTENCIA PARA LA ATENCION DE LAS ADICCIONES DEL ESTADO DE DURANGO | 5 | as first published, then each reform: 18 April 2011 to 10 June 2026 |
| `ley-de-proteccion-a-la-maternidad/` | LEY DE PROTECCION A LA MATERNIDAD PARA EL ESTADO DE DURANGO | 4 | as first published, then each reform: 26 June 2011 to 30 March 2023 |
| `ley-de-proteccion-a-los-no-fumadores/` | LEY DE PROTECCION A LOS NO FUMADORES PARA EL ESTADO DE DURANGO | 6 | as first published, then each reform: 30 June 2006 to 31 March 2023 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE DURANGO | 7 | as first published, then each reform: 29 December 2017 to 1 January 2026 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE DURANGO Y SUS MUNICIPIOS | 1 | as first published: 27 December 2025 |
| `ley-de-proteccion-de-periodistas-y-personas-defensoras-de-de/` | LEY DE PROTECCION DE PERIODISTAS Y PERSONAS DEFENSORAS DE DERECHOS HUMANOS EN EL ESTADO DE DURANGO | 3 | as first published, then each reform: 1 January 2022 to 17 November 2025 |
| `ley-de-proteccion-y-bienestar-animal-para-la-sustentabilidad/` | LEY DE PROTECCION Y BIENESTAR ANIMAL PARA LA SUSTENTABILIDAD DEL ESTADO DE DURANGO | 10 | as first published, then each reform: 18 June 2013 to 31 October 2025 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE DURANGO Y SUS MUNICIPIOS | 3 | as first published, then each reform: 1 January 2014 to 6 March 2017 |
| `ley-de-responsabilidades-de-los-servidores-publicos-en-mater/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS EN MATERIA DE JUICIO POLITICO, DECLARACION DE PROCEDENCIA Y EL EJERCICIO DE FACULTADES LEGISLATIVAS EN MATERIA DE ENJUICIAMIENTO POR RESPONSABILIDADES PUBLICAS DEL ESTADO DE DURANGO | 1 | as first published: 12 July 2019 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE DURANGO | 49 | as first published, then each reform: 12 July 2002 to 5 September 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL PARA EL ESTADO DE DURANGO | 3 | as first published, then each reform: 8 July 2022 to 10 June 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE DURANGO | 2 | as first published, then each reform: 27 February 2009 to 20 March 2017 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA PARA EL ESTADO DE DURANGO | 9 | as first published, then each reform: 29 December 2014 to 8 June 2026 |
| `ley-de-servicios-para-el-desarrollo-integral-infantil/` | LEY DE SERVICIOS PARA EL DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE DURANGO | 6 | as first published, then each reform: 24 December 2012 to 17 November 2025 |
| `ley-de-transito-para-los-municipios/` | LEY DE TRANSITO PARA LOS MUNICIPIOS DEL ESTADO DE DURANGO | 20 | as first published, then each reform: 23 December 1996 to 24 October 2025 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE DURANGO Y SUS MUNICIPIOS | 1 | as first published: 27 December 2025 |
| `ley-de-transportes/` | LEY DE TRANSPORTES PARA EL ESTADO DE DURANGO | 10 | as first published, then each reform: 16 June 2002 to 1 January 2026 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE DURANGO | 18 | oldest version available, then each reform: 4 March 2016 to 17 June 2024 |
| `ley-de-valuacion/` | LEY DE VALUACION PARA EL ESTADO DE DURANGO | 1 | as first published: 23 October 2021 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE DURANGO | 4 | as first published, then each reform: 29 December 2017 to 24 March 2023 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE DURANGO | 6 | as first published, then each reform: 23 May 2011 to 2 November 2018 |
| `ley-del-consejo-estatal-de-armonizacion-contable/` | LEY DEL CONSEJO ESTATAL DE ARMONIZACION CONTABLE DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 24 June 2019 to 2 December 2024 |
| `ley-del-gobierno-digital/` | LEY DEL GOBIERNO DIGITAL DEL ESTADO DE DURANGO | 4 | as first published, then each reform: 16 April 2014 to 20 July 2018 |
| `ley-del-instituto-de-defensoria-publica/` | LEY DEL INSTITUTO DE DEFENSORIA PUBLICA DEL ESTADO DE DURANGO | 8 | as first published, then each reform: 11 March 2009 to 19 June 2023 |
| `ley-del-instituto-estatal-de-las-mujeres/` | LEY DEL INSTITUTO ESTATAL DE LAS MUJERES DEL ESTADO DE DURANGO | 4 | as first published, then each reform: 26 December 2014 to 29 November 2024 |
| `ley-del-libro-y-bibliotecas-publicas/` | LEY DEL LIBRO Y BIBLIOTECAS PUBLICAS DEL ESTADO DE DURANGO | 3 | as first published, then each reform: 8 June 2009 to 20 March 2017 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE DURANGO | 6 | as first published, then each reform: 13 April 2018 to 27 April 2026 |
| `ley-del-patrimonio-cultural/` | LEY DEL PATRIMONIO CULTURAL DEL ESTADO DE DURANGO | 5 | as first published, then each reform: 12 November 2007 to 19 November 2017 |
| `ley-del-periodico-oficial-del-gobierno/` | LEY DEL PERIODICO OFICIAL DEL GOBIERNO DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 28 January 2012 to 8 July 2016 |
| `ley-del-sistema-local-anticorrupcion/` | LEY DEL SISTEMA LOCAL ANTICORRUPCION DEL ESTADO DE DURANGO | 7 | as first published, then each reform: 26 May 2017 to 5 December 2025 |
| `ley-estatal-de-desarrollo-y-fomento-minero-de-durango/` | LEY ESTATAL DE DESARROLLO Y FOMENTO MINERO DE DURANGO | 2 | as first published, then each reform: 1 January 2018 to 9 March 2020 |
| `ley-estatal-de-prevencion-y-eliminacion-de-la-discriminacion/` | LEY ESTATAL DE PREVENCION Y ELIMINACION DE LA DISCRIMINACION, DEL ESTADO DE DURANGO | 11 | as first published, then each reform: 27 December 2009 to 25 March 2024 |
| `ley-estatal-para-la-proteccion-de-personas-que-intervienen-e/` | LEY ESTATAL PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCESO PENAL DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 28 November 2014 to 6 March 2017 |
| `ley-ganadera/` | LEY GANADERA PARA EL ESTADO DE DURANGO | 6 | as first published, then each reform: 14 August 2006 to 23 November 2025 |
| `ley-general-de-catastro/` | LEY GENERAL DE CATASTRO PARA EL ESTADO DE DURANGO | 4 | as first published, then each reform: 3 July 2000 to 11 May 2026 |
| `ley-general-de-los-pueblos-y-comunidades-indigenas/` | LEY GENERAL DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE DURANGO | 7 | as first published, then each reform: 23 July 2007 to 31 March 2023 |
| `ley-hacendaria-para-el-municipio-de-rodeo-durango/` | LEY HACENDARIA PARA EL MUNICIPIO DE RODEO, DURANGO | 1 | as first published: 21 September 2005 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE DURANGO | 11 | as first published, then each reform: 2 October 2022 to 8 June 2026 |
| `ley-organica-de-la-benemerita-y-centenaria-escuela-normal/` | LEY ORGANICA DE LA BENEMERITA Y CENTENARIA ESCUELA NORMAL DEL ESTADO DE DURANGO - ANTES LEY ORGANICA DE LA ESCUELA NORMAL DEL ESTADO DE DURANGO - | 3 | as first published, then each reform: 4 July 1977 to 11 March 2013 |
| `ley-organica-de-la-escuela-secundaria/` | LEY ORGANICA DE LA ESCUELA SECUNDARIA DEL ESTADO "LIC. BENITO JUAREZ" | 2 | as first published, then each reform: 8 July 1965 to 1 September 1969 |
| `ley-organica-de-la-fiscalia-especializada-en-combate-a-la-co/` | LEY ORGANICA DE LA FISCALIA ESPECIALIZADA EN COMBATE A LA CORRUPCION DEL ESTADO DE DURANGO | 4 | as first published, then each reform: 17 July 2017 to 3 November 2023 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE DURANGO ANTES - LEY ORGANICA DE LA PROCURADURIA GENERAL DE JUSTICIA DEL ESTADO DE DURANGO- | 14 | as first published, then each reform: 1 March 2009 to 2 May 2025 |
| `ley-organica-de-la-universidad-juarez/` | LEY ORGANICA DE LA UNIVERSIDAD JUAREZ DEL ESTADO DE DURANGO | 2 | as first published, then each reform: 16 August 2013 to 19 November 2017 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE DURANGO | 1 | as first published: 16 November 2020 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Monterrey, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
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
