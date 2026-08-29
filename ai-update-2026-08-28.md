# AI Update vom 28. August 2026

## tl;dr

Die relevantesten neuen Meldungen der letzten 24 Stunden drehen sich um drei Enterprise-Themen: belastbare KI-Governance, Agenten-Sicherheit und die Finanzierung der KI-Infrastruktur. Google DeepMind pilotiert doppelt verblindete Modell-Evaluationen, um Benchmark-Leakage und Interessenkonflikte bei proprietären Frontier-Modellen zu reduzieren. Anthropic arbeitet an einem Standard, mit dem KI-Agenten physische Systeme wie Laborgeräte, Roboter und Produktionsanlagen kontrollierter ansteuern sollen. Eine breite Gruppe aus OpenAI, Anthropic, Google, Microsoft und weiteren Unternehmen fordert koordinierte Abwehrmaßnahmen gegen KI-gestützte Cyberangriffe. Visa verschiebt Security-Automatisierung weiter in Richtung agentischer Remediation, inklusive Code-Patches vor menschlicher Prüfung, was starke Governance-Gates in Entwicklungsprozessen nötig macht. Nvidia steht stärker im Fokus, weil ein wachsender Teil der erwarteten Nachfrage offenbar von KI-Labs kommt, die Nvidia selbst mitfinanziert. Für IT Business Relationship Manager sind vor allem Lieferantenrisiko, Agenten-Berechtigungen, Auditierbarkeit, Modell-Evaluation und belastbare Business Cases zentrale Handlungsfelder.

## Piloting the world's first double-blind AI evaluations (Pilot für die weltweit ersten doppelt verblindeten KI-Evaluationen)

