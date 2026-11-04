# athensapps.gr

Αρχική σελίδα του [athensapps.gr](https://athensapps.gr), με πιλοτικές web εφαρμογές που αξιοποιούν τα ανοιχτά δεδομένα του Δήμου Αθηναίων. Κάθε εφαρμογή ζει στο δικό της subdomain.

## Πιλοτικά

| Εφαρμογή | URL | Κατάσταση |
|---|---|---|
| Athens Pulse | [pulse.athensapps.gr](https://pulse.athensapps.gr) | Live |
| Athens Breath | [breath.athensapps.gr](https://breath.athensapps.gr) | Live |
| Πού να παίξω | [sports.athensapps.gr](https://sports.athensapps.gr) | Live |
| Γειτονιές της Αθήνας | [athenshoods.gr](https://athenshoods.gr) | Live |
| Οδοί της Αθήνας | streets.athensapps.gr | Σύντομα |

## Δομή

Στατική σελίδα σε ένα αρχείο (`index.html`), χωρίς build. Ανεβαίνει όπως είναι στο `public_html` του hosting.

## Προσθήκη νέου πιλοτικού

Στο τέλος του `index.html` υπάρχει η λίστα `PILOTS`. Πρόσθεσε ένα αντικείμενο:

```js
{
  name: "Όνομα εφαρμογής",
  sign: "ΚΕΙΜΕΝΟ ΠΙΝΑΚΙΔΑΣ",  // κεφαλαία χωρίς τόνους
  latin: "Keimeno pinakidas", // λατινικοί χαρακτήρες κάτω από την πινακίδα
  url: "https://onoma.athensapps.gr",
  status: "live",            // "live" | "beta" | "soon"
  description: "Σύντομη περιγραφή.",
  tags: ["Tag 1", "Tag 2"]
}
```

## Σημείωση

Προσωπικό έργο του [Thomas Ntoupis](https://thomasthemoustache.com). Δεν αποτελεί επίσημη υπηρεσία του Δήμου Αθηναίων.

## Άδεια

MIT

## Λογότυπο και εικόνες

Στον φάκελο `brand/`:

| Αρχείο | Χρήση |
|---|---|
| `logo.svg`, `logo-1200.png` | Κύριο λογότυπο (πινακίδα) |
| `logo-inverse.svg`, `logo-inverse-1200.png` | Λογότυπο για σκούρο φόντο |
| `logo-with-icon.svg`, `logo-with-icon-1200.png` | Σήμα μαζί με το όνομα |
| `icon.svg`, `icon-512.png` | Σήμα AA |
| `avatar.svg`, `avatar-1000.png` | Εικόνα προφίλ για social και GitHub |

Στη ρίζα βρίσκονται τα `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`, `icon-192.png` και `og-image.png` (εικόνα που εμφανίζεται όταν κοινοποιείται το link).
