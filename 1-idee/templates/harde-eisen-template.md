# **⚙️ Harde Eisen: {Feature/Project Naam}**

Een gestructureerde aanpak voor het definiëren van actoren, componenten, activiteiten, eigenschappen en gedragingen voor een feature of project.

🔐 **Vastgelegde Informatie:** Wie/wat betrokken is, wat er gebeurt, welke waardes relevant zijn, hoe het zich gedraagt, plus ideeën en vragen.

## **🤖 AI Agent Context**

💡 *Essentiële informatie voor de AI-agent om deze vereisten te begrijpen en effectief uit te voeren. Bekijk alle gelinkte bronnen grondig voordat je verdergaat.*
![img.png](img.png)
### **📚 Relevante Project Bestanden & Code**

💡 *Lijst alle projectbestanden, code snippets of directories die de AI agent moet lezen en begrijpen. Voeg paden toe relatief aan de project root en een korte notitie over hun relevantie.*

* `[pad/naar/relevante/feature_beschrijving.md]` - (Relevantie: Overzicht op hoog niveau van de feature)
* `[pad/naar/bestaande/module_indien_gerelateerd/]` - (Relevantie: Code voor gerelateerde bestaande functionaliteit)
* *Voorbeeld: `docs/data_modellen.md` - (Relevantie: Definities van bestaande datastructuren)*

### **🌐 Relevante Documentatie & Links**

💡 *Lijst externe webpagina's, API documentatie, ontwerp specificaties (bijv. Figma links), of andere online bronnen die de AI agent moet raadplegen.*

* `[Link naar Gebruikersverhalen of Epic]` - (Relevantie: Gebruikersgerichte weergave van de vereisten)
* `[Link naar UI Mockups/Prototypes (Figma, etc.)]` - (Relevantie: Visueel en interactie ontwerp)
* *Voorbeeld: `https://www.w3.org/TR/WCAG21/` - (Relevantie: Toegankelijkheidsrichtlijnen indien van toepassing)*

### **💡 Andere Belangrijke Informatie**

💡 *Voeg andere kritieke context toe, specifieke instructies, of punten waar de AI agent zich bewust van moet zijn.*

* `[Context punt 1: bijv. Deze vereisten zijn voor de MVP (Minimum Viable Product) release.]`
* `[Context punt 2: bijv. Het systeem moet integreren met de bestaande authenticatie service.]`
* *Voorbeeld: Prestaties zijn een belangrijke overweging; vermijd oplossingen die bekend staan als resource-intensief.*

## **💼 Business Waarde / Rechtvaardiging**

💡 *Waarom is deze feature/project belangrijk? Welke waarde levert het op? Kwantificeer indien mogelijk.*

[Gedetailleerde uitleg van de business waarde en rechtvaardiging]

## **🎯 Strategische Doelstellingen**

💡 *Wat zijn de hoofddoelen die deze vereisten willen bereiken? Lijst 2-5 belangrijke doelstellingen.*

* **Doel 1:** [Beschrijving van strategisch doel]
  * Doelstelling 1.1: [Specifieke, meetbare doelstelling]
  * Doelstelling 1.2: [Specifieke, meetbare doelstelling]
* **Doel 2:** [Beschrijving van strategisch doel]
  * Doelstelling 2.1: [Specifieke, meetbare doelstelling]

## **📈 Succes Metrics / KPIs**

💡 *Hoe meten we het succes? Definieer belangrijke prestatie-indicatoren.*

* **KPI 1:** [Naam van KPI] - Doel: [Meetbaar Doel]
* **KPI 2:** [Naam van KPI] - Doel: [Meetbaar Doel]
* **KPI 3:** [Naam van KPI] - Doel: [Meetbaar Doel]

## **🧩 Actoren & Componenten (Wie of wat)**

💡 *Iemand of iets dat acties kan uitvoeren of waarmee geïnteracteerd kan worden (voorbeelden zijn Gebruiker, Knop, Scherm, Invoerveld, Bericht, Systeem, API, Database).*

> *Wie heeft hier baat bij? · Wie onderhoudt dit? · Waarmee interacteren gebruikers? · Wat toont informatie? · Wat verwerkt data? · Wat slaat data op? · Welke externe systemen zijn betrokken? · Wat moet gemonitord worden?*

