# AI Update vom 3. Juni 2026

## tl;dr
Microsoft adressiert mit neuen Open-Source-Werkzeugen zwei zentrale Enterprise-Probleme bei KI-Agenten: verlässliche Verhaltenskontrolle und anwendungsspezifische Regressionstests. OpenAI erweitert Codex deutlich in Richtung Wissensarbeit und positioniert agentische Werkzeuge damit jenseits der Softwareentwicklung. Anthropic skaliert Claude Mythos für kritische Infrastrukturen, was den Wettbewerb um KI-gestützte Cybersecurity weiter verschärft. Google bringt eine Android-Funktion gegen KI-gestützte Deepfake-Anrufe, während Amazon wegen Ring-Gesichtserkennung mit einer Sammelklage konfrontiert ist. In den USA wird KI-Aufsicht regulatorisch konkreter, aber weiterhin industriekompatibel ausgestaltet. Insgesamt verschiebt sich der Enterprise-Fokus von Modellleistung hin zu Governance, Compliance, Sicherheitsarchitektur und kontrollierter Integration in Geschäftsprozesse.

### New Microsoft tool lets devs spin up AI behavior tests using text descriptions (Microsoft-Werkzeug erzeugt KI-Verhaltenstests aus Textbeschreibungen)

Autor: Ram Iyer  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/new-microsoft-tool-lets-devs-spin-up-ai-behavior-tests-using-text-descriptions/)  
Veröffentlichungsdatum: 2. Juni 2026, 12:02 PM PDT

Microsoft stellt mit ASSERT ein Open-Source-Framework für KI-Evaluationen vor, das aus natürlichsprachlichen Ziel-, Policy- und Verhaltensbeschreibungen strukturierte Tests generiert. Für Enterprise-Teams ist das relevant, weil klassische Benchmarks kaum prüfen, ob ein KI-System die konkreten Regeln eines Unternehmens einhält, etwa Vertraulichkeit, Rollenfreigaben oder erlaubte Tool-Nutzung. Besonders wichtig ist der Ansatz für BRM-nahe Use Cases, bei denen Fachbereiche KI-Agenten in Workflows bringen wollen, ohne jedes Risiko manuell in Code übersetzen zu müssen. ASSERT kann zudem Zwischenschritte und Tool Calls protokollieren, was die Nachvollziehbarkeit von Fehlern und Abweichungen verbessert.

### Microsoft offers devs a better way to control AI agent behavior (Microsoft bietet Entwicklern eine bessere Kontrolle über KI-Agenten)

Autor: Ram Iyer  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/microsoft-offers-devs-a-better-way-to-control-ai-agent-behavior/)  
Veröffentlichungsdatum: 2. Juni 2026, 11:00 AM PDT

Microsofts neue Agent Control Specification soll Policies für KI-Agenten standardisieren und über verschiedene Frameworks hinweg portierbar machen. Regeln können festlegen, was ein Agent tun darf, wann menschliche Freigabe nötig ist, welche Evidenz geloggt wird und wann Inhalte blockiert oder redigiert werden. Der Ansatz ist für Unternehmen strategisch wichtig, weil Agenten-Governance bisher häufig aus verstreuten System Prompts, Speziallogik und nachgelagerten Filtern besteht. Unterstützt werden unter anderem LangChain, OpenAI Agents SDK, Anthropic Agents SDK, AutoGen, CrewAI, Semantic Kernel und MCP-Tools.

### OpenAI launches new Codex tools for white-collar work (OpenAI erweitert Codex für Wissensarbeit)

Autor: Russell Brandom  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/openai-launches-new-codex-tools-for-white-collar-work/)  
Veröffentlichungsdatum: 2. Juni 2026, 9:00 AM PDT

OpenAI erweitert Codex mit Plug-ins für Datenanalyse, Creative Production, Sales, Produktdesign, Equity Investing und Investment Banking. Laut Bericht wächst die Nutzung durch Wissensarbeiter schneller als die klassische Entwicklernutzung; rund 20 Prozent der Codex-Nutzer sollen bereits aus diesem Segment kommen. Für Enterprise-Organisationen deutet das auf eine Verschiebung hin: Agentische Werkzeuge werden nicht mehr nur als Developer Productivity Tools positioniert, sondern als Arbeitsplatzplattform für funktionsspezifische Aufgaben. Neue Features wie gehostete interaktive Websites und dokumentbezogene Annotationen erhöhen zugleich die Anforderungen an Berechtigungen, Datenklassifikation und Output-Governance.

### Anthropic scales Claude Mythos to critical infrastructure in 15+ countries (Anthropic skaliert Claude Mythos für kritische Infrastrukturen)

Autor: Rebecca Bellan  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/anthropic-scales-claude-mythos-to-critical-infrastructure-in-15-countries/)  
Veröffentlichungsdatum: 2. Juni 2026, 7:44 AM PDT

