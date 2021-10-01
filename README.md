# Vaja2-ADC-continuos-conversion-STM32F0

•	Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to?
PC0

•	Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?
ADC3_IN1

•	V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj opazite?
Program se takoj prilagodi na spremembo

•	Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana?
16 MHz

•	Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 cikov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah? 
(enačba: tvz=tvz_ciklih/fpreskalriana)?
16,219 μs

Komentar na delovanje:
Če bi zamenjala potenciometer bi lahko dobila bolj natančne rezultate.