* `[Actor/Component 1]`
* `[Actor/Component 2]`
  * `[Kind Actor/Component 2.1]`
* ...

## **🎬 Activiteiten (Wie of wat doet wat?)**

💡 *Acties die een Actor of Component uitvoert (voorbeelden zijn Lijst Aanmaken, Item Verwijderen, Data Synchroniseren, en ze moeten altijd een werkwoord + actie bevatten).*

> *Wat kan elke actor doen? · Wat moet automatisch gebeuren? · Wat heeft gebruikersinput nodig? · Wat gebeurt periodiek? · Wat triggert andere activiteiten? · Wat moet gelogd worden? · Wat moet gemeten worden? · Wat heeft autorisatie nodig?*

* `[Actor/Component Naam]`
  * `[Activiteit 1 voor deze Actor/Component]`
  * `[Activiteit 2 voor deze Actor/Component]`
* ...

### **🌊 Activiteitsstromen & Scenario's (Wat in welke volgorde?)**

💡 *Sequenties van Atomaire Acties die de stappen beschrijven om een Activiteit te voltooien. Kunnen optionele paden hebben voor succesvolle afronding (Happy Flow), fouten (Error Flow), en scenario's zoals geen verbinding, lege states, laad states, etc.*

> *Wat is het ideale pad? · Wat kan falen? · Wat moet gevalideerd worden? · Wat moet bevestigd worden? · Wat is tijdsgevoelig? · Wat heeft herstelstappen nodig? · Wat moet gecached worden? · Wat moet opnieuw geprobeerd worden? · Wat heeft rollback nodig?*

* `[Activiteit Naam]`
  * **Happy Flow:**
    * GEGEVEN `[voorwaarde]`
    * WANNEER `[actie]`
    * DAN `[verwacht resultaat]`
  * **Error Flow (bijv. Ongeldige Input):**
    * GEGEVEN `[voorwaarde]`
    * WANNEER `[actie met ongeldige input]`
    * DAN `[foutmelding wordt getoond]`

## **📝 Eigenschappen (Welke waardes?)**

💡 *Beschrijft een waarde of configuratie die bij een object hoort (voorbeelden zijn breedte, kleur, id, naam).*

> *Wat identificeert het? · Wat beschrijft het? · Wat configureert het? · Wat meet het? · Wat stijlt het? · Wat formatteert het? · Wat volgt het? · Wat groepeert het? · Wat ordent het?*

* `[Actor/Component/Activiteit Naam]`
  * `[eigenschap_naam : data_type (bijv. gebruiker_id : string, is_ingeschakeld : boolean)]`
  * `[andere_eigenschap : data_type]`
* ...

## **🛠️ Gedragingen (Hoe gedraagt het zich wanneer.. in termen van..?)**

💡 *Definieert hoe iets eruitziet, werkt en presteert. Voorbeelden zijn ui/ux, regels & limieten, data & analytics, beveiliging, prestaties en schaalbaarheid.*

> *Wanneer moet het veranderen? · Hoe moet het reageren? · Wat zijn de limieten? · Wat moet validatie? · Wat moet animatie? · Wat moet bescherming? · Wat moet gecached worden? · Wat moet geoptimaliseerd worden? · Wat moet gemonitord worden? · Wat heeft fallback nodig? · Hoe moet het schalen? · Wat moet gelogd worden? · Hoe moet het falen? · Wat moet gemeten worden? · Wat heeft autorisatie nodig?*

* `[Actor/Component/Activiteit/Eigenschap Naam]`
  * `[Gedrag 1: bijv. Knop moet een laad-spinner tonen wanneer aangeklikt en een API call bezig is.]`
  * `[Gedrag 2: bijv. Invoerveld voor 'email' moet formaat valideren tegen standaard email regex.]`
* ...

## **🔗 Afhankelijkheden**

💡 *Zijn er interne of externe afhankelijkheden die impact kunnen hebben?*

* **Interne Afhankelijkheden:** [bijv. Afhankelijk van Team X voor Component Y]
* **Externe Afhankelijkheden:** [bijv. Third-party API beschikbaarheid]

