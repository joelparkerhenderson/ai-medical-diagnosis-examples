# AI medical diagnosis example: Claude Opus 4.1

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses Anthropic Claude Opus 4.1.

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

These symptoms, especially the combination of breathing difficulties, throat closing sensations, and mental confusion, warrant immediate medical attention. Here's why:

Based on your symptoms, I'll rank the most probable SNOMED CT diagnoses from most to least likely:

## Most Likely Diagnoses (Ranked):

**1. Acute laryngotracheobronchitis (Croup) - 85319003**
- Your combination of stridor, wheezing, barking cough, and throat closing sensation strongly suggests upper airway inflammation
- The "wind knocked out" feeling and near-instant throat closing are characteristic of laryngeal involvement
- Though more common in children, adult croup does occur

**2. Acute bronchitis - 10509002**
- Productive cough, wheezing, shortness of breath for 5 days
- Fever, chills, and sweats support infectious process
- Common progression from upper respiratory infection

**3. Influenza with respiratory manifestations - 442438000**
- Fever, severe chills, sweats
- Respiratory symptoms including cough and shortness of breath
- Total loss of appetite and confusion could be systemic flu effects
- The "imploding" sensation might be severe muscle aches

**4. Bacterial pneumonia - 53084003**
- Productive cough, fever, chills, shortness of breath
- Mental confusion (possible hypoxia)
- Gold-colored mucus initially suggests bacterial infection

**5. Acute epiglottitis - 80384002**
- Throat burning, sensation of throat closing
- Difficulty breathing, stridor
- This is a medical emergency if suspected - less likely given 6-day duration

**6. Post-viral reactive airway disease - 195967001**
- Wheezing, cough following upper respiratory infection
- Shortness of breath with difficulty taking deep breaths

## Critical Warning Signs:

Your symptoms of **throat closing** and **mental confusion** are concerning and warrant immediate medical evaluation. These could indicate:
- Airway compromise
- Hypoxia
- Severe systemic infection

**Please seek urgent medical care immediately**, especially given:
- The throat closing sensation (potential airway emergency)
- Mental confusion episode
- Breathing difficulty with stridor
- Duration and severity of symptoms

This combination of symptoms, particularly with upper airway involvement and systemic effects, requires professional medical assessment and likely treatment with corticosteroids, bronchodilators, or antibiotics depending on the cause.