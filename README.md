# TachoMat

Self-service kiosks for reading tachograph driver cards, on transit routes in Poland.

Under EU rules (Regulation (EU) 581/2010), transport companies must download the data from each driver card at least every 28 days, and the driver has to bring the card to a reader. On international routes that often means a detour to the company base, where the card reader is, or waiting for an office to open. At a TachoMat kiosk the driver inserts the card, pays by BLIK or with a prepaid code and gets the DDD file in about a minute. The file goes to the driver by e-mail, or straight to the office that settles the carrier's working time.

## Where to find us

- Kalisz, Królów and Torzym: kiosks at fuel stations
- Olszyna: a kiosk at a roadside bar by the Olszyna-Forst border crossing on the A18

The kiosks are open day and night. The screens work in Polish, English and Ukrainian. Since October 2026 three of them also show an animated hint when a card goes in the wrong way.

## In numbers

- 4 kiosks in service
- 1,989 successful reads through our B2B channel at the Kalisz kiosk alone (kiosk counter, 28 October 2026)
- in business since 1 February 2026

## How it is built

We write our own software: the card-reading engine for 1st and 2nd generation cards, the kiosk application, the central server and the fleet panel. The same kiosk program runs on more than one class of hardware. Every new version is checked on a digital twin of the kiosk and in a separate test environment, with 269 automated tests across the panel, the full flow and the kiosk. Then it goes to one kiosk first and to the rest of the network after that.

The source code is private. This profile describes the company and the service.

## Contact

- Website: https://tachomat.pl
- Prepaid codes: https://kup.tachomat.pl
- E-mail: biuro@tachomat.pl

TachoMat is run by Żaneta Matyśkiewicz (Żaneta Matyśkiewicz TachoMat, sole proprietorship registered in Poland).

## Po polsku

TachoMat to samoobsługowe kioski do odczytu karty kierowcy przy trasach tranzytowych. Kierowca wkłada kartę, płaci BLIK-iem albo kodem przedpłaconym i po około minucie ma plik DDD na e-mailu. W kanale B2B plik trafia od razu do biura, które rozlicza czas pracy kierowców przewoźnika. Kioski stoją w Kaliszu, Królowie i Torzymiu na stacjach paliw oraz w barze w Olszynie, przy przejściu granicznym z Niemcami. Kontakt: biuro@tachomat.pl.
