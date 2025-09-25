# AI medical diagnosis example: Copilot Think Deeper

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses Microsoft Copilot Think Deeper.

## AI input prompt

```text
You are an expert medical doctor. You know medical SNOMED CT codes.

Rank the probable medical SNOMED CT codes for diagnosing these symptoms.

This symptom list is in my own words.

Sick for 6 days with significant changes in symptoms over days.

Nose:
- Gold-color mucus at start of illness.
- Runny nose then blocked nose, with lots of postnasal drip, 4 days.
- Blowing nose every few minutes, 4 days.

Skin:
- Fever.
- Soaking sweats.
- Shivering chills.

Lungs:
- Shortness of breath for 5 days; hard to breathe in, hard to breathe deep.
- Pervasive semi-productive cough, every few minutes or so.
- Intermittent stridor, wheezing, whistling breath.

Throat:
- My upper throat and back of my mouth feels like it's burning.
- Yesterday, a sensation that I couldn't breathe in, like the wind knocked out of me. 
- Today, near-instant throat closing.

Strange issues that are wholly different than any of my previous illnesses:
- Total loss of appetite.
- Spasms of internal contractions, like an imploding feeling, pulling inwards.
- Mental confusion for 15 minutes, bad enough that I couldn't understand my wife.
```

## AI output response

### Probable SNOMED CT diagnoses (ranked)

| Rank | SNOMED CT concept | Concept ID | Key reason to consider |
|------|-------------------|------------:|------------------------|
| 1 | Acute upper respiratory tract infection | 442696006 | Progressive nasal, throat and systemic symptoms beginning as runny nose and coloured sputum |
| 2 | Acute bronchitis | 10509002 | Persistent productive cough, dyspnea and lower airway involvement |
| 3 | Laryngotracheobronchitis (croup) | 82271004 | Stridor, barking/whistling breath and intermittent airway obstruction symptoms |
| 4 | Acute sinusitis | 36971009 | Initial purulent (gold-colour) mucus and prolonged postnasal drip |
| 5 | Influenza | 6142004 | Fever with chills, sweats, myalgic/systemic features and rapid clinical change |
| 6 | Dyspnea | 267036007 | Subjective shortness of breath, difficulty inhaling and reduced inspiratory depth |
| 7 | Wheeze | 56018004 | Audible wheeze/whistling breaths on exam and reported intermittent wheeze |
| 8 | Epiglottitis | 23924001 | Sudden throat‑closing sensation and severe inspiratory difficulty (urgent consideration) |
| 9 | Acute confusion (delirium) | 289908002 | Transient period of mental confusion impairing comprehension |
| 10 | Anorexia (loss of appetite) | 271327008 | Total loss of appetite accompanying systemic illness |
| 11 | COVID-19 | 840539006 | Viral respiratory syndrome with variable presentation including anosmia, systemic signs and confusion |
| 12 | Sepsis | 91302008 | Consider if systemic signs progress (fever, rigors, confusion, hemodynamic instability) |

---

### Short clinical interpretation and next steps
- The pattern suggests a viral upper respiratory infection with lower airway involvement (acute bronchitis) and possible laryngotracheal irritation causing intermittent stridor; however, the near‑instant throat‑closing, transient severe confusion, worsening dyspnea and systemic symptoms raise concern for a potentially serious complication (epiglottitis, airway compromise, or evolving sepsis) that requires urgent assessment.  
- Immediate evaluation is recommended if you have increasing breathlessness, ongoing throat‑closing, inability to swallow, drooling, stridor at rest, altered consciousness, or high fever. Emergency department assessment with airway examination and urgent imaging/ENT review may be needed.

If you want, I can:
- Produce a pared list of the single most likely primary diagnosis and the top three problem-based SNOMED codes for an electronic record, or  
- Draft suggested brief wording to present to triage or ED staff, using these SNOMED concepts.
