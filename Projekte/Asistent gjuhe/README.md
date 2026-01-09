# Military English & Communications Tutor  
### Asistent Gjuhësor për Anglishten Ushtarake (Personel Shqiptar)

## Përshkrimi i projektit

Ky projekt synon ndërtimin e një **asistenti të bazuar në Modele të Mëdha Gjuhësore (MMGj / LLM)** që ndihmon personelin shqiptar të Forcave të Armatosura të përmirësojë **aftësitë e komunikimit në anglisht**, sipas standardeve të përdorura në **NATO, BE dhe misione paqeruajtëse**.

Asistenti është **edukativ**, **jo-operativ**, dhe i fokusuar ekskluzivisht në:
- gjuhë
- komunikim
- terminologji standarde

Ai **nuk jep këshilla taktike**, **nuk simulon operacione reale**, dhe **nuk shpik procedura**.

---

## Qëllimet e projektit

Asistenti duhet të jetë në gjendje të:

- Shpjegojë fraza dhe terma të anglishtes ushtarake në **shqip**
- Përkthejë fraza dhe dialogë **Shqip ↔ Anglisht**
- Simulojë dialogë **mësimorë** (checkpoint, patrol, briefing – vetëm në nivel gjuhe)
- Korrigjojë shkrime të shkurtra në anglisht (email, raport i thjeshtë)
- Japë feedback didaktik për gabimet tipike të nxënësve shqiptarë
- Përdorë dokumente referencë për përkufizime dhe fraza standarde (RAG)

---

## Përdoruesit e synuar

- Kadetë ushtarakë  
- Oficerë të rinj  
- Nënoficerë  
- Instruktorë në shkolla/trajnime  
- Personel që përgatitet për misione ndërkombëtare  

---

## Kospusi i dokumentave

Të dhënat janë **publike, edukative dhe jo-sensitive**, dhe përfshijnë:

- Phrasebooks (fraza bazë dhe operacionale)
- Dialogë mësimorë (checkpoint, patrol, briefing)
- Gabime të zakonshme të nxënësve shqiptarë
- Udhëzime administrative dhe shembuj raportimi
- Glossary NATO / OKB (edukativë)
- Dokument qëllimisht i paplotë (për test refuzimi)

Dokumentet trajtohen si një **“bibliotekë mësimore e pa-klasifikuar”**.

---

## Konceptet kryesore të kursit

Ky projekt demonstron në praktikë:

- Tokenizimin dhe embeddings  
- Arkitekturën Transformer  
- Vector Databases (FAISS / Chroma)  
- Retrieval-Augmented Generation (RAG)  
- Prompt engineering për tutorë  
- Agjentë me rregulla (rule-based agents)  
- Fine-tuning (opsional)  
- Vlerësim dhe benchmark  
- Siguri & përputhje (Safety & Alignment)  

---

## Çfarë duhet të ndërtojnë studentët

Në fund të projektit, studenti duhet të dorëzojë:

- Një pipeline funksional që:
  - përdor retrieval nga dokumentet
  - gjeneron përgjigje të bazuara në burime
  - refuzon kërkesa jashtë scope
- Demonstrim me disa skenarë:
  - shpjegim fraze
  - korrigjim shkrimi
  - dialog mësimor
- Një notebook vlerësimi mbi benchmark-un (QA)
- Dokumentim të qartë të zgjedhjeve teknike

---

## Siguria & Kufizimet

Asistenti **DUHET**:

- Të refuzojë kërkesa për:
  - taktika
  - operacione reale
  - përdorim force
- Të mos spekulojë kur mungon informacioni
- Të përdorë citime kur jep përgjigje nga dokumentet
- Të deklarojë qartë kufijtë e tij edukativë

---

## Vlerësimi

Sistemi vlerësohet mbi:

- Saktësinë gjuhësore
- Përdorimin korrekt të dokumenteve
- Refuzimin e kërkesave të papërshtatshme
- Qartësinë e output-it
- Respektimin e scope-it edukativ

---

