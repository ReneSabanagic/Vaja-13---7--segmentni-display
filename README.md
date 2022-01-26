Vaja13-7segment-STM32L1

V Pinout & Configuraton pogledu glede na vašo razvojno ploščico postavite 7 prvih prostih pinov skupine A na GPIO_Output. Pine označite (label) s črkami segmenta: a, b, c, d, e, f in g.
Zapišite izbrane (konfigurirane) pine: 

Segment a: PA1

Segment b: PA2

Segment e: PA5

Segment c: PA3 

Segment f: PA6

Segment d: PA4 

Segment g: PA7

7-segmentni display je lahko v izvedbi skupne anode ali skupne katode. Vaš prikazovalnik testirate tako, da ga zvežete po spodnji (levi ali desni) shemi in preizkusite, katera polariteta je ustrezna (rdeča 5V, modra GND): Vaš prikazovalnik je s skupno _katodo_. Preverite delovanje še preostalih segmentov!

Kaj dela ukaz GPIOA -> ODR ?
GPIOA nastavi na odrodr je 16 bitni register

Opazujte delovanje 7-segmentega prikazovalnika. Kaj se zgodi, ko pritisnemo črno tipko na STM32L1? Številke se ponovno resetirajo in začnejo se ponovno prikazovati od 0 do 9.

Komentar: Na začetku sva imela težave z vezavo, vendar sva jih odpravila. Številke so se pravilno in enakomerno spreminjale, s pritiskom na črno tipko pa se začne prikazovati od začetka.
