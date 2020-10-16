# Adathalmaz bemutatása

Az adathalmaz egy online cikkből van amit Nuno Antonio, Ana Almeida, és Luis Nunes csinált 2019 februárjában. Az adathalmazt kaggle.com-ról töltöttem le.

Ez az adathalmaz hotelfoglalási adatokat tartalmaz, egy városi szállodáról és egy üdülőszállóról. Mindkét szálloda esetében 31 különböző változó található, összesen közel 120.000 mintával.

A változók a következők:

- **hotel**: A hotel típusát adja meg, azaz városi szálloda vagy üdülőszálló.
- **lead_time**: Hány nappal hamarabb foglalták le a szállást mint ahogy érkeznek.
- **arrival_date_year**: Melyik évben érkezik a vendég a szállásra.
- **arrival_date_month**: Melyik hónapban érkezik a vendég a szállásra.
- **arrival_date_week_number**: Hanyadik héten érkezik a vendég a szállásra.
- **arrival_date_day_month**: Hanyadik napon a hónapban érkezik a vendég a szállásra.
- **stays_in_weekend_nights**: Hány hétvégi éjszakát (szombat, vasárnap) marad/foglalt a vendég.
- **stays_in_week_nights**: Hány hétköznapi éjszakát (hétfőtől, péntekig) marad/foglalt a vendég.
- **adults**: Felnőttek száma.
- **children**: Gyerekek száma.
- **babies**: Babák száma.
- **meal**: Milyen étkezést foglalt a vendég (reggeli, félpanzió, teljes ellátás).
- **county**: Milyen országból származik a vendég.
- **market_segment**: Milyen piaci szegmensből érkezett a foglalás (online/offline utazási irodán keresztül, direkt szállódával stb.).
- **distribution_channel**: Milyen csatornán keresztül foglaltak (utazási iroda, direkt szállódával stb).
- **is_repeated_guest**: Visszajáró vendég-e.
- **previous_cancellations**: Hány foglalást mondott le eddig a vendég.
- **previous_bookings_not_canceled**: Hány foglast nem mondott le a vendég.
- **reserved_room_type**: A foglalt szoba típusa.
- **assigned_room_type**: A kapott szoba típusa.
- **booking_changes**: Hányszor módosították a foglalást a megérkezésig.
- **deposit_type**: Fizetett-e előleget a vendég. 3 lehetőség van, nem fizetett, fizetett de visszakaphatja, fizetett és nem kaphatja vissza.
- **agent**: Az utazási iroda ID-ja amin keresztül a foglalt a vendég.
- **company**: A cég ID-je amin keresztül foglaltak és aki felelős azért, hogy ki legyen fizetve a szállás.
- **days_in_waiting_list**: A napok száma mielőtt visszaigazoltak egy foglalást.
- **customer_type**: Milyen típusú a foglalás.
- **adr**: Napi átlagár.
- **required_car_parking_spaces**: Hány parkolóhelyet kért a vendég.
- **total_of_special_requests**: Hány különleges kérése volt a vendégnek.
- **is_canceled**: Le lett-e mondva a foglalás.

Ebben az iparágban a bevételbecsléshez biztosan kell előrejelzéseket, jóslátokat meg fogalmazni a jövővel kapcsolatban.
Egy ilyen adathalmaz és a belőle betanított modellek és ezeknek az adatoknak az elemzése hasznos információkkal szolgálhatnak egy szállodának a világ bármely pontján hiszen a szállás már a foglalás pillanatában tudja, hogy milyen valószínűséggel fog megérkezni a vendég. 
Felmerülhet a kérdés, hogy megkockáztassa-e több szoba kiadását mint ahány összesen rendelkezésre áll így próbálva maximalizálni a szálláshely profitját hiszen van egy foglalásuk ami nagy eséllyel le lesz mondva.


# Linkek

Link a cikkhez: https://www.sciencedirect.com/science/article/pii/S2352340918315191
Link kaggle.com-hoz: https://www.kaggle.com/jessemostipak/hotel-booking-demand