## Kostenlose WCAG 2.1 (Level AA) Tools

Liste kostenloser Tools, um eine Website auf die Einhaltung der **WCAG 2.1 (Level AA)** zu testen:

---

### **1. WAVE (Web Accessibility Evaluation Tool)**  
- **Beschreibung:** Ein browserbasiertes Tool, das Barrierefreiheitsprobleme visuell direkt auf der Website hervorhebt.  
- **URL:** [wave.webaim.org](https://wave.webaim.org)  
- **Besonderheiten:**  
  - Integration als Browser-Extension für Chrome und Firefox.  
  - Identifiziert WCAG-Probleme und gibt Lösungsvorschläge.

---

### **2. Axe DevTools**  
- **Beschreibung:** Ein leistungsstarkes Tool von Deque Systems, das sich in Entwickler-Tools von Browsern integrieren lässt.  
- **URL:** [deque.com/axe](https://www.deque.com/axe/)  
- **Besonderheiten:**  
  - Browser-Erweiterungen für Chrome und Edge.  
  - Liefert detaillierte Berichte zu WCAG-Verstößen.  
  - Fokus auf Entwicklerfreundlichkeit.

---

### **3. Lighthouse (Google)**  
- **Beschreibung:** Ein Open-Source-Tool von Google, das direkt im Chrome-Browser integriert ist.  
- **URL:** [Lighthouse-Dokumentation](https://developer.chrome.com/docs/lighthouse/)  
- **Besonderheiten:**  
  - Prüft Barrierefreiheit sowie Leistung, SEO und Best Practices.  
  - WCAG-Check ist Teil des Berichts zur Barrierefreiheit.  
  - Kann automatisiert in CI/CD integriert werden.

---

### **4. Accessibility Insights**  
- **Beschreibung:** Ein Tool von Microsoft, das manuelle und automatisierte Barrierefreiheitstests kombiniert.  
- **URL:** [accessibilityinsights.io](https://accessibilityinsights.io)  
- **Besonderheiten:**  
  - Unterstützt Web und Desktop-Anwendungen.  
  - Integration mit WCAG-Leitlinien.  
  - Live-Tracking von WCAG-Konformität.

---

### **5. Tenon**  
- **Beschreibung:** Ein cloudbasiertes Tool zur Überprüfung von Barrierefreiheit mit einem Fokus auf WCAG-Konformität.  
- **URL:** [tenon.io](https://tenon.io)  
- **Besonderheiten:**  
  - Erfordert Registrierung für die kostenlose Version.  
  - API-Unterstützung für automatisierte Tests.  

---

### **6. Pa11y**  
- **Beschreibung:** Ein Open-Source-Tool für automatisierte Tests auf Barrierefreiheit.  
- **URL:** [pa11y.org](https://pa11y.org)  
- **Besonderheiten:**  
  - CLI-basiert und einfach in CI/CD-Pipelines integrierbar.  
  - Vollständig anpassbar.  

---

### **7. Siteimprove Accessibility Checker**  
- **Beschreibung:** Ein kostenloses Browser-Plugin zur Überprüfung von Barrierefreiheit basierend auf den WCAG.  
- **URL:** [Siteimprove Accessibility Checker](https://siteimprove.com/en/accessibility/free-tools/)  
- **Besonderheiten:**  
  - Hervorhebung von Problemen direkt auf der Seite.  
  - Fokussiert auf einfache Bedienung für Nicht-Entwickler.

---

### **8. tota11y**  
- **Beschreibung:** Ein interaktives Tool, das Barrierefreiheitsprobleme visuell aufzeigt.  
- **URL:** [tota11y-Dokumentation](https://khan.github.io/tota11y/)  
- **Besonderheiten:**  
  - Einfaches JavaScript-Plugin, das in die Seite eingebettet wird.  
  - Hervorragend für schnelle, visuelle Tests.

---

### **9. Color Contrast Analyzer (CCA)**  
- **Beschreibung:** Ein Tool zur Überprüfung von Farbkontrasten gemäß den WCAG-Vorgaben.  
- **URL:** [TPGi Color Contrast Analyzer](https://www.tpgi.com/color-contrast-checker/)  
- **Besonderheiten:**  
  - Desktop-App für Windows und macOS.  
  - Kontrastanalyse mit Echtzeit-Vorschau.

---

### **10. ARC Toolkit**  
- **Beschreibung:** Ein Browser-Plugin für Chrome, das Tests basierend auf WCAG und Section 508 durchführt.  
- **URL:** [ARC Toolkit](https://www.levelaccess.com/arc-toolkit/)  
- **Besonderheiten:**  
  - Genaue und detaillierte Analyse von Barrierefreiheitsproblemen.  
  - Entwickelt für Entwickler und Tester.

---

Wenn du besonders umfassende Tests durchführen möchtest, bietet es sich an, mehrere dieser Tools zu kombinieren, da jedes unterschiedliche Aspekte der WCAG überprüft.

## Empfehlungen für den Anfang

Wenn du gerade erst anfängst, eine Website auf Barrierefreiheit zu testen, würde ich mit **WAVE** und **Axe DevTools** starten, da sie einfach zu bedienen sind, gute Ergebnisse liefern und sich ideal für erste Analysen eignen. Hier ist, warum ich diese beiden Tools empfehlen würde:

---

### **1. WAVE (Web Accessibility Evaluation Tool)**  
- **Warum?**
  - Es ist extrem anfängerfreundlich und bietet eine visuelle Darstellung der Probleme direkt auf der Website.
  - Du bekommst sofort hilfreiche Hinweise zu Fehlern und Verbesserungsvorschlägen.
  - Kein technisches Wissen erforderlich – ideal, um ein erstes Verständnis für Barrierefreiheitsprobleme zu entwickeln.
- **Wann verwenden?**
  - Für eine **erste Überprüfung der gesamten Seite**, um offensichtliche Probleme (wie fehlende Alt-Texte oder Farbkontraste) zu identifizieren.

---

### **2. Axe DevTools**  
- **Warum?**
  - Es ist genauer und entwickelt sich ideal für **automatisierte Tests** im Browser-Inspektor (Chrome/Edge/Firefox).
  - Es bietet klare Hinweise, wie jedes Problem behoben werden kann, und priorisiert die Fehler.
  - Perfekt für Entwickler, da es tief in den Quellcode blicken lässt.
- **Wann verwenden?**
  - Um **detailliertere technische Tests** durchzuführen, vor allem auf WCAG-Level AA bezogen.

---

### **Wie würde ich testen?**
1. **WAVE nutzen:**
   - Lade die Website in WAVE (entweder im Browser oder über die [WAVE-Website](https://wave.webaim.org)).
   - Analysiere die visuellen Markierungen und erkenne Probleme wie:
     - Fehlende Alternativtexte für Bilder.
     - Falsche oder fehlende Überschriftenstruktur.
     - Kontrastprobleme.
   
2. **Axe DevTools nutzen:**
   - Installiere die Axe-Browsererweiterung.
   - Öffne die Entwicklerwerkzeuge (F12) und starte Axe, um automatisierte Tests durchzuführen.
   - Fokussiere auf technische Details und WCAG-Level AA-Konformität.
   - Arbeite die Fehlerliste durch, angefangen bei schwerwiegenden Problemen.

---

### **Alternative für schnelle Tests:**  
- **Lighthouse:** Wenn du bereits Chrome nutzt, kannst du einfach über die Entwickler-Tools einen schnellen Accessibility-Check machen. Es bietet eine solide Übersicht über Probleme und ist sofort verfügbar.

---

Das Ziel sollte sein, mit einfachen Tools wie WAVE einen Überblick zu erhalten und anschließend mit detaillierteren Tools wie Axe oder Lighthouse ins Detail zu gehen. Kombiniere Tools, um ein vollständigeres Bild zu bekommen! 😊