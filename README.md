# Madrid: law history in git

The law of the autonomous community of Madrid (Comunidad de Madrid, Spain) as a git history: one file per article, one commit per norm that changed it, dated the day the change took effect, with the amending norm as the commit's author. `git blame` names the norm behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `es-md/`. Spain's national law is in [lexifina/spain-law](https://github.com/lexifina/spain-law).

The text is in Spanish, exactly as the BOE's consolidated text prints it. Texts in co-official languages are not included.

Basado en datos de la Agencia Estatal Boletín Oficial del Estado (<https://www.boe.es>). Every text here is a consolidated text for information only (texto consolidado de carácter meramente informativo), not an official publication.

## What this repository holds

183 norms with 848 versions so far: the Estatuto de Autonomía first, then the laws, decree-laws and legislative decrees in force that the BOE consolidates, oldest first, added in parts of about 50. 24 of them are repealed norms the BOE consolidates: their whole history is kept, and their last commit removes the text on the day the repeal took effect, credited to the repealing norm. Regulations are not included (the BOE consolidates no autonomic decrees or orders).

| Folder | Norm | Versions | History | BOE last updated |
| --- | --- | ---: | --- | --- |
| `estatuto-de-autonomia/` | Ley Orgánica 3/1983, de 25 de febrero, de Estatuto de Autonomía de la Comunidad de Madrid. | 7 | as first published, then each change: 1 March 1983 to 18 July 2010 | 2026-10-09 |
| `ley-1983-001/` | Ley 1/1983, de 13 de diciembre, del Gobierno y Administración de la Comunidad de Madrid. | 26 | as first published, then each change: 20 December 1983 to 14 August 2025 | 2025-12-16 |
| `ley-1983-002/` | Ley 2/1983 de 23 de diciembre de bandera, escudo e himno de la Comunidad de Madrid. | 1 | as first published: 24 December 1983 | 2025-12-16 |
| `ley-1984-001/` | Ley 1/1984, de 19 de enero reguladora de la Administración institucional de la Comunidad de Madrid. | 19 | as first published, then each change: 3 February 1984 to 1 January 2026 | 2026-02-12 |
| `ley-1984-008/` | Ley 8/1984, de 25 de abril, por la que se declara Fiesta de la Comunidad de Madrid la jornada del 2 de mayo de cada año. | 1 | as first published: 14 May 1984 | 2025-12-16 |
| `ley-1984-017/` | Ley 17/1984, de 20 de diciembre, reguladora del abastecimiento y saneamiento de agua en la Comunidad de Madrid. | 4 | as first published, then each change: 31 December 1984 to 1 January 2026 | 2026-02-12 |
| `ley-1985-005/` | Ley 5/1985, de 16 de mayo, de creación del Consorcio Regional de Transportes Públicos Regulares de Madrid. | 10 | as first published, then each change: 27 May 1985 to 1 January 2019 | 2025-12-16 |
| `ley-1986-001/` | Ley 1/1986, de 10 de abril, de la Función Pública de la Comunidad de Madrid. | 44 | as first published, then each change: 24 April 1986 to 1 January 2026 | 2026-02-12 |
| `ley-1986-003/` | Ley 3/1986, de 12 de junio, de ayudas a la prensa local y comarcal de la Comunidad de Madrid. | 2 | as first published, then each change: 25 June 1986 to 27 August 1993 | 2025-12-17 |
| `ley-1986-006/` | Ley 6/1986, de 25 de junio, de iniciativa legislativa popular y de los Ayuntamientos de la Comunidad de Madrid. | 1 | as first published: 29 July 1986 | 2026-10-19 |
| `ley-1986-008/` | Ley 8/1986, de 23 de julio, del Estatuto del Diputado. | 1 | as first published: 30 July 1986 | 2025-12-17 |
| `ley-1986-011/` | Ley 11/1986, de 16 de diciembre, Electoral de la Comunidad de Madrid. | 9 | oldest version available, then each change: 26 December 1986 to 1 January 2007 | 2026-10-20 |
| `ley-1987-001/` | Ley 1/1987, de 5 de marzo, de Cementerios Supramunicipales de la Comunidad de Madrid. | 1 | as first published: 17 March 1987 | 2025-12-17 |
| `ley-1989-004/` | Ley 4/1989, de 6 de abril, de Provisión de Puestos de Trabajo Reservados a Personal Funcionario de la Comunidad de Madrid. | 3 | as first published, then each change: 5 May 1989 to 1 January 2016 | 2026-10-20 |
| `ley-1989-005/` | Ley 5/1989, de 6 de abril, por la que se establecen los criterios básicos por los que han de regirse las relaciones de empleo del personal al servicio de la Comunidad de Madrid. | 1 | as first published: 5 May 1989 | 2025-12-17 |
| `ley-1989-011/` | Ley 11/1989, de 5 de diciembre, de capitalidad de los partidos judiciales de la Comunidad de Madrid. | 1 | as first published: 18 December 1989 | 2025-12-17 |
| `ley-1990-005/` | Ley 5/1990, de 17 de mayo, reguladora de la facultad de disolución de la Asamblea de Madrid por el Presidente de la Comunidad. | 1 | as first published: 29 May 1990 | 2025-12-17 |
| `ley-1990-007/` | Ley 7/1990, de 28 de junio, de Protección de Embalses y Zonas Húmedas de la Comunidad Autónoma de Madrid. | 3 | as first published, then each change: 11 July 1990 to 1 January 2016 | 2025-12-17 |
| `ley-1991-002/` | Ley 2/1991, de 14 de febrero, para la Protección y Regulación de la Fauna y Flora Silvestres en la Comunidad de Madrid. | 5 | as first published, then each change: 5 March 1991 to 28 December 2024 | 2026-07-17 |
| `ley-1991-003/` | Ley 3/1991, de 7 de marzo, de Carreteras de la Comunidad de Madrid. | 9 | as first published, then each change: 21 March 1991 to 16 June 2026 | 2026-07-28 |
| `ley-1992-006/` | Ley 6/1992, de 15 de julio, de creación del Consejo de Cultura de la Comunidad de Madrid. | 1 | as first published: 23 July 1992 | 2025-12-17 |
| `ley-1993-008/` | Ley 8/1993, de 22 de junio, de Promoción de la Accesibilidad y Supresión de Barreras Arquitectónicas. | 7 | as first published, then each change: 29 June 1993 to 27 December 2024 | 2025-12-17 |
| `ley-1993-010/` | Ley 10/1993, de 26 de octubre, sobre Vertidos Líquidos Industriales al Sistema Integral de Saneamiento. | 3 | as first published, then each change: 12 November 1993 to 1 January 2015 | 2026-10-05 |
| `ley-1994-008/` | Ley 8/1994, de 6 de julio, sobre planes y programas de la Comunidad de Madrid en relación con los Fondos Estructurales de la Unión Europea. | 1 | as first published: 13 July 1994 | 2025-12-17 |
| `ley-1994-015/` | Ley 15/1994, de 28 de diciembre, del Deporte de la Comunidad de Madrid. | 6 | as first published, then each change: 12 January 1995 to 27 December 2024 | 2025-12-18 |
| `ley-1995-002/` | Ley 2/1995, de 8 de marzo, de subvenciones de la Comunidad de Madrid. | 12 | as first published, then each change: 21 March 1995 to 1 January 2026 | 2026-02-12 |
| `ley-1995-007/` | Ley 7/1995, de 28 de marzo, de participación de los agentes sociales en las entidades públicas de la Administración de la Comunidad de Madrid. | 1 | as first published: 10 April 1995 | 2025-12-18 |
| `ley-1995-009/` | Ley 9/1995, de 28 de marzo, de Medidas de Política Territorial, Suelo y Urbanismo. | 12 | as first published, then each change: 1 May 1995 to 16 June 2026 | 2026-07-28 |
| `ley-1995-012/` | Ley 12/1995, de 21 de abril, de Estadística de la Comunidad de Madrid. | 4 | as first published, then each change: 3 May 1995 to 23 December 2022 | 2025-12-18 |
| `ley-1995-014/` | Ley 14/1995, de 21 de abril, de Incompatibilidades de Altos Cargos de la Comunidad de Madrid. | 8 | as first published, then each change: 4 May 1995 to 23 December 2022 | 2025-12-18 |
| `ley-1995-016/` | Ley 16/1995, de 4 de mayo, Forestal y de Protección de la Naturaleza de la Comunidad de Madrid. | 17 | as first published, then each change: 30 May 1995 to 21 September 2026 | 2026-09-21 |
| `ley-1996-004/` | Ley 4/1996, de 1 de julio, de creación del Consejo Asesor de Asuntos Europeos de la Comunidad de Madrid. | 1 | as first published: 8 July 1996 | 2025-12-18 |
| `ley-1996-011/` | Ley 11/1996, de 19 de diciembre, de Creación de la Agencia Antidroga de la Comunidad de Madrid. | 3 | as first published, then each change: 1 January 1997 to 14 December 2004 | 2025-12-18 |
| `ley-1997-001/` | Ley 1/1997, de 8 de enero, Reguladora de la Venta Ambulante de la Comunidad de Madrid. | 4 | as first published, then each change: 13 January 1997 to 1 January 2016 | 2026-05-18 |
| `ley-1997-006/` | Ley 6/1997, de 8 de enero, de Protección Pública a la Vivienda de la Comunidad de Madrid. | 1 | as first published: 13 January 1997 | 2026-10-20 |
| `ley-1997-009/` | Ley 9/1997, de 14 de abril, de Creación del Colegio Profesional de Podólogos de la Comunidad de Madrid. | 1 | as first published: 23 April 1997 | 2025-12-18 |
| `ley-1997-010/` | Ley 10/1997, de 14 de abril, de Creación del Colegio Profesional de Fisioterapeutas de la Comunidad de Madrid. | 1 | as first published: 23 April 1997 | 2025-12-18 |
| `ley-1997-012/` | Ley 12/1997, de 4 de junio, reguladora de las Actuaciones Inspectoras y de la Potestad Sancionadora en Materia de Depósito de Fianzas de Arrendamiento de la Comunidad de Madrid. | 1 | as first published: 11 June 1997 | 2026-10-09 |
| `ley-1997-015/` | Ley 15/1997, de 25 de junio, de Ordenación de Actividades Feriales de la Comunidad de Madrid. | 3 | as first published, then each change: 7 July 1997 to 1 January 2009 | 2025-12-18 |
| `ley-1997-017/` | Ley 17/1997, de 4 de julio, de Espectáculos Públicos y Actividades Recreativas. | 14 | as first published, then each change: 7 July 1997 to 21 September 2026 | 2026-09-21 |
| `ley-1997-019/` | Ley 19/1997, de 11 de julio, de Colegios Profesionales de la Comunidad de Madrid. | 3 | as first published, then each change: 16 July 1997 to 30 December 2009 | 2025-12-18 |
| `ley-1997-025/` | Ley 25/1997, de 26 de diciembre, de Regulación del Servicio de Atención de Urgencias 112. | 2 | as first published, then each change: 30 December 1997 to 30 December 2005 | 2025-12-18 |
| `ley-1997-026/` | Ley 26/1997, de 26 de diciembre, de Creación del Instituto Madrileño de Investigación Agraria y Alimentaria (IMIA) de la Comunidad de Madrid. | 4 | as first published, then each change: 30 December 1997 to 28 December 2024 | 2025-12-18 |
| `ley-1998-001/` | Ley 1/1998, de 2 de marzo, de Fundaciones de la Comunidad de Madrid. | 9 | as first published, then each change: 8 April 1998 to 1 January 2015 | 2025-12-18 |
| `ley-1998-004/` | Ley 4/1998, de 8 de abril, de Coordinación Universitaria de la Comunidad de Madrid. | 2 | as first published, then each change: 21 April 1998 to 30 December 1998 | 2025-12-18 |
| `ley-1998-005/` | Ley 5/1998, de 7 de mayo, de Fomento de la Investigación Científica y la Innovación Tecnológica. | 4 | as first published, then each change: 20 May 1998 to 1 January 2011 | 2025-12-18 |
| `ley-1998-006/` | Ley 6/1998, de 28 de mayo, de Régimen Jurídico de la Cámara Agraria de la Comunidad de Madrid. | 1 | as first published: 3 June 1998 | 2025-12-18 |
| `ley-1998-008/` | Ley 8/1998, de 15 de junio, de Vías Pecuarias de la Comunidad de Madrid. | 7 | as first published, then each change: 23 June 1998 to 16 June 2026 | 2026-07-28 |
| `ley-1998-011/` | Ley 11/1998, de 9 de julio, de Protección de los Consumidores de la Comunidad de Madrid. | 9 | as first published, then each change: 17 July 1998 to 27 December 2024 | 2025-12-18 |
| `ley-1998-020/` | Ley 20/1998, de 27 de noviembre, de Ordenación y Coordinación de los Transportes Urbanos de la Comunidad de Madrid. | 7 | as first published, then each change: 4 December 1998 to 28 December 2024 | 2025-12-18 |
| `ley-1998-021/` | Ley 21/1998, de 30 de noviembre, de Ordenación, Protección y Promoción de la Artesanía en la Comunidad de Madrid. | 3 | as first published, then each change: 10 December 1999 to 1 January 2011 | 2025-12-18 |
| `ley-1999-001/` | Ley 1/1999, de 12 de marzo, de Ordenación del Turismo de la Comunidad de Madrid. | 7 | as first published, then each change: 23 March 1999 to 16 June 2026 | 2026-07-28 |
| `ley-1999-002/` | Ley 2/1999, de 17 de marzo, de Medidas para la Calidad de la Edificación. | 1 | as first published: 29 August 1999 | 2025-12-18 |
| `ley-1999-003/` | Ley 3/1999, de 30 de marzo, de Ordenación de los Servicios Jurídicos de la Comunidad de Madrid. | 8 | oldest version available, then each change: 12 April 1999 to 1 January 2016 | 2025-12-18 |
| `ley-1999-009/` | Ley 9/1999, de 9 de abril, de Museos de la Comunidad de Madrid. | 4 | as first published, then each change: 23 April 1999 to 27 December 2024 | 2025-12-18 |
| `ley-1999-011/` | Ley 11/1999, de 29 de abril, de la Cámara de Cuentas de la Comunidad de Madrid. | 6 | as first published, then each change: 13 June 1999 to 1 January 2026 | 2026-02-12 |
| `ley-1999-012/` | Ley 12/1999, de 29 de abril, de creación del Consejo Escolar de la Comunidad de Madrid. | 3 | as first published, then each change: 14 May 1999 to 1 January 2011 | 2025-12-18 |
| `ley-1999-013/` | Ley 13/1999, de 29 de abril, de Cooperación para el Desarrollo de la Comunidad de Madrid. | 3 | as first published, then each change: 14 May 1999 to 1 January 2014 | 2025-12-18 |
| `ley-1999-014/` | Ley 14/1999, de 29 de abril, de creación del Colegio Profesional de Protésicos Dentales de la Comunidad de Madrid. | 1 | as first published: 14 May 1999 | 2025-12-18 |
| `ley-1999-015/` | Ley 15/1999, de 29 de abril, de las academias de ámbito de la Comunidad de Madrid. | 1 | as first published: 5 June 1999 | 2025-12-18 |
| `ley-1999-016/` | Ley 16/1999, de 29 de abril, de Comercio Interior de la Comunidad de Madrid. | 9 | as first published, then each change: 19 May 1999 to 1 January 2013 | 2025-12-18 |
| `ley-1999-017/` | Ley 17/1999, de 29 de abril, sobre aprovechamiento de pastos y rastrojeras para la protección de la ganadería extensiva. | 1 | as first published: 17 May 1999 | 2025-12-18 |
| `ley-1999-020/` | Ley 20/1999, de 3 de mayo, del Parque Regional del Curso Medio del río Guadarrama y su entorno. | 6 | as first published, then each change: 24 May 1999 to 23 December 2022 | 2025-12-18 |
| `ley-2000-004/` | Ley 4/2000, de 8 de mayo, reguladora de las escalas y funciones del Personal de Emergencias Sanitarias de la Comunidad de Madrid. | 2 | as first published, then each change: 12 May 2000 to 27 October 2006 | 2025-12-18 |
| `ley-2000-007/` | Ley 7/2000, de 19 de junio, de Rehabilitación de Espacios Urbanos Degradados y de Inmuebles que deban ser objeto de Preservación. | 1 | as first published: 12 July 2000 | 2025-12-18 |
| `ley-2000-008/` | Ley 8/2000, de 20 de junio, por la que se procede a la homologación de las retribuciones de los miembros del Gobierno y Altos Cargos de la Comunidad de Madrid con los de la Administración General del Estado, y de los Diputados de la Asamblea de Madrid con los Diputados por Madrid del Congreso. | 2 | as first published, then each change: 1 July 2000 to 1 January 2025 | 2025-12-18 |
| `ley-2000-009/` | Ley 9/2000, de 30 de junio, de Mutualidades de Previsión Social. | 2 | as first published, then each change: 7 July 2000 to 1 January 2001 | 2025-12-18 |
| `ley-2001-001/` | Ley 1/2001, de 29 de marzo, por la que se establece la duración máxima y el régimen de silencio administrativo de determinados procedimientos. | 9 | as first published, then each change: 11 April 2001 to 28 December 2024 | 2025-12-18 |
| `ley-2001-002/` | Ley 2/2001, de 18 de abril, de Contenidos Audiovisuales y Servicios Adicionales. | 6 | as first published, then each change: 5 May 2001 to 30 December 2023 | 2025-12-18 |
| `ley-2001-003/` | Ley 3/2001, de 21 de junio, de Patrimonio de la Comunidad de Madrid. | 10 | as first published, then each change: 3 September 2001 to 28 December 2024 | 2025-12-18 |
| `ley-2001-006/` | Ley 6/2001, de 3 de julio, del juego en la Comunidad de Madrid. | 11 | as first published, then each change: 5 July 2001 to 23 December 2022 | 2025-12-18 |
| `ley-2001-009/` | Ley 9/2001, de 17 de julio, del Suelo, de la Comunidad de Madrid. | 23 | as first published, then each change: 27 August 2001 to 16 June 2026 | 2026-07-28 |
| `ley-2001-011/` | Ley 11/2001, de 19 de diciembre, de Uniones de Hecho de la Comunidad de Madrid. | 4 | as first published, then each change: 4 January 2002 to 27 December 2024 | 2025-12-18 |
| `ley-2001-012/` | Ley 12/2001, de 21 de diciembre, de Ordenación Sanitaria de la Comunidad de Madrid. | 11 | as first published, then each change: 26 December 2001 to 23 December 2022 | 2025-12-18 |
| `ley-2001-015/` | Ley 15/2001, de 27 de diciembre, de Renta Mínima de Inserción en la Comunidad de Madrid. | 4 | as first published, then each change: 1 January 2002 to 23 December 2022 | 2026-05-18 |
| `ley-2002-001/` | Ley 1/2002, de 27 de marzo, por la que se crea el Cuerpo de Agentes Forestales de la Comunidad de Madrid. | 2 | as first published, then each change: 5 April 2002 to 23 December 2022 | 2025-12-18 |
| `ley-2002-002/` | Ley 2/2002, de 19 de junio, de Evaluación Ambiental de la Comunidad de Madrid. | 7 | as first published, then each change: 2 July 2002 to 28 December 2024 | 2025-12-18 |
| `ley-2002-005/` | Ley 5/2002, de 27 de junio, sobre Drogodependencias y otros Trastornos Adictivos. | 11 | as first published, then each change: 28 July 2002 to 28 December 2015 | 2025-12-18 |
| `decreto-legislativo-2002-001/` | Decreto Legislativo 1/2002, de 24 de octubre, por el que se aprueba el texto refundido de la Ley de Tasas y Precios Públicos de la Comunidad de Madrid. | 25 | as first published, then each change: 30 October 2002 to 1 January 2026 | 2026-02-12 |
| `ley-2002-008/` | Ley 8/2002, de 27 de noviembre, de Juventud de la Comunidad de Madrid. | 2 | as first published, then each change: 6 December 2002 to 27 December 2024 | 2025-12-18 |
| `ley-2002-009/` | Ley 9/2002, de 11 de diciembre, de Creación del Colegio Profesional de Higienistas Dentales de la Comunidad de Madrid. | 1 | as first published: 21 December 2002 | 2025-12-18 |
| `ley-2002-012/` | Ley 12/2002, de 18 de diciembre, de los Consejos Sociales de las Universidades Públicas de la Comunidad de Madrid. | 2 | as first published, then each change: 23 December 2002 to 1 January 2014 | 2025-12-18 |
| `ley-2002-013/` | Ley 13/2002, de 20 de diciembre, de Medidas Fiscales y Administrativas. | 7 | as first published, then each change: 23 December 2002 to 17 April 2023 | 2025-12-18 |
| `ley-2003-002/` | Ley 2/2003, de 11 de marzo, de Administración Local de la Comunidad de Madrid. | 9 | as first published, then each change: 19 March 2003 to 28 December 2024 | 2025-12-18 |
| `ley-2003-003/` | Ley 3/2003, de 11 de marzo, para el desarrollo del pacto Local. | 2 | as first published, then each change: 7 April 2003 to 1 January 2013 | 2025-12-18 |
| `ley-2003-004/` | Ley 4/2003, de 11 de marzo, de Cajas de Ahorros de la Comunidad de Madrid. | 10 | as first published, then each change: 18 March 2003 to 1 January 2014 | 2025-12-18 |
| `ley-2003-009/` | Ley 9/2003, de 26 de marzo, del régimen sancionador en materia de viviendas protegidas de la Comunidad de Madrid. | 2 | as first published, then each change: 3 May 2003 to 1 January 2006 | 2025-12-18 |
| `ley-2004-003/` | Ley 3/2004, de 10 de diciembre, de creación de la Agencia de la Comunidad de Madrid para la reeducación y reinserción del menor infractor. | 2 | as first published, then each change: 14 December 2004 to 23 December 2022 | 2025-12-18 |
| `ley-2004-005/` | Ley 5/2004, de 28 de diciembre, de medidas fiscales y administrativas. | 4 | as first published, then each change: 1 January 2005 to 26 October 2010 | 2025-12-18 |
| `ley-2004-007/` | Ley 7/2004, de 28 de diciembre, de medidas en materia sanitaria. | 1 | as first published: 30 December 2004 | 2025-12-18 |
| `ley-2005-003/` | Ley 3/2005, de 23 de mayo, por la que se regula el ejercicio del derecho a formular instrucciones previas en el ámbito sanitario y se crea el registro correspondiente. | 2 | as first published, then each change: 14 September 2005 to 22 March 2017 | 2025-12-18 |
| `ley-2005-005/` | Ley 5/2005, de 20 de diciembre, integral contra la violencia de género de la Comunidad de Madrid. | 2 | as first published, then each change: 30 December 2005 to 18 July 2018 | 2025-12-18 |
| `ley-2005-007/` | Ley 7/2005, de 23 de diciembre, de medidas fiscales y administrativas. | 9 | as first published, then each change: 1 January 2006 to 28 December 2024 | 2025-12-18 |
| `ley-2005-008/` | Ley 8/2005, de 26 de diciembre, de protección y fomento del arbolado urbano de la Comunidad de Madrid. | 3 | as first published, then each change: 1 January 2006 to 28 December 2024 | 2025-12-18 |
| `decreto-legislativo-2006-001/` | Decreto Legislativo 1/2006, de 28 de septiembre, por el que se aprueba el Texto Refundido de la Ley por la que se regulan los Servicios de Prevención, Extinción de Incendios y Salvamentos de la Comunidad de Madrid. | 3 | oldest version available, then each change: 27 October 2006 to 23 December 2022 | 2023-12-26 |
| `ley-2007-001/` | Ley 1/2007, de 21 de febrero, de Mediación Familiar de la Comunidad de Madrid. | 1 | as first published: 6 March 2007 | 2025-12-19 |
| `ley-2007-002/` | Ley 2/2007, de 27 de marzo, por la que se regula la garantía del suministro eléctrico de la Comunidad de Madrid. | 3 | as first published, then each change: 17 April 2007 to 28 December 2024 | 2025-12-19 |
| `ley-2007-003/` | Ley 3/2007, de 26 de julio, de medidas urgentes de modernización del Gobierno y Administración de la Comunidad de Madrid. | 5 | as first published, then each change: 31 July 2007 to 27 November 2015 | 2025-12-19 |
| `ley-2008-001/` | Ley 1/2008, de 26 de junio, de Modernización del Comercio de la Comunidad de Madrid. | 1 | as first published: 12 July 2008 | 2025-12-19 |
| `ley-2009-001/` | Ley 1/2009, de 15 de junio, para la creación de una Comisión Permanente no Legislativa para las Políticas Integrales de la Discapacidad. | 1 | as first published: 22 June 2009 | 2025-12-19 |
| `ley-2009-005/` | Ley 5/2009, de 20 de octubre, de Ordenación del Transporte y la Movilidad por Carretera. | 2 | as first published, then each change: 22 October 2009 to 1 January 2011 | 2025-12-19 |
| `ley-2009-006/` | Ley 6/2009, de 16 de noviembre, de Libertad de Elección en la Sanidad de la Comunidad de Madrid. | 1 | as first published: 19 November 2009 | 2025-12-19 |
| `ley-2009-007/` | Ley 7/2009, de 15 de diciembre, por la que se liberaliza el régimen jurídico de la actividad de inspección técnica de vehículos en la Comunidad de Madrid. | 1 | as first published: 18 January 2010 | 2025-12-19 |
| `ley-2009-008/` | Ley 8/2009, de 21 de diciembre, de Medidas Liberalizadoras y de Apoyo a la Empresa Madrileña. | 3 | as first published, then each change: 30 December 2009 to 23 December 2022 | 2025-12-19 |
| `ley-2010-002/` | Ley 2/2010, de 15 de junio, de Autoridad del Profesor. | 1 | as first published: 30 June 2010 | 2025-12-19 |
| `ley-2010-003/` | Ley 3/2010, de 22 de junio, de Instalaciones Aeronáuticas de la Comunidad de Madrid. | 1 | as first published: 30 June 2010 | 2025-12-19 |
| `decreto-legislativo-2010-001/` | Decreto Legislativo 1/2010, de 21 de octubre, del Consejo de Gobierno, por el que se aprueba el Texto Refundido de las Disposiciones Legales de la Comunidad de Madrid en materia de tributos cedidos por el Estado. | 26 | oldest version available, then each change: 26 October 2010 to 11 July 2026 | 2026-08-31 |
| `ley-2010-009/` | Ley 9/2010, de 23 de diciembre, de Medidas Fiscales, Administrativas y de Racionalización del Sector Público. | 8 | as first published, then each change: 29 December 2010 to 1 January 2025 | 2025-12-19 |
| `ley-2011-002/` | Ley 2/2011, de 15 de marzo, de la Cañada Real Galiana. | 1 | as first published: 30 March 2011 | 2025-12-19 |
| `ley-2011-003/` | Ley 3/2011, de 22 de marzo, por la que se establece y regula una red de apoyo a la mujer embarazada. | 1 | as first published: 18 April 2011 | 2025-12-19 |
| `ley-2012-001/` | Ley 1/2012, de 26 de marzo, para la Protección de los Derechos de los Consumidores Mediante el Fomento de la Transparencia en la Contratación Hipotecaria en la Comunidad de Madrid. | 4 | as first published, then each change: 2 July 2012 to 6 December 2018 | 2025-12-19 |
| `ley-2012-002/` | Ley 2/2012, de 12 de junio, de Dinamización de la Actividad Comercial en la Comunidad de Madrid. | 2 | as first published, then each change: 15 July 2012 to 1 January 2013 | 2026-04-24 |
| `ley-2012-004/` | Ley 4/2012, de 4 de julio, de modificación de la Ley de Presupuestos Generales de la Comunidad de Madrid para el año 2012, y de medidas urgentes de racionalización del gasto público e impulso y agilización de la actividad económica. | 4 | as first published, then each change: 10 July 2012 to 23 December 2022 | 2025-12-19 |
| `ley-2012-006/` | Ley 6/2012, de 20 de diciembre, de derogación de la Ley 5/1984, de 7 de marzo, reguladora del Consejo Asesor de Radio y Televisión Española en la Comunidad de Madrid. | 1 | as first published: 1 January 2013 | 2025-12-19 |
| `ley-2012-008/` | Ley 8/2012, de 28 de diciembre, de Medidas Fiscales y Administrativas. | 7 | as first published, then each change: 1 January 2013 to 1 January 2016 | 2025-12-19 |
| `ley-2013-001/` | Ley 1/2013, de 2 de abril, por la que se crea el Colegio Profesional de Logopedas de la Comunidad de Madrid. | 1 | as first published: 9 April 2013 | 2025-12-19 |
| `ley-2014-001/` | Ley 1/2014, de 25 de julio, de Adaptación del Régimen Local de la Comunidad de Madrid a la Ley 27/2013, de 27 de diciembre, de Racionalización y Sostenibilidad de la Administración Local. | 2 | as first published, then each change: 30 July 2014 to 28 December 2024 | 2025-12-19 |
| `ley-2014-002/` | Ley 2/2014, de 16 de diciembre, por la que se regula la Cámara Oficial de Comercio, Industria y Servicios de Madrid. | 2 | as first published, then each change: 26 December 2014 to 30 December 2023 | 2025-12-19 |
| `ley-2015-001/` | Ley 1/2015, de 24 de febrero, del Voluntariado en la Comunidad de Madrid. | 2 | as first published, then each change: 23 March 2015 to 16 April 2023 | 2025-12-19 |
| `ley-2015-002/` | Ley 2/2015, de 10 de marzo, de Acceso al Entorno de Personas con Discapacidad que Precisan el Acompañamiento de Perros de Asistencia. | 1 | as first published: 14 March 2015 | 2025-12-19 |
| `ley-2015-007/` | Ley 7/2015, de 28 de diciembre, de Supresión del Consejo Consultivo. | 3 | as first published, then each change: 31 December 2015 to 30 December 2023 | 2025-12-19 |
| `ley-2015-008/` | Ley 8/2015, de 28 de diciembre, de Radio Televisión Madrid. | 5 | as first published, then each change: 30 December 2015 to 30 December 2023 | 2025-12-19 |
| `ley-2015-009/` | Ley 9/2015, de 28 de diciembre, de medidas fiscales y administrativas. | 5 | as first published, then each change: 1 January 2016 to 23 December 2022 | 2026-05-26 |
| `ley-2016-002/` | Ley 2/2016, de 29 de marzo, de Identidad y Expresión de Género e Igualdad Social y no Discriminación de la Comunidad de Madrid. | 4 | as first published, then each change: 27 April 2016 to 26 December 2024 | 2025-12-19 |
| `ley-2016-003/` | Ley 3/2016, de 22 de julio, de Protección Integral contra LGTBIfobia y la Discriminación por Razón de Orientación e Identidad Sexual en la Comunidad de Madrid. | 4 | as first published, then each change: 11 August 2016 to 15 May 2025 | 2025-12-19 |
| `ley-2016-004/` | Ley 4/2016, de 22 de julio, de Protección de los Animales de Compañía de la Comunidad de Madrid. | 2 | as first published, then each change: 10 February 2016 to 28 December 2024 | 2025-12-19 |
| `ley-2016-005/` | Ley 5/2016, de 22 de julio, por la que se modifica la Regulación del Tribunal Administrativo de Contratación Pública de la Comunidad de Madrid. | 2 | as first published, then each change: 11 August 2016 to 23 December 2022 | 2025-12-19 |
| `ley-2016-006/` | Ley 6/2016, de 24 de noviembre, por la que se ordena el ejercicio de las profesiones del deporte en la Comunidad de Madrid. | 4 | as first published, then each change: 15 June 2017 to 16 April 2023 | 2025-12-19 |
| `ley-2017-001/` | Ley 1/2017, de 9 de marzo, de Creación del Colegio Profesional de Terapeutas Ocupacionales de la Comunidad de Madrid. | 1 | as first published: 13 April 2017 | 2025-12-19 |
| `ley-2017-002/` | Ley 2/2017, de 9 de marzo, de Creación del Colegio Profesional de Dietistas-Nutricionistas de la Comunidad de Madrid. | 1 | as first published: 23 March 2017 | 2025-12-19 |
| `ley-2017-004/` | Ley 4/2017, de 9 de marzo, de Derechos y Garantías de las Personas en el Proceso de Morir. | 1 | as first published: 22 March 2017 | 2025-12-19 |
| `ley-2017-007/` | Ley 7/2017, de 27 de junio, de Gratuidad de los Libros de Texto y el Material Curricular de la Comunidad de Madrid. | 2 | as first published, then each change: 12 July 2017 to 15 November 2017 | 2025-12-19 |
| `ley-2017-009/` | Ley 9/2017, de 3 de julio, por la que se establece el mecanismo de naturaleza no tributaria compensatorio de la repercusión obligatoria del Impuesto sobre Bienes Inmuebles a los arrendatarios de viviendas de la Agencia de Vivienda Social de la Comunidad de Madrid y se adoptan medidas en materia de vivienda protegida. | 2 | as first published, then each change: 21 July 2017 to 28 December 2024 | 2025-12-19 |
| `ley-2017-011/` | Ley 11/2017, de 22 de diciembre, de Buen Gobierno y Profesionalización de la Gestión de los Centros y Organizaciones Sanitarias del Servicio Madrileño de Salud. | 2 | as first published, then each change: 4 January 2018 to 30 December 2023 | 2025-12-20 |
| `ley-2018-001/` | Ley 1/2018, de 22 de febrero, de Coordinación de Policías Locales de la Comunidad de Madrid. | 5 | as first published, then each change: 1 April 2018 to 23 December 2022 | 2025-12-20 |
| `ley-2018-005/` | Ley 5/2018, de 17 de octubre, para la protección, reconocimiento y memoria de las víctimas del terrorismo. | 5 | as first published, then each change: 26 October 2018 to 7 May 2025 | 2025-12-20 |
| `ley-2018-007/` | Ley 7/2018, de 26 de diciembre, de Atencion a la Salud Bucodental y de creacion del Programa de Atencion Dental Infantil - Comunidad de Madrid. | 2 | as first published, then each change: 1 January 2019 to 27 December 2024 | 2025-12-20 |
| `ley-2019-003/` | Ley 3/2019, de 6 de marzo, Reguladora de los Puntos de Encuentro Familiar en la Comunidad de Madrid. | 1 | as first published: 14 March 2019 | 2025-12-20 |
| `ley-2019-010/` | Ley 10/2019, de 10 de abril, de Transparencia y de Participación de la Comunidad de Madrid. | 5 | as first published, then each change: 1 January 2020 to 28 December 2024 | 2025-12-20 |
| `ley-2022-001/` | Ley 1/2022, de 10 de febrero, Maestra de Libertad de Elección Educativa de la Comunidad de Madrid. | 1 | as first published: 16 February 2022 | 2025-12-20 |
| `ley-2022-006/` | Ley 6/2022, de 29 de junio, de Mercado Abierto. | 1 | as first published: 30 September 2022 | 2025-12-20 |
| `ley-2022-010/` | Ley 10/2022, de 16 de noviembre, de Defensa de la Autonomía Financiera de la Comunidad de Madrid. | 1 | as first published: 22 November 2022 | 2025-12-20 |
| `ley-2022-012/` | Ley 12/2022, de 21 de diciembre, de Servicios Sociales de la Comunidad de Madrid. | 1 | oldest version available: 11 January 2023 | 2025-12-20 |
| `ley-2022-013/` | Ley 13/2022, de 21 de diciembre, de Ordenación y Atención Farmacéutica de la Comunidad de Madrid. | 1 | as first published: 23 December 2022 | 2025-12-20 |
| `ley-2023-001/` | Ley 1/2023, de 15 de febrero, de creación de la Agencia Madrileña para el Apoyo a las Personas Adultas con Discapacidad. | 4 | as first published, then each change: 18 February 2023 to 30 November 2023 | 2025-12-20 |
| `ley-2023-002/` | Ley 2/2023, de 24 de febrero, de Cooperativas de la Comunidad de Madrid. | 2 | as first published, then each change: 28 April 2023 to 30 December 2023 | 2025-12-20 |
| `ley-2023-004/` | Ley 4/2023, de 22 de marzo, de Derechos, Garantías y Protección Integral de la Infancia y la Adolescencia de la Comunidad de Madrid. | 1 | as first published: 16 April 2023 | 2025-12-20 |
| `ley-2023-005/` | Ley 5/2023, de 22 de marzo, de Creación del Sistema Integrado de Protección Civil y Emergencias de la Comunidad de Madrid. | 2 | as first published, then each change: 17 April 2023 to 30 December 2023 | 2025-12-20 |
| `ley-2023-006/` | Ley 6/2023, de 30 de marzo, de Archivos y Documentos de la Comunidad de Madrid. | 1 | as first published: 12 May 2023 | 2026-08-17 |
| `ley-2023-007/` | Ley 7/2023, de 30 de marzo, del Libro, la Lectura y el Patrimonio Bibliográfico de la Comunidad de Madrid. | 1 | as first published: 13 April 2023 | 2025-12-20 |
| `ley-2023-008/` | Ley 8/2023, de 30 de marzo, de Patrimonio Cultural de la Comunidad de Madrid. | 6 | as first published, then each change: 13 April 2023 to 21 September 2026 | 2026-09-21 |
| `ley-2024-001/` | Ley 1/2024, de 17 de abril, de Economía Circular de la Comunidad de Madrid. | 1 | as first published: 25 April 2024 | 2025-12-20 |
| `ley-2024-002/` | Ley 2/2024, de 22 de abril, por la que se regulan las Distinciones Honoríficas de la Comunidad de Madrid. | 1 | as first published: 24 April 2024 | 2025-12-20 |
| `ley-2024-003/` | Ley 3/2024, de 28 de junio, de medidas urbanísticas para la promoción de vivienda protegida. | 2 | as first published, then each change: 4 July 2024 to 16 June 2026 | 2026-07-28 |
| `ley-2024-007/` | Ley 7/2024, de 26 de diciembre, de medidas para un desarrollo equilibrado en materia de medio ambiente y ordenación del territorio. | 2 | as first published, then each change: 28 December 2024 to 7 January 2027 | 2026-08-31 |
| `ley-2025-005/` | Ley 5/2025, de 23 de diciembre, de Hacienda de la Comunidad de Madrid. | 1 | as first published: 1 January 2026 | 2026-02-24 |
| `ley-2026-002/` | Ley 2/2026, de 11 de junio, de medidas urgentes para el incremento de la Oferta de Vivienda con Protección Pública. | 1 | as first published: 16 June 2026 | 2026-08-04 |
| `ley-2026-004/` | Ley 4/2026, de 2 de julio, de Caza y Pesca de la Comunidad de Madrid. | 1 | as first published: 7 January 2027 | 2026-08-31 |
| `ley-2026-005/` | Ley 5/2026, de 7 de julio, de reconocimiento del concebido en la aplicación de las medidas de apoyo a la familia en la Comunidad de Madrid. | 2 | as first published, then each change: 11 July 2026 to 10 January 2027 | 2026-08-31 |
| `ley-1985-003/` | Ley 3/1985, de 22 de marzo, de la Medalla de la Comunidad de Madrid. | 2 | as first published, then each change: 25 March 1985 to 24 April 2024; **repealed** 24 April 2024 by Ley 2/2024, de 22 de abril (BOE-A-2024-15000) | 2025-12-16 |
| `ley-1989-001/` | Ley 1/1989, de 2 de marzo, reguladora del Control Parlamentario de la Administración Institucional de la Comunidad de Madrid. | 3 | as first published, then each change: 21 March 1989 to 1 January 2026; **repealed** 1 January 2026 by Ley 5/2025, de 23 de diciembre (BOE-A-2026-3217) | 2026-05-18 |
| `ley-1989-010/` | Ley 10/1989, de 5 de octubre, de Bibliotecas. | 2 | as first published, then each change: 25 October 1989 to 13 April 2023; **repealed** 13 April 2023 by Ley 7/2023, de 30 de marzo (BOE-A-2023-15469) | 2025-12-17 |
| `ley-1990-001/` | Ley 1/1990, de 1 de febrero, de Protección de los Animales Domésticos. | 5 | as first published, then each change: 15 February 1990 to 10 February 2017; **repealed** 10 February 2017 by Ley 4/2016, de 22 de julio (BOE-A-2016-11097) | 2025-12-17 |
| `ley-1990-009/` | Ley 9/1990, de 8 de noviembre, reguladora de la Hacienda de la Comunidad de Madrid. | 30 | as first published, then each change: 21 November 1990 to 1 January 2026; **repealed** 1 January 2026 by Ley 5/2025, de 23 de diciembre (BOE-A-2026-3217) | 2026-10-09 |
| `ley-1991-016/` | Ley 16/1991, de 18 de diciembre, del recargo de la Comunidad de Madrid en el Impuesto sobre Actividades Económicas. | 4 | as first published, then each change: 23 December 1991 to 1 January 2022; **repealed** 1 January 2022 by Ley 3/2021, de 22 de diciembre (BOE-A-2022-1193) | 2025-12-17 |
| `ley-1992-004/` | Ley 4/1992, de 8 de julio, de Coordinación de Policías Locales. | 9 | as first published, then each change: 21 July 1992 to 1 April 2018; **repealed** 1 April 2018 by Ley 1/2018, de 22 de febrero (BOE-A-2018-7516) | 2026-05-18 |
| `ley-1993-004/` | Ley 4/1993, de 21 de abril, de Archivos y Patrimonio Documental de la Comunidad de Madrid. | 2 | as first published, then each change: 30 April 1993 to 12 May 2023; **repealed** 12 May 2023 by Ley 6/2023, de 30 de marzo (BOE-A-2023-15468) | 2025-12-17 |
| `ley-1995-004/` | Ley 4/1995, de 21 de marzo, de creación de la Agencia Madrileña para la Tutela de Adultos. | 4 | oldest version available, then each change: 28 March 1995 to 18 February 2023; **repealed** 18 February 2023 by Ley 1/2023, de 15 de febrero (BOE-A-2023-13671) | 2025-12-18 |
| `ley-1995-006/` | Ley 6/1995, de 28 de marzo, de Garantías de los Derechos de la Infancia y la Adolescencia en la Comunidad de Madrid. | 10 | as first published, then each change: 7 April 1995 to 16 April 2023; **repealed** 16 April 2023 by Ley 4/2023, de 22 de marzo (BOE-A-2023-14347) | 2025-12-18 |
| `ley-1996-012/` | Ley 12/1996, de 19 de diciembre, de Ayuda a las Víctimas del Terrorismo. | 3 | as first published, then each change: 1 January 1997 to 26 October 2018; **repealed** 26 October 2018 by Ley 5/2018, de 17 de octubre (BOE-A-2018-16540) | 2025-12-18 |
| `ley-1998-019/` | Ley 19/1998, de 25 de noviembre, de Ordenación y Atención Farmacéutica de la Comunidad de Madrid. | 6 | as first published, then each change: 3 December 1998 to 23 December 2022; **repealed** 23 December 2022 by Ley 13/2022, de 21 de diciembre (BOE-A-2023-13539) | 2025-12-18 |
| `ley-1999-004/` | Ley 4/1999, de 30 de marzo, de Cooperativas de la Comunidad de Madrid. | 6 | as first published, then each change: 13 June 1999 to 28 April 2023; **repealed** 28 April 2023 by Ley 2/2023, de 24 de febrero (BOE-A-2023-13672) | 2025-12-18 |
| `ley-1999-005/` | Ley 5/1999, de 30 de marzo, de fomento del libro y la lectura de la Comunidad de Madrid. | 2 | as first published, then each change: 16 April 1999 to 13 April 2023; **repealed** 13 April 2023 by Ley 7/2023, de 30 de marzo (BOE-A-2023-15469) | 2025-12-18 |
| `ley-1999-018/` | Ley 18/1999, de 29 de abril, reguladora de los Consejos de Atención a la Infancia y la Adolescencia de la Comunidad de Madrid. | 5 | as first published, then each change: 20 May 1999 to 16 April 2023; **repealed** 16 April 2023 by Ley 4/2023, de 22 de marzo (BOE-A-2023-14347) | 2025-12-18 |
| `ley-2000-003/` | Ley 3/2000, de 8 de mayo, de Medidas Urgentes Fiscales y Administrativas sobre los Juegos de Suerte, Envite y Azar y Apuestas en la Comunidad de Madrid. | 5 | as first published, then each change: 12 May 2000 to 1 January 2022; **repealed** 1 January 2022 by Ley 3/2021, de 22 de diciembre (BOE-A-2022-1193) | 2025-12-18 |
| `ley-2002-011/` | Ley 11/2002, de 18 de diciembre, de Ordenación de la Actividad de los Centros y Servicios de Acción Social y de Mejora de la Calidad en la Prestación de los Servicios Sociales de la Comunidad de Madrid. | 5 | as first published, then each change: 23 March 2003 to 11 January 2023; **repealed** 11 January 2023 by Ley 12/2022, de 21 de diciembre (BOE-A-2023-13538) | 2025-12-18 |
| `ley-2003-005/` | Ley 5/2003, de 20 de marzo, de Residuos de la Comunidad de Madrid. | 7 | as first published, then each change: 1 April 2003 to 25 April 2024; **repealed** 25 April 2024 by Ley 1/2024, de 17 de abril (BOE-A-2024-14999) | 2025-12-18 |
| `ley-2003-006/` | Ley 6/2003, de 20 de marzo, del Impuesto sobre Depósito de Residuos. | 3 | as first published, then each change: 1 April 2003 to 1 January 2022; **repealed** 1 January 2022 by Ley 3/2021, de 22 de diciembre (BOE-A-2022-1193) | 2025-12-18 |
| `ley-2003-011/` | Ley 11/2003, de 27 de marzo, de Servicios Sociales de la Comunidad de Madrid. | 5 | as first published, then each change: 15 April 2003 to 11 January 2023; **repealed** 11 January 2023 by Ley 12/2022, de 21 de diciembre (BOE-A-2023-13538) | 2025-12-18 |
| `ley-2007-006/` | Ley 6/2007, de 21 de diciembre, Reguladora del Consejo Consultivo de la Comunidad de Madrid. | 3 | as first published, then each change: 1 January 2008 to 31 December 2015; **repealed** 31 December 2015 by Ley 7/2015, de 28 de diciembre (BOE-A-2016-2870) | 2025-12-19 |
| `ley-2012-005/` | Ley 5/2012, de 20 de diciembre, de Viviendas Rurales Sostenibles. | 2 | as first published, then each change: 28 December 2012 to 15 April 2016; **repealed** 15 April 2016 by Ley 1/2016, de 29 de marzo (BOE-A-2016-6727) | 2025-12-19 |
| `ley-2013-003/` | Ley 3/2013, de 18 de junio, de Patrimonio Histórico de la Comunidad de Madrid. | 10 | as first published, then each change: 20 June 2013 to 13 April 2023; **repealed** 13 April 2023 by Ley 8/2023, de 30 de marzo (BOE-A-2023-18316) | 2025-12-19 |
| `ley-2017-008/` | Ley 8/2017, de 27 de junio, de creación del Consejo de la Juventud de la Comunidad de Madrid. | 2 | as first published, then each change: 12 July 2017 to 28 December 2024; **repealed** 28 December 2024 by Ley 8/2024, de 26 de diciembre (BOE-A-2025-5523) | 2025-12-19 |

## Source

The consolidated legislation of the Agencia Estatal Boletín Oficial del Estado (BOE), through its open-data API, <https://www.boe.es/datosabiertos/api/legislacion-consolidada>. For each consolidated norm it gives every block of the text (article, disposition, annex, heading) with every version of that block, the day each version took effect (fecha_vigencia) and the norm that made it (id_norma). Each version here is the whole text as it stood on one of those days. The last column above is the BOE's own last-update date for the consolidated text.

## Dates

- Each commit is dated at **noon, Europe/Madrid, on the day the change took effect**: the fecha_vigencia the BOE gives the new block versions.
- A day on which the BOE records a new block version that changes no words is not a version here.
- Block versions with no in-force date (the BOE's 99999999, a date not yet fixed) are left out.
- An act's first commit is its first publication when the BOE's earliest text is the act as enacted; otherwise it is the oldest version the BOE holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 bis; `da-01.md` the Disposición adicional primera, `dt-` transitional, `dd-` repealing and `df-` final dispositions (`-unica` for "única"); `preambulo.md` the preamble, `firma.md` the signature, `anexo-*.md` the annexes. The book, title, chapter and section headings sit at the top of the file of the article that follows them. One paragraph per line; a table one line per row, cells separated by ` | `.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the BOE's own text of that day, rebuilt from the source XML by a separate reader, and every file's text appears in it.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the norm that changed the text (a law, a decree-law, a ruling of the Constitutional Court), named by its title and BOE identifier, with an e-mail address that cannot exist (`<boe id>@boe.es.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. Only the texts published in the official journals are authentic. The history starts with the oldest text the BOE consolidates for each norm. Only the norms listed above are included; norms the BOE does not consolidate are not.
