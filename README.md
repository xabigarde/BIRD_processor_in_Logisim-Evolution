# BIRD_processor_in_Logisim-Evolution

## BIRD konputagailuaren simulazioa Logisim-Evolution softwarean.
*(más abajo en castellano)*

BIRD konputagailua 16 biteko RISC konputagailu sinple bat da. Memoria-helbideak eta datuak 16 bitekoak dira, baina aginduak 32 bitekoak dira, hots, bi memoria-posizio okupatzen dituzte. PC eta IR erregistroez gain, 16 biteko 32 errekistro orokor dauzka: r0 - r31. r0 erregistroaren edukia 0 da beti, eta r31 erregistroak SParena egiten du.
TXORI mihiztadura-hizkuntza ere sinplea da, ohiko aginduak besterik ez baitauzka: eragiketa aritmetiko/logiko arruntenak, load/store aginduak, jauziak, eta azpirrutinak kontrolatzeko aginduak (call, ret, push eta pop). Helbideratze moduak ere sinpleenak dira.

BIRD konputagailua Donostiako Informatika Fakultatean (UPV/EHU) erabiltzen da, Informatika Ingeniaritzako lehen mailako **Sistema Digitalak Diseinatzeko Oinarriak** (SDDO) irakasgaian
Biltegi hontako zirkuitua eraikitzeko, irakasgai horren bi liburu hauek erabili dira oinarri gisa:

  - [Sistema digitalen diseinu-hastapenak: Oinarrizko kontzeptuak eta adibideakm, Arbelaitz et al. UPV/EHU,  2005. ISBN: 84-8438-069-6. Egileak: Olatz Arbelaitz Gallego, Txelo Ruiz Vazquez, Olatz Arregi Uriarte, Agustin Arruabarrena Frutos, Izaskun Etxeberria Uztarroz, Amaia Ibarra Lasa.](https://www.ueu.eus/argitaletxea/liburuak/sistema-digitalen-diseinu-hastapenak-oinarrizko-kontzeptuak-eta-adibideak) 
  - [Makina-Hizkuntza: Oinarrizko konputagailu baten egitura, agindu-multzoa eta programazioa](https://openlibrary.org/books/OL47300811M/Makina-hizkuntza._Oinarrizko_konputagailu_baten_egitura_agindu-multzoa_eta_programazioa)

  ![Bird Prozesadorearen zirkuitua Logisim-Evolution-en](BIRD_euskara_2026-01-07.png "Bird Prozesadorearen zirkuitua Logisim-Evolution-en")
 
## Simulación del computador BIRD en el software Logisim-Evolution.
 
BIRD es un computador simple RISC de 16 bits. Las direcciones de memoria y los datos son de 16 bits, pero las órdenes son de 32 bits, es decir, ocupan dos posiciones de memoria. Además de los registros PC e IR, contiene 32 registros generales de 16 bits: r0 - r31. El contenido del registro  r0 es siempre 0, y el registro r31 hace de SP.
El lenguaje ensamblador TXORI también es sencillo, ya que contiene únicamente las instrucciones más comunes: operaciones aritméticas/lógicas más comunes, órdenes load/store, saltos, y órdenes de control de subrutinas (call, ret, push y pop). Los modos de direccionamiento también son los más sencillos.

La computadora BIRD se utiliza en la Facultad de Informática de Donostia-San Sebastián (UPV/EHU) en la asignatura de primer curso de Ingeniería Informática **Principios de Diseño de Sistemas Digitales** (PDSD)
Para la construcción del circuito de este repositorio se han utilizado como base los dos libros principales de esta materia:

 - “Principios de diseño de sistemas digitales. Conceptos básicos y ejemplos”, Arbelaitz et al. UPV/EHU, 2008. ISBN: 84-8438-069-6. Autores: Olatz Arbelaitz Gallego, Txelo Ruiz Vazquez, Olatz Arregi Uriarte, Agustin Arruabarrena Frutos, Izaskun Etxeberria Uztarroz, Amaia Ibarra Lasa. [Enlace de descarga del libro en euskara](https://www.ueu.eus/argitaletxea/liburuak/sistema-digitalen-diseinu-hastapenak-oinarrizko-kontzeptuak-eta-adibideak)
 - [Makina-Hizkuntza: Oinarrizko konputagailu baten egitura, agindu-multzoa eta programazioa](https://openlibrary.org/books/OL47300811M/Makina-hizkuntza._Oinarrizko_konputagailu_baten_egitura_agindu-multzoa_eta_programazioa)

 ![Imagen del circuito del procesador BIRD](BIRD_processor_in_Logisim-Evolution_v2025.12.18.png "Bird Prozesadorearen zirkuitua Logisim-Evolution-en")
