# AI Update vom 22. Mai 2026

## tl;dr

Enterprise-KI verschiebt sich weiter von Chatbots zu agentischen Plattformen, Betriebsautomatisierung und Governance. Besonders relevant sind neue Ansätze für verlässliche Agenten-Memory, strukturierte Entscheidungslogik und produktionsnahe SRE-Agenten. Alibaba positioniert Qwen3.7-Max als leistungsfähiges, aber proprietäres Agentenmodell mit langen autonomen Laufzeiten und günstigerer API-Ökonomie als westliche Frontier-Modelle. Kore.ai und Resolve AI adressieren typische Enterprise-Hürden: sichere Orchestrierung, Auditierbarkeit, deterministische Regeln und Integration in vorhandene Toolchains. Gleichzeitig zeigt die verschobene US-Executive-Order zur KI-Sicherheitsprüfung, dass regulatorische Vorabkontrollen für Frontier-Modelle politisch umkämpft bleiben. Für IT Business Relationship Manager werden Partnerauswahl, Datenresidenz, Agenten-Governance und Betriebsrisiken zu zentralen Bewertungskriterien.

## Alibaba's proprietary Qwen3.7-Max can run for 35 hours autonomously and supports external harnesses like Anthropic's Claude Code (Alibabas Qwen3.7-Max läuft 35 Stunden autonom und unterstützt Agenten-Frameworks)

