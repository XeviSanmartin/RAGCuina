# Informe de documents

Data de l'anàlisi: 2026-09-13.

## Criteri i fonts

- Els fitxers de `docs/` s'han llegit sense modificar-los.
- Els PDF s'han analitzat amb PyMuPDF; per a cada fitxer s'ha extret text de la primera, central i última pàgina.
- Els EPUB s'han llegit com a arxius ZIP: s'han analitzat el primer, central i últim document XHTML declarat a l'spine. El recompte és el de documents XHTML de lectura, no la paginació visual d'un lector EPUB.
- Els DOC i DOCX s'han verificat amb Microsoft Word en mode només lectura; per al DOCX també s'ha extret el XML intern.
- Un document és `escanejat` quan la mitjana de caràcters de les mostres és inferior a 200, inclosos els que no tenen text extraïble.
- `mcp-local-rag` 0.18.4 accepta per a ingesta de fitxers PDF, DOCX, TXT i Markdown. No accepta EPUB, DOC, MOBI, RAR, INI ni fitxers sense extensió. Font: [README oficial](https://www.npmjs.com/package/mcp-local-rag#supported-content), consultat el 2026-09-13.
- No s'ha convertit cap fitxer. Els EPUB o DOC amb text requereixen conversió a DOCX o Markdown després de confirmació. Els escanejats es conserven, però no s'ingereixen.

## Resum

- Total: 1019 fitxers.
- PDF: 307 amb text; 469 escanejats.
- EPUB: 182 amb text; 25 escanejats.
- DOC: 1 amb text i 1 escanejat; DOCX: 1 amb text.

## Inventari i mostres

Les mostres es mostren com `unitat: caràcters`; `mitjana` és la mitjana de les mostres. Les pàgines dels formats auxiliars són `n/a`.

| Fitxer | Format | Mida | Pàgines | Mostres (pàgina: caràcters) | Mitjana |
| --- | --- | ---: | ---: | --- | ---: |
| `.gitkeep` | SENSE EXTENSI? | 0.0 KiB | n/a | n/a | n/a |
| `Aliments/AVE QUE VUELA....pdf` | PDF | 1.38 MiB | 15 | 1: 218, 8: 1576, 15: 466 | 753.3 |
| `Aliments/Aguacate.pdf` | PDF | 1.75 MiB | 30 | 1: 21, 16: 21, 30: 21 | 21.0 |
| `Aliments/BERBERECHOS.pdf` | PDF | 1.24 MiB | 6 | 1: 0, 4: 0, 6: 0 | 0.0 |
| `Aliments/Bacallà/Bacalao Recetas de Portugal.pdf` | PDF | 1.55 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Aliments/Bacallà/Bacalhau para Todos.pdf` | PDF | 51.71 MiB | 178 | 1: 0, 90: 0, 178: 0 | 0.0 |
| `Aliments/Bacallà/Biblioteca Lecturas 30 recetas en 30 minutos Bacalao.pdf` | PDF | 28.92 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Aliments/Bacallà/Toma bacalao.pdf` | PDF | 1.13 MiB | 16 | 1: 21, 9: 21, 16: 21 | 21.0 |
| `Aliments/Bacallà/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Aliments/Bolets/8ª Jornadas gastronómicas de las setas y hongos.pdf` | PDF | 1.38 MiB | 84 | 1: 66, 43: 817, 84: 194 | 359.0 |
| `Aliments/Bolets/Comer bien Setas y hongos.pdf` | PDF | 8.38 MiB | 87 | 1: 0, 44: 0, 87: 0 | 0.0 |
| `Aliments/Bolets/Jaume Prat Setas Del bosque a la mesa.pdf` | PDF | 4.89 MiB | 154 | 1: 0, 78: 1623, 154: 0 | 541.0 |
| `Aliments/Bolets/Jose Ramon Ruiz La mejor receta para cada seta.pdf` | PDF | 11.08 MiB | 220 | 1: 12, 111: 1761, 220: 653 | 808.7 |
| `Aliments/Bolets/Llorenç Petràs Cocinar con setas.pdf` | PDF | 64.77 MiB | 171 | 1: 0, 86: 0, 171: 0 | 0.0 |
| `Aliments/Bolets/V Jornadas gastronómicas de setas y hongos.pdf` | PDF | 2.86 MiB | 84 | 1: 16, 43: 746, 84: 0 | 254.0 |
| `Aliments/Bolets/VI Jornadas gastronómicas setas y hongos.pdf` | PDF | 898.8 KiB | 72 | 1: 16, 37: 442, 72: 0 | 152.7 |
| `Aliments/Bolets/VII jornadas gastronómicas de setas & hongos.pdf` | PDF | 941.9 KiB | 68 | 1: 33, 35: 796, 68: 207 | 345.3 |
| `Aliments/Bolets/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Aliments/Borrajas.pdf` | PDF | 2.20 MiB | 7 | 1: 0, 4: 0, 7: 0 | 0.0 |
| `Aliments/COCINA EN UN FISH FAST.pdf` | PDF | 5.11 MiB | 15 | 1: 22, 8: 1705, 15: 160 | 629.0 |
| `Aliments/Caprabo Frutas.pdf` | PDF | 2.44 MiB | 19 | 1: 0, 10: 0, 19: 0 | 0.0 |
| `Aliments/Carmelo Perez Pequeña guia de setas comestibles.pdf` | PDF | 1.90 MiB | 28 | 1: 448, 15: 2168, 28: 1293 | 1303.0 |
| `Aliments/Casquería.pdf` | PDF | 1.72 MiB | 31 | 1: 21, 16: 21, 31: 21 | 21.0 |
| `Aliments/Cocina con gusto Pollo & Aves.pdf` | PDF | 9.77 MiB | 64 | 1: 0, 33: 0, 64: 0 | 0.0 |
| `Aliments/Cocina popular Pescados y mariscos espectaculares.pdf` | PDF | 6.25 MiB | 40 | 1: 0, 21: 0, 40: 0 | 0.0 |
| `Aliments/Como cocinar fruta.pdf` | PDF | 23.08 MiB | 40 | 1: 0, 21: 0, 40: 0 | 0.0 |
| `Aliments/Con Miel.pdf` | PDF | 2.20 MiB | 7 | 1: 0, 4: 0, 7: 0 | 0.0 |
| `Aliments/DEL MAR, EL CALAMAR.pdf` | PDF | 1.56 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Aliments/De segundo, carne.pdf` | PDF | 1.27 MiB | 53 | 1: 0, 27: 0, 53: 0 | 0.0 |
| `Aliments/De segundo, pescado.pdf` | PDF | 1.68 MiB | 28 | 1: 21, 15: 21, 28: 21 | 21.0 |
| `Aliments/Denise Jarrett Chocolates.pdf` | PDF | 80.60 MiB | 66 | 1: 45, 34: 0, 66: 0 | 15.0 |
| `Aliments/ESPECIAL CALABACÍN.pdf` | PDF | 1.37 MiB | 12 | 1: 214, 7: 2097, 12: 362 | 891.0 |
| `Aliments/ESPECIAL CALABAZA.pdf` | PDF | 1.39 MiB | 12 | 1: 175, 7: 1286, 12: 365 | 608.7 |
| `Aliments/El gran libro del huevo.pdf` | PDF | 21.01 MiB | 167 | 1: 0, 84: 9, 167: 10 | 6.3 |
| `Aliments/El-Gran-Libro-de-las-Manzanas.pdf` | PDF | 56.62 MiB | 184 | 1: 0, 93: 1144, 184: 0 | 381.3 |
| `Aliments/Especial Ajos.pdf` | PDF | 4.54 MiB | 7 | 1: 0, 4: 0, 7: 0 | 0.0 |
| `Aliments/Especial Conejo.pdf` | PDF | 1.36 MiB | 19 | 1: 21, 10: 21, 19: 21 | 21.0 |
| `Aliments/Especial berenjena.pdf` | PDF | 15.99 MiB | 66 | 1: 0, 34: 0, 66: 0 | 0.0 |
| `Aliments/Especial calabacin vol II.pdf` | PDF | 1.13 MiB | 16 | 1: 21, 9: 21, 16: 21 | 21.0 |
| `Aliments/Especial pollo II.pdf` | PDF | 13.43 MiB | 55 | 1: 0, 28: 0, 55: 0 | 0.0 |
| `Aliments/Especial pollo.pdf` | PDF | 12.08 MiB | 51 | 1: 0, 26: 0, 51: 0 | 0.0 |
| `Aliments/Espárragos blancos y verdes.pdf` | PDF | 1.72 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Aliments/Felipe Luzón La cocina del mejillon.pdf` | PDF | 809.0 KiB | 215 | 1: 65, 108: 1929, 215: 614 | 869.3 |
| `Aliments/Gallina blanca Recetario de patatas.pdf` | PDF | 625.9 KiB | 24 | 1: 0, 13: 597, 24: 588 | 395.0 |
| `Aliments/Hortalizas Otoño-Invierno.pdf` | PDF | 1.60 MiB | 19 | 1: 21, 10: 21, 19: 21 | 21.0 |
| `Aliments/Ideas para degustar la aceituna.pdf` | PDF | 4.50 MiB | 30 | 1: 46, 16: 46, 30: 46 | 46.0 |
| `Aliments/Joan Antoni Miró Con un par de huevos.pdf` | PDF | 10.79 MiB | 470 | 1: 0, 236: 1112, 470: 0 | 370.7 |
| `Aliments/Kocinarte Recetas de carne.pdf` | PDF | 4.05 MiB | 12 | 1: 0, 7: 1079, 12: 800 | 626.3 |
| `Aliments/LIBRO+ARROCES+DE+ESPAÑA.pdf` | PDF | 14.64 MiB | 52 | 1: 112, 27: 0, 52: 40 | 50.7 |
| `Aliments/La gran mariscada.pdf` | PDF | 2.04 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Aliments/La sandia recetas.pdf` | PDF | 415.5 KiB | 7 | 1: 130, 4: 2460, 7: 1146 | 1245.3 |
| `Aliments/Legumbres.pdf` | PDF | 1.61 MiB | 26 | 1: 21, 14: 21, 26: 21 | 21.0 |
| `Aliments/Los chiles de México.pdf` | PDF | 7.01 MiB | 97 | 1: 21, 49: 21, 97: 21 | 21.0 |
| `Aliments/Los mejores quesos.pdf` | PDF | 1.37 MiB | 76 | 1: 889, 39: 801, 76: 212 | 634.0 |
| `Aliments/Maru Castilla Pollo gourmet.epub` | EPUB | 3.57 MiB | 1 | 1: 29032 | 29032.0 |
| `Aliments/Montse Bradford Algas Las verduras del mar.pdf` | PDF | 53.52 MiB | 114 | 1: 0, 58: 0, 114: 0 | 0.0 |
| `Aliments/Montse Bradford Algas, las verduras del mar.pdf` | PDF | 53.53 MiB | 114 | 1: 17, 58: 17, 114: 17 | 17.0 |
| `Aliments/OGGI BROCCOLI.pdf` | PDF | 3.32 MiB | 4 | 1: 0, 3: 0, 4: 0 | 0.0 |
| `Aliments/Pablo Battro Todo lo que siempre quiso saber sobre quesos.epub` | EPUB | 7.24 MiB | 15 | 1: 5, 8: 765, 15: 280 | 350.0 |
| `Aliments/Pollos al Horno Mediterráneo.pdf` | PDF | 6.38 MiB | 98 | 1: 0, 50: 0, 98: 0 | 0.0 |
| `Aliments/RECETAS PRODUCTOS DEL MAR.pdf` | PDF | 5.73 MiB | 73 | 1: 33, 37: 1202, 73: 1045 | 760.0 |
| `Aliments/Recetario a base de cereales y otros granos.mobi` | MOBI | 2.18 MiB | n/a | n/a | n/a |
| `Aliments/Salmón Cenas fáciles para el día a día.pdf` | PDF | 1.44 MiB | 18 | 1: 21, 10: 21, 18: 21 | 21.0 |
| `Aliments/Superfoods for Life, Cacao.epub` | EPUB | 14.7 KiB | n/a | error d'anàlisi: File is not a zip file | n/a |
| `Aliments/Todo patata.pdf` | PDF | 4.04 MiB | 62 | 1: 21, 32: 47, 62: 655 | 241.0 |
| `Aliments/Todo queso.pdf` | PDF | 1.62 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Aliments/Todo verde.pdf` | PDF | 1.61 MiB | 24 | 1: 21, 13: 21, 24: 21 | 21.0 |
| `Aliments/VI_jornadas_gastronómicas_del_iberico.pdf` | PDF | 2.01 MiB | 76 | 1: 16, 39: 1089, 76: 261 | 455.3 |
| `Aliments/recetario-merluza.pdf` | PDF | 2.90 MiB | 14 | 1: 18, 8: 756, 14: 1254 | 676.0 |
| `Aliments/recetas-chocolate (1).pdf` | PDF | 7.92 MiB | 24 | 1: 0, 13: 2677, 24: 0 | 892.3 |
| `Aliments/Ángel León Pescados azules.pdf` | PDF | 10.20 MiB | 8 | 1: 0, 5: 0, 8: 0 | 0.0 |
| `Cocció de marisc i crustacis.doc` | DOC | 23.5 KiB | 2 | 1: 2838 | 1419.0 |
| `Col·leccions/100% CRÊPES.pdf` | PDF | 1.54 MiB | 16 | 1: 192, 9: 2730, 16: 414 | 1112.0 |
| `Col·leccions/100% FRESA.pdf` | PDF | 1.67 MiB | 15 | 1: 215, 8: 759, 15: 425 | 466.3 |
| `Col·leccions/100% LASAÑA.pdf` | PDF | 1.65 MiB | 15 | 1: 262, 8: 2531, 15: 500 | 1097.7 |
| `Col·leccions/100% PAPILLOTE.pdf` | PDF | 1.84 MiB | 15 | 1: 262, 8: 1293, 15: 547 | 700.7 |
| `Col·leccions/100% tomate.pdf` | PDF | 3.33 MiB | 51 | 1: 21, 26: 21, 51: 21 | 21.0 |
| `Col·leccions/20 recetas navideñas Platos vegetarianos.pdf` | PDF | 554.4 KiB | 52 | 1: 0, 27: 1400, 52: 0 | 466.7 |
| `Col·leccions/20 recetas navideñas para preparar postres helados.pdf` | PDF | 537.4 KiB | 49 | 1: 0, 25: 1133, 49: 0 | 377.7 |
| `Col·leccions/30 recetas en 30 minutos Ensaladas.pdf` | PDF | 26.36 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/30 recetas en 30 minutos Pastas y arroces.pdf` | PDF | 26.56 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/@malu320   Cocina Facil 2019-04-01.pdf` | PDF | 26.40 MiB | 148 | 1: 0, 75: 652, 148: 0 | 217.3 |
| `Col·leccions/Ada Parellada La cocina sostenible.epub` | EPUB | 10.61 MiB | 20 | 1: 8, 11: 21252, 20: 448 | 7236.0 |
| `Col·leccions/Anna Helm Ensaladas en frasco.epub` | EPUB | 2.04 MiB | 2 | 1: 5, 2: 19 | 12.0 |
| `Col·leccions/Anne Wilson Aperitivos y entrantes.pdf` | PDF | 20.85 MiB | 32 | 1: 0, 17: 0, 32: 0 | 0.0 |
| `Col·leccions/Anne Wilson Cocina asiática vegetariana.pdf` | PDF | 15.14 MiB | 32 | 1: 0, 17: 0, 32: 0 | 0.0 |
| `Col·leccions/Anne Wilson Cocina vegetariana rápida.pdf` | PDF | 7.39 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Anne Wilson Cocinar con wok.pdf` | PDF | 20.75 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Anne Wilson Guisos y cazuelas.pdf` | PDF | 5.75 MiB | 34 | 1: 0, 18: 0, 34: 0 | 0.0 |
| `Col·leccions/Anne Wilson Las mejores recetas de Asia.pdf` | PDF | 58.40 MiB | 175 | 1: 0, 88: 0, 175: 0 | 0.0 |
| `Col·leccions/Anne Wilson Pizzas y gratinados.pdf` | PDF | 7.09 MiB | 31 | 1: 0, 16: 0, 31: 0 | 0.0 |
| `Col·leccions/Anne Wilson Recetas de patatas populares.pdf` | PDF | 3.36 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Anne Wilson Sopas.pdf` | PDF | 8.59 MiB | 33 | 1: 716, 17: 2152, 33: 1900 | 1589.3 |
| `Col·leccions/Biblioteca Lecturas 30 recetas en 30 minutos Mousses.pdf` | PDF | 14.26 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Biblioteca lecturas 30 recetas en 30 minutos Pollo.pdf` | PDF | 5.61 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (2).pdf` | PDF | 13.02 MiB | 34 | 1: 0, 18: 0, 34: 0 | 0.0 |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (3).pdf` | PDF | 13.51 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (4).pdf` | PDF | 12.64 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en.pdf` | PDF | 14.84 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Col·leccions/Bimbo Recetas de Cuaresma.pdf` | PDF | 3.37 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Col·leccions/Buen Provecho num. 143 Enero 2017.pdf` | PDF | 16.73 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 22 Junio-Julio 2016.pdf` | PDF | 8.10 MiB | 40 | 1: 0, 21: 0, 40: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 59 Diciembre 2014.pdf` | PDF | 25.79 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 61 Febrero 2015.pdf` | PDF | 23.81 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 62 Marzo 2015.pdf` | PDF | 26.28 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 63 Abril 2015.pdf` | PDF | 24.52 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 65 Junio 2015.pdf` | PDF | 24.09 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 66 Julio 2015.pdf` | PDF | 23.10 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 69 Octubre 2015.pdf` | PDF | 34.03 MiB | 84 | 1: 143, 43: 1212, 84: 0 | 451.7 |
| `Col·leccions/Cocina Semana num. 70 Noviembre 2015.pdf` | PDF | 27.00 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 71 Diciembre 2015.pdf` | PDF | 32.96 MiB | 84 | 1: 159, 43: 776, 84: 0 | 311.7 |
| `Col·leccions/Cocina Semana num. 79 Agosto 2016.pdf` | PDF | 19.81 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina Semana num. 80 Septiembre 2016.pdf` | PDF | 20.40 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Col·leccions/Cocina fácil Comida tipica mexicana.pdf` | PDF | 7.03 MiB | 52 | 1: 0, 27: 0, 52: 0 | 0.0 |
| `Col·leccions/Cocina fácil Edición especial Bocadillos.pdf` | PDF | 11.78 MiB | 66 | 1: 0, 34: 0, 66: 0 | 0.0 |
| `Col·leccions/Cocina fácil Fabulosos postres.pdf` | PDF | 6.30 MiB | 70 | 1: 0, 36: 0, 70: 0 | 0.0 |
| `Col·leccions/Cocina fácil Todo al horno.pdf` | PDF | 6.03 MiB | 61 | 1: 0, 31: 0, 61: 0 | 0.0 |
| `Col·leccions/Cocina fácil lecturas num. 231.pdf` | PDF | 18.88 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/Cocina ilustrada Cocina fácil y rápida.pdf` | PDF | 60.42 MiB | 95 | 1: 0, 48: 0, 95: 0 | 0.0 |
| `Col·leccions/Cocina semana num. 74 Marzo 2016.pdf` | PDF | 16.25 MiB | 84 | 1: 145, 43: 2, 84: 0 | 49.0 |
| `Col·leccions/Gallina Blanca Cocinar con microondas.pdf` | PDF | 1.83 MiB | 32 | 1: 0, 17: 596, 32: 1083 | 559.7 |
| `Col·leccions/Gallina Blanca Del mar a la mesa.pdf` | PDF | 1.94 MiB | 22 | 1: 0, 12: 1015, 22: 717 | 577.3 |
| `Col·leccions/Gallina Blanca Las sopas.pdf` | PDF | 2.44 MiB | 35 | 1: 45, 18: 538, 35: 540 | 374.3 |
| `Col·leccions/Gallina Blanca Platos fáciles y económicos.pdf` | PDF | 1.01 MiB | 32 | 1: 0, 17: 1026, 32: 882 | 636.0 |
| `Col·leccions/Gallina Blanca Recetario Platos ligeros.pdf` | PDF | 708.4 KiB | 32 | 1: 35, 17: 1237, 32: 1072 | 781.3 |
| `Col·leccions/Gallina Blanca Recetario de ensaladas veraniegas.pdf` | PDF | 1.20 MiB | 27 | 1: 0, 14: 682, 27: 1169 | 617.0 |
| `Col·leccions/Gallina Blanca Recetario de las colaboradoras.pdf` | PDF | 1.36 MiB | 29 | 1: 0, 15: 599, 29: 711 | 436.7 |
| `Col·leccions/Gallina Blanca Recetario de otoño.pdf` | PDF | 393.8 KiB | 25 | 1: 35, 13: 1104, 25: 696 | 611.7 |
| `Col·leccions/Gallina Blanca Recetario de pescado.pdf` | PDF | 468.0 KiB | 24 | 1: 0, 13: 883, 24: 1250 | 711.0 |
| `Col·leccions/Gallina Blanca Recetario de picnic.pdf` | PDF | 844.1 KiB | 31 | 1: 35, 16: 812, 31: 1222 | 689.7 |
| `Col·leccions/Gallina Blanca Recetario de potajes y guisos.pdf` | PDF | 844.1 KiB | 36 | 1: 73, 19: 169, 36: 606 | 282.7 |
| `Col·leccions/Gallina Blanca Recetario de setas 2010.pdf` | PDF | 1.24 MiB | 60 | 1: 62, 31: 64, 60: 1035 | 387.0 |
| `Col·leccions/Gallina Blanca Recetario especial huevos.pdf` | PDF | 1.46 MiB | 33 | 1: 35, 17: 405, 33: 1188 | 542.7 |
| `Col·leccions/Gallina Blanca Recetario legumbres.pdf` | PDF | 625.1 KiB | 25 | 1: 50, 13: 925, 25: 967 | 647.3 |
| `Col·leccions/Gallina Blanca Recetario pescado azul.pdf` | PDF | 670.7 KiB | 30 | 1: 42, 16: 1155, 30: 1115 | 770.7 |
| `Col·leccions/Gallina Blanca Recetas para principiantes.pdf` | PDF | 2.07 MiB | 51 | 1: 0, 26: 906, 51: 590 | 498.7 |
| `Col·leccions/Gallina blanca Recetario de patatas (2).pdf` | PDF | 625.9 KiB | 24 | 1: 0, 13: 597, 24: 588 | 395.0 |
| `Col·leccions/Gallina blanca Recetario de patatas.pdf` | PDF | 625.9 KiB | 24 | 1: 0, 13: 597, 24: 588 | 395.0 |
| `Col·leccions/Gallina_Blanca_Aperitivos_para_deleitar.pdf` | PDF | 1.76 MiB | 47 | 1: 0, 24: 415, 47: 405 | 273.3 |
| `Col·leccions/Gaston Acurio en tu Cocina 02 - Pescados.pdf` | PDF | 7.94 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 03 - Maiz, arroz y otros cereales.pdf` | PDF | 8.47 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 04 - Aves.pdf` | PDF | 8.60 MiB | 24 | 1: 18, 13: 0, 24: 0 | 6.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 05 - Frejoles.pdf` | PDF | 9.04 MiB | 24 | 1: 38, 13: 0, 24: 0 | 12.7 |
| `Col·leccions/Gaston Acurio en tu Cocina 06 - Carnes rojas.pdf` | PDF | 8.90 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 07 - Tallarines y otras pastas.pdf` | PDF | 8.85 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 08 - Ajies, hierbas y vegetales.pdf` | PDF | 21.51 MiB | 24 | 1: 440, 13: 730, 24: 1951 | 1040.3 |
| `Col·leccions/Gaston Acurio en tu Cocina 09 - Mariscos.pdf` | PDF | 28.10 MiB | 24 | 1: 448, 13: 1323, 24: 1966 | 1245.7 |
| `Col·leccions/Gaston Acurio en tu Cocina 10 - Sopas, chupes y caldos.pdf` | PDF | 11.86 MiB | 24 | 1: 449, 13: 1478, 24: 1879 | 1268.7 |
| `Col·leccions/Gaston Acurio en tu Cocina 11 - Cócteles peruanos.pdf` | PDF | 10.34 MiB | 24 | 1: 448, 13: 510, 24: 1642 | 866.7 |
| `Col·leccions/Gaston Acurio en tu Cocina 12 - Postres.pdf` | PDF | 12.01 MiB | 24 | 1: 434, 13: 1148, 24: 1857 | 1146.3 |
| `Col·leccions/Gaston Acurio en tu Cocina 13 - Guisos y estofados.pdf` | PDF | 12.15 MiB | 24 | 1: 462, 13: 935, 24: 1804 | 1067.0 |
| `Col·leccions/Gaston Acurio en tu Cocina 14 - Piqueos.pdf` | PDF | 12.28 MiB | 24 | 1: 426, 13: 794, 24: 1896 | 1038.7 |
| `Col·leccions/Gaston Acurio en tu Cocina 15 - Recetas especiales.pdf` | PDF | 12.94 MiB | 24 | 1: 445, 13: 1522, 24: 1923 | 1296.7 |
| `Col·leccions/Gaston Acurio en tu cocina 01 - Papas.pdf` | PDF | 8.59 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Col·leccions/Lekue Mindfuld Eating.pdf` | PDF | 2.34 MiB | 26 | 1: 42, 14: 1530, 26: 13 | 528.3 |
| `Col·leccions/Lekue Nutrición y deporte.pdf` | PDF | 3.50 MiB | 25 | 1: 87, 13: 1789, 25: 13 | 629.7 |
| `Col·leccions/Lekue Recetas de supervivencia para principiantes.pdf` | PDF | 55.91 MiB | 93 | 1: 0, 47: 0, 93: 0 | 0.0 |
| `Col·leccions/Lekue Recetas para el día a día.pdf` | PDF | 1.68 MiB | 14 | 1: 25, 8: 473, 14: 13 | 170.3 |
| `Col·leccions/Lekue Saca partido a tu microondas.pdf` | PDF | 1.99 MiB | 24 | 1: 87, 13: 834, 24: 818 | 579.7 |
| `Col·leccions/Mariano Orzola 120 recetas navideñas Carnes y aves.epub` | EPUB | 319.9 KiB | 132 | 1: 5, 67: 1471, 132: 11 | 495.7 |
| `Col·leccions/Mariano Orzola 168 recetas americanas e italianas.epub` | EPUB | 166.7 KiB | 2 | 1: 34, 2: 260420 | 130227.0 |
| `Col·leccions/Mariano Orzola 168 recetas americanas y españolas.epub` | EPUB | 164.9 KiB | 2 | 1: 34, 2: 239362 | 119698.0 |
| `Col·leccions/Mariano Orzola 168 recetas americanas y francesas.epub` | EPUB | 171.4 KiB | 2 | 1: 34, 2: 260764 | 130399.0 |
| `Col·leccions/Mariano Orzola 168 recetas americanas y mediterráneas.epub` | EPUB | 165.2 KiB | 2 | 1: 38, 2: 251096 | 125567.0 |
| `Col·leccions/Mariano Orzola 168 recetas americanas y mexicanas.epub` | EPUB | 162.1 KiB | 2 | 1: 34, 2: 239025 | 119529.5 |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y francesas.epub` | EPUB | 167.5 KiB | 2 | 1: 34, 2: 255614 | 127824.0 |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y mediterráneas.epub` | EPUB | 285.9 KiB | 26 | 1: 5, 14: 16540, 26: 11 | 5518.7 |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y mexicanas.epub` | EPUB | 160.0 KiB | 2 | 1: 34, 2: 233875 | 116954.5 |
| `Col·leccions/Mariano Orzola 168 recetas con aceitunas y con huevo.epub` | EPUB | 158.6 KiB | 2 | 1: 37, 2: 219685 | 109861.0 |
| `Col·leccions/Mariano Orzola 168 recetas de ocasión Entrantes y postres.epub` | EPUB | 182.4 KiB | 2 | 1: 22, 2: 204674 | 102348.0 |
| `Col·leccions/Mariano Orzola 168 recetas españolas y francesas.epub` | EPUB | 300.0 KiB | 26 | 1: 5, 14: 13687, 26: 11 | 4567.7 |
| `Col·leccions/Mariano Orzola 168 recetas orientales e italianas.epub` | EPUB | 192.9 KiB | 2 | 1: 34, 2: 252867 | 126450.5 |
| `Col·leccions/Mariano Orzola 168 recetas orientales y francesas.epub` | EPUB | 197.7 KiB | 2 | 1: 34, 2: 253212 | 126623.0 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar budines y mousse.epub` | EPUB | 284.0 KiB | 27 | 1: 5, 14: 3063, 27: 11 | 1026.3 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar con aves y cordero.epub` | EPUB | 193.8 KiB | 2 | 1: 44, 2: 251516 | 125780.0 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar escabeches y dip.epub` | EPUB | 144.1 KiB | 2 | 1: 42, 2: 172544 | 86293.0 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar flanes y mousse.epub` | EPUB | 282.7 KiB | 27 | 1: 5, 14: 3063, 27: 11 | 1026.3 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar galletas y panes.epub` | EPUB | 188.8 KiB | 2 | 1: 42, 2: 239522 | 119782.0 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar omelettes y mousse.epub` | EPUB | 296.5 KiB | 27 | 1: 5, 14: 3063, 27: 11 | 1026.3 |
| `Col·leccions/Mariano Orzola 168 recetas para preparar tortas y café.epub` | EPUB | 261.5 KiB | 27 | 1: 5, 14: 2582, 27: 11 | 866.0 |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Pizzas premium.epub` | EPUB | 171.8 KiB | 31 | 1: 5, 16: 2139, 31: 11 | 718.3 |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Platos mediterráneos.epub` | EPUB | 159.9 KiB | 30 | 1: 5, 16: 706, 30: 11 | 240.7 |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Platos vegetarianos.epub` | EPUB | 161.5 KiB | 30 | 1: 5, 16: 1650, 30: 11 | 555.3 |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Postres helados.epub` | EPUB | 151.5 KiB | 30 | 1: 5, 16: 902, 30: 11 | 306.0 |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Postres livianos.epub` | EPUB | 155.7 KiB | 30 | 1: 5, 16: 1208, 30: 11 | 408.0 |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Aperitivos.epub` | EPUB | 301.8 KiB | 2 | 1: 33, 2: 44213 | 22123.0 |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Entrantes y ensaladas.epub` | EPUB | 246.2 KiB | 2 | 1: 44, 2: 50445 | 25244.5 |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Exquisiteces saladas.epub` | EPUB | 190.2 KiB | 32 | 1: 5, 17: 817, 32: 11 | 277.7 |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Segundos platos.epub` | EPUB | 329.5 KiB | 2 | 1: 38, 2: 51829 | 25933.5 |
| `Col·leccions/Mariano Orzola 20 recetas navideñas con mariscos.epub` | EPUB | 171.3 KiB | 32 | 1: 5, 17: 653, 32: 11 | 223.0 |
| `Col·leccions/Mariano Orzola 20 recetas para preparar postres livianos.epub` | EPUB | 178.5 KiB | 32 | 1: 5, 17: 1100, 32: 11 | 372.0 |
| `Col·leccions/Mariano Orzola 25 recetas livianas y sin grasa.epub` | EPUB | 270.6 KiB | 17 | 1: 5, 9: 16426, 17: 109 | 5513.3 |
| `Col·leccions/Mariano Orzola 72 recetas para prepara con cerdo.epub` | EPUB | 218.5 KiB | 82 | 1: 5, 42: 894, 82: 11 | 303.3 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar budines.epub` | EPUB | 206.6 KiB | 82 | 1: 5, 42: 781, 82: 11 | 265.7 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con arroz.epub` | EPUB | 205.0 KiB | 82 | 1: 5, 42: 857, 82: 11 | 291.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con aves.epub` | EPUB | 238.9 KiB | 82 | 1: 5, 42: 2084, 82: 11 | 700.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con canela.epub` | EPUB | 187.6 KiB | 82 | 1: 5, 42: 718, 82: 11 | 244.7 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con huevo.epub` | EPUB | 214.7 KiB | 82 | 1: 5, 42: 1106, 82: 11 | 374.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con marisco.epub` | EPUB | 218.0 KiB | 82 | 1: 5, 42: 1012, 82: 11 | 342.7 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con pescados.epub` | EPUB | 211.5 KiB | 82 | 1: 5, 42: 1217, 82: 11 | 411.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con pollo.epub` | EPUB | 260.8 KiB | 82 | 1: 5, 42: 872, 82: 11 | 296.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar guarniciones.epub` | EPUB | 220.6 KiB | 82 | 1: 5, 42: 1194, 82: 11 | 403.3 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar guisados.epub` | EPUB | 214.8 KiB | 82 | 1: 5, 42: 922, 82: 11 | 312.7 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar omelettes.epub` | EPUB | 205.4 KiB | 84 | 1: 5, 43: 1106, 84: 11 | 374.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar platos fríos.epub` | EPUB | 219.2 KiB | 82 | 1: 5, 42: 635, 82: 11 | 217.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar platos suculentos.epub` | EPUB | 219.6 KiB | 82 | 1: 5, 42: 680, 82: 11 | 232.0 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar postres helados.epub` | EPUB | 257.8 KiB | 82 | 1: 5, 42: 1071, 82: 11 | 362.3 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar sopas.epub` | EPUB | 200.4 KiB | 82 | 1: 5, 42: 1741, 82: 11 | 585.7 |
| `Col·leccions/Mariano Orzola 72 recetas para preparar tortas.epub` | EPUB | 241.0 KiB | 82 | 1: 5, 42: 1188, 82: 11 | 401.3 |
| `Col·leccions/Mariano Orzola 72 recetas para sorprender.epub` | EPUB | 233.6 KiB | 83 | 1: 5, 42: 1620, 83: 11 | 545.3 |
| `Col·leccions/Mariano Orzola 72 recetas saludables para cuidar tu silueta.epub` | EPUB | 194.1 KiB | 82 | 1: 5, 42: 1205, 82: 11 | 407.0 |
| `Col·leccions/Mariano Orzola 84 recetas con aceitunas.epub` | EPUB | 132.9 KiB | 2 | 1: 24, 2: 126449 | 63236.5 |
| `Col·leccions/Mariano Orzola 84 recetas con arroz.epub` | EPUB | 318.1 KiB | 2 | 1: 20, 2: 136331 | 68175.5 |
| `Col·leccions/Mariano Orzola 84 recetas con carne.epub` | EPUB | 313.0 KiB | 2 | 1: 20, 2: 138316 | 69168.0 |
| `Col·leccions/Mariano Orzola 84 recetas con cereales.epub` | EPUB | 123.8 KiB | 2 | 1: 23, 2: 132225 | 66124.0 |
| `Col·leccions/Mariano Orzola 84 recetas con frutos secos.epub` | EPUB | 145.2 KiB | 2 | 1: 26, 2: 135790 | 67908.0 |
| `Col·leccions/Mariano Orzola 84 recetas con huevo.epub` | EPUB | 139.0 KiB | 2 | 1: 20, 2: 122381 | 61200.5 |
| `Col·leccions/Mariano Orzola 84 recetas con pescado.epub` | EPUB | 304.2 KiB | 2 | 1: 23, 2: 120695 | 60359.0 |
| `Col·leccions/Mariano Orzola 84 recetas con semillas.epub` | EPUB | 125.9 KiB | 2 | 1: 23, 2: 128788 | 64405.5 |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina española.epub` | EPUB | 154.5 KiB | 2 | 1: 32, 2: 119499 | 59765.5 |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina francesa.epub` | EPUB | 140.6 KiB | 2 | 1: 32, 2: 140916 | 70474.0 |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina italiana.epub` | EPUB | 153.3 KiB | 2 | 1: 32, 2: 140579 | 70305.5 |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina mexicana.epub` | EPUB | 149.0 KiB | 2 | 1: 32, 2: 119159 | 59595.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar bebidas.epub` | EPUB | 299.1 KiB | 2 | 1: 32, 2: 60803 | 30417.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar budines.epub` | EPUB | 178.1 KiB | 2 | 1: 32, 2: 117192 | 58612.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar café y chocolate.epub` | EPUB | 325.1 KiB | 2 | 1: 41, 2: 98468 | 49254.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar comida rápida.epub` | EPUB | 312.1 KiB | 2 | 1: 38, 2: 128858 | 64448.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar comidas al wok.epub` | EPUB | 324.6 KiB | 2 | 1: 39, 2: 130820 | 65429.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar dip.epub` | EPUB | 131.9 KiB | 2 | 1: 28, 2: 92668 | 46348.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar ensaladas gourmets.epub` | EPUB | 122.4 KiB | 2 | 1: 42, 2: 103885 | 51963.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar galletas.epub` | EPUB | 313.0 KiB | 2 | 1: 33, 2: 116519 | 58276.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar pasteles salados.epub` | EPUB | 168.5 KiB | 18 | 1: 5, 10: 13040, 18: 11 | 4352.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar pizzas.epub` | EPUB | 305.0 KiB | 2 | 1: 31, 2: 136523 | 68277.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar platos fríos.epub` | EPUB | 320.3 KiB | 2 | 1: 37, 2: 106918 | 53477.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar postres.epub` | EPUB | 313.2 KiB | 2 | 1: 32, 2: 128532 | 64282.0 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar tapas.epub` | EPUB | 307.7 KiB | 2 | 1: 30, 2: 95529 | 47779.5 |
| `Col·leccions/Mariano Orzola 84 recetas para preparar tartas dulces.epub` | EPUB | 193.4 KiB | 2 | 1: 38, 2: 138134 | 69086.0 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con chocolate.epub` | EPUB | 146.1 KiB | 17 | 1: 5, 9: 16168, 17: 11 | 5394.7 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con fibra.epub` | EPUB | 139.4 KiB | 18 | 1: 5, 10: 12756, 18: 11 | 4257.3 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con legumbres.epub` | EPUB | 270.4 KiB | 18 | 1: 5, 10: 14345, 18: 11 | 4787.0 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de comida express.epub` | EPUB | 138.3 KiB | 17 | 1: 5, 9: 17217, 17: 11 | 5744.3 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de invierno.epub` | EPUB | 131.6 KiB | 17 | 1: 5, 9: 11817, 17: 11 | 3944.3 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de postres del mundo.pdf` | PDF | 751.2 KiB | 195 | 1: 0, 98: 531, 195: 0 | 177.0 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas frescas.epub` | EPUB | 133.4 KiB | 18 | 1: 5, 10: 10736, 18: 11 | 3584.0 |
| `Col·leccions/Mariano Orzola Selección de 84 recetas para guarniciones.epub` | EPUB | 295.4 KiB | 18 | 1: 5, 10: 10654, 18: 11 | 3556.7 |
| `Col·leccions/Mariano Orzolas 20 recetas gourmets Pasteles hojaldres.epub` | EPUB | 162.4 KiB | 30 | 1: 5, 16: 979, 30: 11 | 331.7 |
| `Col·leccions/Mariano_Orzola_100_recetas_navideñas.epub` | EPUB | 313.8 KiB | 2 | 1: 84, 2: 158971 | 79527.5 |
| `Col·leccions/Mariano_Orzola_168_recetas_de_ocasión (2).epub` | EPUB | 197.8 KiB | 2 | 1: 22, 2: 235377 | 117699.5 |
| `Col·leccions/Mariano_Orzola_168_recetas_de_ocasión.epub` | EPUB | 195.7 KiB | 2 | 1: 22, 2: 223106 | 111564.0 |
| `Col·leccions/Mariano_Orzola_168_recetas_para (2).epub` | EPUB | 156.2 KiB | 2 | 1: 54, 2: 226346 | 113200.0 |
| `Col·leccions/Mariano_Orzola_168_recetas_para (3).epub` | EPUB | 182.7 KiB | 2 | 1: 49, 2: 231772 | 115910.5 |
| `Col·leccions/Mariano_Orzola_168_recetas_para (4).epub` | EPUB | 173.7 KiB | 2 | 1: 48, 2: 183998 | 92023.0 |
| `Col·leccions/Mariano_Orzola_168_recetas_para.epub` | EPUB | 194.1 KiB | 2 | 1: 45, 2: 239338 | 119691.5 |
| `Col·leccions/Mariano_Orzola_20_recetas_navideñas (2).epub` | EPUB | 181.4 KiB | 32 | 1: 5, 17: 862, 32: 11 | 292.7 |
| `Col·leccions/Mariano_Orzola_20_recetas_navideñas.epub` | EPUB | 179.2 KiB | 32 | 1: 5, 17: 1037, 32: 11 | 351.0 |
| `Col·leccions/Mariano_Orzola_35_recetas_navideñas.epub` | EPUB | 187.9 KiB | 47 | 1: 5, 24: 818, 47: 11 | 278.0 |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas (2).epub` | EPUB | 232.2 KiB | 72 | 1: 5, 37: 931, 72: 11 | 315.7 |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas (3).epub` | EPUB | 356.8 KiB | 74 | 1: 5, 38: 2525, 74: 101 | 877.0 |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas.epub` | EPUB | 229.5 KiB | 72 | 1: 5, 37: 1406, 72: 11 | 474.0 |
| `Col·leccions/Mariano_Orzola_72_recetas_para_preparar.epub` | EPUB | 203.6 KiB | 71 | 1: 5, 36: 1071, 71: 11 | 362.3 |
| `Col·leccions/Mariano_Orzola_84_recetas_para_preparar (2).epub` | EPUB | 192.2 KiB | 2 | 1: 55, 2: 129588 | 64821.5 |
| `Col·leccions/Mariano_Orzola_84_recetas_para_preparar.epub` | EPUB | 124.6 KiB | 2 | 1: 55, 2: 114252 | 57153.5 |
| `Col·leccions/Mariano_Orzola_Selección_de_84_recetas.epub` | EPUB | 216.1 KiB | 19 | 1: 5, 10: 2405, 19: 11 | 807.0 |
| `Col·leccions/Pescanova Anguriñas.pdf` | PDF | 7.34 MiB | 49 | 1: 0, 25: 0, 49: 0 | 0.0 |
| `Col·leccions/Pescanova La cocina del pescado.pdf` | PDF | 3.42 MiB | 7 | 1: 55, 4: 1862, 7: 1249 | 1055.3 |
| `Col·leccions/Pescanova Langostinos.pdf` | PDF | 4.83 MiB | 35 | 1: 0, 18: 0, 35: 0 | 0.0 |
| `Col·leccions/Pescanova Merluza Pescanova en microondas.pdf` | PDF | 6.65 MiB | 45 | 1: 0, 23: 0, 45: 0 | 0.0 |
| `Col·leccions/Pescanova Merluza en microondas.pdf` | PDF | 2.27 MiB | 12 | 1: 0, 7: 0, 12: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario con Omega 3.pdf` | PDF | 7.05 MiB | 13 | 1: 0, 7: 1020, 13: 1774 | 931.3 |
| `Col·leccions/Pescanova Recetario de Semana Santa.pdf` | PDF | 1.43 MiB | 11 | 1: 72, 6: 1111, 11: 1493 | 892.0 |
| `Col·leccions/Pescanova Recetario de bacalao.pdf` | PDF | 12.11 MiB | 13 | 1: 0, 7: 0, 13: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario de cuaresma 2012.pdf` | PDF | 5.18 MiB | 11 | 1: 42, 6: 1005, 11: 1048 | 698.3 |
| `Col·leccions/Pescanova Recetario de merluza.pdf` | PDF | 2.27 MiB | 12 | 1: 0, 7: 0, 12: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario de navidad 2009.pdf` | PDF | 1.49 MiB | 17 | 1: 0, 9: 0, 17: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario de navidad 2011.pdf` | PDF | 1.13 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario de navidad 2012.pdf` | PDF | 3.32 MiB | 6 | 1: 45, 4: 2709, 6: 3114 | 1956.0 |
| `Col·leccions/Pescanova Recetario de pescado rebozado y empanado.pdf` | PDF | 419.7 KiB | 6 | 1: 925, 4: 1447, 6: 1102 | 1158.0 |
| `Col·leccions/Pescanova Recetario de rabas y chopirones.pdf` | PDF | 8.65 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Col·leccions/Pescanova Recetario de salmón ahumado.pdf` | PDF | 644.9 KiB | 2 | 1: 0, 2: 0 | 0.0 |
| `Col·leccions/Pescanova Recetas de Tallarimis.pdf` | PDF | 4.71 MiB | 6 | 1: 0, 4: 0, 6: 0 | 0.0 |
| `Col·leccions/Pescanova Recetas de anguriñas y surimi.pdf` | PDF | 794.2 KiB | 6 | 1: 909, 4: 2217, 6: 37 | 1054.3 |
| `Col·leccions/Pescanova Recetas de surimi para sorprender.pdf` | PDF | 5.10 MiB | 19 | 1: 0, 10: 0, 19: 0 | 0.0 |
| `Col·leccions/Pescanova Recetas ligeras.pdf` | PDF | 2.35 MiB | 6 | 1: 33, 4: 1211, 6: 1364 | 869.3 |
| `Col·leccions/cocina fácil lecturas num. 124.pdf` | PDF | 59.98 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 127.pdf` | PDF | 63.97 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 133.pdf` | PDF | 63.33 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 135.pdf` | PDF | 63.67 MiB | 67 | 1: 0, 34: 0, 67: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 150.pdf` | PDF | 60.13 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 153.pdf` | PDF | 58.67 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 154.pdf` | PDF | 58.22 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 156.pdf` | PDF | 61.60 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 182.pdf` | PDF | 14.92 MiB | 61 | 1: 0, 31: 0, 61: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 203.pdf` | PDF | 31.39 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 204.pdf` | PDF | 100.07 MiB | 68 | 1: 3, 35: 3, 68: 3 | 3.0 |
| `Col·leccions/cocina fácil lecturas num. 209.pdf` | PDF | 12.41 MiB | 68 | 1: 0, 35: 1373, 68: 1 | 458.0 |
| `Col·leccions/cocina fácil lecturas num. 210.pdf` | PDF | 19.46 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 215.pdf` | PDF | 19.53 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 217.pdf` | PDF | 31.76 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 218.pdf` | PDF | 37.00 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 220.pdf` | PDF | 17.75 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 221.pdf` | PDF | 22.03 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 222.pdf` | PDF | 19.40 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 223.pdf` | PDF | 27.08 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 224.pdf` | PDF | 21.60 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 225.pdf` | PDF | 19.77 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 226.pdf` | PDF | 15.73 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 229.pdf` | PDF | 21.12 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 232.pdf` | PDF | 29.56 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 234.pdf` | PDF | 13.45 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 235.pdf` | PDF | 23.77 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 236.pdf` | PDF | 82.38 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 237.pdf` | PDF | 61.43 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 238.pdf` | PDF | 25.72 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 239.pdf` | PDF | 27.06 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 240.pdf` | PDF | 25.25 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 242.pdf` | PDF | 18.64 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 243.pdf` | PDF | 15.52 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Col·leccions/cocina fácil lecturas num. 244.pdf` | PDF | 35.25 MiB | 68 | 1: 288, 35: 1370, 68: 0 | 552.7 |
| `Col·leccions/cocina fácil lecturas num. 89.pdf` | PDF | 100.19 MiB | 164 | 1: 0, 83: 0, 164: 0 | 0.0 |
| `Cuina del mon/2019-09-01 Louisiana Cookin.pdf` | PDF | 45.98 MiB | 102 | 1: 0, 52: 341, 102: 0 | 113.7 |
| `Cuina del mon/40 Menus sencillamente deliciosos.pdf` | PDF | 7.70 MiB | 28 | 1: 98, 15: 99, 28: 99 | 98.7 |
| `Cuina del mon/@malu320 Gastronomia-Peruana.pdf` | PDF | 5.04 MiB | 16 | 1: 1, 9: 0, 16: 0 | 0.3 |
| `Cuina del mon/A cociña galega.pdf` | PDF | 136.70 MiB | 171 | 1: 0, 86: 0, 171: 0 | 0.0 |
| `Cuina del mon/Alimentos Del Norte.mobi` | MOBI | 2.31 MiB | n/a | n/a | n/a |
| `Cuina del mon/Andalucia destapa Andalucia.epub` | EPUB | 9.62 MiB | 2 | 1: 5, 2: 624 | 314.5 |
| `Cuina del mon/Aurora Sonia Montesino Cocinas mestizas de Chile.pdf` | PDF | 6.80 MiB | 132 | 1: 362, 67: 58, 132: 671 | 363.7 |
| `Cuina del mon/Bartolo Mutari Cocina siciliana.pdf` | PDF | 3.78 MiB | 247 | 1: 52, 124: 488, 247: 52 | 197.3 |
| `Cuina del mon/Biblioteca Metropoli Nuestra cocina País vasco.pdf` | PDF | 3.92 MiB | 108 | 1: 0, 55: 1345, 108: 0 | 448.3 |
| `Cuina del mon/COCINA ASIÁTICA.pdf` | PDF | 1.68 MiB | 15 | 1: 193, 8: 799, 15: 431 | 474.3 |
| `Cuina del mon/COCINA ESPAÑOLA. VOL I.pdf` | PDF | 1.77 MiB | 18 | 1: 184, 10: 2194, 18: 778 | 1052.0 |
| `Cuina del mon/COCINA ESPAÑOLA. VOL II.pdf` | PDF | 1.75 MiB | 17 | 1: 188, 9: 1747, 17: 1259 | 1064.7 |
| `Cuina del mon/COMIDA SALUDABLE ESTILO JAPONES.pdf` | PDF | 3.44 MiB | 49 | 1: 104, 25: 1377, 49: 0 | 493.7 |
| `Cuina del mon/Camargo Rain La cocina española de siempre.epub` | EPUB | 460.6 KiB | 346 | 1: 61, 174: 681, 346: 1076 | 606.0 |
| `Cuina del mon/Carl Jan Clásicos de la cocina sueca.pdf` | PDF | 2.45 MiB | 52 | 1: 0, 27: 0, 52: 885 | 295.0 |
| `Cuina del mon/Carmen Gil Por la cocina española.pdf` | PDF | 10.64 MiB | 9 | 1: 72, 5: 730, 9: 1153 | 651.7 |
| `Cuina del mon/Chef Oropeza Comida atipica mexicana.pdf` | PDF | 4.69 MiB | 52 | 1: 0, 27: 2, 52: 0 | 0.7 |
| `Cuina del mon/Classiche italiane salse per accompagnare.pdf` | PDF | 4.01 MiB | 53 | 1: 0, 27: 0, 53: 0 | 0.0 |
| `Cuina del mon/Club de guisanderas El libro de las guisanderas de Asturias.pdf` | PDF | 14.94 MiB | 68 | 1: 23, 35: 24, 68: 24 | 23.7 |
| `Cuina del mon/Cocina America del Sur (2).pdf` | PDF | 4.72 MiB | 28 | 1: 0, 15: 0, 28: 0 | 0.0 |
| `Cuina del mon/Cocina America del Sur.pdf` | PDF | 4.72 MiB | 28 | 1: 0, 15: 0, 28: 0 | 0.0 |
| `Cuina del mon/Cocina Francesa.pdf` | PDF | 15.52 MiB | 169 | 1: 0, 85: 0, 169: 0 | 0.0 |
| `Cuina del mon/Cocina Gallega.pdf` | PDF | 6.13 MiB | 157 | 1: 2231, 79: 2575, 157: 3211 | 2672.3 |
| `Cuina del mon/Cocina Italiana.pdf` | PDF | 8.85 MiB | 94 | 1: 189, 48: 1189, 94: 2854 | 1410.7 |
| `Cuina del mon/Cocina Vasca Jorge Beramendi - Desconocido.pdf` | PDF | 9.29 MiB | 80 | 1: 0, 41: 0, 80: 0 | 0.0 |
| `Cuina del mon/Cocina china I paso a paso.pdf` | PDF | 8.40 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Cuina del mon/Cocina cubana 5 siglos de tradición.pdf` | PDF | 4.08 MiB | 361 | 1: 0, 181: 780, 361: 0 | 260.0 |
| `Cuina del mon/Cocina italiana.epub` | EPUB | 20.3 KiB | 1 | 1: 41875 | 41875.0 |
| `Cuina del mon/Cocina japonesa paso a paso.pdf` | PDF | 8.05 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Cuina del mon/Cocina mediterránea paso a paso.pdf` | PDF | 7.87 MiB | 54 | 1: 0, 28: 0, 54: 0 | 0.0 |
| `Cuina del mon/Cocina mexicana paso a paso.pdf` | PDF | 7.77 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Cuina del mon/Cocina tradicional de la sierra de Cádiz.epub` | EPUB | 21.01 MiB | 2 | 1: 5, 2: 33 | 19.0 |
| `Cuina del mon/Cocina árabe I paso a paso.pdf` | PDF | 8.18 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Cuina del mon/Comida china.pdf` | PDF | 6.79 MiB | 32 | 1: 0, 17: 0, 32: 0 | 0.0 |
| `Cuina del mon/Círculo de Lectores El gran libro de la cocina ecuatoriana.pdf` | PDF | 13.06 MiB | 105 | 1: 0, 53: 0, 105: 0 | 0.0 |
| `Cuina del mon/De rechupete Empanadas gallegas.pdf` | PDF | 1.24 MiB | 38 | 1: 18, 20: 625, 38: 706 | 449.7 |
| `Cuina del mon/Editorial Blume Cocina tailandesa.epub` | EPUB | 6.8 KiB | 1 | 1: 10994 | 10994.0 |
| `Cuina del mon/Editorial Espasa El gran libro de la cocina gallega.pdf` | PDF | 4.26 MiB | 982 | 1: 0, 492: 225, 982: 0 | 75.0 |
| `Cuina del mon/Editorial konemann Cocina japonesa y coreana.pdf` | PDF | 40.17 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Cuina del mon/Editorial_Cocinamos_La_cocina_española.pdf` | PDF | 4.49 MiB | 36 | 1: 24, 19: 25, 36: 25 | 24.7 |
| `Cuina del mon/El gran libro del wok.pdf` | PDF | 58.99 MiB | 65 | 1: 0, 33: 0, 65: 0 | 0.0 |
| `Cuina del mon/Emi Kazuko Comida japonesa.pdf` | PDF | 29.09 MiB | 187 | 1: 30, 94: 3490, 187: 0 | 1173.3 |
| `Cuina del mon/Empanadas Gallegas.pdf` | PDF | 1.24 MiB | 38 | 1: 18, 20: 625, 38: 706 | 449.7 |
| `Cuina del mon/Encarnación_Lenza_Recetas_tradicionales.mobi` | MOBI | 9.14 MiB | n/a | n/a | n/a |
| `Cuina del mon/Escapada a La India.pdf` | PDF | 1.57 MiB | 22 | 1: 21, 12: 21, 22: 21 | 21.0 |
| `Cuina del mon/Fernando Ordoñez La gran cocina peruana.pdf` | PDF | 5.24 MiB | 268 | 1: 0, 135: 1845, 268: 1287 | 1044.0 |
| `Cuina del mon/Festín Griego (2).pdf` | PDF | 1.38 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Cuina del mon/Festín Griego.pdf` | PDF | 1.38 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Cuina del mon/Fuga in India.pdf` | PDF | 6.32 MiB | 70 | 1: 0, 36: 0, 70: 0 | 0.0 |
| `Cuina del mon/Gabriele Napolitano Entradas italianas.epub` | EPUB | 101.6 KiB | 35 | 1: 5, 18: 325, 35: 327 | 219.0 |
| `Cuina del mon/Gastronomía aragonesa.pdf` | PDF | 1.70 MiB | 20 | 1: 7, 11: 3235, 20: 45 | 1095.7 |
| `Cuina del mon/Gobierno de Aragón Hoy comemos sin gluten.pdf` | PDF | 1.03 MiB | 145 | 1: 78, 73: 1185, 145: 0 | 421.0 |
| `Cuina del mon/Graciela Bajraj Las 105 recetas más famosas del mundo.epub` | EPUB | 3.04 MiB | 112 | 1: 5, 57: 1445, 112: 946 | 798.7 |
| `Cuina del mon/Gran menú americano.pdf` | PDF | 2.01 MiB | 19 | 1: 0, 10: 0, 19: 0 | 0.0 |
| `Cuina del mon/Hawwaiian Pool Party.pdf` | PDF | 4.34 MiB | 18 | 1: 0, 10: 0, 18: 0 | 0.0 |
| `Cuina del mon/Instituto Culinario de México Cocina árabe.pdf` | PDF | 1.89 MiB | 50 | 1: 12, 26: 1066, 50: 437 | 505.0 |
| `Cuina del mon/Japón es más que sushi.pdf` | PDF | 9.73 MiB | 101 | 1: 21, 51: 21, 101: 21 | 21.0 |
| `Cuina del mon/Jaume Fàbrega La cocina de Menorca.pdf` | PDF | 54.36 MiB | 118 | 1: 0, 60: 2133, 118: 133 | 755.3 |
| `Cuina del mon/Joanna Farrow Cocina griega.pdf` | PDF | 81.44 MiB | 97 | 1: 0, 49: 1760, 97: 532 | 764.0 |
| `Cuina del mon/Jornadas gastronómicas de Castilla y León.pdf` | PDF | 1.97 MiB | 24 | 1: 85, 13: 1095, 24: 27 | 402.3 |
| `Cuina del mon/José Aguilera La cocina de Almería.pdf` | PDF | 9.06 MiB | 87 | 1: 15, 44: 15, 87: 15 | 15.0 |
| `Cuina del mon/LIBRO+ARROCES+DE+ESPAÑA.pdf` | PDF | 14.64 MiB | 52 | 1: 112, 27: 0, 52: 40 | 50.7 |
| `Cuina del mon/La Verdadera Cocina Criolla.pdf` | PDF | 54.72 MiB | 65 | 1: 18, 33: 18, 65: 18 | 18.0 |
| `Cuina del mon/La cocina japonesa de Harumi.PDF` | PDF | 24.09 MiB | 165 | 1: 0, 83: 0, 165: 0 | 0.0 |
| `Cuina del mon/La cocina tradicional en Chiclana.pdf` | PDF | 1.81 MiB | 123 | 1: 0, 62: 490, 123: 157 | 215.7 |
| `Cuina del mon/Las cocineras de Sils.pdf` | PDF | 26.30 MiB | 236 | 1: 197, 119: 1660, 236: 981 | 946.0 |
| `Cuina del mon/Las recetas de Isabella Cocina austro-hungara.epub` | EPUB | 8.32 MiB | 58 | 1: 5, 30: 254, 58: 2209 | 822.7 |
| `Cuina del mon/Libro de cocina tradicional del sur de Italia.epub` | EPUB | 95.2 KiB | 17 | 1: 5, 9: 1709, 17: 939 | 884.3 |
| `Cuina del mon/Lo mejor de la comida árabe.epub` | EPUB | 3.02 MiB | 2 | 1: 5, 2: 27 | 16.0 |
| `Cuina del mon/MARRUECOS.pdf` | PDF | 1.70 MiB | 14 | 1: 210, 8: 472, 14: 434 | 372.0 |
| `Cuina del mon/Maria Adela Díaz Cocina murciana.pdf` | PDF | 14.96 MiB | 79 | 1: 0, 40: 0, 79: 0 | 0.0 |
| `Cuina del mon/Maria José Martin Comida tradicional española.pdf` | PDF | 3.00 MiB | 22 | 1: 0, 12: 0, 22: 0 | 0.0 |
| `Cuina del mon/Miriam Becker Pasión por la cocina judia.pdf` | PDF | 26.66 MiB | 89 | 1: 0, 45: 0, 89: 0 | 0.0 |
| `Cuina del mon/Málaga Recetas populares.pdf` | PDF | 1.88 MiB | 55 | 1: 165, 28: 1474, 55: 1662 | 1100.3 |
| `Cuina del mon/México está de fiesta.pdf` | PDF | 19.74 MiB | 89 | 1: 0, 45: 0, 89: 0 | 0.0 |
| `Cuina del mon/Nora Pérez Salsas taqueras mexicanas.epub` | EPUB | 113.8 KiB | 21 | 1: 5, 11: 217, 21: 542 | 254.7 |
| `Cuina del mon/Nuestro libro de cocina vasca.pdf` | PDF | 2.06 MiB | 334 | 1: 0, 168: 1521, 334: 0 | 507.0 |
| `Cuina del mon/Osno Monto Empanada criolla y picadillo llanero.epub` | EPUB | 2.57 MiB | 3 | 1: 5, 2: 132, 3: 9420 | 3185.7 |
| `Cuina del mon/Otilia Kusmin Delicias de la cocina rusa.pdf` | PDF | 17.46 MiB | 195 | 1: 0, 98: 0, 195: 0 | 0.0 |
| `Cuina del mon/Pablo Castro La Cocina de la Serranía de Ronda.pdf` | PDF | 9.01 MiB | 107 | 1: 413, 54: 170, 107: 3 | 195.3 |
| `Cuina del mon/Pablo Castro La cocina del entorno de los embalses.pdf` | PDF | 8.70 MiB | 108 | 1: 466, 55: 0, 108: 0 | 155.3 |
| `Cuina del mon/Panaderia Mexicana 01.pdf` | PDF | 3.95 MiB | 23 | 1: 0, 12: 0, 23: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 02.pdf` | PDF | 4.56 MiB | 23 | 1: 0, 12: 0, 23: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 03.pdf` | PDF | 4.44 MiB | 25 | 1: 0, 13: 0, 25: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 04.pdf` | PDF | 5.20 MiB | 22 | 1: 0, 12: 0, 22: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 05.pdf` | PDF | 4.19 MiB | 26 | 1: 0, 14: 0, 26: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 06.pdf` | PDF | 3.93 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 07.pdf` | PDF | 4.66 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 08.pdf` | PDF | 6.27 MiB | 26 | 1: 0, 14: 0, 26: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 09.pdf` | PDF | 4.03 MiB | 25 | 1: 0, 13: 0, 25: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 10.pdf` | PDF | 3.33 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 11.pdf` | PDF | 3.58 MiB | 29 | 1: 0, 15: 0, 29: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 12.pdf` | PDF | 3.03 MiB | 25 | 1: 0, 13: 0, 25: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 13.pdf` | PDF | 4.36 MiB | 26 | 1: 0, 14: 0, 26: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 14.pdf` | PDF | 4.29 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 15.pdf` | PDF | 3.69 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 16.pdf` | PDF | 3.67 MiB | 24 | 1: 0, 13: 0, 24: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 17.pdf` | PDF | 4.06 MiB | 22 | 1: 0, 12: 0, 22: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 18.pdf` | PDF | 3.71 MiB | 23 | 1: 0, 12: 0, 23: 0 | 0.0 |
| `Cuina del mon/Panaderia Mexicana 20.pdf` | PDF | 3.36 MiB | 21 | 1: 0, 11: 0, 21: 0 | 0.0 |
| `Cuina del mon/Panadería Mexicana 19.PDF` | PDF | 3.70 MiB | 23 | 1: 0, 12: 0, 23: 0 | 0.0 |
| `Cuina del mon/Plan andaluz de salud Cocina andaluza Dieta mediterránea.pdf` | PDF | 1.47 MiB | 111 | 1: 90, 56: 1194, 111: 50 | 444.7 |
| `Cuina del mon/RECETAS TIPICAS GRIEGAS.pdf` | PDF | 347.6 KiB | 4 | 1: 35, 3: 2303, 4: 2785 | 1707.7 |
| `Cuina del mon/REVISTASGOLD35K.Maxi  Marzo 2019.pdf` | PDF | 16.74 MiB | 80 | 1: 0, 41: 0, 80: 0 | 0.0 |
| `Cuina del mon/Recetario cocina japonesa.pdf` | PDF | 665.8 KiB | 146 | 1: 2257, 74: 2317, 146: 1065 | 1879.7 |
| `Cuina del mon/Recetario de Cocina Asiatica.pdf` | PDF | 29.39 MiB | 94 | 1: 0, 48: 0, 94: 0 | 0.0 |
| `Cuina del mon/Recetario de Cocina Gallega.pdf` | PDF | 1.82 MiB | 52 | 1: 0, 27: 1851, 52: 306 | 719.0 |
| `Cuina del mon/Recetario tradicional aragonés del siglo XXI (2).pdf` | PDF | 4.67 MiB | 96 | 1: 74, 49: 676, 96: 0 | 250.0 |
| `Cuina del mon/Recetario tradicional aragonés del siglo XXI.pdf` | PDF | 2.73 MiB | 98 | 1: 0, 50: 676, 98: 0 | 225.3 |
| `Cuina del mon/Recetas Cocina Arabé MArroqui.pdf` | PDF | 8.20 MiB | 12 | 1: 74, 7: 1803, 12: 35 | 637.3 |
| `Cuina del mon/Recetas de cocina arabe marroquí.pdf` | PDF | 8.20 MiB | 12 | 1: 74, 7: 1803, 12: 35 | 637.3 |
| `Cuina del mon/Recetas de cocina argentina.pdf` | PDF | 15.02 MiB | 2843 | 1: 768, 1422: 1248, 2843: 60 | 692.0 |
| `Cuina del mon/Recetas mexicanas.epub` | EPUB | 23.0 KiB | 1 | 1: 80023 | 80023.0 |
| `Cuina del mon/Recetas mexicanas.pdf` | PDF | 4.15 MiB | 36 | 1: 48, 19: 1217, 36: 29 | 431.3 |
| `Cuina del mon/Recetas sabrosas Cocina china.epub` | EPUB | 4.41 MiB | 2 | 1: 5, 2: 12 | 8.5 |
| `Cuina del mon/SABORES DE ITALIA.pdf` | PDF | 1.38 MiB | 13 | 1: 189, 7: 1781, 13: 319 | 763.0 |
| `Cuina del mon/Saboreando Asturias.pdf` | PDF | 3.66 MiB | 95 | 1: 84, 48: 1735, 95: 11 | 610.0 |
| `Cuina del mon/Sabores de Chile para el mundo.pdf` | PDF | 10.73 MiB | 136 | 1: 72, 69: 73, 136: 74 | 73.0 |
| `Cuina del mon/Sabores del mundo Cocina japonesa paso a paso.pdf` | PDF | 14.35 MiB | 94 | 1: 0, 48: 0, 94: 0 | 0.0 |
| `Cuina del mon/Salah Jamal Aroma arabe.epub` | EPUB | 742.9 KiB | 83 | 1: 5, 42: 3838, 83: 444 | 1429.0 |
| `Cuina del mon/Supermaxi Italia al dente.pdf` | PDF | 10.28 MiB | 134 | 1: 0, 68: 726, 134: 0 | 242.0 |
| `Cuina del mon/TUTTO BACCALA BIMBY.pdf` | PDF | 1.63 MiB | 39 | 1: 83, 20: 0, 39: 682 | 255.0 |
| `Cuina del mon/TUTTO POLPETTONI BIMBY.pdf` | PDF | 3.01 MiB | 65 | 1: 85, 33: 1215, 65: 1383 | 894.3 |
| `Cuina del mon/Taste_of_Persia_A_Cook’s_Travels_Through_Armenia,_Azerbaijan,_Georgia.pdf` | PDF | 51.56 MiB | 401 | 1: 17, 201: 255, 401: 1018 | 430.0 |
| `Cuina del mon/Todo sobre la cocina argentina server gardel.pdf` | PDF | 29.07 MiB | 2567 | 1: 988, 1284: 1209, 2567: 917 | 1038.0 |
| `Cuina del mon/Tutto bavarese.pdf` | PDF | 1.83 MiB | 42 | 1: 83, 22: 1310, 42: 1046 | 813.0 |
| `Cuina del mon/Tutto frittata.pdf` | PDF | 2.98 MiB | 51 | 1: 83, 26: 989, 51: 843 | 638.3 |
| `Cuina del mon/Tutto ravioli.pdf` | PDF | 2.53 MiB | 62 | 1: 82, 32: 1401, 62: 1391 | 958.0 |
| `Cuina del mon/Tutto romagnolo.pdf` | PDF | 1.55 MiB | 22 | 1: 85, 12: 800, 22: 1347 | 744.0 |
| `Cuina del mon/VIVA MÉXICO.pdf` | PDF | 1.55 MiB | 15 | 1: 192, 8: 1606, 15: 453 | 750.3 |
| `Cuina del mon/Vinaròs, la gastronomia.pdf` | PDF | 1.96 MiB | 35 | 1: 43, 18: 2349, 35: 203 | 865.0 |
| `Cuina del mon/Vincenzo y Rafaella Fabrocini La dieta mediterránea.pdf` | PDF | 854.6 KiB | 184 | 1: 0, 93: 1107, 184: 37 | 381.3 |
| `Cuina del mon/Viva México.doc` | DOC | 7.36 MiB | 13 | 1: 25 | 1.9 |
| `Cuina del mon/Yuka Kaneko Las mejores recetas de sushi.pdf` | PDF | 47.16 MiB | 85 | 1: 0, 43: 0, 85: 0 | 0.0 |
| `Cuina del mon/asia.pdf` | PDF | 8.88 MiB | 78 | 1: 21, 40: 21, 78: 21 | 21.0 |
| `Cuina del mon/comida de boteco.pdf` | PDF | 615.8 KiB | 69 | 1: 70, 35: 955, 69: 1255 | 760.0 |
| `Cuina del mon/el-gran-libro-de-la-cocina-italiana.pdf` | PDF | 63.90 MiB | 288 | 1: 0, 145: 0, 288: 0 | 0.0 |
| `Cuina del mon/recetario_empanadas_gallegas.pdf` | PDF | 1.24 MiB | 38 | 1: 18, 20: 625, 38: 706 | 449.7 |
| `Cuina del mon/recetariococina-multicultural.pdf` | PDF | 11.57 MiB | 103 | 1: 97, 52: 815, 103: 45 | 319.0 |
| `Cuina del mon/recetas-cocina-italiana-web.pdf` | PDF | 852.1 KiB | 45 | 1: 26, 23: 2635, 45: 311 | 990.7 |
| `Cuina del mon/recetas-halloween.pdf` | PDF | 17.18 MiB | 32 | 1: 0, 17: 1784, 32: 0 | 594.7 |
| `Cuina del mon/Índia.pdf` | PDF | 27.63 MiB | 158 | 1: 0, 80: 0, 158: 0 | 0.0 |
| `Cultura culinaria/Atlas ilustrado de plantas medicinales y curativas.epub` | EPUB | 17.85 MiB | 253 | 1: 5, 127: 2903, 253: 49 | 985.7 |
| `Cultura culinaria/COCINA AL VAPOR.pdf` | PDF | 1.47 MiB | 15 | 1: 257, 8: 873, 15: 538 | 556.0 |
| `Cultura culinaria/Carlos Abehsera Cocinar sin carbohidratos.epub` | EPUB | 9.68 MiB | 159 | 1: 5, 80: 25, 159: 25 | 18.3 |
| `Cultura culinaria/Cocina al instante Cocina bajo cero.pdf` | PDF | 2.93 MiB | 60 | 1: 0, 31: 0, 60: 0 | 0.0 |
| `Cultura culinaria/Dr Álvaro Campillo Alimentación para deportistas.epub` | EPUB | 1.86 MiB | 23 | 1: 5, 12: 1690, 23: 72 | 589.0 |
| `Cultura culinaria/Editorial Grijalbo Guia de la verdura.pdf` | PDF | 29.15 MiB | 128 | 1: 0, 65: 0, 128: 0 | 0.0 |
| `Cultura culinaria/Editorial_Everest_El_gran_libro.pdf` | PDF | 125.96 MiB | 258 | 1: 0, 130: 0, 258: 0 | 0.0 |
| `Cultura culinaria/El libro de la cocina natural.pdf` | PDF | 68.51 MiB | 178 | 1: 0, 90: 0, 178: 0 | 0.0 |
| `Cultura culinaria/El_Sabor_en_Familia_Antología_de.pdf` | PDF | 7.92 MiB | 90 | 1: 0, 46: 0, 90: 0 | 0.0 |
| `Cultura culinaria/Elisabeth Lambert Enciclopedia de las especias.pdf` | PDF | 31.30 MiB | 274 | 1: 195, 138: 4618, 274: 0 | 1604.3 |
| `Cultura culinaria/Enciclopedia de las hierbas mágicas.pdf` | PDF | 105.1 KiB | 23 | 1: 505, 12: 2247, 23: 1736 | 1496.0 |
| `Cultura culinaria/Escuela_Superior_de_Hostereria_de.pdf` | PDF | 2.67 MiB | 108 | 1: 67, 55: 922, 108: 1068 | 685.7 |
| `Cultura culinaria/Frank Suarez El poder del metabolismo.pdf` | PDF | 9.71 MiB | 365 | 1: 0, 183: 1760, 365: 1034 | 931.3 |
| `Cultura culinaria/François_Couplan_Reconoce_facilmente.epub` | EPUB | 6.45 MiB | 2 | 1: 5, 2: 11 | 8.0 |
| `Cultura culinaria/Gloria Spencer  La Cocina Enzimatica.pdf` | PDF | 4.31 MiB | 207 | 1: 0, 104: 0, 207: 0 | 0.0 |
| `Cultura culinaria/Harinas Bufort Manual del panadero.pdf` | PDF | 630.4 KiB | 14 | 1: 86, 8: 1556, 14: 167 | 603.0 |
| `Cultura culinaria/Hermann Schmidt  Las especias Condimentos vegetales.pdf` | PDF | 3.04 MiB | 103 | 1: 529, 52: 1103, 103: 0 | 544.0 |
| `Cultura culinaria/Hervé This Los secretos de los pucheros.epub` | EPUB | 16.04 MiB | 335 | 1: 5, 168: 1010, 335: 620 | 545.0 |
| `Cultura culinaria/Integral El libro de las especias.pdf` | PDF | 42.55 MiB | 95 | 1: 0, 48: 0, 95: 0 | 0.0 |
| `Cultura culinaria/Jean Pedrazzani Los remedios de la abuela.pdf` | PDF | 663.7 KiB | 70 | 1: 73, 36: 5117, 70: 1863 | 2351.0 |
| `Cultura culinaria/Jean Seignalet La alimentación La 3ª medicina.epub` | EPUB | 7.88 MiB | 11 | 1: 5, 6: 151261, 11: 1606 | 50957.3 |
| `Cultura culinaria/Jennifer Eloff Vamos a comer bajo en carbohidratos.epub` | EPUB | 1.72 MiB | 2 | 1: 5, 2: 78732 | 39368.5 |
| `Cultura culinaria/Joaquin Pérez Cocinar con una pizca de ciencia.pdf` | PDF | 8.29 MiB | 255 | 1: 1, 128: 3875, 255: 3 | 1293.0 |
| `Cultura culinaria/John_Seymour_La_conservacion_de.pdf` | PDF | 33.24 MiB | 96 | 1: 0, 49: 0, 96: 0 | 0.0 |
| `Cultura culinaria/Jose Luis Armendariz Técnicas de cocina para profesionales.pdf` | PDF | 26.04 MiB | 332 | 1: 67, 167: 2181, 332: 499 | 915.7 |
| `Cultura culinaria/Jose Luis Armendáriz Técnicas de cocina para profesionales.pdf` | PDF | 26.06 MiB | 332 | 1: 67, 167: 2181, 332: 499 | 915.7 |
| `Cultura culinaria/La cocina aromatica - Francois Chartier.epub` | EPUB | 7.92 MiB | 25 | 1: 8, 13: 12828, 25: 432 | 4422.7 |
| `Cultura culinaria/La cocina de la congelación.pdf` | PDF | 10.50 MiB | 51 | 1: 7, 26: 8, 51: 8 | 7.7 |
| `Cultura culinaria/Laura Landra Como conservar fruta y verdura.epub` | EPUB | 155.6 KiB | 22 | 1: 5, 12: 1223, 22: 281 | 503.0 |
| `Cultura culinaria/Libro de recetas del aula de hosteleria curso 2008-2009.pdf` | PDF | 3.03 MiB | 110 | 1: 110, 56: 1160, 110: 432 | 567.3 |
| `Cultura culinaria/Low carb ¡Come sano!.epub` | EPUB | 4.84 MiB | 129 | 1: 5, 65: 1293, 129: 1025 | 774.3 |
| `Cultura culinaria/Manual del aspirante a chef - MasterChef.epub` | EPUB | 17.88 MiB | 9 | 1: 8, 5: 1062, 9: 1736 | 935.3 |
| `Cultura culinaria/Manual práctico sobre pescados y mariscos frescos.pdf` | PDF | 11.68 MiB | 299 | 1: 49, 150: 3, 299: 3 | 18.3 |
| `Cultura culinaria/Manuel Arasa Gil Manual de nutrición deportiva.pdf` | PDF | 3.65 MiB | 161 | 1: 0, 81: 2983, 161: 3849 | 2277.3 |
| `Cultura culinaria/Maria Jesus Gil de Antuñano Escuela de cocina.pdf` | PDF | 5.14 MiB | 146 | 1: 67, 74: 3102, 146: 9250 | 4139.7 |
| `Cultura culinaria/Masterchef Manual del aspirante a chef.pdf` | PDF | 14.16 MiB | 281 | 1: 0, 141: 0, 281: 0 | 0.0 |
| `Cultura culinaria/PARA DEPORTISTAS.pdf` | PDF | 1.86 MiB | 26 | 1: 21, 14: 21, 26: 21 | 21.0 |
| `Cultura culinaria/REVISTASGOLD31K. 12-18-CocinaVital.pdf` | PDF | 21.27 MiB | 84 | 1: 1, 43: 0, 84: 0 | 0.3 |
| `Cultura culinaria/Saturnino Calleja Manual de la cocinera.pdf` | PDF | 25.02 MiB | 94 | 1: 0, 48: 0, 94: 1122 | 374.0 |
| `Cultura culinaria/Sergio Casado Una aventura en el mundo de la cocina.epub` | EPUB | 1.73 MiB | 2 | 1: 5, 2: 159962 | 79983.5 |
| `Gourmand_29_Janvier_2020 .pdf` | PDF | 102.53 MiB | 104 | 1: 0, 53: 0, 104: 0 | 0.0 |
| `Guisats i estofats/Estofados.pdf` | PDF | 1.46 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Guisats i estofats/Guisos de patata.pdf` | PDF | 1.30 MiB | 17 | 1: 21, 9: 21, 17: 21 | 21.0 |
| `Guisats i estofats/IX jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | 2.96 MiB | 84 | 1: 16, 43: 975, 84: 252 | 414.3 |
| `Guisats i estofats/V Jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | 1.75 MiB | 80 | 1: 18, 41: 852, 80: 55 | 308.3 |
| `Guisats i estofats/VI Jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | 841.0 KiB | 88 | 1: 18, 45: 1328, 88: 55 | 467.0 |
| `Guisats i estofats/VII jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | 3.33 MiB | 84 | 1: 18, 43: 791, 84: 55 | 288.0 |
| `Guisats i estofats/VIII jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | 1.04 MiB | 72 | 1: 0, 37: 987, 72: 208 | 398.3 |
| `Guisats i estofats/losguisosdelaabuela.pdf` | PDF | 5.16 MiB | 98 | 1: 68, 50: 837, 98: 142 | 349.0 |
| `Postres/1 MOLDE 10 RECETAS.pdf` | PDF | 1.26 MiB | 14 | 1: 217, 8: 979, 14: 351 | 515.7 |
| `Postres/100 Dulces Y Postres - Patry Jordan.pdf` | PDF | 7.51 MiB | 204 | 1: 0, 103: 0, 204: 0 | 0.0 |
| `Postres/12 Recetas de galletas.pdf` | PDF | 3.58 MiB | 33 | 1: 36, 17: 24, 33: 24 | 28.0 |
| `Postres/30 recetas prácticas Postres rápidos.pdf` | PDF | 12.37 MiB | 33 | 1: 0, 17: 0, 33: 0 | 0.0 |
| `Postres/555 Recetas de postres - Eva Arguinano.pdf` | PDF | 1.89 MiB | 1102 | 1: 0, 552: 579, 1102: 17 | 198.7 |
| `Postres/Angela García Tartas del mundo.pdf` | PDF | 12.63 MiB | 173 | 1: 0, 87: 0, 173: 0 | 0.0 |
| `Postres/Aprenda a hacer dulzuras caseras.pdf` | PDF | 7.03 MiB | 38 | 1: 0, 20: 0, 38: 0 | 0.0 |
| `Postres/Arte del azucar 01.pdf` | PDF | 16.39 MiB | 83 | 1: 0, 42: 0, 83: 0 | 0.0 |
| `Postres/Arte del azucar 02.pdf` | PDF | 15.82 MiB | 86 | 1: 0, 44: 0, 86: 0 | 0.0 |
| `Postres/BOLLERÍA CASERA .pdf` | PDF | 1.89 MiB | 18 | 1: 185, 10: 230, 18: 413 | 276.0 |
| `Postres/Bea Roque El rincón de Bea Delicias para compartir.epub` | EPUB | 7.00 MiB | 179 | 1: 5, 90: 756, 179: 1361 | 707.3 |
| `Postres/Bimbo - Recetas de Cuaresma.pdf` | PDF | 3.37 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Postres/Bricoreposteria - VVAA.epub` | EPUB | 3.48 MiB | 85 | 1: 5, 43: 548, 85: 1075 | 542.7 |
| `Postres/Cecilia Paseiro Pastelería artesanal.pdf` | PDF | 376.9 KiB | 147 | 1: 152, 74: 662, 147: 1558 | 790.7 |
| `Postres/Cheesecakes.pdf` | PDF | 2.06 MiB | 25 | 1: 21, 13: 21, 25: 21 | 21.0 |
| `Postres/Chef Express Postres livianos.pdf` | PDF | 6.97 MiB | 29 | 1: 0, 15: 0, 29: 0 | 0.0 |
| `Postres/Chocolate Recetas que explotan sus sentidos.pdf` | PDF | 91.47 MiB | 63 | 1: 0, 32: 0, 63: 0 | 0.0 |
| `Postres/Cioccolate.pdf` | PDF | 2.54 MiB | 21 | 1: 0, 11: 679, 21: 768 | 482.3 |
| `Postres/Cocina fácil Dulces de Navidad.pdf` | PDF | 10.01 MiB | 31 | 1: 0, 16: 0, 31: 0 | 0.0 |
| `Postres/Curso alta reposteria chocolates turin.pdf` | PDF | 11.30 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Postres/Dolcezze tirolesi.pdf` | PDF | 7.82 MiB | 90 | 1: 0, 46: 0, 90: 0 | 0.0 |
| `Postres/Dolci ma non troppo.pdf` | PDF | 2.43 MiB | 28 | 1: 0, 15: 0, 28: 0 | 0.0 |
| `Postres/Dolci sorprese Galette des rois.pdf` | PDF | 6.87 MiB | 81 | 1: 0, 41: 0, 81: 0 | 0.0 |
| `Postres/Dolci sorprese.pdf` | PDF | 993.8 KiB | 15 | 1: 32, 8: 0, 15: 4 | 12.0 |
| `Postres/Dulce Tentación (México).pdf` | PDF | 12.81 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Postres/Dulces Navideños.pdf` | PDF | 2.21 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Postres/Edición chocolate.pdf` | PDF | 65.59 MiB | 244 | 1: 0, 123: 0, 244: 32 | 10.7 |
| `Postres/Editorial El Pais Siete Pecados.pdf` | PDF | 23.91 MiB | 71 | 1: 74, 36: 3664, 71: 4055 | 2597.7 |
| `Postres/Editorial NGV Helados, sorbetes y otros.epub` | EPUB | 5.42 MiB | 2020 | 1: 5, 1011: 96, 2020: 48 | 49.7 |
| `Postres/El libro de oro de la reposteria para ti.pdf` | PDF | 78.93 MiB | 98 | 1: 0, 50: 0, 98: 0 | 0.0 |
| `Postres/El rincón de los postres.pdf` | PDF | 1.86 MiB | 24 | 1: 37, 13: 759, 24: 221 | 339.0 |
| `Postres/Emily Scott Los 10 postres más famosos del mundo.epub` | EPUB | 481.0 KiB | 27 | 1: 5, 14: 256, 27: 5113 | 1791.3 |
| `Postres/Festín de Sri Lanka.pdf` | PDF | 4.64 MiB | 19 | 1: 0, 10: 0, 19: 0 | 0.0 |
| `Postres/Flan y pudín.pdf` | PDF | 1.71 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Postres/Fruta natural.pdf` | PDF | 1.79 MiB | 25 | 1: 21, 13: 21, 25: 21 | 21.0 |
| `Postres/GRANDES TARTAS.pdf` | PDF | 4.31 MiB | 57 | 1: 21, 29: 21, 57: 21 | 21.0 |
| `Postres/Gabriele Colditz Fruta escarchada.pdf` | PDF | 24.98 MiB | 65 | 1: 0, 33: 0, 65: 0 | 0.0 |
| `Postres/Giuliana Bonomo Guía de dulces.pdf` | PDF | 60.49 MiB | 128 | 1: 0, 65: 2897, 128: 2721 | 1872.7 |
| `Postres/HELADOS Y SORBETES. VOL. I.pdf` | PDF | 1.18 MiB | 12 | 1: 193, 7: 1509, 12: 289 | 663.7 |
| `Postres/José Maréchal Sabrosas tentaciones en vasitos.pdf` | PDF | 10.80 MiB | 64 | 1: 0, 33: 0, 64: 0 | 0.0 |
| `Postres/Juan Diaz La pequeña cuisiniere.epub` | EPUB | 635.6 KiB | 42 | 1: 5, 22: 61, 42: 186 | 84.0 |
| `Postres/La cocina de Sumito Postres para impresionar.pdf` | PDF | 5.85 MiB | 39 | 1: 19, 20: 0, 39: 19 | 12.7 |
| `Postres/La magia del chocolate.pdf` | PDF | 3.11 MiB | 28 | 1: 0, 15: 0, 28: 0 | 0.0 |
| `Postres/Las 100 mejores recetas dulces de Ana Sevilla.pdf` | PDF | 44.68 MiB | 128 | 1: 21, 65: 21, 128: 21 | 21.0 |
| `Postres/Las mejores gelatinas presenta flanes.pdf` | PDF | 6.72 MiB | 30 | 1: 0, 16: 0, 30: 0 | 0.0 |
| `Postres/Les meilleurs de mini cakes.pdf` | PDF | 13.71 MiB | 80 | 1: 71, 41: 72, 80: 72 | 71.7 |
| `Postres/Lo mejor de la leche dulce num. 33.pdf` | PDF | 10.13 MiB | 25 | 1: 0, 13: 0, 25: 0 | 0.0 |
| `Postres/Lolita Avellana Les postres de casa meva.epub` | EPUB | 823.9 KiB | 200 | 1: 10, 101: 990, 200: 3293 | 1431.0 |
| `Postres/MAGDALENAS.pdf` | PDF | 1.08 MiB | 15 | 1: 21, 8: 21, 15: 21 | 21.0 |
| `Postres/Masterclass Tartas increibles.pdf` | PDF | 7.58 MiB | 20 | 1: 0, 11: 1240, 20: 55 | 431.7 |
| `Postres/Maxine Clark Tartas dulces y saladas.epub` | EPUB | 5.31 MiB | 2 | 1: 5, 2: 23 | 14.0 |
| `Postres/Montagud Editores Pastry Revolution.pdf` | PDF | 24.34 MiB | 102 | 1: 0, 52: 0, 102: 0 | 0.0 |
| `Postres/Muffin dolci e salati.pdf` | PDF | 5.10 MiB | 41 | 1: 0, 21: 0, 41: 0 | 0.0 |
| `Postres/Muffins Dulces y salados.pdf` | PDF | 3.76 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Postres/NGV Super muffins.pdf` | PDF | 9.51 MiB | 120 | 1: 0, 61: 0, 120: 0 | 0.0 |
| `Postres/Nestlé ¡A comer bien! Recetas para postres.pdf` | PDF | 1.04 MiB | 12 | 1: 0, 7: 0, 12: 0 | 0.0 |
| `Postres/POSTRES INDIVIDUALES.pdf` | PDF | 1.66 MiB | 15 | 1: 233, 8: 2231, 15: 455 | 973.0 |
| `Postres/Panadería y pastelería profesional.pdf` | PDF | 1.82 MiB | 120 | 1: 66, 61: 1019, 120: 241 | 442.0 |
| `Postres/Panquecitos.pdf` | PDF | 3.89 MiB | 22 | 1: 0, 12: 0, 22: 0 | 0.0 |
| `Postres/Panqués.pdf` | PDF | 3.25 MiB | 30 | 1: 0, 16: 0, 30: 0 | 0.0 |
| `Postres/Pasteleria y reposteria Curso avanzado.epub` | EPUB | 48.22 MiB | 2 | 1: 5, 2: 23 | 14.0 |
| `Postres/Pastelería artesana num. 03.epub` | EPUB | 1.71 MiB | 2 | 1: 5, 2: 1993 | 999.0 |
| `Postres/Postres de Navidad-1.pdf` | PDF | 21.77 MiB | 110 | 1: 0, 56: 0, 110: 0 | 0.0 |
| `Postres/Postres del Mediterráneo.pdf` | PDF | 1.53 MiB | 20 | 1: 21, 11: 21, 20: 21 | 21.0 |
| `Postres/Postres del mundo.pdf` | PDF | 18.15 MiB | 52 | 1: 49, 27: 49, 52: 49 | 49.0 |
| `Postres/Postres en vaso - VVAA.epub` | EPUB | 5.96 MiB | 237 | 1: 5, 119: 207, 237: 965 | 392.3 |
| `Postres/Postres para celebrar.pdf` | PDF | 6.60 MiB | 92 | 1: 59, 47: 952, 92: 21 | 344.0 |
| `Postres/Postres y Dulces Galletas.pdf` | PDF | 4.09 MiB | 30 | 1: 0, 16: 0, 30: 0 | 0.0 |
| `Postres/Postres y dulces Flanes.pdf` | PDF | 5.46 MiB | 21 | 1: 0, 11: 0, 21: 0 | 0.0 |
| `Postres/Pralinky.pdf` | PDF | 3.59 MiB | 56 | 1: 21, 29: 21, 56: 21 | 21.0 |
| `Postres/REPOSTERÍA Y PASTELERÍA I.pdf` | PDF | 7.38 MiB | 92 | 1: 194, 47: 1359, 92: 2167 | 1240.0 |
| `Postres/Receitas-Pequenas-Delicias.pdf` | PDF | 1.44 MiB | 9 | 1: 39, 5: 1582, 9: 39 | 553.3 |
| `Postres/Receta-Roscon-Reyes-LeCreuset.pdf` | PDF | 328.4 KiB | 5 | 1: 15, 3: 1030, 5: 57 | 367.3 |
| `Postres/Recetario El Horno de Villablanca'.pdf` | PDF | 12.05 MiB | 114 | 1: 0, 58: 0, 114: 0 | 0.0 |
| `Postres/Recetas de cremas, mousses y helados.pdf` | PDF | 18.39 MiB | 63 | 1: 77, 32: 0, 63: 0 | 25.7 |
| `Postres/Recetas inedittas do convento para a bimby.pdf` | PDF | 18.80 MiB | 136 | 1: 0, 69: 0, 136: 0 | 0.0 |
| `Postres/SABOR A CHOCOLATE.pdf` | PDF | 1.12 MiB | 12 | 1: 217, 7: 802, 12: 357 | 458.7 |
| `Postres/Saints Román Postres y otras recetas.epub` | EPUB | 947.5 KiB | 3 | 1: 5, 2: 22584, 3: 39 | 7542.7 |
| `Postres/Xavier Barriga Cocas, tortas y otras delicias.pdf` | PDF | 87.24 MiB | 160 | 1: 0, 81: 0, 160: 0 | 0.0 |
| `Postres/YOGURES.pdf` | PDF | 1.49 MiB | 15 | 1: 241, 8: 998, 15: 405 | 548.0 |
| `Postres/galletas caseras.pdf` | PDF | 4.40 MiB | 43 | 1: 0, 22: 0, 43: 0 | 0.0 |
| `Postres/recetas-chocolate (1).pdf` | PDF | 7.92 MiB | 24 | 1: 0, 13: 2677, 24: 0 | 892.3 |
| `Postres/Ángela García & Hanns Geel - Tartas del mundo.pdf` | PDF | 12.63 MiB | 173 | 1: 0, 87: 0, 173: 0 | 0.0 |
| `Postres/Éclair per una merenda chic.pdf` | PDF | 8.44 MiB | 104 | 1: 0, 53: 0, 104: 0 | 0.0 |
| `REVISTASGOLD26K,1112-18-dcamera-byneon.pdf` | PDF | 21.92 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Receptes/100 recetas premiadas Tulipan.epub` | EPUB | 5.59 MiB | 2 | 1: 20, 2: 1119 | 569.5 |
| `Receptes/Cocina con garrote - Martin Berasategui.kepub.epub` | EPUB | 19.15 MiB | 314 | 1: 5, 158: 1195, 314: 4571 | 1923.7 |
| `Receptes/Grandes Recetas Para Cocinas Pequeñas - Marta Carnicero.pdf` | PDF | 1.67 MiB | 282 | 1: 0, 142: 1908, 282: 857 | 921.7 |
| `Receptes/Karlos Arguiñano Cocina día a día.epub` | EPUB | 54.17 MiB | 13 | 1: 8, 7: 253257, 13: 119 | 84461.3 |
| `Receptes/Libro de recetas Sencillo & saludable.mobi` | MOBI | 3.41 MiB | n/a | n/a | n/a |
| `Receptes/Maravillosas-Recetas-de-La-Abuela-pdf.pdf` | PDF | 3.79 MiB | 40 | 1: 35, 21: 809, 40: 69 | 304.3 |
| `Receptes/MasterChef - Las Recetas De Marta.pdf` | PDF | 14.28 MiB | 232 | 1: 0, 117: 1125, 232: 0 | 375.0 |
| `Receptes/Recetario blog Exquisit 2014.pdf` | PDF | 52.31 MiB | 269 | 1: 37, 135: 1064, 269: 352 | 484.3 |
| `Receptes/Recetario blog Exquisit Recetas de sopas y cremas.pdf` | PDF | 699.7 KiB | 8 | 1: 23, 5: 23, 8: 23 | 23.0 |
| `Receptes/Recetario blog exquisit 2015.pdf` | PDF | 52.07 MiB | 356 | 1: 37, 179: 1570, 356: 351 | 652.7 |
| `Receptes/Recetario blog exquisit 2016.pdf` | PDF | 46.74 MiB | 388 | 1: 37, 195: 934, 388: 351 | 440.7 |
| `Receptes/Recetario blog exquisit 2017.pdf` | PDF | 35.71 MiB | 321 | 1: 37, 161: 1141, 321: 337 | 505.0 |
| `Receptes/Recetario blog exquisit 40 exquisitos bocadillos.pdf` | PDF | 3.46 MiB | 47 | 1: 102, 24: 478, 47: 316 | 298.7 |
| `Receptes/Recetario_blog_Exquisit_Recetas.pdf` | PDF | 736.1 KiB | 10 | 1: 24, 6: 24, 10: 25 | 24.3 |
| `Receptes/Velocidad cuchara  Lo mejor del blog.pdf` | PDF | 2.53 MiB | 35 | 1: 21, 18: 21, 35: 21 | 21.0 |
| `Receptes/cocina fácil lecturas.rar` | RAR | 1347.32 MiB | n/a | n/a | n/a |
| `Receptes/recetas con humor.pdf` | PDF | 11.27 MiB | 68 | 1: 125, 35: 1027, 68: 594 | 582.0 |
| `Thermomix/01_Thermomix_-_Mis_Mejores_Recetas_-_Cristina_Galiano.pdf` | PDF | 35.05 MiB | 393 | 1: 0, 197: 0, 393: 0 | 0.0 |
| `Thermomix/10.- A todo vapor TMX31.Johnnygan.pdf` | PDF | 33.63 MiB | 189 | 1: 0, 95: 0, 189: 0 | 0.0 |
| `Thermomix/24.- Las Recetas De La Abuela II.Johnnygan.pdf` | PDF | 58.21 MiB | 93 | 1: 0, 47: 0, 93: 0 | 0.0 |
| `Thermomix/4.- 100 Recetas practicas.Johnnygan.pdf` | PDF | 11.67 MiB | 126 | 1: 0, 64: 0, 126: 0 | 0.0 |
| `Thermomix/43.- Imprescindible para su cocina.Johnnygan.pdf` | PDF | 20.76 MiB | 102 | 1: 14, 52: 2701, 102: 1953 | 1556.0 |
| `Thermomix/5.- 100 nuevas recetas.Johnnygan.pdf` | PDF | 20.87 MiB | 119 | 1: 0, 60: 0, 119: 0 | 0.0 |
| `Thermomix/Al calor de un caldo.pdf` | PDF | 1.48 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Thermomix/BAOS.pdf` | PDF | 4.12 MiB | 12 | 1: 0, 7: 0, 12: 0 | 0.0 |
| `Thermomix/BARBACOA ESPECIAL Y DIFERENTE.pdf` | PDF | 1.51 MiB | 42 | 1: 268, 22: 84, 42: 726 | 359.3 |
| `Thermomix/BARRETTE DALLA COMMUNITY.pdf` | PDF | 2.67 MiB | 4 | 1: 0, 3: 0, 4: 0 | 0.0 |
| `Thermomix/Como en casa.pdf` | PDF | 40.78 MiB | 186 | 1: 26, 94: 1347, 186: 474 | 615.7 |
| `Thermomix/DIETA MEDITERRANEA CON THERMOMIX.pdf` | PDF | 13.07 MiB | 163 | 1: 183, 82: 1820, 163: 998 | 1000.3 |
| `Thermomix/De cuchara.pdf` | PDF | 1.75 MiB | 26 | 1: 21, 14: 21, 26: 21 | 21.0 |
| `Thermomix/DeliciosoYRapido.pdf` | PDF | 767.5 KiB | 12 | 1: 21, 7: 21, 12: 21 | 21.0 |
| `Thermomix/EXPERIENCIA GASTRONÓMICA Thermomix TM5.pdf` | PDF | 3.81 MiB | 13 | 1: 39, 7: 1370, 13: 678 | 695.7 |
| `Thermomix/Food Truck una fiesta de sabores.pdf` | PDF | 24.85 MiB | 172 | 1: 0, 87: 0, 172: 0 | 0.0 |
| `Thermomix/Gran Bretaña.pdf` | PDF | 2.61 MiB | 8 | 1: 0, 5: 0, 8: 0 | 0.0 |
| `Thermomix/Il cibo degli atleti.pdf` | PDF | 1.89 MiB | 29 | 1: 32, 15: 0, 29: 0 | 10.7 |
| `Thermomix/Kale.pdf` | PDF | 3.32 MiB | 10 | 1: 0, 6: 0, 10: 0 | 0.0 |
| `Thermomix/Kinder.pdf` | PDF | 1.81 MiB | 32 | 1: 81, 17: 962, 32: 472 | 505.0 |
| `Thermomix/Maravillosas-Recetas-de-La-Abuela-pdf.pdf` | PDF | 3.79 MiB | 40 | 1: 35, 21: 809, 40: 69 | 304.3 |
| `Thermomix/Pastillas de caldo.pdf` | PDF | 2.65 MiB | 10 | 1: 0, 6: 0, 10: 0 | 0.0 |
| `Thermomix/Picoteo de Cine.pdf` | PDF | 4.17 MiB | 12 | 1: 0, 7: 0, 12: 0 | 0.0 |
| `Thermomix/RECETAS DE DIARIO.pdf` | PDF | 2.10 MiB | 33 | 1: 60, 17: 679, 33: 432 | 390.3 |
| `Thermomix/Recetas del  mundo para cocinar a diario.pdf` | PDF | 8.17 MiB | 100 | 1: 217, 51: 2234, 100: 3527 | 1992.7 |
| `Thermomix/SMOOTHIE BOWLS THERMOMIX .pdf` | PDF | 1.17 MiB | 15 | 1: 0, 8: 0, 15: 0 | 0.0 |
| `Thermomix/Simple & Dulce con thermomix.pdf` | PDF | 7.54 MiB | 20 | 1: 144, 11: 2204, 20: 112 | 820.0 |
| `Thermomix/Thermomix 135 - Enero 2020.pdf` | PDF | 11.75 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/Thermomix 40 AÑOS.pdf` | PDF | 33.08 MiB | 346 | 1: 0, 174: 0, 346: 0 | 0.0 |
| `Thermomix/Thermomix Marzo 2017.pdf` | PDF | 21.28 MiB | 100 | 1: 21, 51: 21, 100: 21 | 21.0 |
| `Thermomix/Thermomix marzo 2020.pdf` | PDF | 17.74 MiB | 56 | 1: 0, 29: 0, 56: 0 | 0.0 |
| `Thermomix/Thermomix num. 123 Enero 2019.pdf` | PDF | 29.31 MiB | 100 | 1: 241, 51: 3809, 100: 161 | 1403.7 |
| `Thermomix/Thermomix num. 126  Abril 2019.pdf` | PDF | 30.20 MiB | 99 | 1: 0, 50: 0, 99: 0 | 0.0 |
| `Thermomix/Thermomix num. 127 Mayo 2019.pdf` | PDF | 26.46 MiB | 44 | 1: 0, 23: 0, 44: 0 | 0.0 |
| `Thermomix/Thermomix num. 128 Junio 2019.pdf` | PDF | 30.76 MiB | 100 | 1: 231, 51: 2624, 100: 0 | 951.7 |
| `Thermomix/Thermomix num. 129 Julio 2019.pdf` | PDF | 31.02 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/Thermomix num. 130 Agosto 2019.pdf` | PDF | 32.34 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/Thermomix num. 131 Septiembre 2019.pdf` | PDF | 21.03 MiB | 99 | 1: 0, 50: 0, 99: 0 | 0.0 |
| `Thermomix/Thermomix num. 132 Octubre 2019.pdf` | PDF | 29.22 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/Thermomix num. 133 Noviembre 2019.pdf` | PDF | 19.11 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/Thermomix num. 134 Diciembre 2019.pdf` | PDF | 42.92 MiB | 148 | 1: 0, 75: 0, 148: 0 | 0.0 |
| `Thermomix/Thermomix num. 135 Enero 2020.pdf` | PDF | 11.75 MiB | 100 | 1: 1, 51: 0, 100: 0 | 0.3 |
| `Thermomix/Thermomix num. 138 Abril 2020.pdf` | PDF | 23.77 MiB | 79 | 1: 0, 40: 0, 79: 0 | 0.0 |
| `Thermomix/Thermomix septiembre 2018.pdf` | PDF | 18.78 MiB | 100 | 1: 316, 51: 1561, 100: 0 | 625.7 |
| `Thermomix/VOLANDO VOY alitas de pollo.pdf` | PDF | 3.18 MiB | 11 | 1: 0, 6: 0, 11: 0 | 0.0 |
| `Thermomix/adelgazar con thermomix.pdf` | PDF | 11.14 MiB | 195 | 1: 0, 98: 20, 195: 344 | 121.3 |
| `Thermomix/recetas_especiales.pdf` | PDF | 3.28 MiB | 36 | 1: 283, 19: 27, 36: 45 | 118.3 |
| `Thermomix/reposteria tmx.pdf` | PDF | 7.77 MiB | 154 | 1: 0, 78: 0, 154: 0 | 0.0 |
| `Thermomix/{RDL} 08-19-Thermomix.pdf` | PDF | 32.34 MiB | 100 | 1: 3, 51: 0, 100: 0 | 1.0 |
| `Thermomix/{RL} 05-20-Thermomix.pdf` | PDF | 27.01 MiB | 76 | 1: 1, 39: 0, 76: 0 | 0.3 |
| `Thermomix/{RL} 09-19-Thermomix.pdf` | PDF | 32.74 MiB | 100 | 1: 1, 51: 0, 100: 0 | 0.3 |
| `Thermomix/{RL} 10-19-Thermomix.pdf` | PDF | 15.64 MiB | 52 | 1: 1, 27: 0, 52: 0 | 0.3 |
| `Thermomix/{RL} 11-19-Thermomix.pdf` | PDF | 19.11 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Thermomix/{RL} Thermomix Un nuevo amanecer.pdf` | PDF | 20.02 MiB | 185 | 1: 0, 93: 0, 185: 0 | 0.0 |
| `Tipus de Cuina/Amanides/Club gente saludable Ensaladas.pdf` | PDF | 452.2 KiB | 12 | 1: 0, 7: 1197, 12: 1190 | 795.7 |
| `Tipus de Cuina/Amanides/De rechupete Recetas de ensalada.pdf` | PDF | 2.11 MiB | 64 | 1: 20, 33: 2440, 64: 706 | 1055.3 |
| `Tipus de Cuina/Amanides/Ensaladas Para Todo El Año - Martín Berasategui.pdf` | PDF | 32.27 MiB | 362 | 1: 0, 182: 0, 362: 163 | 54.3 |
| `Tipus de Cuina/Amanides/Ensaladas XXL.pdf` | PDF | 2.32 MiB | 53 | 1: 21, 27: 21, 53: 21 | 21.0 |
| `Tipus de Cuina/Amanides/Ensaladas para todo el año - Martin Berasategui.epub` | EPUB | 40.30 MiB | 17 | 1: 7, 9: 37409, 17: 2593 | 13336.3 |
| `Tipus de Cuina/Amanides/Ensaladas y aliños.pdf` | PDF | 1.49 MiB | 18 | 1: 21, 10: 21, 18: 21 | 21.0 |
| `Tipus de Cuina/Amanides/Pon una ensalada en tu verano 2016.pdf` | PDF | 29.33 MiB | 132 | 1: 72, 67: 1578, 132: 0 | 550.0 |
| `Tipus de Cuina/Amanides/Por una ensalada en tu verano 2013.pdf` | PDF | 6.09 MiB | 134 | 1: 15, 68: 1643, 134: 67 | 575.0 |
| `Tipus de Cuina/Amanides/Supermaxi Ensaladas para toda ocasión.pdf` | PDF | 14.32 MiB | 129 | 1: 0, 65: 976, 129: 0 | 325.3 |
| `Tipus de Cuina/Amanides/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Amanides/recetario_ensaladas.pdf` | PDF | 2.11 MiB | 64 | 1: 20, 33: 2440, 64: 706 | 1055.3 |
| `Tipus de Cuina/Amb nens/Divertirsi in cucina.pdf` | PDF | 6.14 MiB | 75 | 1: 0, 38: 0, 75: 0 | 0.0 |
| `Tipus de Cuina/Amb nens/Junior Masterchef Recetas para cocinar con niños.pdf` | PDF | 18.90 MiB | 347 | 1: 0, 174: 257, 347: 29 | 95.3 |
| `Tipus de Cuina/Amb nens/Niños _a comer!.pdf` | PDF | 3.06 MiB | 57 | 1: 21, 29: 21, 57: 21 | 21.0 |
| `Tipus de Cuina/Amb nens/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Arros/Angelica Sasaki Cocina en 30 minutos Arroces.pdf` | PDF | 8.10 MiB | 59 | 1: 0, 30: 0, 59: 0 | 0.0 |
| `Tipus de Cuina/Arros/Arroces Valencianos.pdf` | PDF | 310.9 KiB | 16 | 1: 2545, 9: 1833, 16: 0 | 1459.3 |
| `Tipus de Cuina/Arros/Arroz un básico 5 recetas.pdf` | PDF | 2.65 MiB | 9 | 1: 0, 5: 0, 9: 0 | 0.0 |
| `Tipus de Cuina/Arros/Cocinar arroces con fantasia.pdf` | PDF | 30.74 MiB | 101 | 1: 83, 51: 0, 101: 0 | 27.7 |
| `Tipus de Cuina/Arros/Especial arroces Vol II.pdf` | PDF | 3.13 MiB | 44 | 1: 21, 23: 21, 44: 21 | 21.0 |
| `Tipus de Cuina/Arros/Especial arroces.pdf` | PDF | 3.14 MiB | 47 | 1: 21, 24: 21, 47: 21 | 21.0 |
| `Tipus de Cuina/Arros/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Autor/Chiringuito de Pepe Las recetas de Pepe Leal y Sergi Roca.epub` | EPUB | 5.56 MiB | 75 | 1: 5, 38: 777, 75: 2578 | 1120.0 |
| `Tipus de Cuina/Autor/Cocina_con_Joan_Roca_a_baja_tem.epub` | EPUB | 52.46 MiB | 353 | 1: 13, 177: 4287, 353: 2037 | 2112.3 |
| `Tipus de Cuina/Autor/Grandes chefs.pdf` | PDF | 2.05 MiB | 26 | 1: 21, 14: 21, 26: 21 | 21.0 |
| `Tipus de Cuina/Autor/Joan Roca Cocina con Joan Roca a baja temperatura.epub` | EPUB | 52.46 MiB | 353 | 1: 13, 177: 4287, 353: 2037 | 2112.3 |
| `Tipus de Cuina/Autor/Juan Mari Arzak Arzak.epub` | EPUB | 6.91 MiB | 17 | 1: 5, 9: 16280, 17: 215 | 5500.0 |
| `Tipus de Cuina/Autor/Karlos Arguiñano 1000 recetas de oro.epub` | EPUB | 25.78 MiB | 24 | 1: 5, 13: 118037, 24: 249 | 39430.3 |
| `Tipus de Cuina/Autor/Las 1150 recetas - Martín Berasategui.epub` | EPUB | 1.42 MiB | 27 | 1: 5, 14: 55044, 27: 414 | 18487.7 |
| `Tipus de Cuina/Autor/Martín Berasategui Cocina en casa con Martín Berasategui.epub` | EPUB | 632.4 KiB | 23 | 1: 5, 12: 168635, 23: 409 | 56349.7 |
| `Tipus de Cuina/Autor/Martín Berasategui La cocina de Martín Berasategui.epub` | EPUB | 23.84 MiB | 19 | 1: 5, 10: 30970, 19: 2851 | 11275.3 |
| `Tipus de Cuina/Autor/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Cacera/VII jornadas gastronómicas de la caza.pdf` | PDF | 1.91 MiB | 76 | 1: 16, 39: 604, 76: 0 | 206.7 |
| `Tipus de Cuina/Cacera/VIII jornadas gastronómicas de la caza.pdf` | PDF | 893.2 KiB | 68 | 1: 16, 35: 585, 68: 0 | 200.3 |
| `Tipus de Cuina/Cacera/X Jornadas gastronómicas de la caza.pdf` | PDF | 2.12 MiB | 84 | 1: 0, 43: 1360, 84: 194 | 518.0 |
| `Tipus de Cuina/Cacera/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Casolana/9ª Jornadas Gastronómicas de la caza.pdf` | PDF | 4.83 MiB | 84 | 1: 0, 43: 0, 84: 0 | 0.0 |
| `Tipus de Cuina/Casolana/Asados con guarnición.pdf` | PDF | 18.73 MiB | 88 | 1: 0, 45: 0, 88: 0 | 0.0 |
| `Tipus de Cuina/Casolana/Carnes rojas y blancas.epub` | EPUB | 2.11 MiB | 10 | 1: 10, 6: 6, 10: 6 | 7.3 |
| `Tipus de Cuina/Casolana/Cocina Exótica del Mediterráneo.pdf` | PDF | 2.33 MiB | 28 | 1: 21, 15: 21, 28: 21 | 21.0 |
| `Tipus de Cuina/Casolana/Con carne de ave.epub` | EPUB | 3.22 MiB | 1 | 1: 10 | 10.0 |
| `Tipus de Cuina/Casolana/Con huevo o masa.epub` | EPUB | 3.47 MiB | 2 | 1: 13, 2: 6 | 9.5 |
| `Tipus de Cuina/Casolana/De verduras y hortalizas.epub` | EPUB | 2.90 MiB | 1 | 1: 10 | 10.0 |
| `Tipus de Cuina/Casolana/Empanadas y empanadillas.pdf` | PDF | 1.58 MiB | 16 | 1: 216, 9: 308, 16: 466 | 330.0 |
| `Tipus de Cuina/Casolana/Especial Albóndigas.pdf` | PDF | 1.94 MiB | 31 | 1: 21, 16: 21, 31: 21 | 21.0 |
| `Tipus de Cuina/Casolana/Fritos & Cía.pdf` | PDF | 2.19 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Tipus de Cuina/Casolana/I Jornada gastronómicas del ajo.pdf` | PDF | 743.1 KiB | 32 | 1: 16, 17: 383, 32: 52 | 150.3 |
| `Tipus de Cuina/Casolana/Joan Roca Cuina mare.epub` | EPUB | 14.31 MiB | 19 | 1: 7, 10: 21908, 19: 228 | 7381.0 |
| `Tipus de Cuina/Casolana/Juan José Yagüe Cocina marinera.pdf` | PDF | 4.15 MiB | 42 | 1: 39, 22: 1776, 42: 1784 | 1199.7 |
| `Tipus de Cuina/Casolana/La magia del vapore.pdf` | PDF | 18.82 MiB | 261 | 1: 32, 131: 0, 261: 4 | 12.0 |
| `Tipus de Cuina/Casolana/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Casolana/¡COMO EN CASA!.pdf` | PDF | 7.48 MiB | 88 | 1: 207, 45: 1325, 88: 2939 | 1490.3 |
| `Tipus de Cuina/Celíac/COCINA SIN GLUTEN VOL. II.pdf` | PDF | 1.92 MiB | 24 | 1: 21, 13: 21, 24: 21 | 21.0 |
| `Tipus de Cuina/Celíac/Cocina Fácil para Celíacos con TMX.pdf` | PDF | 23.48 MiB | 32 | 1: 0, 17: 0, 32: 0 | 0.0 |
| `Tipus de Cuina/Celíac/Cocina sin gluten.pdf` | PDF | 2.77 MiB | 33 | 1: 21, 17: 21, 33: 21 | 21.0 |
| `Tipus de Cuina/Celíac/De rechupete Recetas para celiacos.pdf` | PDF | 1.81 MiB | 50 | 1: 21, 26: 3196, 50: 706 | 1307.7 |
| `Tipus de Cuina/Celíac/Fabio Dana La vida sin gluten.epub` | EPUB | 567.2 KiB | 48 | 1: 7, 25: 1252, 48: 57 | 438.7 |
| `Tipus de Cuina/Celíac/Gobierno de Aragón Hoy comemos sin gluten (2).pdf` | PDF | 1.03 MiB | 145 | 1: 78, 73: 1185, 145: 0 | 421.0 |
| `Tipus de Cuina/Celíac/REVISTASGOLD29K.2018-11-01 Gluten-Free Heaven.pdf` | PDF | 58.50 MiB | 128 | 1: 739, 65: 2392, 128: 166 | 1099.0 |
| `Tipus de Cuina/Celíac/Restauración Sin Glúten.pdf` | PDF | 3.87 MiB | 90 | 1: 0, 46: 2, 90: 0 | 0.7 |
| `Tipus de Cuina/Celíac/SIN GLUTEN. SIN LIMITES.pdf` | PDF | 9.80 MiB | 104 | 1: 264, 53: 1878, 104: 4160 | 2100.7 |
| `Tipus de Cuina/Celíac/Yo, celiaco - Fabio Dana.epub` | EPUB | 567.2 KiB | 48 | 1: 7, 25: 1252, 48: 57 | 438.7 |
| `Tipus de Cuina/Celíac/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Celíac/recetario_celiacos.pdf` | PDF | 1.83 MiB | 50 | 1: 21, 26: 3196, 50: 706 | 1307.7 |
| `Tipus de Cuina/Cervesa i begudes/Cócteles clásicos.pdf` | PDF | 11.21 MiB | 50 | 1: 0, 26: 0, 50: 0 | 0.0 |
| `Tipus de Cuina/Cervesa i begudes/DE COPAS.pdf` | PDF | 993.3 KiB | 15 | 1: 21, 8: 21, 15: 21 | 21.0 |
| `Tipus de Cuina/Cervesa i begudes/I jornadas gastronómicas de la cerveza.pdf` | PDF | 875.8 KiB | 32 | 1: 16, 17: 334, 32: 52 | 134.0 |
| `Tipus de Cuina/Cervesa i begudes/I jornadas gastronómicas del vino Montilla-Moriles.pdf` | PDF | 1.24 MiB | 80 | 1: 96, 41: 1713, 80: 207 | 672.0 |
| `Tipus de Cuina/Cervesa i begudes/II jornadas gastronómicas de la cerveza.pdf` | PDF | 702.3 KiB | 50 | 1: 16, 26: 693, 50: 52 | 253.7 |
| `Tipus de Cuina/Cervesa i begudes/III jornadas gastronómicas de la cerveza.pdf` | PDF | 727.1 KiB | 54 | 1: 16, 28: 879, 54: 52 | 315.7 |
| `Tipus de Cuina/Cervesa i begudes/IV jornadas gastronómicas de la cerveza.pdf` | PDF | 5.63 MiB | 42 | 1: 0, 22: 1079, 42: 206 | 428.3 |
| `Tipus de Cuina/Cervesa i begudes/La guia del barman.epub` | EPUB | 91.6 KiB | 3 | 1: 5, 2: 68119, 3: 53767 | 40630.3 |
| `Tipus de Cuina/Cervesa i begudes/V jornadas gastronómicas de la cerveza.pdf` | PDF | 2.35 MiB | 44 | 1: 0, 23: 1142, 44: 194 | 445.3 |
| `Tipus de Cuina/Cervesa i begudes/Xavier Garcia La cerveza en España.epub` | EPUB | 2.05 MiB | 33 | 1: 5, 17: 45643, 33: 20 | 15222.7 |
| `Tipus de Cuina/Cervesa i begudes/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Cocina de aprovechamiento .epub` | EPUB | 8.04 MiB | 14 | 1: 5, 8: 6598, 14: 93 | 2232.0 |
| `Tipus de Cuina/Compotas & Conservas.pdf` | PDF | 43.89 MiB | 178 | 1: 0, 90: 0, 178: 0 | 0.0 |
| `Tipus de Cuina/Conserves/COCINA CON CONSERVAS.pdf` | PDF | 1.66 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Tipus de Cuina/Conserves/Conservas de fruta y verdura.pdf` | PDF | 2.34 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Tipus de Cuina/Conserves/Cursos prácticos Conservas saladas y dulces.pdf` | PDF | 3.93 MiB | 22 | 1: 0, 12: 36, 22: 36 | 24.0 |
| `Tipus de Cuina/Conserves/José Maillet El confitero moderno.pdf` | PDF | 56.06 MiB | 163 | 1: 342, 82: 2586, 163: 123 | 1017.0 |
| `Tipus de Cuina/Conserves/La botica de la abuela Tisanas y jarabes deliciosos.epub` | EPUB | 2.93 MiB | 2 | 1: 5, 2: 58 | 31.5 |
| `Tipus de Cuina/Conserves/Mermeladas y compotas.pdf` | PDF | 2.08 MiB | 36 | 1: 60, 19: 21, 36: 21 | 34.0 |
| `Tipus de Cuina/Conserves/Oded Schwartz Conservas.pdf` | PDF | 25.46 MiB | 112 | 1: 0, 57: 0, 112: 0 | 0.0 |
| `Tipus de Cuina/Conserves/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/DESAYUNOS.PARA SOÑAR.pdf` | PDF | 1.46 MiB | 14 | 1: 190, 8: 743, 14: 512 | 481.7 |
| `Tipus de Cuina/El Gran Libro De La Cocina Rapida - Paola Sala.pdf` | PDF | 15.28 MiB | 513 | 1: 0, 257: 191, 513: 114 | 101.7 |
| `Tipus de Cuina/El_Pan_Manual_De_Técnicas_Y_Recetas_De_Panadería_Jeffrey_Hamelman.pdf` | PDF | 15.85 MiB | 720 | 1: 0, 361: 1311, 720: 1165 | 825.3 |
| `Tipus de Cuina/Entrepans/Carlos Crespo Un buen bocadillo.epub` | EPUB | 8.71 MiB | 13 | 1: 8, 7: 178471, 13: 82 | 59520.3 |
| `Tipus de Cuina/Entrepans/Cocina al instante Bocatas a la carta.pdf` | PDF | 2.76 MiB | 60 | 1: 0, 31: 0, 60: 0 | 0.0 |
| `Tipus de Cuina/Entrepans/Cocina para llevar Bocadillos.pdf` | PDF | 3.05 MiB | 25 | 1: 7, 13: 8, 25: 8 | 7.7 |
| `Tipus de Cuina/Entrepans/Un buen bocadillo - Carlos Crespo.epub` | EPUB | 8.71 MiB | 13 | 1: 8, 7: 178471, 13: 82 | 59520.3 |
| `Tipus de Cuina/Entrepans/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Eva y Ulrich Klever El gran libro de las fondues.pdf` | PDF | 4.69 MiB | 128 | 1: 0, 65: 3940, 128: 0 | 1313.3 |
| `Tipus de Cuina/Festa/@malu320    04-19-Gourmet.pdf` | PDF | 11.01 MiB | 84 | 1: 0, 43: 1518, 84: 0 | 506.0 |
| `Tipus de Cuina/Festa/Aperitivos y canapes.pdf` | PDF | 3.96 MiB | 19 | 1: 69, 10: 70, 19: 70 | 69.7 |
| `Tipus de Cuina/Festa/Carnevale salato.pdf` | PDF | 2.17 MiB | 25 | 1: 0, 13: 0, 25: 0 | 0.0 |
| `Tipus de Cuina/Festa/Carolina Ferrer Menú de fiestas.pdf` | PDF | 6.82 MiB | 68 | 1: 0, 35: 0, 68: 0 | 0.0 |
| `Tipus de Cuina/Festa/Como cocinar aperitivos y entrantes.pdf` | PDF | 130.2 KiB | 14 | 1: 2384, 8: 2053, 14: 1555 | 1997.3 |
| `Tipus de Cuina/Festa/Darwin Solorzano Cocina para sorprender.epub` | EPUB | 755.1 KiB | 335 | 1: 5, 168: 34, 335: 11 | 16.7 |
| `Tipus de Cuina/Festa/La marquesa de Parabere Entremeses, aperitivos y ensaladas.pdf` | PDF | 79.54 MiB | 117 | 1: 84, 59: 2766, 117: 2695 | 1848.3 |
| `Tipus de Cuina/Festa/Maria Jesus Gil de Antuñano Cocina para invitados.pdf` | PDF | 2.34 MiB | 71 | 1: 107, 36: 1560, 71: 7405 | 3024.0 |
| `Tipus de Cuina/Festa/NGV Bocados para fiestas.epub` | EPUB | 12.18 MiB | 2 | 1: 5, 2: 20 | 12.5 |
| `Tipus de Cuina/Festa/RECIBIR CON ARTE.pdf` | PDF | 1.21 MiB | 12 | 1: 193, 7: 1962, 12: 723 | 959.3 |
| `Tipus de Cuina/Festa/Recetas para un día especial.pdf` | PDF | 10.84 MiB | 40 | 1: 0, 21: 0, 40: 0 | 0.0 |
| `Tipus de Cuina/Festa/SORPRENDE A  TUS INVITADOS.pdf` | PDF | 12.50 MiB | 147 | 1: 229, 74: 1995, 147: 947 | 1057.0 |
| `Tipus de Cuina/Festa/Taller comida de fiesta Verano 2019.pdf` | PDF | 1.28 MiB | 7 | 1: 37, 4: 0, 7: 0 | 12.3 |
| `Tipus de Cuina/Festa/UN TOQUE GOURMET.pdf` | PDF | 1.30 MiB | 14 | 1: 208, 8: 874, 14: 366 | 482.7 |
| `Tipus de Cuina/Festa/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Food.Heaven.Presents.Bread.2020.pdf` | PDF | 71.33 MiB | 100 | 1: 23, 51: 0, 100: 32 | 18.3 |
| `Tipus de Cuina/Fàcil/21 recetas de primavera (cocina para emancipados).pdf` | PDF | 5.53 MiB | 48 | 1: 7, 25: 8, 48: 8 | 7.7 |
| `Tipus de Cuina/Fàcil/50 recetas de verano - cocina para emancipados.pdf` | PDF | 7.34 MiB | 46 | 1: 0, 24: 0, 46: 0 | 0.0 |
| `Tipus de Cuina/Fàcil/Angelita Alfaro Cocina para estudiantes.pdf` | PDF | 3.81 MiB | 202 | 1: 0, 102: 490, 202: 668 | 386.0 |
| `Tipus de Cuina/Fàcil/Cheap & cheerful.pdf` | PDF | 15.23 MiB | 71 | 1: 0, 36: 0, 71: 0 | 0.0 |
| `Tipus de Cuina/Fàcil/Cocina_Exotica_Al_Alcance_De_Todos.epub` | EPUB | 1.37 MiB | 55 | 1: 5, 28: 821, 55: 987 | 604.3 |
| `Tipus de Cuina/Fàcil/FÁCIL Y RÁPIDO VOL. II.pdf` | PDF | 1.33 MiB | 14 | 1: 195, 8: 686, 14: 411 | 430.7 |
| `Tipus de Cuina/Fàcil/FÁCIL Y RÁPIDO. VOL. I.pdf` | PDF | 1.08 MiB | 12 | 1: 186, 7: 1197, 12: 358 | 580.3 |
| `Tipus de Cuina/Fàcil/Gallina Blanca Cocina para papá.pdf` | PDF | 1.18 MiB | 30 | 1: 0, 16: 961, 30: 618 | 526.3 |
| `Tipus de Cuina/Fàcil/INSPIRACIÓN para el día a día.pdf` | PDF | 2.46 MiB | 8 | 1: 0, 5: 0, 8: 0 | 0.0 |
| `Tipus de Cuina/Fàcil/Ligeras para dos.pdf` | PDF | 1.25 MiB | 16 | 1: 21, 9: 21, 16: 21 | 21.0 |
| `Tipus de Cuina/Fàcil/Liz Franklin Platos exprés.pdf` | PDF | 10.91 MiB | 161 | 1: 0, 81: 0, 161: 0 | 0.0 |
| `Tipus de Cuina/Fàcil/Marcos H. S. Nosotros cocinamos recien casados.epub` | EPUB | 201.1 KiB | 3 | 1: 5, 2: 31, 3: 119684 | 39906.7 |
| `Tipus de Cuina/Fàcil/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Hamburguesa i fast food/BURGUERS THERMOMIX .pdf` | PDF | 1.60 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Brochetas fáciles y rápidas.pdf` | PDF | 1.97 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Burguers irresistibles.pdf` | PDF | 1.60 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Burguers saludables.pdf` | PDF | 2.86 MiB | 10 | 1: 0, 6: 0, 10: 0 | 0.0 |
| `Tipus de Cuina/Hamburguesa i fast food/FAST FOOD PARA SIBARITAS.pdf` | PDF | 1.61 MiB | 15 | 1: 205, 8: 874, 15: 459 | 512.7 |
| `Tipus de Cuina/Hamburguesa i fast food/Fast Food Saludable.pdf` | PDF | 1.53 MiB | 21 | 1: 21, 11: 21, 21: 21 | 21.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Food Truck una fiesta de sabores.pdf` | PDF | 24.85 MiB | 172 | 1: 0, 87: 0, 172: 0 | 0.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Food Truck.pdf` | PDF | 3.45 MiB | 14 | 1: 23, 8: 23, 14: 23 | 23.0 |
| `Tipus de Cuina/Hamburguesa i fast food/Hamburguesas Las mejores recetas.pdf` | PDF | 1.65 MiB | 8 | 1: 23, 5: 23, 8: 23 | 23.0 |
| `Tipus de Cuina/Hamburguesa i fast food/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Ibèric/III_jornadas_gastronómicas_del_iberico.pdf` | PDF | 929.2 KiB | 72 | 1: 18, 37: 1458, 72: 55 | 510.3 |
| `Tipus de Cuina/Ibèric/II_Jornadas_Gastronómicas_del_iberico.pdf` | PDF | 1.22 MiB | 64 | 1: 18, 33: 922, 64: 55 | 331.7 |
| `Tipus de Cuina/Ibèric/IV_jornadas_gastronómicas_del_iberico.pdf` | PDF | 1.49 MiB | 88 | 1: 38, 45: 1034, 88: 207 | 426.3 |
| `Tipus de Cuina/Ibèric/V_jornadas_gastronómicas_del_iberico.pdf` | PDF | 4.55 MiB | 76 | 1: 83, 39: 951, 76: 208 | 414.0 |
| `Tipus de Cuina/Ibèric/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Julia Osuna Cocina canalla.epub` | EPUB | 39.59 MiB | 247 | 1: 35, 124: 54, 247: 42 | 43.7 |
| `Tipus de Cuina/LIGERAS.pdf` | PDF | 1.37 MiB | 14 | 1: 188, 8: 778, 14: 444 | 470.0 |
| `Tipus de Cuina/Las_mejores_recetas_con_marihuana.pdf` | PDF | 2.11 MiB | 320 | 1: 0, 161: 586, 320: 226 | 270.7 |
| `Tipus de Cuina/M. Palla Entrantes y entremeses.pdf` | PDF | 13.55 MiB | 32 | 1: 0, 17: 0, 32: 0 | 0.0 |
| `Tipus de Cuina/MENÚS COMPLETOS.pdf` | PDF | 1.36 MiB | 13 | 1: 164, 7: 2290, 13: 507 | 987.0 |
| `Tipus de Cuina/María Victoria Llamas El libro del microondas.pdf` | PDF | 9.74 MiB | 160 | 1: 0, 81: 0, 160: 0 | 0.0 |
| `Tipus de Cuina/Masas Editable.docx` | DOCX | 5.77 MiB | n/a | 1: 939257 | 939257.0 |
| `Tipus de Cuina/Masas Editable.pdf` | PDF | 16.03 MiB | 276 | 1: 0, 139: 2411, 276: 0 | 803.7 |
| `Tipus de Cuina/MasterChef Cocina de aprovechamiento.epub` | EPUB | 8.04 MiB | 14 | 1: 5, 8: 6598, 14: 93 | 2232.0 |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de alta proteína.epub` | EPUB | 145.0 KiB | 52 | 1: 5, 27: 638, 52: 1244 | 629.0 |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de cocción lenta con carne.epub` | EPUB | 142.1 KiB | 52 | 1: 5, 27: 815, 52: 1056 | 625.3 |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de enchiladas.epub` | EPUB | 153.1 KiB | 53 | 1: 5, 27: 1304, 53: 1377 | 895.3 |
| `Tipus de Cuina/Nadal/Blanca Navidad.pdf` | PDF | 14.25 MiB | 112 | 1: 21, 57: 21, 112: 21 | 21.0 |
| `Tipus de Cuina/Nadal/Buffet Navideño.pdf` | PDF | 25.48 MiB | 143 | 1: 0, 72: 0, 143: 0 | 0.0 |
| `Tipus de Cuina/Nadal/Cocina para emancipados Recetas de Navidad 2016.pdf` | PDF | 44.68 MiB | 83 | 1: 62, 42: 1546, 83: 19 | 542.3 |
| `Tipus de Cuina/Nadal/Enric Monzonis Recetas de Navidad 2017.pdf` | PDF | 6.03 MiB | 12 | 1: 40, 7: 1, 12: 127 | 56.0 |
| `Tipus de Cuina/Nadal/Feliz Navidad.pdf` | PDF | 2.80 MiB | 38 | 1: 21, 20: 21, 38: 21 | 21.0 |
| `Tipus de Cuina/Nadal/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Oggi... frutta.pdf` | PDF | 11.08 MiB | 135 | 1: 0, 68: 0, 135: 0 | 0.0 |
| `Tipus de Cuina/Pa/22.- Pan Bolleria.Johnnygan.pdf` | PDF | 17.34 MiB | 62 | 1: 0, 32: 1442, 62: 788 | 743.3 |
| `Tipus de Cuina/Pa/Elaboració casolana de pa i pastes.epub` | EPUB | 4.03 MiB | 1 | 1: 34 | 34.0 |
| `Tipus de Cuina/Pa/Elaboración Artesanal del Pan.pdf` | PDF | 27.14 MiB | 175 | 1: 0, 88: 0, 175: 0 | 0.0 |
| `Tipus de Cuina/Pa/Maria Lunarillos Panes.pdf` | PDF | 6.99 MiB | 37 | 1: 0, 19: 0, 37: 0 | 0.0 |
| `Tipus de Cuina/Pa/Panes creativos.pdf` | PDF | 4.74 MiB | 66 | 1: 21, 34: 21, 66: 21 | 21.0 |
| `Tipus de Cuina/Pa/Rolando Alvarado Manual de formulas y saberes de panadería.epub` | EPUB | 303.8 KiB | 7 | 1: 5, 4: 2223, 7: 29753 | 10660.3 |
| `Tipus de Cuina/Pa/Rosa Tovar Masas.pdf` | PDF | 11.53 MiB | 276 | 1: 0, 139: 0, 276: 0 | 0.0 |
| `Tipus de Cuina/Pa/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Pa/el libro del pan 1.pdf` | PDF | 20.38 MiB | 122 | 1: 0, 62: 0, 122: 0 | 0.0 |
| `Tipus de Cuina/Pa/Área Gastronomía Manual de panadería.pdf` | PDF | 818.9 KiB | 31 | 1: 21, 16: 1584, 31: 291 | 632.0 |
| `Tipus de Cuina/Paco Blanco Crockpot.epub` | EPUB | 198.6 KiB | 30 | 1: 5, 16: 1739, 30: 28 | 590.7 |
| `Tipus de Cuina/Para untar.pdf` | PDF | 2.12 MiB | 35 | 1: 21, 18: 21, 35: 21 | 21.0 |
| `Tipus de Cuina/Pasta/Ema García Recetas de pasta y fideos.epub` | EPUB | 1.31 MiB | 1412 | 1: 5, 707: 341, 1412: 1498 | 614.7 |
| `Tipus de Cuina/Pasta/Ema García Recetas de plato principal de pasta.pdf` | PDF | 103.61 MiB | 1516 | 1: 0, 759: 420, 1516: 397 | 272.3 |
| `Tipus de Cuina/Pasta/Masas saladas.pdf` | PDF | 4.27 MiB | 64 | 1: 21, 33: 21, 64: 21 | 21.0 |
| `Tipus de Cuina/Pasta/Monica Ponttiroli Pastas caseras.epub` | EPUB | 826.6 KiB | 25 | 1: 5, 13: 2005, 25: 1528 | 1179.3 |
| `Tipus de Cuina/Pasta/Nicol Pardo Pizzas y pastas.epub` | EPUB | 7.40 MiB | 2 | 1: 5, 2: 22433 | 11219.0 |
| `Tipus de Cuina/Pasta/TODO PASTA.pdf` | PDF | 2.25 MiB | 24 | 1: 184, 13: 2118, 24: 836 | 1046.0 |
| `Tipus de Cuina/Pasta/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Pasta/🇮🇹. Pizza e Pasta Italiana. January 2020.pdf` | PDF | 26.06 MiB | 132 | 1: 47, 67: 0, 132: 0 | 15.7 |
| `Tipus de Cuina/Per Endur/20 Recetas express para un mes de tupper.pdf` | PDF | 340.5 KiB | 21 | 1: 0, 11: 469, 21: 942 | 470.3 |
| `Tipus de Cuina/Per Endur/Cocina para llevar al trabajo.pdf` | PDF | 2.35 MiB | 28 | 1: 0, 15: 668, 28: 709 | 459.0 |
| `Tipus de Cuina/Per Endur/De rechupete Recetas de táper para el curro.mobi` | MOBI | 13.65 MiB | n/a | n/a | n/a |
| `Tipus de Cuina/Per Endur/Gallina Blanca Cocina para llevar al trabajo.pdf` | PDF | 2.35 MiB | 28 | 1: 0, 15: 668, 28: 709 | 459.0 |
| `Tipus de Cuina/Per Endur/Lunch Box.pdf` | PDF | 3.35 MiB | 45 | 1: 0, 23: 0, 45: 0 | 0.0 |
| `Tipus de Cuina/Per Endur/PARA LLEVAR (2).pdf` | PDF | 3.71 MiB | 22 | 1: 11, 12: 1268, 22: 678 | 652.3 |
| `Tipus de Cuina/Per Endur/Para llevar Comer fuera como en casa.pdf` | PDF | 324.7 KiB | 16 | 1: 1426, 9: 774, 16: 0 | 733.3 |
| `Tipus de Cuina/Per Endur/Para llevar de picnic.pdf` | PDF | 4.31 MiB | 59 | 1: 97, 30: 719, 59: 21 | 279.0 |
| `Tipus de Cuina/Per Endur/Para llevar.pdf` | PDF | 3.05 MiB | 25 | 1: 7, 13: 8, 25: 8 | 7.7 |
| `Tipus de Cuina/Per Endur/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Per Endur/recetario_picnic.pdf` | PDF | 2.14 MiB | 48 | 1: 22, 25: 1952, 48: 706 | 893.3 |
| `Tipus de Cuina/Pescado y marisco.epub` | EPUB | 5.31 MiB | 1 | 1: 10 | 10.0 |
| `Tipus de Cuina/Pescado ¡ Buen provecho !.epub` | EPUB | 544.6 KiB | 2 | 1: 5, 2: 5 | 5.0 |
| `Tipus de Cuina/Pescados y mariscos.pdf` | PDF | 3.68 MiB | 57 | 1: 21, 29: 293, 57: 21 | 111.7 |
| `Tipus de Cuina/Pizza/Maxine Clark Pizza, calzone & Focaccia.pdf` | PDF | 8.16 MiB | 143 | 1: 0, 72: 0, 143: 0 | 0.0 |
| `Tipus de Cuina/Pizza/Nicol Pardo Pizzas y pastas.epub` | EPUB | 7.40 MiB | 2 | 1: 5, 2: 22433 | 11219.0 |
| `Tipus de Cuina/Pizza/Pizza e Pasta Italiana Febbraio 2020.pdf` | PDF | 19.83 MiB | 100 | 1: 89, 51: 89, 100: 89 | 89.0 |
| `Tipus de Cuina/Pizza/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Pizza/🇮🇹. Pizza e Pasta Italiana. January 2020.pdf` | PDF | 26.06 MiB | 132 | 1: 47, 67: 0, 132: 0 | 15.7 |
| `Tipus de Cuina/RECETARIO DE BATIDOS.pdf` | PDF | 1.21 MiB | 35 | 1: 60, 18: 248, 35: 164 | 157.3 |
| `Tipus de Cuina/RECETAS PRODUCTOS DEL MAR.pdf` | PDF | 5.73 MiB | 73 | 1: 33, 37: 1202, 73: 1045 | 760.0 |
| `Tipus de Cuina/RICO BATIDO. MADE IN USA.pdf` | PDF | 1.21 MiB | 14 | 1: 215, 8: 967, 14: 375 | 519.0 |
| `Tipus de Cuina/Raw Food.pdf` | PDF | 1.18 MiB | 17 | 1: 21, 9: 21, 17: 21 | 21.0 |
| `Tipus de Cuina/Recetas de patés.pdf` | PDF | 102.9 KiB | 3 | 1: 1134, 2: 930, 3: 1072 | 1045.3 |
| `Tipus de Cuina/Recetas de pescados.pdf` | PDF | 406.2 KiB | 10 | 1: 2593, 6: 2830, 10: 1358 | 2260.3 |
| `Tipus de Cuina/Recetas de zumos.pdf` | PDF | 1.44 MiB | 11 | 1: 1462, 6: 1390, 11: 1851 | 1567.7 |
| `Tipus de Cuina/Recetas_Saludables_Julio_2017 (1).pdf` | PDF | 3.82 MiB | 44 | 1: 86, 23: 279, 44: 985 | 450.0 |
| `Tipus de Cuina/Roberto Peralta Los secretos de la cocina con microondas.epub` | EPUB | 157.0 KiB | 103 | 1: 5, 52: 1009, 103: 664 | 559.3 |
| `Tipus de Cuina/SIN LACTOSA.pdf` | PDF | 1.45 MiB | 13 | 1: 219, 7: 1241, 13: 472 | 644.0 |
| `Tipus de Cuina/Sabor a bosque.pdf` | PDF | 2.08 MiB | 27 | 1: 21, 14: 21, 27: 21 | 21.0 |
| `Tipus de Cuina/Salses/Claudia_Viviana_Hernández_Salsas.epub` | EPUB | 3.04 MiB | 70 | 1: 5, 36: 31, 70: 2836 | 957.3 |
| `Tipus de Cuina/Salses/El monstruo de las recetas 70 recetas de salsas fáciles.pdf` | PDF | 8.24 MiB | 161 | 1: 0, 81: 432, 161: 763 | 398.3 |
| `Tipus de Cuina/Salses/Giorgio Stuart Las mejores salsas.epub` | EPUB | 253.5 KiB | 202 | 1: 5, 102: 490, 202: 4282 | 1592.3 |
| `Tipus de Cuina/Salses/José María Campos La elaboración de las salsas.pdf` | PDF | 12.06 MiB | 102 | 1: 0, 52: 0, 102: 0 | 0.0 |
| `Tipus de Cuina/Salses/Modern_Sauces_More_than_150_Recipes_for_Every_Cook,_Every_Day_Martha.epub` | EPUB | 1.95 MiB | 159 | 1: 5, 80: 1897, 159: 86 | 662.7 |
| `Tipus de Cuina/Salses/Muchogusto.net Recetas caseras de salsas para pastas.pdf` | PDF | 1.28 MiB | 21 | 1: 52, 11: 1511, 21: 1440 | 1001.0 |
| `Tipus de Cuina/Salses/Practilibros Salsas y vinagretas.pdf` | PDF | 604.8 KiB | 134 | 1: 0, 68: 211, 134: 198 | 136.3 |
| `Tipus de Cuina/Salses/Recetario Especial Sofritos.pdf` | PDF | 2.39 MiB | 33 | 1: 0, 17: 881, 33: 712 | 531.0 |
| `Tipus de Cuina/Salses/Salsas, pan y queso.epub` | EPUB | 3.61 MiB | 1 | 1: 10 | 10.0 |
| `Tipus de Cuina/Salses/Salse.pdf` | PDF | 3.49 MiB | 34 | 1: 0, 18: 0, 34: 0 | 0.0 |
| `Tipus de Cuina/Salses/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Sano e leggero Piatti unici.pdf` | PDF | 2.55 MiB | 28 | 1: 0, 15: 0, 28: 0 | 0.0 |
| `Tipus de Cuina/Sapori di montagna.pdf` | PDF | 6.87 MiB | 74 | 1: 0, 38: 0, 74: 0 | 0.0 |
| `Tipus de Cuina/Secondi di carne.pdf` | PDF | 19.81 MiB | 149 | 1: 0, 75: 0, 149: 0 | 0.0 |
| `Tipus de Cuina/Sopa/Al calor de un caldo.pdf` | PDF | 1.48 MiB | 29 | 1: 21, 15: 21, 29: 21 | 21.0 |
| `Tipus de Cuina/Sopa/Aurora Abarca Las sopas de Aurora.epub` | EPUB | 178.0 KiB | 2 | 1: 5, 2: 80101 | 40053.0 |
| `Tipus de Cuina/Sopa/CREMAS CALIENTES VOLUMEN II.pdf` | PDF | 1.29 MiB | 18 | 1: 21, 10: 21, 18: 21 | 21.0 |
| `Tipus de Cuina/Sopa/CREMAS CALIENTES. VOL I.pdf` | PDF | 1.18 MiB | 14 | 1: 192, 8: 1194, 14: 391 | 592.3 |
| `Tipus de Cuina/Sopa/CREMAS Y SOPAS FRÍAS.pdf` | PDF | 1.21 MiB | 12 | 1: 241, 7: 924, 12: 356 | 507.0 |
| `Tipus de Cuina/Sopa/Cocina Popular Sopas poderosas.pdf` | PDF | 15.44 MiB | 42 | 1: 0, 22: 0, 42: 0 | 0.0 |
| `Tipus de Cuina/Sopa/Editorial Blume Selección culinaria Sopas.mobi` | MOBI | 4.60 MiB | n/a | n/a | n/a |
| `Tipus de Cuina/Sopa/SOPAS CON TROPEZÓN.pdf` | PDF | 1.49 MiB | 22 | 1: 21, 12: 21, 22: 21 | 21.0 |
| `Tipus de Cuina/Sopa/Sopas (Selección culinaria).pdf` | PDF | 45.71 MiB | 82 | 1: 0, 42: 0, 82: 0 | 0.0 |
| `Tipus de Cuina/Sopa/Sopas Detox - Nicole Pisani y Kate Adams.pdf` | PDF | 4.39 MiB | 297 | 1: 0, 149: 1275, 297: 261 | 512.0 |
| `Tipus de Cuina/Sopa/Sopas Exquisitas.pdf` | PDF | 8.17 MiB | 218 | 1: 0, 110: 0, 218: 0 | 0.0 |
| `Tipus de Cuina/Sopa/Sopas frías. Refrescate con cuchara.pdf` | PDF | 2.36 MiB | 48 | 1: 21, 25: 21, 48: 21 | 21.0 |
| `Tipus de Cuina/Sopa/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Sopa/doce-recetas-de-gazpacho-ajoblanco-y-sopas-frias (1).pdf` | PDF | 730.3 KiB | 19 | 1: 58, 10: 1323, 19: 1730 | 1037.0 |
| `Tipus de Cuina/Supermaxi Los secretos de la carne.pdf` | PDF | 12.68 MiB | 129 | 1: 51, 65: 941, 129: 1990 | 994.0 |
| `Tipus de Cuina/Tapes/101 recetas de tapas.pdf` | PDF | 298.8 KiB | 34 | 1: 2719, 18: 2804, 34: 368 | 1963.7 |
| `Tipus de Cuina/Tapes/DE TAPEO. APERITIVOS Y TAPAS.pdf` | PDF | 1.50 MiB | 15 | 1: 176, 8: 2388, 15: 523 | 1029.0 |
| `Tipus de Cuina/Tapes/De Tapas Con Quique Dacosta.pdf` | PDF | 15.06 MiB | 342 | 1: 0, 172: 1030, 342: 46 | 358.7 |
| `Tipus de Cuina/Tapes/Gallina_Blanca_Aperitivos_para_deleitar.pdf` | PDF | 1.76 MiB | 47 | 1: 0, 24: 415, 47: 405 | 273.3 |
| `Tipus de Cuina/Tapes/Mundorecetas Recetas saladas de picoteo 1ª parte.pdf` | PDF | 6.27 MiB | 130 | 1: 48, 66: 963, 130: 0 | 337.0 |
| `Tipus de Cuina/Tapes/Mundorecetas Recetas saladas de picoteo 2ª parte.pdf` | PDF | 5.44 MiB | 119 | 1: 43, 60: 643, 119: 674 | 453.3 |
| `Tipus de Cuina/Tapes/Pedrito Rico Tapas Gourmet.epub` | EPUB | 1.22 MiB | 91 | 1: 5, 46: 932, 91: 106 | 347.7 |
| `Tipus de Cuina/Tapes/Pedro Martín Donosti pintxo a pintxo.epub` | EPUB | 116.7 KiB | 5 | 1: 5, 3: 60, 5: 83394 | 27819.7 |
| `Tipus de Cuina/Tapes/Recetario aperitivos y canapés.pdf` | PDF | 2.29 MiB | 10 | 1: 68, 6: 68, 10: 69 | 68.3 |
| `Tipus de Cuina/Tapes/Recetario blog Exquisit Ideas para picar.pdf` | PDF | 16.51 MiB | 98 | 1: 63, 50: 1284, 98: 340 | 562.3 |
| `Tipus de Cuina/Tapes/Salvador Arimany Canapès a l'abast de tothom.pdf` | PDF | 7.87 MiB | 138 | 1: 0, 70: 0, 138: 0 | 0.0 |
| `Tipus de Cuina/Tapes/Santiago(e)Tapas.pdf` | PDF | 8.13 MiB | 300 | 1: 0, 151: 3, 300: 0 | 1.0 |
| `Tipus de Cuina/Tapes/Sylvie Ait-Ali 30 recetas de aperitivos para cenar.epub` | EPUB | 83.9 KiB | 3 | 1: 5, 2: 33149, 3: 756 | 11303.3 |
| `Tipus de Cuina/Tapes/Tapas & Pinchos.pdf` | PDF | 224.7 KiB | 39 | 1: 2650, 20: 2257, 39: 19 | 1642.0 |
| `Tipus de Cuina/Tapes/Tapas con rock 'n' roll - Jordi Cruz.epub` | EPUB | 12.35 MiB | 13 | 1: 7, 7: 47828, 13: 4105 | 17313.3 |
| `Tipus de Cuina/Tapes/Tapas y Montaditos.pdf` | PDF | 1.60 MiB | 21 | 1: 58, 11: 392, 21: 377 | 275.7 |
| `Tipus de Cuina/Tapes/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Temporada/Chef Oropeza Sabores de verano.pdf` | PDF | 4.48 MiB | 52 | 1: 19, 27: 4, 52: 43 | 22.0 |
| `Tipus de Cuina/Temporada/Cocina con aroma a Primavera.pdf` | PDF | 3.36 MiB | 32 | 1: 0, 17: 743, 32: 1359 | 700.7 |
| `Tipus de Cuina/Temporada/Primavera.pdf` | PDF | 3.99 MiB | 67 | 1: 21, 34: 21, 67: 21 | 21.0 |
| `Tipus de Cuina/Temporada/Verano Recetas de temporada.pdf` | PDF | 1.57 MiB | 23 | 1: 21, 12: 21, 23: 21 | 21.0 |
| `Tipus de Cuina/Temporada/desktop.ini` | INI | 0.2 KiB | n/a | n/a | n/a |
| `Tipus de Cuina/Temporada/temporada_octubre.pdf` | PDF | 1.01 MiB | 2 | 1: 331, 2: 1163 | 747.0 |
| `Vegetariana/500 Recetas Vegetarianas - Sandra figueroa y Consuelo Bedoya.pdf` | PDF | 1.41 MiB | 432 | 1: 0, 217: 879, 432: 851 | 576.7 |
| `Vegetariana/@malu320    04-19-Cocina Vegana.pdf` | PDF | 23.42 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/@malu320   Cocina Vegetariana - abril 2019.pdf` | PDF | 48.46 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/@malu320 05-19-Cocina Vegetariana.pdf` | PDF | 19.47 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/@malu320 05-19-Extra Cocina Vegetariana.pdf` | PDF | 20.33 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/@malu320-Cocina Vegana - febrero 2019(1).pdf` | PDF | 49.62 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/Ana Moreno Curso completo de cocina vegetariana.pdf` | PDF | 180.1 KiB | 49 | 1: 41, 25: 2188, 49: 45 | 758.0 |
| `Vegetariana/Antonio Castellanos Top 30 recetas veganas.epub` | EPUB | 2.07 MiB | 47 | 1: 5, 24: 314, 47: 511 | 276.7 |
| `Vegetariana/COCINA  VEGETARIANA.pdf` | PDF | 1.69 MiB | 17 | 1: 198, 9: 1605, 17: 591 | 798.0 |
| `Vegetariana/COCINA VEGETARIANA VOL II.pdf` | PDF | 1.44 MiB | 15 | 1: 212, 8: 1766, 15: 434 | 804.0 |
| `Vegetariana/COCINA VEGETARIANA.pdf` | PDF | 1.69 MiB | 17 | 1: 198, 9: 1605, 17: 591 | 798.0 |
| `Vegetariana/Cocina Vegetariana - abril 2020.pdf` | PDF | 80.14 MiB | 100 | 1: 445, 51: 129, 100: 42 | 205.3 |
| `Vegetariana/Cocina Vegetariana 02-20.pdf` | PDF | 23.69 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/Cocina Vegetariana Platos principales.pdf` | PDF | 1.95 MiB | 40 | 1: 21, 21: 21, 40: 21 | 21.0 |
| `Vegetariana/Cocina Vegetariana Recetas rápidas.pdf` | PDF | 1.27 MiB | 15 | 1: 21, 8: 21, 15: 21 | 21.0 |
| `Vegetariana/Cocina Verde - Rodrigo de la Calle.pdf` | PDF | 23.17 MiB | 424 | 1: 0, 213: 1477, 424: 0 | 492.3 |
| `Vegetariana/Cocina fácil para vegetarianos y veganos.pdf` | PDF | 1.56 MiB | 68 | 1: 0, 35: 977, 68: 0 | 325.7 |
| `Vegetariana/Cocina vegetariana (2).pdf` | PDF | 15.44 MiB | 76 | 1: 21, 39: 21, 76: 21 | 21.0 |
| `Vegetariana/Cocina vegetariana cookidoo.pdf` | PDF | 15.44 MiB | 76 | 1: 21, 39: 21, 76: 21 | 21.0 |
| `Vegetariana/CreatiVegan Como hacer galletas veganas.pdf` | PDF | 6.43 MiB | 96 | 1: 111, 49: 1612, 96: 123 | 615.3 |
| `Vegetariana/CreatiVegan Menú de Navidad 2011.pdf` | PDF | 4.95 MiB | 12 | 1: 20, 7: 2711, 12: 2209 | 1646.7 |
| `Vegetariana/CreatiVegan Menú de Navidad 2012.pdf` | PDF | 14.73 MiB | 27 | 1: 36, 14: 3505, 27: 151 | 1230.7 |
| `Vegetariana/CreatiVegan Minirecetario especial Biocultura.pdf` | PDF | 351.0 KiB | 2 | 1: 2369, 2: 6201 | 4285.0 |
| `Vegetariana/CreatiVegan Navidad 2016.pdf` | PDF | 1.63 MiB | 46 | 1: 138, 24: 1470, 46: 449 | 685.7 |
| `Vegetariana/CreatiVegan Recetario festivo 2013.pdf` | PDF | 15.09 MiB | 152 | 1: 33, 77: 20, 152: 146 | 66.3 |
| `Vegetariana/CreatiVegan Recetario vegano nochevieja y año nuevo.pdf` | PDF | 1.00 MiB | 5 | 1: 985, 3: 3677, 5: 3310 | 2657.3 |
| `Vegetariana/CreatiVegan Recetas festivas 2014.pdf` | PDF | 13.20 MiB | 108 | 1: 51, 55: 2111, 108: 3 | 721.7 |
| `Vegetariana/Dr. Eduardo Alfonso Cocina vegetariana.pdf` | PDF | 23.40 MiB | 35 | 1: 25, 18: 3841, 35: 3898 | 2588.0 |
| `Vegetariana/Dulces navideños veganos.pdf` | PDF | 2.43 MiB | 21 | 1: 181, 11: 1151, 21: 0 | 444.0 |
| `Vegetariana/Gigi Ro Las mejores hamburguesas veganas y vegetarianas.pdf` | PDF | 2.85 MiB | 237 | 1: 0, 119: 540, 237: 13 | 184.3 |
| `Vegetariana/Guia de iniciación de dieta vegetariana.pdf` | PDF | 1.25 MiB | 9 | 1: 223, 5: 4079, 9: 1921 | 2074.3 |
| `Vegetariana/Ignacio Domenech La cocina vegetariana moderna.pdf` | PDF | 39.45 MiB | 66 | 1: 32, 34: 2090, 66: 0 | 707.3 |
| `Vegetariana/Jack Norris Veganos para siempre.pdf` | PDF | 3.15 MiB | 232 | 1: 0, 117: 2589, 232: 441 | 1010.0 |
| `Vegetariana/La cocina vegetariana de Marta.pdf` | PDF | 489.9 KiB | 91 | 1: 239, 46: 524, 91: 725 | 496.0 |
| `Vegetariana/Michael Chung La biblia de smoothies verdes.epub` | EPUB | 130.6 KiB | 51 | 1: 5, 26: 830, 51: 504 | 446.3 |
| `Vegetariana/Noemí Cervantes 50 recetas vegetarianas.epub` | EPUB | 863.5 KiB | 53 | 1: 5, 27: 695, 53: 1551 | 750.3 |
| `Vegetariana/Pasqua vegetariana.pdf` | PDF | 6.12 MiB | 75 | 1: 0, 38: 0, 75: 0 | 0.0 |
| `Vegetariana/Pequeña biblia de la cocina vegetariana.pdf` | PDF | 6.45 MiB | 52 | 1: 64, 27: 64, 52: 64 | 64.0 |
| `Vegetariana/REVISTASGOLD22K-COCINAVEGETARIANA.pdf` | PDF | 25.42 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/REVISTASGOLD29K.12-18-cvegetariana-byneon.pdf` | PDF | 22.71 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/Recetario Granvita 2017.pdf` | PDF | 4.71 MiB | 74 | 1: 23, 38: 57, 74: 44 | 41.3 |
| `Vegetariana/Recetario vegano.pdf` | PDF | 3.23 MiB | 30 | 1: 0, 16: 2376, 30: 0 | 792.0 |
| `Vegetariana/Recetario vegetariano internacional.pdf` | PDF | 207.8 KiB | 21 | 1: 1800, 11: 3662, 21: 870 | 2110.7 |
| `Vegetariana/Recetas vegetarianas fáciles Parte I.pdf` | PDF | 163.3 KiB | 25 | 1: 36, 13: 1533, 25: 897 | 822.0 |
| `Vegetariana/Recetas vegetarianas fáciles Parte II.pdf` | PDF | 156.8 KiB | 21 | 1: 37, 11: 2688, 21: 1541 | 1422.0 |
| `Vegetariana/Ricas recetas veganas con sabor latino.epub` | EPUB | 135.7 KiB | 34 | 1: 5, 18: 2856, 34: 2764 | 1875.0 |
| `Vegetariana/SOY VEGANO. VOL II.pdf` | PDF | 1.33 MiB | 14 | 1: 226, 8: 2040, 14: 364 | 876.7 |
| `Vegetariana/SOY VEGANO.pdf` | PDF | 1.59 MiB | 17 | 1: 192, 9: 1607, 17: 547 | 782.0 |
| `Vegetariana/Sally Reyes Dieta vegana.epub` | EPUB | 219.9 KiB | 3 | 1: 5, 2: 135573, 3: 148684 | 94754.0 |
| `Vegetariana/Sandra Figueroa de Castro Cocina vegetariana.pdf` | PDF | 7.69 MiB | 326 | 1: 0, 164: 1300, 326: 172 | 490.7 |
| `Vegetariana/Soy Vegano vol III.pdf` | PDF | 1.23 MiB | 17 | 1: 21, 9: 21, 17: 21 | 21.0 |
| `Vegetariana/Stella Osterhoff Smoothies verdes.epub` | EPUB | 145.5 KiB | 42 | 1: 5, 22: 168, 42: 129 | 100.7 |
| `Vegetariana/Susaeta Cocina vegetariana.epub` | EPUB | 12.32 MiB | 2 | 1: 5, 2: 18 | 11.5 |
| `Vegetariana/Susaeta Recetas con verduras.pdf` | PDF | 21.41 MiB | 50 | 1: 0, 26: 0, 50: 0 | 0.0 |
| `Vegetariana/Vegetarian N27 MarzoAprile 2020 .pdf` | PDF | 48.97 MiB | 100 | 1: 907, 51: 1577, 100: 0 | 828.0 |
| `Vegetariana/Vida y cocina vegana nº 3.pdf` | PDF | 23.42 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/We Veg N62 Marzo 2020 .pdf` | PDF | 84.43 MiB | 100 | 1: 198, 51: 150, 100: 150 | 166.0 |
| `Vegetariana/Xabier Arguiñaz Cocina vegetariana.epub` | EPUB | 28.2 KiB | 11 | 1: 104, 6: 17748, 11: 2505 | 6785.7 |
| `Vegetariana/cocina vegetariana num 109.pdf` | PDF | 21.85 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 101.pdf` | PDF | 22.71 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 103.pdf` | PDF | 46.83 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 104.pdf` | PDF | 30.52 MiB | 100 | 1: 335, 51: 1685, 100: 0 | 673.3 |
| `Vegetariana/cocina vegetariana num. 105.pdf` | PDF | 19.86 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 106.pdf` | PDF | 19.47 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 108.pdf` | PDF | 43.69 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 22.pdf` | PDF | 31.15 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 42.pdf` | PDF | 9.38 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 43.pdf` | PDF | 19.04 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 44.pdf` | PDF | 23.42 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 45.pdf` | PDF | 24.22 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 46.pdf` | PDF | 9.01 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 47.pdf` | PDF | 18.68 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 48.pdf` | PDF | 16.07 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 49.pdf` | PDF | 16.34 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 50.pdf` | PDF | 8.90 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 51.pdf` | PDF | 27.64 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 52.pdf` | PDF | 15.96 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 53.pdf` | PDF | 9.24 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 55.pdf` | PDF | 18.81 MiB | 100 | 1: 21, 51: 21, 100: 21 | 21.0 |
| `Vegetariana/cocina vegetariana num. 57.pdf` | PDF | 21.27 MiB | 101 | 1: 0, 51: 0, 101: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 60.pdf` | PDF | 13.78 MiB | 100 | 1: 917, 51: 1883, 100: 0 | 933.3 |
| `Vegetariana/cocina vegetariana num. 62.pdf` | PDF | 13.12 MiB | 100 | 1: 864, 51: 3193, 100: 0 | 1352.3 |
| `Vegetariana/cocina vegetariana num. 63.pdf` | PDF | 26.76 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 94.pdf` | PDF | 41.32 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina vegetariana num. 95.pdf` | PDF | 51.76 MiB | 100 | 1: 71, 51: 2841, 100: 350 | 1087.3 |
| `Vegetariana/cocina vegetariana num. 97.pdf` | PDF | 25.42 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/cocina_vegetariana_2018_07_01.pdf` | PDF | 41.56 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/extra cocina vegetariana num. 03.pdf` | PDF | 100.11 MiB | 100 | 1: 7, 51: 7, 100: 7 | 7.0 |
| `Vegetariana/extra cocina vegetariana num. 19.pdf` | PDF | 42.47 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/extra cocina vegetariana num. 21.pdf` | PDF | 20.33 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/vida y cocina vegana nº 2.pdf` | PDF | 49.62 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/{RDL} 08-19-Cocina Vegetariana.pdf` | PDF | 21.85 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `Vegetariana/{RL} 01-20-Cocina Vegetarinana.pdf` | PDF | 22.21 MiB | 100 | 1: 0, 51: 0, 100: 0 | 0.0 |
| `temporada_octubre.pdf` | PDF | 1.01 MiB | 2 | 1: 331, 2: 1163 | 747.0 |

## Decisió d'ingesta

| Fitxer | Format | Text o escanejat | Format suportat? | Acció | Ingerit (sí/no) |
| --- | --- | --- | --- | --- | --- |
| `.gitkeep` | SENSE EXTENSI? | no aplicable | no | descartar | no |
| `Aliments/AVE QUE VUELA....pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Aguacate.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/BERBERECHOS.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bacallà/Bacalao Recetas de Portugal.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bacallà/Bacalhau para Todos.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bacallà/Biblioteca Lecturas 30 recetas en 30 minutos Bacalao.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bacallà/Toma bacalao.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bacallà/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Aliments/Bolets/8ª Jornadas gastronómicas de las setas y hongos.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Bolets/Comer bien Setas y hongos.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bolets/Jaume Prat Setas Del bosque a la mesa.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Bolets/Jose Ramon Ruiz La mejor receta para cada seta.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Bolets/Llorenç Petràs Cocinar con setas.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bolets/V Jornadas gastronómicas de setas y hongos.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Bolets/VI Jornadas gastronómicas setas y hongos.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Bolets/VII jornadas gastronómicas de setas & hongos.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Bolets/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Aliments/Borrajas.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/COCINA EN UN FISH FAST.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Caprabo Frutas.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Carmelo Perez Pequeña guia de setas comestibles.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Casquería.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Cocina con gusto Pollo & Aves.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Cocina popular Pescados y mariscos espectaculares.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Como cocinar fruta.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Con Miel.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/DEL MAR, EL CALAMAR.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/De segundo, carne.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/De segundo, pescado.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Denise Jarrett Chocolates.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/ESPECIAL CALABACÍN.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/ESPECIAL CALABAZA.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/El gran libro del huevo.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/El-Gran-Libro-de-las-Manzanas.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Especial Ajos.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Especial Conejo.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Especial berenjena.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Especial calabacin vol II.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Especial pollo II.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Especial pollo.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Espárragos blancos y verdes.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Felipe Luzón La cocina del mejillon.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Gallina blanca Recetario de patatas.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Hortalizas Otoño-Invierno.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Ideas para degustar la aceituna.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Joan Antoni Miró Con un par de huevos.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Kocinarte Recetas de carne.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/LIBRO+ARROCES+DE+ESPAÑA.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/La gran mariscada.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/La sandia recetas.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Legumbres.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Los chiles de México.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Los mejores quesos.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Maru Castilla Pollo gourmet.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Aliments/Montse Bradford Algas Las verduras del mar.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Montse Bradford Algas, las verduras del mar.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/OGGI BROCCOLI.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Pablo Battro Todo lo que siempre quiso saber sobre quesos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Aliments/Pollos al Horno Mediterráneo.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/RECETAS PRODUCTOS DEL MAR.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Recetario a base de cereales y otros granos.mobi` | MOBI | no aplicable | no | descartar | no |
| `Aliments/Salmón Cenas fáciles para el día a día.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Superfoods for Life, Cacao.epub` | EPUB | escanejat | no | descartar | no |
| `Aliments/Todo patata.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Todo queso.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/Todo verde.pdf` | PDF | escanejat | sí | descartar | no |
| `Aliments/VI_jornadas_gastronómicas_del_iberico.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/recetario-merluza.pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/recetas-chocolate (1).pdf` | PDF | text | sí | ingerir | sí |
| `Aliments/Ángel León Pescados azules.pdf` | PDF | escanejat | sí | descartar | no |
| `Cocció de marisc i crustacis.doc` | DOC | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/100% CRÊPES.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/100% FRESA.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/100% LASAÑA.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/100% PAPILLOTE.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/100% tomate.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/20 recetas navideñas Platos vegetarianos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/20 recetas navideñas para preparar postres helados.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/30 recetas en 30 minutos Ensaladas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/30 recetas en 30 minutos Pastas y arroces.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/@malu320   Cocina Facil 2019-04-01.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Ada Parellada La cocina sostenible.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Anna Helm Ensaladas en frasco.epub` | EPUB | escanejat | no | descartar | no |
| `Col·leccions/Anne Wilson Aperitivos y entrantes.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Cocina asiática vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Cocina vegetariana rápida.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Cocinar con wok.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Guisos y cazuelas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Las mejores recetas de Asia.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Pizzas y gratinados.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Recetas de patatas populares.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Anne Wilson Sopas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Biblioteca Lecturas 30 recetas en 30 minutos Mousses.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Biblioteca lecturas 30 recetas en 30 minutos Pollo.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (2).pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (3).pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en (4).pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Biblioteca_Lecturas_30_recetas_en.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Bimbo Recetas de Cuaresma.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Buen Provecho num. 143 Enero 2017.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 22 Junio-Julio 2016.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 59 Diciembre 2014.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 61 Febrero 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 62 Marzo 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 63 Abril 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 65 Junio 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 66 Julio 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 69 Octubre 2015.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Cocina Semana num. 70 Noviembre 2015.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 71 Diciembre 2015.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Cocina Semana num. 79 Agosto 2016.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina Semana num. 80 Septiembre 2016.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina fácil Comida tipica mexicana.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina fácil Edición especial Bocadillos.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina fácil Fabulosos postres.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina fácil Todo al horno.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina fácil lecturas num. 231.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina ilustrada Cocina fácil y rápida.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Cocina semana num. 74 Marzo 2016.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gallina Blanca Cocinar con microondas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Del mar a la mesa.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Las sopas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Platos fáciles y económicos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario Platos ligeros.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de ensaladas veraniegas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de las colaboradoras.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de otoño.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de pescado.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de picnic.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de potajes y guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario de setas 2010.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario especial huevos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario legumbres.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetario pescado azul.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina Blanca Recetas para principiantes.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina blanca Recetario de patatas (2).pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina blanca Recetario de patatas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gallina_Blanca_Aperitivos_para_deleitar.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 02 - Pescados.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 03 - Maiz, arroz y otros cereales.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 04 - Aves.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 05 - Frejoles.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 06 - Carnes rojas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 07 - Tallarines y otras pastas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Gaston Acurio en tu Cocina 08 - Ajies, hierbas y vegetales.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 09 - Mariscos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 10 - Sopas, chupes y caldos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 11 - Cócteles peruanos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 12 - Postres.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 13 - Guisos y estofados.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 14 - Piqueos.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu Cocina 15 - Recetas especiales.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Gaston Acurio en tu cocina 01 - Papas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Lekue Mindfuld Eating.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Lekue Nutrición y deporte.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Lekue Recetas de supervivencia para principiantes.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Lekue Recetas para el día a día.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Lekue Saca partido a tu microondas.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Mariano Orzola 120 recetas navideñas Carnes y aves.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas americanas e italianas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas americanas y españolas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas americanas y francesas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas americanas y mediterráneas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas americanas y mexicanas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y francesas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y mediterráneas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas argentinas y mexicanas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas con aceitunas y con huevo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas de ocasión Entrantes y postres.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas españolas y francesas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas orientales e italianas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas orientales y francesas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar budines y mousse.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar con aves y cordero.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar escabeches y dip.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar flanes y mousse.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar galletas y panes.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar omelettes y mousse.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 168 recetas para preparar tortas y café.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Pizzas premium.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Platos mediterráneos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Platos vegetarianos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Postres helados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas gourmet Postres livianos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Aperitivos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Entrantes y ensaladas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Exquisiteces saladas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas navideñas Segundos platos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas navideñas con mariscos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 20 recetas para preparar postres livianos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 25 recetas livianas y sin grasa.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para prepara con cerdo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar budines.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con arroz.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con aves.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con canela.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con huevo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con marisco.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con pescados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar con pollo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar guarniciones.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar guisados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar omelettes.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar platos fríos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar platos suculentos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar postres helados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar sopas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para preparar tortas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas para sorprender.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 72 recetas saludables para cuidar tu silueta.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con aceitunas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con arroz.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con carne.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con cereales.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con frutos secos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con huevo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con pescado.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas con semillas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina española.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina francesa.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina italiana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas de la cocina mexicana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar bebidas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar budines.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar café y chocolate.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar comida rápida.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar comidas al wok.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar dip.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar ensaladas gourmets.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar galletas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar pasteles salados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar pizzas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar platos fríos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar postres.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar tapas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola 84 recetas para preparar tartas dulces.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con chocolate.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con fibra.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas con legumbres.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de comida express.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de invierno.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas de postres del mundo.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas frescas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzola Selección de 84 recetas para guarniciones.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano Orzolas 20 recetas gourmets Pasteles hojaldres.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_100_recetas_navideñas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_de_ocasión (2).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_de_ocasión.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_para (2).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_para (3).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_para (4).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_168_recetas_para.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_20_recetas_navideñas (2).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_20_recetas_navideñas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_35_recetas_navideñas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas (2).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas (3).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_60_recetas_navideñas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_72_recetas_para_preparar.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_84_recetas_para_preparar (2).epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_84_recetas_para_preparar.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Mariano_Orzola_Selección_de_84_recetas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Col·leccions/Pescanova Anguriñas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova La cocina del pescado.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Langostinos.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Merluza Pescanova en microondas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Merluza en microondas.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario con Omega 3.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetario de Semana Santa.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetario de bacalao.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario de cuaresma 2012.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetario de merluza.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario de navidad 2009.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario de navidad 2011.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario de navidad 2012.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetario de pescado rebozado y empanado.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetario de rabas y chopirones.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetario de salmón ahumado.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetas de Tallarimis.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetas de anguriñas y surimi.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/Pescanova Recetas de surimi para sorprender.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/Pescanova Recetas ligeras.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/cocina fácil lecturas num. 124.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 127.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 133.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 135.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 150.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 153.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 154.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 156.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 182.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 203.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 204.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 209.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/cocina fácil lecturas num. 210.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 215.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 217.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 218.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 220.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 221.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 222.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 223.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 224.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 225.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 226.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 229.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 232.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 234.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 235.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 236.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 237.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 238.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 239.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 240.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 242.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 243.pdf` | PDF | escanejat | sí | descartar | no |
| `Col·leccions/cocina fácil lecturas num. 244.pdf` | PDF | text | sí | ingerir | sí |
| `Col·leccions/cocina fácil lecturas num. 89.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/2019-09-01 Louisiana Cookin.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/40 Menus sencillamente deliciosos.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/@malu320 Gastronomia-Peruana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/A cociña galega.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Alimentos Del Norte.mobi` | MOBI | no aplicable | no | descartar | no |
| `Cuina del mon/Andalucia destapa Andalucia.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Aurora Sonia Montesino Cocinas mestizas de Chile.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Bartolo Mutari Cocina siciliana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Biblioteca Metropoli Nuestra cocina País vasco.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/COCINA ASIÁTICA.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/COCINA ESPAÑOLA. VOL I.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/COCINA ESPAÑOLA. VOL II.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/COMIDA SALUDABLE ESTILO JAPONES.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Camargo Rain La cocina española de siempre.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Carl Jan Clásicos de la cocina sueca.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Carmen Gil Por la cocina española.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Chef Oropeza Comida atipica mexicana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Classiche italiane salse per accompagnare.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Club de guisanderas El libro de las guisanderas de Asturias.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina America del Sur (2).pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina America del Sur.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina Francesa.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina Gallega.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Cocina Italiana.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Cocina Vasca Jorge Beramendi - Desconocido.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina china I paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina cubana 5 siglos de tradición.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Cocina italiana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Cocina japonesa paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina mediterránea paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina mexicana paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Cocina tradicional de la sierra de Cádiz.epub` | EPUB | escanejat | no | descartar | no |
| `Cuina del mon/Cocina árabe I paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Comida china.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Círculo de Lectores El gran libro de la cocina ecuatoriana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/De rechupete Empanadas gallegas.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Editorial Blume Cocina tailandesa.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Editorial Espasa El gran libro de la cocina gallega.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Editorial konemann Cocina japonesa y coreana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Editorial_Cocinamos_La_cocina_española.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/El gran libro del wok.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Emi Kazuko Comida japonesa.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Empanadas Gallegas.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Encarnación_Lenza_Recetas_tradicionales.mobi` | MOBI | no aplicable | no | descartar | no |
| `Cuina del mon/Escapada a La India.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Fernando Ordoñez La gran cocina peruana.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Festín Griego (2).pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Festín Griego.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Fuga in India.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Gabriele Napolitano Entradas italianas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Gastronomía aragonesa.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Gobierno de Aragón Hoy comemos sin gluten.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Graciela Bajraj Las 105 recetas más famosas del mundo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Gran menú americano.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Hawwaiian Pool Party.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Instituto Culinario de México Cocina árabe.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Japón es más que sushi.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Jaume Fàbrega La cocina de Menorca.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Joanna Farrow Cocina griega.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Jornadas gastronómicas de Castilla y León.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/José Aguilera La cocina de Almería.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/LIBRO+ARROCES+DE+ESPAÑA.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/La Verdadera Cocina Criolla.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/La cocina japonesa de Harumi.PDF` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/La cocina tradicional en Chiclana.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Las cocineras de Sils.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Las recetas de Isabella Cocina austro-hungara.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Libro de cocina tradicional del sur de Italia.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Lo mejor de la comida árabe.epub` | EPUB | escanejat | no | descartar | no |
| `Cuina del mon/MARRUECOS.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Maria Adela Díaz Cocina murciana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Maria José Martin Comida tradicional española.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Miriam Becker Pasión por la cocina judia.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Málaga Recetas populares.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/México está de fiesta.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Nora Pérez Salsas taqueras mexicanas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Nuestro libro de cocina vasca.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Osno Monto Empanada criolla y picadillo llanero.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Otilia Kusmin Delicias de la cocina rusa.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Pablo Castro La Cocina de la Serranía de Ronda.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Pablo Castro La cocina del entorno de los embalses.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 01.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 02.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 03.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 04.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 05.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 06.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 07.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 08.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 09.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 10.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 11.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 12.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 13.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 14.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 15.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 16.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 17.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 18.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panaderia Mexicana 20.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Panadería Mexicana 19.PDF` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Plan andaluz de salud Cocina andaluza Dieta mediterránea.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/RECETAS TIPICAS GRIEGAS.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/REVISTASGOLD35K.Maxi  Marzo 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Recetario cocina japonesa.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetario de Cocina Asiatica.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Recetario de Cocina Gallega.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetario tradicional aragonés del siglo XXI (2).pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetario tradicional aragonés del siglo XXI.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetas Cocina Arabé MArroqui.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetas de cocina arabe marroquí.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetas de cocina argentina.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetas mexicanas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Recetas mexicanas.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Recetas sabrosas Cocina china.epub` | EPUB | escanejat | no | descartar | no |
| `Cuina del mon/SABORES DE ITALIA.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Saboreando Asturias.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Sabores de Chile para el mundo.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Sabores del mundo Cocina japonesa paso a paso.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/Salah Jamal Aroma arabe.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cuina del mon/Supermaxi Italia al dente.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/TUTTO BACCALA BIMBY.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/TUTTO POLPETTONI BIMBY.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Taste_of_Persia_A_Cook’s_Travels_Through_Armenia,_Azerbaijan,_Georgia.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Todo sobre la cocina argentina server gardel.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Tutto bavarese.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Tutto frittata.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Tutto ravioli.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Tutto romagnolo.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/VIVA MÉXICO.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Vinaròs, la gastronomia.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Vincenzo y Rafaella Fabrocini La dieta mediterránea.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Viva México.doc` | DOC | escanejat | no | descartar | no |
| `Cuina del mon/Yuka Kaneko Las mejores recetas de sushi.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/asia.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/comida de boteco.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/el-gran-libro-de-la-cocina-italiana.pdf` | PDF | escanejat | sí | descartar | no |
| `Cuina del mon/recetario_empanadas_gallegas.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/recetariococina-multicultural.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/recetas-cocina-italiana-web.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/recetas-halloween.pdf` | PDF | text | sí | ingerir | sí |
| `Cuina del mon/Índia.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Atlas ilustrado de plantas medicinales y curativas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/COCINA AL VAPOR.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Carlos Abehsera Cocinar sin carbohidratos.epub` | EPUB | escanejat | no | descartar | no |
| `Cultura culinaria/Cocina al instante Cocina bajo cero.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Dr Álvaro Campillo Alimentación para deportistas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Editorial Grijalbo Guia de la verdura.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Editorial_Everest_El_gran_libro.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/El libro de la cocina natural.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/El_Sabor_en_Familia_Antología_de.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Elisabeth Lambert Enciclopedia de las especias.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Enciclopedia de las hierbas mágicas.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Escuela_Superior_de_Hostereria_de.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Frank Suarez El poder del metabolismo.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/François_Couplan_Reconoce_facilmente.epub` | EPUB | escanejat | no | descartar | no |
| `Cultura culinaria/Gloria Spencer  La Cocina Enzimatica.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Harinas Bufort Manual del panadero.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Hermann Schmidt  Las especias Condimentos vegetales.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Hervé This Los secretos de los pucheros.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Integral El libro de las especias.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Jean Pedrazzani Los remedios de la abuela.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Jean Seignalet La alimentación La 3ª medicina.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Jennifer Eloff Vamos a comer bajo en carbohidratos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Joaquin Pérez Cocinar con una pizca de ciencia.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/John_Seymour_La_conservacion_de.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Jose Luis Armendariz Técnicas de cocina para profesionales.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Jose Luis Armendáriz Técnicas de cocina para profesionales.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/La cocina aromatica - Francois Chartier.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/La cocina de la congelación.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Laura Landra Como conservar fruta y verdura.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Libro de recetas del aula de hosteleria curso 2008-2009.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Low carb ¡Come sano!.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Manual del aspirante a chef - MasterChef.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Cultura culinaria/Manual práctico sobre pescados y mariscos frescos.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Manuel Arasa Gil Manual de nutrición deportiva.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Maria Jesus Gil de Antuñano Escuela de cocina.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Masterchef Manual del aspirante a chef.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/PARA DEPORTISTAS.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/REVISTASGOLD31K. 12-18-CocinaVital.pdf` | PDF | escanejat | sí | descartar | no |
| `Cultura culinaria/Saturnino Calleja Manual de la cocinera.pdf` | PDF | text | sí | ingerir | sí |
| `Cultura culinaria/Sergio Casado Una aventura en el mundo de la cocina.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Gourmand_29_Janvier_2020 .pdf` | PDF | escanejat | sí | descartar | no |
| `Guisats i estofats/Estofados.pdf` | PDF | escanejat | sí | descartar | no |
| `Guisats i estofats/Guisos de patata.pdf` | PDF | escanejat | sí | descartar | no |
| `Guisats i estofats/IX jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Guisats i estofats/V Jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Guisats i estofats/VI Jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Guisats i estofats/VII jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Guisats i estofats/VIII jornadas gastronómicas de la cazuela y los guisos.pdf` | PDF | text | sí | ingerir | sí |
| `Guisats i estofats/losguisosdelaabuela.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/1 MOLDE 10 RECETAS.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/100 Dulces Y Postres - Patry Jordan.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/12 Recetas de galletas.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/30 recetas prácticas Postres rápidos.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/555 Recetas de postres - Eva Arguinano.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Angela García Tartas del mundo.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Aprenda a hacer dulzuras caseras.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Arte del azucar 01.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Arte del azucar 02.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/BOLLERÍA CASERA .pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Bea Roque El rincón de Bea Delicias para compartir.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Bimbo - Recetas de Cuaresma.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Bricoreposteria - VVAA.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Cecilia Paseiro Pastelería artesanal.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Cheesecakes.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Chef Express Postres livianos.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Chocolate Recetas que explotan sus sentidos.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Cioccolate.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Cocina fácil Dulces de Navidad.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Curso alta reposteria chocolates turin.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dolcezze tirolesi.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dolci ma non troppo.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dolci sorprese Galette des rois.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dolci sorprese.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dulce Tentación (México).pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Dulces Navideños.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Edición chocolate.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Editorial El Pais Siete Pecados.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Editorial NGV Helados, sorbetes y otros.epub` | EPUB | escanejat | no | descartar | no |
| `Postres/El libro de oro de la reposteria para ti.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/El rincón de los postres.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Emily Scott Los 10 postres más famosos del mundo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Festín de Sri Lanka.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Flan y pudín.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Fruta natural.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/GRANDES TARTAS.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Gabriele Colditz Fruta escarchada.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Giuliana Bonomo Guía de dulces.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/HELADOS Y SORBETES. VOL. I.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/José Maréchal Sabrosas tentaciones en vasitos.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Juan Diaz La pequeña cuisiniere.epub` | EPUB | escanejat | no | descartar | no |
| `Postres/La cocina de Sumito Postres para impresionar.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/La magia del chocolate.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Las 100 mejores recetas dulces de Ana Sevilla.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Las mejores gelatinas presenta flanes.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Les meilleurs de mini cakes.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Lo mejor de la leche dulce num. 33.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Lolita Avellana Les postres de casa meva.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/MAGDALENAS.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Masterclass Tartas increibles.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Maxine Clark Tartas dulces y saladas.epub` | EPUB | escanejat | no | descartar | no |
| `Postres/Montagud Editores Pastry Revolution.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Muffin dolci e salati.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Muffins Dulces y salados.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/NGV Super muffins.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Nestlé ¡A comer bien! Recetas para postres.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/POSTRES INDIVIDUALES.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Panadería y pastelería profesional.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Panquecitos.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Panqués.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Pasteleria y reposteria Curso avanzado.epub` | EPUB | escanejat | no | descartar | no |
| `Postres/Pastelería artesana num. 03.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Postres de Navidad-1.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Postres del Mediterráneo.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Postres del mundo.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Postres en vaso - VVAA.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Postres para celebrar.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Postres y Dulces Galletas.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Postres y dulces Flanes.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Pralinky.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/REPOSTERÍA Y PASTELERÍA I.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Receitas-Pequenas-Delicias.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Receta-Roscon-Reyes-LeCreuset.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Recetario El Horno de Villablanca'.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Recetas de cremas, mousses y helados.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Recetas inedittas do convento para a bimby.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/SABOR A CHOCOLATE.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Saints Román Postres y otras recetas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Postres/Xavier Barriga Cocas, tortas y otras delicias.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/YOGURES.pdf` | PDF | text | sí | ingerir | sí |
| `Postres/galletas caseras.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/recetas-chocolate (1).pdf` | PDF | text | sí | ingerir | sí |
| `Postres/Ángela García & Hanns Geel - Tartas del mundo.pdf` | PDF | escanejat | sí | descartar | no |
| `Postres/Éclair per una merenda chic.pdf` | PDF | escanejat | sí | descartar | no |
| `REVISTASGOLD26K,1112-18-dcamera-byneon.pdf` | PDF | escanejat | sí | descartar | no |
| `Receptes/100 recetas premiadas Tulipan.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Receptes/Cocina con garrote - Martin Berasategui.kepub.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Receptes/Grandes Recetas Para Cocinas Pequeñas - Marta Carnicero.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Karlos Arguiñano Cocina día a día.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Receptes/Libro de recetas Sencillo & saludable.mobi` | MOBI | no aplicable | no | descartar | no |
| `Receptes/Maravillosas-Recetas-de-La-Abuela-pdf.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/MasterChef - Las Recetas De Marta.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario blog Exquisit 2014.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario blog Exquisit Recetas de sopas y cremas.pdf` | PDF | escanejat | sí | descartar | no |
| `Receptes/Recetario blog exquisit 2015.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario blog exquisit 2016.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario blog exquisit 2017.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario blog exquisit 40 exquisitos bocadillos.pdf` | PDF | text | sí | ingerir | sí |
| `Receptes/Recetario_blog_Exquisit_Recetas.pdf` | PDF | escanejat | sí | descartar | no |
| `Receptes/Velocidad cuchara  Lo mejor del blog.pdf` | PDF | escanejat | sí | descartar | no |
| `Receptes/cocina fácil lecturas.rar` | RAR | no aplicable | no | descartar | no |
| `Receptes/recetas con humor.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/01_Thermomix_-_Mis_Mejores_Recetas_-_Cristina_Galiano.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/10.- A todo vapor TMX31.Johnnygan.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/24.- Las Recetas De La Abuela II.Johnnygan.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/4.- 100 Recetas practicas.Johnnygan.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/43.- Imprescindible para su cocina.Johnnygan.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/5.- 100 nuevas recetas.Johnnygan.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Al calor de un caldo.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/BAOS.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/BARBACOA ESPECIAL Y DIFERENTE.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/BARRETTE DALLA COMMUNITY.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Como en casa.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/DIETA MEDITERRANEA CON THERMOMIX.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/De cuchara.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/DeliciosoYRapido.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/EXPERIENCIA GASTRONÓMICA Thermomix TM5.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Food Truck una fiesta de sabores.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Gran Bretaña.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Il cibo degli atleti.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Kale.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Kinder.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Maravillosas-Recetas-de-La-Abuela-pdf.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Pastillas de caldo.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Picoteo de Cine.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/RECETAS DE DIARIO.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Recetas del  mundo para cocinar a diario.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/SMOOTHIE BOWLS THERMOMIX .pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Simple & Dulce con thermomix.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Thermomix 135 - Enero 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix 40 AÑOS.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix Marzo 2017.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix marzo 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 123 Enero 2019.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Thermomix num. 126  Abril 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 127 Mayo 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 128 Junio 2019.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/Thermomix num. 129 Julio 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 130 Agosto 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 131 Septiembre 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 132 Octubre 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 133 Noviembre 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 134 Diciembre 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 135 Enero 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix num. 138 Abril 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/Thermomix septiembre 2018.pdf` | PDF | text | sí | ingerir | sí |
| `Thermomix/VOLANDO VOY alitas de pollo.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/adelgazar con thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/recetas_especiales.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/reposteria tmx.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RDL} 08-19-Thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RL} 05-20-Thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RL} 09-19-Thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RL} 10-19-Thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RL} 11-19-Thermomix.pdf` | PDF | escanejat | sí | descartar | no |
| `Thermomix/{RL} Thermomix Un nuevo amanecer.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amanides/Club gente saludable Ensaladas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amanides/De rechupete Recetas de ensalada.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amanides/Ensaladas Para Todo El Año - Martín Berasategui.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amanides/Ensaladas XXL.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amanides/Ensaladas para todo el año - Martin Berasategui.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Amanides/Ensaladas y aliños.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amanides/Pon una ensalada en tu verano 2016.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amanides/Por una ensalada en tu verano 2013.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amanides/Supermaxi Ensaladas para toda ocasión.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amanides/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Amanides/recetario_ensaladas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Amb nens/Divertirsi in cucina.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amb nens/Junior Masterchef Recetas para cocinar con niños.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amb nens/Niños _a comer!.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Amb nens/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Arros/Angelica Sasaki Cocina en 30 minutos Arroces.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Arros/Arroces Valencianos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Arros/Arroz un básico 5 recetas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Arros/Cocinar arroces con fantasia.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Arros/Especial arroces Vol II.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Arros/Especial arroces.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Arros/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Autor/Chiringuito de Pepe Las recetas de Pepe Leal y Sergi Roca.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Cocina_con_Joan_Roca_a_baja_tem.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Grandes chefs.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Autor/Joan Roca Cocina con Joan Roca a baja temperatura.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Juan Mari Arzak Arzak.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Karlos Arguiñano 1000 recetas de oro.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Las 1150 recetas - Martín Berasategui.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Martín Berasategui Cocina en casa con Martín Berasategui.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/Martín Berasategui La cocina de Martín Berasategui.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Autor/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Cacera/VII jornadas gastronómicas de la caza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cacera/VIII jornadas gastronómicas de la caza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cacera/X Jornadas gastronómicas de la caza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cacera/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Casolana/9ª Jornadas Gastronómicas de la caza.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/Asados con guarnición.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/Carnes rojas y blancas.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Casolana/Cocina Exótica del Mediterráneo.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/Con carne de ave.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Casolana/Con huevo o masa.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Casolana/De verduras y hortalizas.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Casolana/Empanadas y empanadillas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Casolana/Especial Albóndigas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/Fritos & Cía.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/I Jornada gastronómicas del ajo.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/Joan Roca Cuina mare.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Casolana/Juan José Yagüe Cocina marinera.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Casolana/La magia del vapore.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Casolana/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Casolana/¡COMO EN CASA!.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Celíac/COCINA SIN GLUTEN VOL. II.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Celíac/Cocina Fácil para Celíacos con TMX.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Celíac/Cocina sin gluten.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Celíac/De rechupete Recetas para celiacos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Celíac/Fabio Dana La vida sin gluten.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Celíac/Gobierno de Aragón Hoy comemos sin gluten (2).pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Celíac/REVISTASGOLD29K.2018-11-01 Gluten-Free Heaven.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Celíac/Restauración Sin Glúten.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Celíac/SIN GLUTEN. SIN LIMITES.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Celíac/Yo, celiaco - Fabio Dana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Celíac/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Celíac/recetario_celiacos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/Cócteles clásicos.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Cervesa i begudes/DE COPAS.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Cervesa i begudes/I jornadas gastronómicas de la cerveza.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Cervesa i begudes/I jornadas gastronómicas del vino Montilla-Moriles.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/II jornadas gastronómicas de la cerveza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/III jornadas gastronómicas de la cerveza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/IV jornadas gastronómicas de la cerveza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/La guia del barman.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Cervesa i begudes/V jornadas gastronómicas de la cerveza.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Cervesa i begudes/Xavier Garcia La cerveza en España.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Cervesa i begudes/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Cocina de aprovechamiento .epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Compotas & Conservas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/COCINA CON CONSERVAS.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/Conservas de fruta y verdura.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/Cursos prácticos Conservas saladas y dulces.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/José Maillet El confitero moderno.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Conserves/La botica de la abuela Tisanas y jarabes deliciosos.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Conserves/Mermeladas y compotas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/Oded Schwartz Conservas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Conserves/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/DESAYUNOS.PARA SOÑAR.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/El Gran Libro De La Cocina Rapida - Paola Sala.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/El_Pan_Manual_De_Técnicas_Y_Recetas_De_Panadería_Jeffrey_Hamelman.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Entrepans/Carlos Crespo Un buen bocadillo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Entrepans/Cocina al instante Bocatas a la carta.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Entrepans/Cocina para llevar Bocadillos.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Entrepans/Un buen bocadillo - Carlos Crespo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Entrepans/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Eva y Ulrich Klever El gran libro de las fondues.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/@malu320    04-19-Gourmet.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/Aperitivos y canapes.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Festa/Carnevale salato.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Festa/Carolina Ferrer Menú de fiestas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Festa/Como cocinar aperitivos y entrantes.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/Darwin Solorzano Cocina para sorprender.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Festa/La marquesa de Parabere Entremeses, aperitivos y ensaladas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/Maria Jesus Gil de Antuñano Cocina para invitados.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/NGV Bocados para fiestas.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Festa/RECIBIR CON ARTE.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/Recetas para un día especial.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Festa/SORPRENDE A  TUS INVITADOS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/Taller comida de fiesta Verano 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Festa/UN TOQUE GOURMET.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Festa/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Food.Heaven.Presents.Bread.2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/21 recetas de primavera (cocina para emancipados).pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/50 recetas de verano - cocina para emancipados.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/Angelita Alfaro Cocina para estudiantes.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Fàcil/Cheap & cheerful.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/Cocina_Exotica_Al_Alcance_De_Todos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Fàcil/FÁCIL Y RÁPIDO VOL. II.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Fàcil/FÁCIL Y RÁPIDO. VOL. I.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Fàcil/Gallina Blanca Cocina para papá.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Fàcil/INSPIRACIÓN para el día a día.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/Ligeras para dos.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/Liz Franklin Platos exprés.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Fàcil/Marcos H. S. Nosotros cocinamos recien casados.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Fàcil/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/BURGUERS THERMOMIX .pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Brochetas fáciles y rápidas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Burguers irresistibles.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Burguers saludables.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/FAST FOOD PARA SIBARITAS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Hamburguesa i fast food/Fast Food Saludable.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Food Truck una fiesta de sabores.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Food Truck.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/Hamburguesas Las mejores recetas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Hamburguesa i fast food/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Ibèric/III_jornadas_gastronómicas_del_iberico.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Ibèric/II_Jornadas_Gastronómicas_del_iberico.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Ibèric/IV_jornadas_gastronómicas_del_iberico.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Ibèric/V_jornadas_gastronómicas_del_iberico.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Ibèric/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Julia Osuna Cocina canalla.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/LIGERAS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Las_mejores_recetas_con_marihuana.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/M. Palla Entrantes y entremeses.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/MENÚS COMPLETOS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/María Victoria Llamas El libro del microondas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Masas Editable.docx` | DOCX | text | sí | ingerir | sí |
| `Tipus de Cuina/Masas Editable.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/MasterChef Cocina de aprovechamiento.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de alta proteína.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de cocción lenta con carne.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Mattis Lundqvist 50 recetas de enchiladas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Nadal/Blanca Navidad.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Nadal/Buffet Navideño.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Nadal/Cocina para emancipados Recetas de Navidad 2016.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Nadal/Enric Monzonis Recetas de Navidad 2017.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Nadal/Feliz Navidad.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Nadal/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Oggi... frutta.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/22.- Pan Bolleria.Johnnygan.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Pa/Elaboració casolana de pa i pastes.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Pa/Elaboración Artesanal del Pan.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/Maria Lunarillos Panes.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/Panes creativos.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/Rolando Alvarado Manual de formulas y saberes de panadería.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Pa/Rosa Tovar Masas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Pa/el libro del pan 1.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pa/Área Gastronomía Manual de panadería.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Paco Blanco Crockpot.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Para untar.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pasta/Ema García Recetas de pasta y fideos.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Pasta/Ema García Recetas de plato principal de pasta.pdf` | PDF | text | sí | ingerir | no |
| `Tipus de Cuina/Pasta/Masas saladas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pasta/Monica Ponttiroli Pastas caseras.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Pasta/Nicol Pardo Pizzas y pastas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Pasta/TODO PASTA.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Pasta/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Pasta/🇮🇹. Pizza e Pasta Italiana. January 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Per Endur/20 Recetas express para un mes de tupper.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/Cocina para llevar al trabajo.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/De rechupete Recetas de táper para el curro.mobi` | MOBI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Per Endur/Gallina Blanca Cocina para llevar al trabajo.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/Lunch Box.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Per Endur/PARA LLEVAR (2).pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/Para llevar Comer fuera como en casa.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/Para llevar de picnic.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Per Endur/Para llevar.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Per Endur/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Per Endur/recetario_picnic.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Pescado y marisco.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Pescado ¡ Buen provecho !.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Pescados y mariscos.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pizza/Maxine Clark Pizza, calzone & Focaccia.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pizza/Nicol Pardo Pizzas y pastas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Pizza/Pizza e Pasta Italiana Febbraio 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Pizza/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Pizza/🇮🇹. Pizza e Pasta Italiana. January 2020.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/RECETARIO DE BATIDOS.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/RECETAS PRODUCTOS DEL MAR.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/RICO BATIDO. MADE IN USA.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Raw Food.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Recetas de patés.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Recetas de pescados.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Recetas de zumos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Recetas_Saludables_Julio_2017 (1).pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Roberto Peralta Los secretos de la cocina con microondas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/SIN LACTOSA.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Sabor a bosque.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Salses/Claudia_Viviana_Hernández_Salsas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Salses/El monstruo de las recetas 70 recetas de salsas fáciles.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Salses/Giorgio Stuart Las mejores salsas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Salses/José María Campos La elaboración de las salsas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Salses/Modern_Sauces_More_than_150_Recipes_for_Every_Cook,_Every_Day_Martha.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Salses/Muchogusto.net Recetas caseras de salsas para pastas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Salses/Practilibros Salsas y vinagretas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Salses/Recetario Especial Sofritos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Salses/Salsas, pan y queso.epub` | EPUB | escanejat | no | descartar | no |
| `Tipus de Cuina/Salses/Salse.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Salses/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Sano e leggero Piatti unici.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sapori di montagna.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Secondi di carne.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Al calor de un caldo.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Aurora Abarca Las sopas de Aurora.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Sopa/CREMAS CALIENTES VOLUMEN II.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/CREMAS CALIENTES. VOL I.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Sopa/CREMAS Y SOPAS FRÍAS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Sopa/Cocina Popular Sopas poderosas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Editorial Blume Selección culinaria Sopas.mobi` | MOBI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Sopa/SOPAS CON TROPEZÓN.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Sopas (Selección culinaria).pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Sopas Detox - Nicole Pisani y Kate Adams.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Sopa/Sopas Exquisitas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/Sopas frías. Refrescate con cuchara.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Sopa/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Sopa/doce-recetas-de-gazpacho-ajoblanco-y-sopas-frias (1).pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Supermaxi Los secretos de la carne.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/101 recetas de tapas.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/DE TAPEO. APERITIVOS Y TAPAS.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/De Tapas Con Quique Dacosta.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Gallina_Blanca_Aperitivos_para_deleitar.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Mundorecetas Recetas saladas de picoteo 1ª parte.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Mundorecetas Recetas saladas de picoteo 2ª parte.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Pedrito Rico Tapas Gourmet.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Tapes/Pedro Martín Donosti pintxo a pintxo.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Tapes/Recetario aperitivos y canapés.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Tapes/Recetario blog Exquisit Ideas para picar.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Salvador Arimany Canapès a l'abast de tothom.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Tapes/Santiago(e)Tapas.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Tapes/Sylvie Ait-Ali 30 recetas de aperitivos para cenar.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Tapes/Tapas & Pinchos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/Tapas con rock 'n' roll - Jordi Cruz.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Tipus de Cuina/Tapes/Tapas y Montaditos.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Tapes/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Temporada/Chef Oropeza Sabores de verano.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Temporada/Cocina con aroma a Primavera.pdf` | PDF | text | sí | ingerir | sí |
| `Tipus de Cuina/Temporada/Primavera.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Temporada/Verano Recetas de temporada.pdf` | PDF | escanejat | sí | descartar | no |
| `Tipus de Cuina/Temporada/desktop.ini` | INI | no aplicable | no | descartar | no |
| `Tipus de Cuina/Temporada/temporada_octubre.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/500 Recetas Vegetarianas - Sandra figueroa y Consuelo Bedoya.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/@malu320    04-19-Cocina Vegana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/@malu320   Cocina Vegetariana - abril 2019.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/@malu320 05-19-Cocina Vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/@malu320 05-19-Extra Cocina Vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/@malu320-Cocina Vegana - febrero 2019(1).pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Ana Moreno Curso completo de cocina vegetariana.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Antonio Castellanos Top 30 recetas veganas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/COCINA  VEGETARIANA.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/COCINA VEGETARIANA VOL II.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/COCINA VEGETARIANA.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Cocina Vegetariana - abril 2020.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Cocina Vegetariana 02-20.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Cocina Vegetariana Platos principales.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Cocina Vegetariana Recetas rápidas.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Cocina Verde - Rodrigo de la Calle.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Cocina fácil para vegetarianos y veganos.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Cocina vegetariana (2).pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Cocina vegetariana cookidoo.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/CreatiVegan Como hacer galletas veganas.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Menú de Navidad 2011.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Menú de Navidad 2012.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Minirecetario especial Biocultura.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Navidad 2016.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Recetario festivo 2013.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/CreatiVegan Recetario vegano nochevieja y año nuevo.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/CreatiVegan Recetas festivas 2014.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Dr. Eduardo Alfonso Cocina vegetariana.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Dulces navideños veganos.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Gigi Ro Las mejores hamburguesas veganas y vegetarianas.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Guia de iniciación de dieta vegetariana.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Ignacio Domenech La cocina vegetariana moderna.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Jack Norris Veganos para siempre.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/La cocina vegetariana de Marta.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Michael Chung La biblia de smoothies verdes.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/Noemí Cervantes 50 recetas vegetarianas.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/Pasqua vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Pequeña biblia de la cocina vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/REVISTASGOLD22K-COCINAVEGETARIANA.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/REVISTASGOLD29K.12-18-cvegetariana-byneon.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Recetario Granvita 2017.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Recetario vegano.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Recetario vegetariano internacional.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Recetas vegetarianas fáciles Parte I.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Recetas vegetarianas fáciles Parte II.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Ricas recetas veganas con sabor latino.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/SOY VEGANO. VOL II.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/SOY VEGANO.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Sally Reyes Dieta vegana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/Sandra Figueroa de Castro Cocina vegetariana.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Soy Vegano vol III.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Stella Osterhoff Smoothies verdes.epub` | EPUB | escanejat | no | descartar | no |
| `Vegetariana/Susaeta Cocina vegetariana.epub` | EPUB | escanejat | no | descartar | no |
| `Vegetariana/Susaeta Recetas con verduras.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Vegetarian N27 MarzoAprile 2020 .pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/Vida y cocina vegana nº 3.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/We Veg N62 Marzo 2020 .pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/Xabier Arguiñaz Cocina vegetariana.epub` | EPUB | text | no | convertir a DOCX o Markdown (pendent de confirmació) | no |
| `Vegetariana/cocina vegetariana num 109.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 101.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 103.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 104.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/cocina vegetariana num. 105.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 106.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 108.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 22.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 42.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 43.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 44.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 45.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 46.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 47.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 48.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 49.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 50.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 51.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 52.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 53.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 55.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 57.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 60.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/cocina vegetariana num. 62.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/cocina vegetariana num. 63.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 94.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina vegetariana num. 95.pdf` | PDF | text | sí | ingerir | sí |
| `Vegetariana/cocina vegetariana num. 97.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/cocina_vegetariana_2018_07_01.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/extra cocina vegetariana num. 03.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/extra cocina vegetariana num. 19.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/extra cocina vegetariana num. 21.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/vida y cocina vegana nº 2.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/{RDL} 08-19-Cocina Vegetariana.pdf` | PDF | escanejat | sí | descartar | no |
| `Vegetariana/{RL} 01-20-Cocina Vegetarinana.pdf` | PDF | escanejat | sí | descartar | no |
| `temporada_octubre.pdf` | PDF | text | sí | ingerir | sí |
