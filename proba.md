# Sistem za upravljanje studentskim praksama

## Opis projekta
Ovaj sistem omogućava povezivanje studenata, kompanija i fakultetskih koordinatora kroz jedinstvenu platformu za upravljanje studentskim praksama. Cilj sistema je olakšati proces prijave, odobravanja i praćenja praksi, kao i omogućiti evaluaciju i izvještavanje.

## Glavne funkcionalnosti
- Registracija i prijava korisnika
- Pregled dostupnih praksi
- Prijava studenata na praksu
- Odobravanje praksi od strane koordinatora
- Praćenje statusa prijave
- Evaluacija studenata nakon završene prakse
- Generisanje izvještaja

## Uloge u sistemu
### Student
- Pregled praksi
- Prijava na praksu
- Praćenje statusa

### Kompanija
- Kreiranje ponuda za praksu
- Pregled prijava studenata
- Odabir kandidata

### Koordinator
- Odobravanje praksi
- Praćenje napretka studenata
- Evaluacija

## Tehnologije
- Backend: ASP.NET Core
- Frontend: Angular
- Baza podataka: PostgreSQL
- Autentikacija: JWT

## Arhitektura
Sistem je baziran na mikroservisnoj arhitekturi, gdje svaki servis ima jasno definisanu odgovornost:
- User Service
- Internship Service
- Notification Service

## MVP (Minimal Viable Product)
Minimalna verzija sistema uključuje:
- Registraciju korisnika
- Pregled i prijavu na praksu
- Osnovno odobravanje praksi

## Buduća unapređenja
- Notifikacije putem emaila
- Integracija sa LinkedIn-om
- Napredna analitika i izvještaji

## Zaključak
Implementacijom ovog sistema značajno se unapređuje proces organizacije studentskih praksi, smanjuje administrativno opterećenje i poboljšava komunikacija između svih učesnika.