# cooktop
reverse engineer electrolux induction cooktop


# connector
+5v
bus
GND

!!! GND to Earth gives 230V !!! mozno naschval, aby fungovali bezkontaktne tlacitka

osadena prepojka tohoto napajania je jediny rozdiel medi doskami
pripojenie dosky do siete dava skaredy impulz, ze ostatne zdroje vypadavaju TV/repro/...

daisy chain: control board - board2 - board1

9600 baud ttl signal on bus


turned off:
every 10seconds 2packet sent 2packet response


