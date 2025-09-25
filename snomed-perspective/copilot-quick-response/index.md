# AI medical diagnosis example: Copilot Quick Response

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses Microsoft Copilot Quick Response.

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

Thanks for sharing such a detailed symptom profile — it paints a vivid clinical picture. Based on your description and current SNOMED CT terminology, here’s a ranked list of probable diagnostic codes that could be considered in a clinical setting:

---

## 🧠 Top Probable SNOMED CT Diagnoses

| Rank | SNOMED CT Concept | Code | Rationale |
|------|--------------------|------|-----------|
| 1️⃣ | **Acute viral upper respiratory tract infection** | 442696006 | Fits the progression from nasal symptoms to throat and lung involvement, with fever and systemic signs. |
| 2️⃣ | **Acute bronchitis** | 10509002 | Persistent cough, mucus production, and wheezing suggest lower airway inflammation. |
| 3️⃣ | **Laryngotracheobronchitis (Croup)** | 82271004 | Stridor, throat burning, and sudden airway closure are hallmark signs. |
| 4️⃣ | **Acute sinusitis** | 36971009 | Gold-colored mucus, postnasal drip, and nasal congestion are classic features. |
| 5️⃣ | **Influenza-like illness** | 442438000 | Fever, chills, sweats, and systemic symptoms including confusion and appetite loss align with flu syndromes. |
| 6️⃣ | **Dyspnea** | 267036007 | Shortness of breath and difficulty inhaling are key respiratory distress indicators. |
| 7️⃣ | **Mental confusion** | 289908002 | Acute cognitive disturbance, even transient, is clinically significant. |
| 8️⃣ | **Anorexia (loss of appetite)** | 271327008 | Total loss of appetite is a notable systemic symptom. |
| 9️⃣ | **Wheezing** | 56018004 | Audible breath sounds and airway narrowing are consistent with this finding. |
| 🔟 | **Postnasal drip** | 64531003 | Described clearly in your nasal symptoms. |

---

## 🧪 Additional Considerations

- **COVID-19** (SNOMED CT: 840539006) could be considered depending on exposure and testing, given the respiratory and systemic symptoms.
- **Epiglottitis** (SNOMED CT: 23924001) is rare but serious — sudden throat closure and stridor warrant urgent evaluation.
- **Sepsis** (SNOMED CT: 91302008) is unlikely but possible if confusion and systemic collapse worsen.

---

If symptoms escalate or breathing becomes more difficult, urgent medical evaluation is essential. Would you like help finding a nearby urgent care or hospital?

Sources:  NHS SNOMED CT Browser and SNOMED CT codelist repositories.
