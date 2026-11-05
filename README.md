# ebPOS — Raportare probleme și sugestii

Acest repository este locul unde se raportează **bug-urile** și se trimit **sugestiile de îmbunătățire** pentru aplicația **ebPOS**.

> ℹ️ Codul sursă al aplicației **nu** se află aici. Repository-ul este folosit exclusiv pentru urmărirea problemelor (Issues).

---

## Cum raportez o problemă

1. Intră în tab-ul **[Issues](https://github.com/dvaduva/ebpos/issues)**.
2. Caută mai întâi dacă problema a mai fost raportată (inclusiv printre cele închise — filtrul `is:issue`, fără `is:open`).
3. Dacă nu există, apasă **New issue**.
4. Completează un **titlu scurt și clar** și o descriere după modelul de mai jos.

### Model de descriere

```text
Zona din aplicație:  (ex. Vânzare / Mese / Kitchen Monitor / Rapoarte / Admin / Etichete)
Rol utilizator:      (ex. Casier, Ospătar, Administrator)
Dispozitiv:          (ex. PC Windows, tabletă Android, imprimantă POS80)

Ce am făcut:
1. ...
2. ...

Ce s-a întâmplat:
...

Ce mă așteptam să se întâmple:
...

Mesaj de eroare (dacă apare):
...
```

**Atașează capturi de ecran** sau o scurtă înregistrare video ori de câte ori este posibil — ajută enorm la rezolvarea rapidă.

### Exemple de titluri bune

| ✅ Bine | ❌ De evitat |
|---|---|
| Masa nu se eliberează după plata cu cardul | Nu merge |
| 403 la deschiderea raportului de vânzări pentru rolul Casier | Eroare |
| Rapoartele nu se pot tipări pe POS80, doar A4 | Problema imprimare |

---

## Sugestii și funcționalități noi

Sugestiile sunt binevenite! Deschide un issue nou și descrie:

- **ce** ai vrea să facă aplicația;
- **de ce** ți-ar fi util (ce situație din activitatea zilnică rezolvă);
- dacă e cazul, **cum** ți-ai imagina că ar arăta (schiță, captură, exemplu din altă aplicație).

---

## Ce se întâmplă după ce trimit

| Etichetă | Semnificație |
|---|---|
| `bug` | Problemă confirmată în funcționarea aplicației |
| `enhancement` | Sugestie / funcționalitate nouă |
| `question` | Sunt necesare informații suplimentare de la tine |
| `duplicate` | Problema a mai fost raportată (vezi issue-ul indicat) |
| `wontfix` | Nu va fi implementat (cu explicație) |

- Un issue **deschis** este în analiză sau în lucru.
- Un issue **închis** a fost rezolvat — modificarea ajunge în aplicație odată cu următoarea actualizare.
- Dacă problema reapare după închidere, scrie un comentariu în același issue în loc să deschizi unul nou.

---

## ⚠️ Atenție la date sensibile

Repository-ul este **public**. Nu include în issue-uri:

- parole, coduri PIN, chei API sau token-uri;
- date personale ale clienților (nume complete, telefoane, adrese);
- date fiscale sau financiare confidențiale.

Ascunde (blur) aceste informații în capturile de ecran înainte de a le încărca.
