# Doctrine & SOP Assistant — QA Dataset

Kjo dosje përmban **dataset-et e pyetje–përgjigje (Q/A)** që përdoren për **trajnim, testim dhe vlerësim** të projektit **Doctrine & SOP Assistant**.
Qëllimi i këtyre dataset-eve është të mundësojnë **vlerësim objektiv, të verifikueshëm dhe të sigurt** të sistemit RAG dhe sjelljes së tij.

---

## Paralajmërim i Rëndësishëm

- Të gjitha pyetjet dhe përgjigjet janë **fiktive** dhe bazohen vetëm në dokumentet edukative të këtij projekti.
- Dataset-et **nuk përmbajnë** dhe **nuk synojnë** njohuri taktike apo operacionale.
- Përdorimi i tyre lejohet **vetëm për qëllime mësimore**.

---

## Qëllimi i Dataset-eve Q/A

Këto dataset-e përdoren për të:

- ndërtuar shembuj Q/A për fine-tuning (opsional)
- testuar retrieval dhe grounding
- matur saktësinë faktike të përgjigjeve
- verifikuar citimet (doc_id + seksion)
- testuar refuzimet e sakta kur informacioni mungon

Dataset-et janë krijuar që përgjigjet të jenë **drejtpërdrejt të verifikueshme në tekst**.

---

## Përmbajtja e Dosjes

```text
qa/
├── qa_train.json
├── evaluation_benchmark_v2_complete.json
└── README.md
