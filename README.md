# athensapps.gr

Αρχική σελίδα του [athensapps.gr](https://athensapps.gr), με πιλοτικές web εφαρμογές που αξιοποιούν τα ανοιχτά δεδομένα του Δήμου Αθηναίων. Κάθε εφαρμογή ζει στο δικό της subdomain.

## Πιλοτικά

| Εφαρμογή | URL | Κατάσταση |
|---|---|---|
| Athens Pulse | [athenspulse.athensapps.gr](https://athenspulse.athensapps.gr) | Live |
| Γειτονιές της Αθήνας | [athenshoods.gr](https://athenshoods.gr) | Live |
| Οδοί της Αθήνας | streets.athensapps.gr | Σύντομα |

## Δομή

Στατική σελίδα σε ένα αρχείο (`index.html`), χωρίς build. Ανεβαίνει όπως είναι στο `public_html` του hosting.

## Προσθήκη νέου πιλοτικού

Στο τέλος του `index.html` υπάρχει η λίστα `PILOTS`. Πρόσθεσε ένα αντικείμενο:

```js
{
  name: "Όνομα εφαρμογής",
  url: "https://onoma.athensapps.gr",
  status: "live",            // "live" | "beta" | "soon"
  color: "#1b3a6b",
  icon: '<path d="..." stroke="currentColor" stroke-width="2.2" fill="none"/>',
  description: "Σύντομη περιγραφή.",
  tags: ["Tag 1", "Tag 2"]
}
```

## Σημείωση

Προσωπικό έργο του [Thomas Ntoupis](https://thomasthemoustache.com). Δεν αποτελεί επίσημη υπηρεσία του Δήμου Αθηναίων.

## Άδεια

MIT
