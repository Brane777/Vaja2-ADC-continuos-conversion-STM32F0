# Vaja2-ADC-continuos-conversion-STM32F0

Glede na vašo razvojno ploščico izberite ustrezni analogni vhod. Kateri pin ste določili? PC2.

Na zaslonu obkljukate izbrani pin (ADC…); usterzno se vam mora pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC1_IN3.

V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj opazite? ABP1 timer clock se je zmanjsal na 32MHz.

Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? 16MHz.

Koliko znaša pravi čas vzorčenja tvz v mikro sekundah? 16.22

Komentar: Sampling time je bil postavljen na 247.5, ker vrednost 239.5 ni bila možna.
