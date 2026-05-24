# AI Update vom 23. Mai 2026

## tl;dr

Enterprise-KI verschiebt sich weiter von Modellvergleichen hin zu Datenarchitektur, Agenten-Governance und belastbarer Wirtschaftlichkeit. Besonders relevant ist Dun & Bradstreets Umbau seiner kommerziellen Datenbasis für agentische Workflows: Agenten benötigen verifizierte Entitäten, geringe Latenz und nachvollziehbare Datenherkunft. VentureBeat berichtet zudem über Direct Corpus Interaction als Ergänzung zu RAG, bei der Agenten direkt mit Dateien, Logs und Code arbeiten, statt ausschließlich über Vektorindizes. Gleichzeitig zeigen neue Supply-Chain-Angriffe auf npm, dass Signaturen und Provenance-Nachweise allein keine ausreichende Vertrauenskette für KI-gestützte Entwicklungsumgebungen bilden. TechCrunch beleuchtet, wie überhöhte ARR-Angaben bei KI-Startups Enterprise-Kunden, Investoren und Beschaffungsteams in die Irre führen können. AI Business sieht die nächste Phase der KI-Adoption vor allem durch ROI, Infrastrukturkosten und Prozessneudesign geprägt. Für IT Business Relationship Manager ergibt sich daraus ein klares Bild: KI-Initiativen sollten nicht nur nach Modellfähigkeit, sondern nach Datenreife, Governance, Sicherheitsarchitektur und messbarem Geschäftsnutzen bewertet werden.

## D&B's database of 642 million businesses was built for humans, not AI agents. So they rebuilt it. (D&B baute seine Datenbank für KI-Agenten um)