## **💣 Risico's & Mitigatie**

💡 *Welke potentiële risico's kunnen de implementatie belemmeren?*

* **Risico 1:** [Beschrijving van risico]
  * Impact: Hoog/Medium/Laag
  * Kans: Hoog/Medium/Laag
  * Mitigatie: [Strategie om dit risico te beperken]

## **💡 Ideeën & 🪵 Achterstand**

💡 *Alles wat later toegevoegd kan worden, nu te complex is, meer onderzoek nodig heeft, leuk zou zijn om te hebben, of alternatieve benaderingen.*

> *Wat kan later toegevoegd worden? · Wat is nu te complex? · Wat heeft meer onderzoek nodig? · Wat zou leuk zijn om te hebben? · Wat zijn alternatieve benaderingen? · Wat kan geautomatiseerd worden?*

* `[Optionele Ouder Context]`
  * `[Idee/Achterstand Item 1: bijv. Verken integratie met X service voor Y feature.]`
  * `[Idee/Achterstand Item 2: bijv. Overweeg gamificatie elementen toe te voegen aan gebruikersprofielen.]`
* ...

## **❓ Vragen**

💡 *Vragen die beantwoord moeten worden om vereisten te verduidelijken.*

> *Wat is onduidelijk? · Wat heeft een beslissing nodig? · Wat zijn de edge cases? · Wat kan verbeterd worden? · Wat missen we? · Welke aannames maken we? · Welke risico's bestaan er? · Welke afhankelijkheden zijn er?*

* `[Optionele Ouder Context]`
  * `[Vraag 1: bijv. Wat is de exacte timeout duur voor API calls? Toegewezen aan: @TechLead]`
  * `[Vraag 2: bijv. Zijn er specifieke merkrichtlijnen voor de foutmeldingen? Toegewezen aan: @UXDesigner]`
* ...

## **🎯 Rollen, 📝 Taken & 🎓 Voorgestelde Aanpak**

💡 *Elk gedrag, eigenschap, activiteit (stroom), scenario, atomaire actie, actor, component moet direct of indirect (via ouders) leiden tot een taak met toegewezen rol.*

> *Wie is verantwoordelijk voor wat?*

* **🎨 UI/UX Ontwerper**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Ontwerp wireframes voor de gebruikersregistratie stroom.]`
    * [ ] `[Taak 2: bijv. Maak high-fidelity mockups voor het instellingen scherm.]`
* **🖥️ Frontend Ontwikkelaar**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Implementeer de login component gebaseerd op Figma ontwerpen.]`
    * [ ] `[Taak 2: bijv. Integreer het gebruikersprofiel API endpoint.]`
* **🔧 Backend Ontwikkelaar**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Maak database schema voor gebruikersprofielen.]`
    * [ ] `[Taak 2: bijv. Ontwikkel API endpoint voor het bijwerken van gebruikersinstellingen.]`
* **📊 Data Engineer**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Stel analytics tracking in voor nieuwe feature X.]`
* **🚀 DevOps Engineer**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Configureer CI/CD pipeline voor geautomatiseerde deployment.]`
* **📌 Project Manager**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Coördineer UAT met stakeholders.]`
* **📣 Marketeer**
  * `[Optionele Ouder Context]`
    * [ ] `[Taak 1: bijv. Bereid aankondigingsmaterialen voor de nieuwe feature voor.]`

## **🧑‍🤝‍🧑 Stakeholders**

💡 *Wie zijn de belangrijkste stakeholders voor deze vereisten?*

* **Product Owner/Sponsor:** [@gebruikersnaam of Team Naam]
* **Belangrijke Business Units:** [bijv. Marketing, Sales, Operations]
* **Development Lead(s):** [@gebruikersnaam of Team Naam]
* **Andere Belangrijke Contacten:**

## **👉 Afsluitende Opmerkingen & Open Punten**

💡 *Andere relevante informatie, links naar ondersteunende documenten, of open punten.*

* **Ondersteunende Documenten:** [Link naar specificaties, onderzoek, analyse, etc.]
* **Open Punten:**
  * [Punt 1 dat nog besproken moet worden]
  * [Punt 2 dat nog besloten moet worden]
