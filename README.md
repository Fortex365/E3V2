# Firmware
###### Je aktuálně nainstalovaná vlastní verze tohoto neoficiálního firmware s konfigurovanými funckonalitami navíc dle hardware tiskárny. 

Neoficiální firmware tiskárny funguje mnohem lépe a je přívětivější než originální od výrobce, je dostupný ke stažení zde
[GitHub](https://github.com/mriscoc/Ender3V2S1/releases) ze souborů s názvy této konvence:

```python
Ender3V2-422-BLTUBL-MPC-yyyymmdd.bin
```

kde `Ender3V` je jméno tiskárny, `422` je verze PCB desky (4.2.2 silent board), `BLTUBL` (BL Touch Unified Bed leveling) neboli kalibrace pomocí sondy.

Před instalací nového firmware je dobrý nápad si opsat všechny nastavené hodnoty ve stávajícím software (některé jsou z fyzické, některé pocházejí přímo z kalibračních procedur)

# Slicer
https://github.com/prusa3d/PrusaSlicer/releases/download/version_2.7.4/PrusaSlicer-2.7.4+win64-202404050928.zip

1) Stáhnout, rozbalit. Spustit `PrusaSlicer.exe`

2) Import konfigurace tiskárny
File -> Import -> Import Config Bundle -> `PrusaSlicer_config_E3V2.ini`

(Případně skrze `.3mf` soubor projektu a importování celé konfigurace)