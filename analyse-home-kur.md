## Accessibility-Prüfergebnisse für die Webseite KUR basierend auf der WCAG (Web Content Accessibility Guidelines). 

### Allgemeine Informationen:
- **Prüftool**: Axe Accessibility Checker
- **Version**: 4.10.2
- **Datum der Analyse**: 17. Februar 2025

---

### Festgestellte Probleme:

#### 1. **Farbkontrastprobleme**:
   - **Beschreibung**: Der Kontrast zwischen Text- und Hintergrundfarben entspricht nicht den Anforderungen der WCAG 2.0 Stufe AA (4.5:1).
   - **Beispielhafte Probleme**:
     - Kalender Widget: Kontrast von 3.51 bei Schriftgröße 13.5pt (z. B. für Text mit der Farbe #888888 auf Hintergrund #fefefe).
   - **Impact**: „Serious“ (schwerwiegend).

#### 2. **Alt-Attribute für Bilder fehlen**:
   - **Beschreibung**: Bilder haben kein `alt`-Attribut oder keine gültige Alternative (z. B. `aria-label` oder `role="presentation"`).
   - **Beispielhafte Probleme**:
     - Logo-Bild: `<img class="badd-logo">`.
     - Weitere Bilder: z. B. in der Klasse `.startseite__angebote__bilder`.
   - **Impact**: „Critical“ (kritisch).

#### 3. **Links ohne zugänglichen Text**:
   - **Beschreibung**: Links enthalten keinen sichtbaren Text oder keine Alternative (z. B. `aria-label`).
   - **Beispielhafte Probleme**:     
     - Header Slider, Teaser Boxen unter Highlights, Partner Logos, Social Media Logos, Links in der Navigation
   - **Impact**: „Serious“ (schwerwiegend).
   
#### 4. **Leere Überschriften**:
   - **Beschreibung**: Einige Überschriften sind leer, was die Zugänglichkeit für Screenreader beeinträchtigt.
   - **Beispielhafte Probleme**:
     - Beispiel: `<h1 class="startseite__slider__title"><span></span></h1>`.
   - **Impact**: „Minor“ (gering).

#### 5. **Fehlende Landmark-Regionen**:
   - **Beschreibung**: Inhalte befinden sich nicht in einer `main`- oder anderen Landmark-Region, was die Navigation für Nutzer von Hilfsmitteln erschwert.
   - **Beispielhafte Probleme**:
     - Elemente wie `.owl-stage-outer` oder `.startseite__quicklinks__link`.
   - **Impact**: „Moderate“ (mäßig).

---

### Empfehlungen:
1. **Farbkontrast verbessern**:
   - Kontraste gemäß den WCAG-Anforderungen anpassen (mind. 4.5:1 für normalen Text).
   - Tools wie Kontrastprüfer verwenden.

2. **Alt-Attribute für Bilder hinzufügen**:
   - Jedem Bild sinnvolle Alternativtexte (`alt`) oder ARIA-Attribute zuweisen.
   - größtenteils redaktionelle Pflege der Alt-Tags in den Bildern evtl. auch vereinzelt Anpassungen am Code notwendig z.B. im Logo oder bei Icons

3. **Zugängliche Links**:
   - Sicherstellen, dass alle Links einen sichtbaren oder programmatisch zugänglichen Text haben.
   - Anpassungen am Code notwendig (umstrukturierung HTML bzw. einfügen von ARIA-Attributen da wo nicht möglich)

4. **Leere Überschriften entfernen**:
   - Inhalte in Überschriften einfügen oder unnötige leere Elemente entfernen.
   - Anpassungen am Code notwendig 

5. **Landmark-Regionen definieren**:
   - `main`-Landmark oder andere Regionen hinzufügen, um die Seitenstruktur für assistive Technologien zu optimieren.