Autor: Sean Michael Kerner  
Quelle: [VentureBeat](https://venturebeat.com/data/d-and-bs-database-of-642-million-businesses-was-built-for-humans-not-ai-agents-so-they-rebuilt-it)  
Datum der Veröffentlichung: 22. Mai 2026, 6:00 Uhr PT

Dun & Bradstreet hat seine Commercial-Graph-Datenbasis mit 642 Millionen Unternehmensdatensätzen neu strukturiert, weil Systeme für menschliche Analysten nicht automatisch agententauglich sind. Agentische Workflows in Kreditprüfung, Beschaffung und Lieferkettenrisiko benötigen eindeutige Entity Resolution, maschinenlesbare Beziehungen, geringe Latenz und eine belastbare Herkunftskette der Daten.

Für Enterprise-Organisationen ist der wichtigste Punkt nicht die Größe des Datenbestands, sondern dessen Operationalisierbarkeit für Agenten. BRMs sollten bei KI-Roadmaps prüfen, ob Stammdaten, Compliance-Kontexte und Identitätsmodelle so aufgebaut sind, dass Agenten konsistent dieselbe Organisation, denselben Kunden oder denselben Lieferanten referenzieren. Ohne diese Grundlage steigt das Risiko falscher Empfehlungen in mehrstufigen Workflows.

## Your AI agents need a terminal, not just a vector database (KI-Agenten brauchen ein Terminal, nicht nur eine Vektordatenbank)

Autor: Ben Dickson  
Quelle: [VentureBeat](https://venturebeat.com/orchestration/your-ai-agents-need-a-terminal-not-just-a-vector-database)  
Datum der Veröffentlichung: 22. Mai 2026, 14:05 Uhr PT

Der Artikel beschreibt Direct Corpus Interaction als Ansatz, bei dem Agenten direkt mit Rohdatenbeständen über Such-, Datei- und Terminalwerkzeuge arbeiten. Das adressiert eine Schwäche klassischer RAG-Architekturen: Vektorindizes sind Momentaufnahmen und können relevante Details wie Versionsnummern, Logzeilen, Fehlercodes oder Dateipfade übersehen.

Für Unternehmen ist der Ansatz vor allem in Incident-Analyse, Code-Recherche, Audit-Trails und Compliance-Prüfungen interessant. Gleichzeitig entstehen neue Anforderungen an Sandboxen, Berechtigungen, Kontextmanagement und Tool-Governance. Eine sinnvolle Architektur dürfte daher hybrid sein: semantische Suche für breite Vorauswahl, direkte Corpus-Interaktion für Präzision und Nachweisbarkeit.

## Valid certificates, stolen accounts: how attackers broke npm's last trust signal (Gültige Zertifikate, gestohlene Konten: Wie Angreifer npm-Provenance aushebelten)

Autor: Louis Columbus  
Quelle: [VentureBeat](https://venturebeat.com/security/npm-sigstore-provenance-stolen-identity-audit-grid-2026)  
Datum der Veröffentlichung: 22. Mai 2026, 15:21 Uhr PT

VentureBeat berichtet, dass 633 bösartige npm-Paketversionen Provenance-Prüfungen bestanden, weil Angreifer über kompromittierte Maintainer-Konten gültige Signaturzertifikate erzeugen konnten. Das zeigt eine kritische Lücke in der Software-Lieferkette: Technische Signaturen bestätigen Herkunftsprozesse, aber nicht zwingend die legitime Autorisierung durch den richtigen Menschen oder die richtige Organisation.

Für Enterprise-IT ist das besonders relevant, weil KI-Coding-Agenten, IDE-Erweiterungen und automatisierte CI/CD-Prozesse Abhängigkeiten schneller integrieren können als klassische Review-Prozesse mithalten. BRMs sollten das Thema in Gesprächen mit Security, DevOps und Plattformteams adressieren: Provenance muss durch Identitätsschutz, Paket-Risikoanalysen, Secret-Scanning, eingeschränkte Agentenrechte und nachgelagerte Laufzeitkontrollen ergänzt werden.

## How VCs and founders use inflated ‘ARR’ to crown AI startups (Wie VCs und Gründer aufgeblähte ARR-Zahlen bei KI-Startups nutzen)

Autor: Marina Temkin  
Quelle: [TechCrunch](https://techcrunch.com/2026/05/22/how-vcs-and-founders-use-inflated-arr-to-kingmake-ai-startups/)  
Datum der Veröffentlichung: 22. Mai 2026, 13:40 Uhr PDT

TechCrunch beschreibt, wie einige KI-Startups annual recurring revenue, contracted ARR und annualized run-rate revenue vermischen oder missverständlich kommunizieren. Dadurch können Wachstumsnarrative entstehen, die stärker auf zugesagten, noch nicht realisierten oder extrapolierten Umsätzen beruhen als auf stabil zahlenden Kunden.

Für Enterprise-Beschaffung und Vendor Management ist das ein konkretes Risiko. Hohe öffentlich kommunizierte ARR-Werte sollten nicht automatisch als Signal für Produktreife, Implementierungsfähigkeit oder finanzielle Stabilität gelten. BRMs sollten bei KI-Anbietern stärker auf Referenzen, Implementierungsdauer, Renewal-Raten, Supportfähigkeit, Datenverarbeitung, Exit-Szenarien und reale Nutzung im Enterprise-Kontext achten.

## Prompt: AI’s Next Challenge Is Proving the Payoff (KI muss jetzt den Geschäftsnutzen beweisen)

Autor: Liz Hughes  
Quelle: [AI Business](https://aibusiness.com/generative-ai/prompt-ai-s-next-challenge-proving-the-payoff)  
Datum der Veröffentlichung: 22. Mai 2026

AI Business argumentiert, dass sich die Debatte von reiner Leistungsfähigkeit hin zu Kosten, ROI und operativer Skalierung verschiebt. Unternehmen investieren weiter massiv in Infrastruktur, Talente, Akquisitionen und agentische Systeme, müssen aber zunehmend nachweisen, dass daraus tragfähige Geschäftsergebnisse entstehen.

Für BRMs ist das eine wichtige Steuerungslogik: KI-Vorhaben sollten nicht nur als Innovationsportfolio betrachtet werden, sondern als Transformation mit klaren Kostenstellen, Nutzenhypothesen und Betriebsmodellen. Relevante Bewertungsfragen sind: Welche Prozesse werden tatsächlich verändert, welche Betriebskosten entstehen durch Compute und Integration, wer trägt fachliche Verantwortung, und wie wird Nutzen über Produktivität, Qualität, Risiko oder Umsatz gemessen?

## AI is being used to resurrect the voices of dead pilots (KI rekonstruiert Stimmen verstorbener Piloten)

Autor: Kirsten Korosec  
Quelle: [TechCrunch](https://techcrunch.com/2026/05/22/ai-is-being-used-to-resurrect-the-voices-of-dead-pilots/)  
Datum der Veröffentlichung: 22. Mai 2026, 16:03 Uhr PDT

TechCrunch berichtet, dass aus öffentlich verfügbaren Untersuchungsdaten eines Flugunfalls mithilfe von KI Näherungen der Cockpit-Audioaufnahmen verstorbener Piloten rekonstruiert wurden. Die US-Verkehrssicherheitsbehörde NTSB schränkte daraufhin den Zugriff auf Teile ihres Docket-Systems temporär ein.

Der Fall ist ein prägnantes Beispiel für neue Datenrisiken: Auch Daten, die nicht direkt als Audio oder personenbezogene Aufzeichnung veröffentlicht werden, können durch KI-Werkzeuge rekonstruiert oder in sensiblere Formate überführt werden. Für Enterprise-Unternehmen betrifft das Data Governance, Open-Data-Programme, interne Wissensdatenbanken und Incident-Dokumentation. BRMs sollten bei Datenfreigaben stärker prüfen lassen, ob scheinbar harmlose Artefakte durch multimodale KI zu vertraulichen oder reputationskritischen Inhalten rekombiniert werden können.

## Goldman Sachs CEO Says Fears Of Mass Unemployment From AI Are ‘Overblown’ (Goldman-Sachs-CEO hält KI-Arbeitsmarktängste für überzogen)

Autor: Antonio Pequeño IV  
Quelle: [Forbes](https://www.forbes.com/sites/antoniopequenoiv/2026/05/22/goldman-sachs-ceo-says-fears-of-mass-unemployment-from-ai-are-overblown/)  
Datum der Veröffentlichung: 22. Mai 2026, 14:07 Uhr EDT

Forbes berichtet über die Einschätzung von Goldman-Sachs-CEO David Solomon, dass Sorgen vor einer massiven KI-bedingten Arbeitslosigkeit überzeichnet seien. Gleichzeitig verweist der Artikel auf Goldman-Sachs-Analysen, nach denen KI in den kommenden zehn Jahren rund ein Viertel heutiger Arbeitsstunden automatisieren könnte.

Für Enterprise-BRMs liegt die praktische Relevanz in der Differenzierung zwischen Jobabbau-Narrativ und Aufgabenwandel. KI-Programme sollten gemeinsam mit HR, Fachbereichen und Betriebsorganisationen als Work-Redesign-Initiativen geführt werden: Welche Tätigkeiten werden automatisiert, welche Kontroll- und Entscheidungsrollen bleiben beim Menschen, welche Skills müssen aufgebaut werden, und wie wird Akzeptanz in den Fachbereichen gemessen?