- Autor: Carl Franzen
- Quelle: [VentureBeat](https://venturebeat.com/technology/alibabas-proprietary-qwen3-7-max-can-run-for-35-hours-autonomously-and-supports-external-harnesses-like-anthropics-claude-code)
- Datum der Veröffentlichung: 21. Mai 2026, 16:53 PT

Alibaba hat Qwen3.7-Max als proprietäres API-Modell vorgestellt, das laut Bericht rund 35 Stunden autonome Agentenarbeit leisten kann. Für Unternehmen ist vor allem relevant, dass das Modell mit einem 1-Million-Token-Kontextfenster, 64K Output-Limit und Kompatibilität zu bestehenden Agenten-Harnesses wie Claude Code positioniert wird. Die Leistungsdaten deuten auf starke Fähigkeiten bei langlaufenden Engineering- und Reasoning-Aufgaben hin, zugleich entsteht durch API-only-Verfügbarkeit ein klarer Zielkonflikt: Kosten- und Performancevorteile stehen Fragen zu Datenresidenz, regulatorischer Compliance und Abhängigkeit von Alibaba Cloud gegenüber.

## A 0.12% parameter add-on gives AI agents the working memory RAG can't (Ein 0,12-Prozent-Adapter ergänzt Agenten um Arbeitsgedächtnis jenseits von RAG)

- Autor: Ben Dickson
- Quelle: [VentureBeat](https://venturebeat.com/orchestration/a-0-12-parameter-add-on-gives-ai-agents-the-working-memory-rag-cant)
- Datum der Veröffentlichung: 21. Mai 2026, 12:00 PT

Der Artikel beschreibt delta-mem, ein leichtgewichtiges Memory-Verfahren, das historische Interaktionen in einer dynamisch aktualisierten Matrix speichert, ohne das Basismodell zu verändern. Im Enterprise-Kontext ist der Ansatz interessant, weil er die Grenzen klassischer RAG-Architekturen adressiert: RAG bleibt stark für zitierfähige Fakten und Dokumente, ist aber teuer und fragil, wenn Agenten über lange Workflows hinweg Arbeitszustände behalten sollen. Für produktive Agentenarchitekturen zeichnet sich damit ein hybrides Zielbild ab: interne Arbeitsgedächtnisse für Task-State und Benutzerpräferenzen, externe Retrieval-Systeme für auditierbares Faktenwissen.

## Enterprise AI agents keep failing because they forget what they learned (Enterprise-Agenten scheitern, weil sie Gelerntes vergessen)

- Autor: Taryn Plumb
- Quelle: [VentureBeat](https://venturebeat.com/orchestration/enterprise-ai-agents-keep-failing-because-they-forget-what-they-learned)
- Datum der Veröffentlichung: 21. Mai 2026, 11:43 PT

VentureBeat analysiert Entscheidungs-Kontextgraphen als Ansatz, um Agenten verlässlicher und nachvollziehbarer zu machen. Der Kern: Agenten brauchen nicht nur relevante Dokumente, sondern strukturierte Informationen darüber, welche Regel wann gilt, welche Ausnahme Vorrang hat und welche Entscheidungspfade bereits validiert wurden. Für regulierte Prozesse wie Banking, Support oder Supply Chain Management ist diese Unterscheidung wichtig, weil eine hohe Trefferquote allein nicht genügt. BRMs sollten solche Architekturen als Governance-Baustein betrachten, nicht nur als technische Erweiterung von RAG.

## Resolve AI says the AI coding boom is breaking production systems. It wants to fix that. (Resolve AI will Produktionsprobleme durch KI-generierten Code entschärfen)

- Autor: Michael Nuñez
- Quelle: [VentureBeat](https://venturebeat.com/technology/resolve-ai-says-the-ai-coding-boom-is-breaking-production-systems-it-wants-to-fix-that)
- Datum der Veröffentlichung: 21. Mai 2026, 06:00 PT

Resolve AI erweitert seine Plattform um Multi-Agenten-Incident-Analyse, Hintergrundagenten und eine gemeinsame Untersuchungsoberfläche für Menschen und KI-Agenten. Das Unternehmen adressiert ein reales Enterprise-Problem: KI beschleunigt Softwareentwicklung, aber Betrieb, Debugging, Monitoring und Incident Response bleiben Engpässe. Besonders relevant sind die beschriebenen Kontrollmechanismen gegen halluzinierte Root Causes, etwa gegenseitige Agentenprüfung, evidenzbasierte Kausalpfade und explizite Unsicherheitskommunikation. Für IT-Organisationen ist das ein Hinweis, AIOps nicht isoliert als Monitoring-Feature zu bewerten, sondern als Teil des gesamten Software-Lifecycle-Managements.

## Kore.ai launches Artemis AI agent platform, takes on Salesforce and ServiceNow (Kore.ai startet Artemis-Plattform für Enterprise-Agenten)

- Autor: Michael Nuñez
- Quelle: [VentureBeat](https://venturebeat.com/technology/kore-ai-launches-artemis-ai-agent-platform-expands-challenge-to-microsoft-and-salesforce)
- Datum der Veröffentlichung: 21. Mai 2026, 06:00 PT

Kore.ai hat die Artemis-Version seiner Agent Platform vorgestellt, mit der Unternehmen Agenten über eine YAML-basierte Agent Blueprint Language definieren, versionieren und betreiben können. Die Plattform kombiniert LLM-basiertes Reasoning mit deterministischer Regelverarbeitung in einer sogenannten Dual-Brain-Architektur. Das ist für regulierte Branchen relevant, weil Guardrails und Geschäftsregeln nicht allein dem Sprachmodell überlassen werden. Strategisch positioniert sich Kore.ai als neutralere Alternative zu Microsoft, Salesforce, Google und ServiceNow, obwohl die Plattform zunächst eng mit Azure, Microsoft Foundry, Agent 365, Entra ID und Microsoft Graph integriert ist.

## Hark raises $700M Series A for its secretive ‘universal’ AI interface (Hark sammelt 700 Millionen US-Dollar für universelle KI-Schnittstelle ein)

- Autor: Tim Fernholz
- Quelle: [TechCrunch](https://techcrunch.com/2026/05/21/hark-raises-700m-series-a-for-its-secretive-universal-ai-interface/)
- Datum der Veröffentlichung: 21. Mai 2026, 07:00 PDT

Hark hat eine Series-A-Finanzierung über 700 Millionen US-Dollar bei einer Bewertung von 6 Milliarden US-Dollar angekündigt. Das Unternehmen entwickelt ein agentisches KI-System als universelle Schnittstelle zur digitalen Welt, bleibt aber inhaltlich noch weitgehend vage. Für Enterprise-Beobachter ist weniger das konkrete Produkt relevant als das Marktsignal: Investoren finanzieren weiter sehr große Wetten auf KI-Agenten, multimodale Modelle, Hardware und eigene Compute-Infrastruktur, obwohl belastbare Produkt-Markt-Nachweise noch ausstehen.

## Trump delays AI security executive order, saying language ‘could have been a blocker’ (Trump verschiebt Executive Order zur KI-Sicherheitsprüfung)

- Autor: Rebecca Bellan
- Quelle: [TechCrunch](https://techcrunch.com/2026/05/21/trump-delays-ai-security-executive-order-i-dont-want-to-get-in-the-way-of-that-leading/)
- Datum der Veröffentlichung: 21. Mai 2026, 10:30 PDT

Die US-Regierung hat die Unterzeichnung einer Executive Order verschoben, die Sicherheitsbewertungen fortgeschrittener KI-Modelle vor deren Veröffentlichung vorgesehen hätte. Laut TechCrunch ging es unter anderem um die Frage, ob KI-Unternehmen Modelle 14 bis 90 Tage vor Launch mit der Regierung teilen müssten. Für Unternehmen mit US-Bezug bleibt damit unklar, ob sich ein stärkeres Vorabprüfregime für Frontier-Modelle durchsetzt. BRMs sollten diese Entwicklung im Kontext von Modellrisikomanagement, Lieferantenbewertung und möglichen Compliance-Anforderungen beobachten.