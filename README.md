# Hej, jag heter Sima 👋

Jag studerar till **fullstackutvecklare med säkerhetsinriktning** på Företagsuniversitetet.
Jag har också läst cybersäkerhet, GRC och dataskydd inom IT och AI.

🔎 **Jag söker LIA 2027:** vecka 11–24 och vecka 33–43.

---

## ParishHub – app för ortodoxa kyrkor

En app som jag bygger för S:t Georgs kyrka. Prästen planerar gudstjänster och
medlemmar, och under gudstjänsten visas liturgin på projektorn på koptiska,
arabiska och svenska samtidigt.

**AI-tolkning live:** prästens predikan på arabiska ska visas som svensk text på
projektorn, och tvärtom. Gränssnittet är byggt och testas med simulerad data.
Kopplingen till tal-till-text och översättning görs i backend.

<table>
  <tr>
    <td><img width="400" alt="Teknikerns vy för att styra skärmen under gudstjänsten" src="https://github.com/user-attachments/assets/14b69bdc-d8fb-45d9-9788-cb7147ec8049" /></td>
    <td><img width="400" alt="Rutan där prästen väljer om predikan ska delas, sparas privat eller raderas" src="https://github.com/user-attachments/assets/9bcb8bd7-93e0-42fa-86fc-c1cd0eedfc81" /></td>
  </tr>
  <tr>
    <td><img width="400" alt="Förberedelse av gudstjänsten med liturgi och material till projektorn" src="https://github.com/user-attachments/assets/4c9e4fe7-f386-4589-92ae-b30d8bdf627b" /></td>
    <td><img width="400" alt="Närvaro för gudstjänster med diagram" src="https://github.com/user-attachments/assets/dca103e7-776e-4672-8643-50468cbcd7c3" /></td>
  </tr>
  <tr>
    <td colspan="2"><img width="400" alt="Formulär för medlemmar" src="https://github.com/user-attachments/assets/d95fbe36-559e-4699-a524-396691c90ccc" /></td>
  </tr>
</table>




*Bilderna visar testdata. Inga riktiga medlemmar.*

**Teknik:** React · TypeScript · Vite · Tailwind CSS · Zod · TanStack Query · i18next (svenska, engelska, arabiska med höger-till-vänster) · Vitest · React Testing Library

**Säkerhet i koden:**
- Rollbaserad behörighet (RBAC). Servern ska alltid kontrollera rollen igen – backend byggs nu
- All data valideras med Zod (vitlista)
- Dataminimering enligt GDPR – tolkad text raderas automatiskt
- Hotmodell med STRIDE för registreringen
- Inga API-nycklar i frontend
- CI på GitHub: typkontroll, lint, över 950 tester och npm audit vid varje push

🔒 *Koden är privat eftersom projektet innehåller licensierat material. Läsåtkomst ges på begäran.*

---

## Bibel- och liturgiapp för ortodoxa församlingar

Examensarbete i JavaScript Advanced och React. En digital resurs på svenska med
Bibeln, böner, liturgi och kyrkofädernas tolkningar.

- Hela Bibeln på svenska och arabiska, med ljud
- Agbeya (8 bönetider), Liturgiboken (8 liturgier) och Stilla veckan, med ljud
- Dagens läsningar med koptiskt datum, Katameros och synaxariet
- Kyrkofädernas tolkningar av Bibeln på svenska
- Läsprofiler (barn, ungdom, ny i tron, fördjupning) med AI-förklaringar anpassade efter profilen
- Favoriter, anteckningar och mörkt/ljust tema

**Teknik:** React · JavaScript · Vite · React Router · Context API · useReducer · Tailwind CSS · GSAP · Vitest

🔒 *Privat repo eftersom appen innehåller licensierat material. Läsåtkomst ges på begäran.*


---

## Publika projekt

- **Portfolio** – [sima-soolind.netlify.app](https://sima-soolind.netlify.app)
- **SM-Bygg** – företagswebbplats i HTML, CSS och JavaScript – [sm-bygg.netlify.app](https://sm-bygg.netlify.app)

---

📫 **Kontakt:** [LinkedIn](https://www.linkedin.com/in/sima-soolind) · [Portfolio](https://sima-soolind.netlify.app)