Anthropic erweitert Project Glasswing auf rund 150 Organisationen in mehr als 15 Ländern. Claude Mythos soll dort Codebasen in Bereichen wie Energie, Wasser, Gesundheitswesen, Kommunikation und Hardware auf Schwachstellen prüfen. Für IT-Verantwortliche ist die Meldung relevant, weil KI-gestützte Schwachstellensuche zunehmend als Bestandteil kritischer Infrastrukturprogramme betrachtet wird. Gleichzeitig entsteht ein Governance-Dilemma: Je leistungsfähiger solche Modelle in der Zero-Day-Erkennung werden, desto wichtiger werden Zugriffskontrolle, Prüfprotokolle, nationale Sicherheitsabstimmung und Missbrauchsprävention.

### Google rolls out fake call detection to protect against AI deepfake impersonation scams (Google führt Schutz vor KI-Deepfake-Anrufen ein)

Autor: Aisha Malik  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/google-rolls-out-fake-call-detection-to-protect-against-ai-deepfake-impersonation-scams/)  
Veröffentlichungsdatum: 2. Juni 2026, 11:00 AM PDT

Google führt für Android eine Erkennung gefälschter Anrufe ein, die insbesondere KI-gestützte Stimmenimitationen und Spoofing vertrauenswürdiger Kontakte adressieren soll. Die Funktion startet global in Phone by Google für Android-12+-Geräte, zunächst auf Pixel-Geräten, und nutzt eine stille Verifikation zwischen Geräten. Für Unternehmen ist dies ein Hinweis darauf, dass Voice Fraud und Deepfake Social Engineering operativ relevanter werden. IT-, Security- und Fachbereichsteams sollten telefonbasierte Freigabeprozesse, Zahlungsfreigaben und Helpdesk-Identitätsprüfungen entsprechend überprüfen.

### Amazon faces class action lawsuit over Ring facial-recognition feature (Amazon sieht Sammelklage wegen Ring-Gesichtserkennung)

Autor: Amanda Silberling  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/amazon-faces-class-action-lawsuit-over-ring-facial-recognition-feature/)  
Veröffentlichungsdatum: 2. Juni 2026, 10:47 AM PDT

Amazon wird wegen der Ring-Funktion Familiar Faces verklagt. Die Klage behauptet, dass Gesichtsdaten von Passanten ohne deren Zustimmung erfasst und gespeichert würden. Für Enterprise-Entscheider ist der Fall ein weiteres Beispiel dafür, dass KI-Funktionen mit biometrischen Daten nicht nur technische, sondern erhebliche Datenschutz-, Consent- und Reputationsrisiken erzeugen. Besonders relevant ist die Abgrenzung zwischen Opt-in der Gerätebesitzer und fehlender Einwilligung Dritter, die von der Erfassung betroffen sind.

### Trump signs narrower executive order on AI oversight after industry objections (Trump unterzeichnet abgeschwächte Executive Order zur KI-Aufsicht)

Autor: Rebecca Bellan  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/trump-signs-narrower-executive-order-on-ai-oversight-after-industry-objections/)  
Veröffentlichungsdatum: 2. Juni 2026, 9:23 AM PDT

Die neue Executive Order sieht freiwillige Prüfungen leistungsfähiger KI-Modelle durch die US-Regierung vor, bevor sie veröffentlicht werden. Gegenüber früheren Entwürfen wurde die Vorlaufzeit nach Einwänden aus der Industrie von bis zu 90 Tagen auf 30 Tage reduziert. Für global tätige Unternehmen ist daran weniger die unmittelbare Pflicht als die Richtung wichtig: Frontier-Modelle rücken stärker in regulatorische Vorabprüfung, Sicherheitsbewertung und nationale Wettbewerbslogik. Zugleich bleibt die US-Regierung bemüht, die Maßnahme nicht als Lizenz- oder Genehmigungssystem erscheinen zu lassen.

### ZeroDrift raises $10M to protect AI models from themselves (ZeroDrift sammelt 10 Millionen US-Dollar für KI-Compliance-Schicht ein)

Autor: Russell Brandom  
Quelle: [TechCrunch](https://techcrunch.com/2026/06/02/zerodrift-raises-10-million-to-protect-ai-models-from-themselves/)  
Veröffentlichungsdatum: 2. Juni 2026, 5:32 AM PDT

ZeroDrift positioniert sich als Compliance-Schicht zwischen KI-Modellen und Endnutzern und hat dafür 10 Millionen US-Dollar Seed-Finanzierung erhalten. Das System soll problematische Antworten deterministisch anhand bekannter Standards wie SOC 2 oder GDPR erkennen und anschließend mit LLM-Unterstützung regelkonforme Alternativen erzeugen. Für Enterprise-Architekturen ist der Ansatz interessant, weil er KI-Sicherheit nicht allein an das Basismodell delegiert, sondern eine kontrollierende Zwischenschicht einzieht. Das passt zu einem breiteren Trend: Governance wird als eigenständige technische Komponente in KI-Stacks implementiert, nicht nur als organisatorische Richtlinie.