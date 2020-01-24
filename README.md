Odgovori:

Kateri pin ste omogočili? PA8.
Kaj se izpiše poleg pina? TIM1_CH1.

Koliko je vrednost Prescaler? 16.

Koliko znaša takt časovnika? 10kHz.

Popravljena koda:

sConfigOC.Pulse = 50;

sConfigOC.Pulse = 25;

1. ukaz:
Vrednost zanke htim1.Istance->CCR1 postane vrednost dutyCycle-a

2. ukaz:
Širina se poveča za 10%.

3. ukaz:
Če pulz preseže 90%, se postavi nazaj na 10%.

Komentar:
Celotno vajo sva ponovila 3x, vendar še vedno ne najdeva težave. Na osciloskopu se pojavi samo šum. Predvidevava, da je težava v programu, vendar je ne najdeva.
