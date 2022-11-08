# Publikacje-DBM
System publikacji Discord Bot Maker ~ feymez

Aby wszystko działało tak jak zostało to przewidziane przed konfiguracją należy przygotować:
  - 3 kanały dla osób sprawdzających publikacje (np. #do-sprawdzenia-rawdaty, #do-sprawdzenia-skrypty, #do-sprawdzenia-api)
  - Po 3 kanały na każdy rodzaj publikacji (np. RAWDATY: #raw-moderacja, #raw-zabawa, #raw-inne itd.)
Cały system jest przygotowany pod 3 kategorie (RAWDATY, SKRYPTY, API) oraz w każdej z kategorii mamy 3 podkategorie (MODERACJA, ZABAWA, INNE)

### UWAGA! System nie nalicza wystawionych publikacji!

#### AUTOR NIE ODPOWIADA ZA DZIAŁANIE PRZEROBIONEJ RAWDATY

Komenda /publikacja

Akcja #8 - Wklejamy ID kanału #do-sprawdzenia-skrypty
Akcja #11 - Wklejamy ID kanału #do-sprawdzenia-rawdaty
Akcja #14 - Wklejamy ID kanału #do-sprawdzenia-api

Przechodzimy do akcji #8
Klikamy w 'Buttons' i przechodzimy do przycisku 'Przyjmij'

Akcja #2 przycisku - Wklejamy ID kanału #skrypty-moderacja
Akcja #8 przycisku - Wklejamy ID kanału #skrypty-zabawa
Akcja #14 przycisku - Wklejamy ID kanału #skrypty-inne

(Dodatkowo jeżeli chcemy możemy zmienić emotki jakie bot doda do wiadomości. Wtedy zmieniamy to w akcjach #3, #4, #9, #10, #15, #16)

Następnie wracamy do akcji komendy. Przechodzimy do akcji #11 => 'Buttons' => 'Przyjmij'

Akcja #2 przycisku - Wklejamy ID kanału #raw-moderacja
Akcja #8 przycisku - Wklejamy ID kanału #raw-zabawa
Akcja #14 przycisku - Wklejamy ID kanału #raw-inne

Następnie wracamy do akcji komendy. Przechodzimy do akcji #14 => 'Buttons' => 'Przyjmij'

Akcja #2 przycisku - Wklejamy ID kanału #api-moderacja
Akcja #8 przycisku - Wklejamy ID kanału #api-zabawa
Akcja #14 przycisku - Wklejamy ID kanału #api-inne

# Publications DBM
Publications system Discord Bot Maker ~ feymez

For everything to work as planned, before the configuration, you should prepare:
  - 3 channels for people checking publications (e.g. #rto-check-rawdata, #to-check-scripts, #to-check-api)
  - 3 channels for each type of publication (e.g. rawdate's: #raw-moderation, #raw-fun, #raw-other etc.)
The whole system is prepared for 3 categories (RAWDATES, SCRIPTS, API) and in each of the categories we have 3 subcategories (MODERATION, FUN, OTHER)

### ATTENTION! The system does not count the published publications!


#### THE AUTHOR IS NOT RESPONSIBLE FOR THE OPERATION OF THE EDITED RAWDATA!

Command /publish

Action #8 - Paste the channel ID #to-check-scripts <br>
Action #11 - Paste the channel ID #to-check-rawdate
Action #14 - Paste the channel ID #to-check-api