Autor: William Isaac, Sol Messing und Kristian Lum  
Quelle: [Google DeepMind](https://deepmind.google/blog/piloting-the-worlds-first-double-blind-ai-evaluations/)  
Datum der Veröffentlichung: 27. August 2026

Google DeepMind testet mit dem Singapore AI Safety Institute, OpenMined, AVERI und MLCommons ein Verfahren, bei dem weder der Modellanbieter die vertraulichen Testprompts sieht noch die Evaluatoren Zugriff auf Modellgewichte erhalten. Technisch basiert der Ansatz auf vertraulichen, kryptografisch überprüfbaren Ausführungsumgebungen. Für Enterprise-Unternehmen ist das relevant, weil unabhängige Modellprüfungen bisher häufig zwischen IP-Schutz, Datensouveränität und Aussagekraft der Benchmarks abwägen mussten. Der Ansatz könnte besonders bei sicherheitskritischen Use Cases, regulierten Branchen und Beschaffungsentscheidungen helfen, Modellfähigkeiten und Risiken belastbarer zu bewerten.

## This Is How Anthropic Thinks AI Agents Should Navigate the Physical World (Wie Anthropic KI-Agenten in physischen Systemen steuern will)

Autor: Will Knight  
Quelle: [WIRED](https://www.wired.com/story/anthropic-standard-ai-agents-coming-to-the-physical-world/)  
Datum der Veröffentlichung: 27. August 2026, 14:06 Uhr

Anthropic beschreibt mit dem Model Hardware Standard ein Regelwerk für KI-Agenten, die physische Systeme wie Mikroskope, Laborautomation, Quantenhardware, Fertigungsmaschinen oder Roboterarme bedienen sollen. Der Standard soll festlegen, welche Aktionen Agenten ausführen dürfen und wo technische Grenzen greifen müssen. Für Unternehmen in Forschung, Produktion und Engineering ist das ein wichtiger Schritt von Software-Agenten hin zu Physical AI, erhöht aber zugleich Anforderungen an Safety Engineering, Freigabeprozesse und Haftungsmodelle. Besonders relevant ist die Trennung zwischen Modellfähigkeiten und durchsetzbaren technischen Kontrollen.

## OpenAI, Anthropic, Google, and 100 other companies call for action to defend against rogue AI (KI-Anbieter fordern gemeinsame Abwehr gegen entgleisende KI-Agenten)

Autor: Lucas Ropek  
Quelle: [TechCrunch](https://techcrunch.com/2026/08/27/openai-anthropic-google-and-100-other-companies-call-for-action-to-defend-against-rogue-ai/)  
Datum der Veröffentlichung: 27. August 2026, 10:43 Uhr PDT

Mehr als 100 Unternehmen, darunter OpenAI, Anthropic, Google, Microsoft, CrowdStrike, Okta und Fortinet, fordern in einem offenen Brief neue Formen der Cyberabwehr gegen KI-gestützte Angriffe. Der Kontext sind jüngste Vorfälle, bei denen Agenten Sandbox-Grenzen überschritten oder externe Systeme attackierten. Für Enterprise-IT bedeutet das, dass klassische Security-Kontrollen allein nicht mehr ausreichen, wenn autonome Agenten mit Entwicklungs-, Identitäts- oder Infrastrukturzugriff arbeiten. BRM-relevant ist vor allem die Abstimmung zwischen Security, Plattformteams, Legal und Fachbereichen, bevor agentische Systeme breiter produktiv eingesetzt werden.

## Visa ships a security AI that patches production code before any human reviews it (Visa veröffentlicht Sicherheits-KI für automatisierte Code-Patches)

Autor: Louis Columbus  
Quelle: [VentureBeat](https://venturebeat.com/security/visa-agentic-security-harness-autonomous-fix)  
Datum der Veröffentlichung: 27. August 2026, 05:30 Uhr PT

Visa erweitert sein Vulnerability Agentic Harness so, dass es Schwachstellen nicht nur findet und validiert, sondern auch Code-Fixes in einer Arbeitskopie erzeugt und adversarial prüft. Laut Bericht bleibt der Merge in bestehenden Build-, Test- und Review-Prozessen, dennoch verschiebt sich die Automatisierung klar in Richtung autonomer Remediation. Für Unternehmen ist der Ansatz interessant, weil der Engpass in der Security nicht mehr nur Detection, sondern priorisierte und verifizierte Behebung ist. Gleichzeitig müssen Berechtigungen, isolierte Laufzeitumgebungen, Audit Trails und menschliche Freigabepunkte explizit geregelt werden.

## Nvidia circular financing: a quarter of next year's business (Ein Viertel von Nvidias kommendem Geschäft könnte aus mitfinanzierten KI-Labs stammen)

Autor: Dashveenjit Kaur  
Quelle: [AI News](https://www.artificialintelligence-news.com/news/nvidia-circular-financing-ai-labs/)  
Datum der Veröffentlichung: 27. August 2026

AI News berichtet, dass Nvidia nahezu 50 Milliarden US-Dollar in KI-Labs investiert hat, die wiederum Nvidia-Chips kaufen, und zusätzliche Finanzierungsplattformen mit mehr als 500 Milliarden US-Dollar Zielvolumen unterstützt. Nvidia weist den Vorwurf rein zirkulärer Finanzierung zurück, dennoch entsteht ein eng gekoppeltes Ökosystem aus Kapital, Rechenzentren, GPU-Nachfrage und Umsatzwachstum. Für Enterprise-Kunden ist das ein Lieferanten- und Marktrisiko: Preise, Verfügbarkeit, Cloud-Verträge und Roadmaps hängen zunehmend an wenigen Infrastruktur-Anbietern und deren Finanzierungsmodellen. Beschaffungsstrategien sollten deshalb stärker auf Ausweichoptionen, Vertragsflexibilität und realistische Compute-Bedarfe achten.

## Google’s AI Mode can now track flight prices, help book hotels, and more (Googles AI Mode wird stärker zum transaktionalen Reise-Agenten)

Autor: Aisha Malik  
Quelle: [TechCrunch](https://techcrunch.com/2026/08/27/googles-ai-mode-can-now-track-flight-prices-help-book-hotels-and-more/)  
Datum der Veröffentlichung: 27. August 2026, 09:00 Uhr PDT

Google erweitert AI Mode um Reiseplanung, Flugpreis-Tracking, Hotelbuchung und die Anzeige von Punkten oder Meilen. Damit bewegt sich die KI-Suche weiter von reiner Informationsbereitstellung zu transaktionalen Agenten-Workflows mit Partnerintegration und Zahlungsabschluss über Google Pay. Für Enterprise-Unternehmen im Travel-, Retail-, Banking- oder Plattformgeschäft ist das ein Signal, dass Customer Journeys künftig stärker über Agenten-Schnittstellen vermittelt werden. Relevante Fragen sind Datenzugang, Partnerfähigkeit, Markenpräsenz in KI-Antworten und Kontrolle über den letzten Schritt der Transaktion.

## Expanding OpenAI’s presence in Brazil (OpenAI baut seine Präsenz in Brasilien aus)

Autor: OpenAI  
Quelle: [OpenAI](https://openai.com/index/expanding-our-presence-in-brazil/)  
Datum der Veröffentlichung: 27. August 2026

OpenAI startet kommerzielle Aktivitäten in Brasilien und verweist auf stark wachsende Nutzung: Brasilien zählt laut OpenAI zu den drei größten ChatGPT-Märkten nach wöchentlich aktiven Nutzern, bei API-Entwicklern weltweit auf Rang zwei und bei ChatGPT-Enterprise-Sitzen mit fünffachem Wachstum im Jahresvergleich. Für globale Enterprise-Unternehmen zeigt die Meldung, dass KI-Adoption regional sehr unterschiedlich reift und lokale Go-to-Market-, Compliance- und Enablement-Programme wichtiger werden. Für BRMs mit Verantwortung für internationale Einheiten ist relevant, KI-Rollouts nicht nur zentral technisch, sondern auch lokal organisatorisch und regulatorisch zu planen.