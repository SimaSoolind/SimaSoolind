# Hej, jag heter Sima 👋

Jag studerar till **fullstackutvecklare med säkerhetsinriktning** på Företagsuniversitetet.
Jag har också läst cybersäkerhet, GRC och dataskydd inom IT och AI, och läser nu
**Tillämpad AI för systemutveckling och test**.

🔎 **Jag söker LIA 2027:** vecka 11–24 och vecka 33–43.

### 🇬🇧 In English

I'm studying to become a full-stack developer with a focus on IT security at Företagsuniversitetet in Stockholm.
I have also studied cybersecurity, GRC and data protection in IT and AI, and I'm currently taking
Applied AI for System Development and Testing. I'm looking for an internship (LIA) in 2027: weeks 11–24 and 33–43.

**ParishHub** – a web app for Orthodox churches, built for St. George's Church. The priest plans services and
manages members, and the liturgy is shown on the projector in Coptic, Arabic and Swedish at the same time.
Live AI interpretation of the sermon (Arabic ↔ Swedish) is designed and tested with simulated data. The connection
to speech-to-text and translation will be built in the backend. React, TypeScript, Zod, role-based access control,
GDPR data minimisation and over 950 automated tests in CI.

**Bible app** – a free Bible and prayer book in Swedish and Arabic for Coptic Orthodox congregations, with audio,
the Church Fathers' commentaries and reading profiles for children, youth, new believers and deeper study.
Built with accessibility in mind. React 19, a Node.js data pipeline and PostgreSQL with 107,000 verses.
The AI features stay switched off until they run on a separate server, so that no API key is ever exposed in the browser.

Both repositories are private because they contain licensed material. Read access is available on request.

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
<td><img width="400" alt="Profilsida för en medlem med uppgifter och närvarohistorik" src="https://github.com/user-attachments/assets/d95fbe36-559e-4699-a524-396691c90ccc" /></td>
<td><img width="400" alt="Färdiga WhatsApp-meddelanden till en medlem och knappen för att radera medlemmen" src="https://github.com/user-attachments/assets/39e0acdc-d7fd-4033-8bca-573c4dc60c45" /></td>
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

## Bibel-appen – digital bibel och bönbok på svenska och arabiska

Påbörjad i kursen JavaScript Advanced och React och under fortsatt utveckling. Appen riktar sig till
svensk-arabisktalande koptisk-ortodoxa församlingar, är gratis och kräver ingen inloggning.

**Tillgänglighet och inkludering:** målet är att ingen ska stängas ute, varken nya i tron, unga, äldre
eller personer med lässvårigheter. Böner och liturgi går att lyssna på, textstorleken går att ändra och
arabiskan visas höger-till-vänster. Knappar är minst 44 pixlar, ikonknappar har beskrivningar för
skärmläsare och animationer stängs av vid minskad rörelse.

**Innehåll**
- Hela Bibeln på svenska och arabiska, inklusive apokryferna
- Agbeya (8 bönetider), Liturgiboken (8 liturgier) och Stilla veckan, med ljud
- Dagens läsningar enligt kyrkoåret med koptiskt datum
- Kyrkofädernas tolkningar kapitel för kapitel, tre verk att jämföra. Översättning till svenska pågår, Matteusevangeliet är klart
- Läsprofiler: barn, ungdom, ny i tron och fördjupning
- Favoriter, anteckningar och mörkt/ljust tema

<table>
<tr>
<td colspan="2"><img width="810" alt="Appens välkomstsida om den ortodoxa tron" src="https://github.com/user-attachments/assets/30c6cdc8-0c42-4a85-8d1a-79f236f495b9" /></td>
</tr>
<tr>
<td><img width="400" alt="Startsidan Bibel för alla med dagens datum" src="https://github.com/user-attachments/assets/440a34c4-81a6-47b7-b5b7-58381a059652" /></td>
<td><img width="400" alt="Startsidan med snabbval till Dagens läsningar, Agbeya, Stilla veckan, Liturgiboken och Katameros" src="https://github.com/user-attachments/assets/9b30501d-4ba2-411f-b5e3-21f3e9b031ca" /></td>
</tr>
<tr>
<td><img width="400" alt="Startsidan med dagens citat, senast lästa kapitel och antal favoriter" src="https://github.com/user-attachments/assets/db2b706e-9058-4e0e-9266-34aed266bfc9" /></td>
<td><img width="400" alt="Liturgiboken med de olika liturgierna" src="https://github.com/user-attachments/assets/ab6048d2-910b-41b5-b667-8f87d1fc27bb" /></td>
</tr>
<tr>
<td><img width="400" alt="Matteus kapitel 4 med knappar för kyrkofädernas tolkning, svenska eller arabiska och uppläsning" src="https://github.com/user-attachments/assets/20a1ab59-d02e-452c-a9f0-ded3e82e6110" /></td>
<td><img width="400" alt="Kyrkofädernas tolkning av Matteus 4 med tre verk att jämföra" src="https://github.com/user-attachments/assets/3c0c75e4-ac45-41e7-a48d-61fbf86f004c" /></td>
</tr>
<tr>
<td><img width="400" alt="AI-rutan som visar att AI-förklaringarna är avstängda tills de flyttas till en egen server" src="https://github.com/user-attachments/assets/9df432b0-8b0c-46b2-a4e8-de42eac21d2a" /></td>
<td><img width="400" alt="Fråga om tron, en AI-assistent som är avstängd tills den flyttas till en egen server" src="https://github.com/user-attachments/assets/0132a92f-fb89-4223-9ed8-e721dc5ce97b" /></td>
</tr>
</table>

**Teknik:** React 19, Vite, React Router och Tailwind. Egen datapipeline i Node.js mot PostgreSQL med 107 000 verser.

**AI:** Gemini översätter tolkningarna från arabiska till lättläst svenska för uppläsning. AI-förklaringar efter
profil är byggda men avstängda tills de flyttas till en egen server, så att API-nyckeln aldrig ligger i webbläsaren.

**Säkerhet:** minsta möjliga databasbehörighet, GDPR artikel 9 och automatiska tester.

🔒 *Privat repo eftersom appen innehåller licensierat material. Läsåtkomst ges på begäran.*

---

## Publika projekt

- **Portfolio** – [sima-soolind.netlify.app](https://sima-soolind.netlify.app)
- **SM-Bygg** – företagswebbplats i HTML, CSS och JavaScript – [sm-bygg.netlify.app](https://sm-bygg.netlify.app)

---

📫 **Kontakt:** [LinkedIn](https://www.linkedin.com/in/sima-soolind) · [Portfolio](https://sima-soolind.netlify.app)
