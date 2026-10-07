# Simulator temperaturnih upozorenja

**Verzija:** demo-v04. Aplikacija služi za ručnu provjeru unesene temperature. Sustav ne uključuje fizički senzor, mjerenje vlage ni automatsku regulaciju ventilatora.

## Pokretanje aplikacije

1. Kopirajte cijelu mapu `tim-01-pametni-senzor` na svoje računalo.
2. Otvorite datoteku `src/index.html` u bilo kojem internetskom pregledniku (dodatne instalacije ili poslužitelji nisu potrebni).
3. Upišite `30` i pritisnite **Provjeri temperaturu** – sustav će generirati upozorenje.
4. Unesite `28` za dopušteno stanje, dok prazno polje mora rezultirati porukom o pogrešci.

Valjani raspon temperature kreće se od -40 do 85 °C uključivo. Upozorenje se aktivira za vrijednosti strogo veće od 28 °C, i to najkasnije pet sekundi nakon klika.

---

## Namjerno neispravna inačica za tutorial 08

U mapi `variants/pogreska-prag/index.html` nalazi se verzija s namjernom pogreškom – koristi prag 35 umjesto zahtijevanih 28 °C. Zbog toga unos vrijednosti `30` odmah otkriva grešku. Nemojte koristiti ovu datoteku kao ispravnu projektnu inačicu.

---

## Dokumentacija

- [Zahtjevi](docs/ZAHTJEVI.md)
- [Testovi](docs/TESTOVI.md)
- [Kanban kartice](docs/KANBAN.md)
- [Scenarij demonstracije](docs/SCENARIJ_DEMO.md)
- [Prijedlog teme](docs/PRIJEDLOG_TEME.md)
- [Prazni predložak prijedloga](docs/PRIJEDLOG_TEME_PRAZNO.md)
- [Izvori](docs/IZVORI.md)
- [AI evidencija](docs/AI_EVIDENCIJA.md)
- [Dnevnik rada](docs/DNEVNIK_RADA.md)
- [Dnevnik odluka](docs/DNEVNIK_ODLUKA.md)
- [Zapisnici](docs/ZAPISNICI.md)
- [Suradnja](docs/SURADNJA.md)

![Kontekst aplikacije](docs/slike/sustav.png)

> **Napomena:** Opseg ove simulacije prilagođen je učenju alata i svladavanju osnova, dok se stvarna složenost godišnjeg projekta definira i dogovara zasebno.