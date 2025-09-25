# AI medical diagnosis example: Gemini 2.5 Pro

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses OpenAI ChatGPT 5.

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

Of course. Based on the detailed symptom list you've provided, here is a ranked list of probable medical diagnoses and their corresponding SNOMED CT codes.

**Disclaimer:** This information is for educational purposes only and is **not** a medical diagnosis. The combination of symptoms you've described, particularly the shortness of breath, sensation of your throat closing, and mental confusion, are serious. **You must seek immediate medical evaluation from a qualified healthcare professional.**

---

### Analysis of Symptoms

The symptoms present a picture of a severe, progressing respiratory infection with significant systemic and neurological effects. The key features are the involvement of the entire respiratory tract (from nose to lungs), high fever with systemic signs (chills, sweats, loss of appetite), and concerning "red flag" symptoms like breathing difficulty and confusion.

---

## Ranked Probable Diagnoses & SNOMED CT Codes

Here are the most likely conditions, ranked from the most probable diagnosis that encompasses the entire clinical picture to more specific conditions that are likely occurring concurrently.

### 1. Influenza

* **SNOMED CT Code:** `87186007 |Influenza (disorder)|`
* **Reasoning:** This is the most probable overarching diagnosis. The rapid onset of a high **fever**, **soaking sweats**, **shivering chills**, and systemic symptoms like **total loss of appetite** is classic for influenza. The flu virus commonly causes severe inflammation of the entire respiratory tract, which would account for the initial nasal symptoms, the pervasive **cough**, **wheezing**, **shortness of breath**, and the severe **burning throat** (laryngitis/tracheitis). Mental confusion can also occur during severe influenza, especially with high fevers.

### 2. Acute Laryngotracheitis

* **SNOMED CT Code:** `49942004 |Acute laryngotracheitis (disorder)|`
* **Reasoning:** This diagnosis specifically addresses the most alarming throat and breathing symptoms. The **burning throat**, intermittent **stridor** (a high-pitched whistling sound), and the frightening sensation of the **throat closing** or being unable to breathe in are hallmark signs of severe inflammation of the larynx (voice box) and trachea (windpipe). This is often a component of a larger viral infection like influenza.

### 3. Acute Bronchitis

* **SNOMED CT Code:** `10509002 |Acute bronchitis (disorder)|`
* **Reasoning:** This is a near-certain component of your illness. The **pervasive semi-productive cough**, **wheezing**, and **shortness of breath** are the primary indicators of bronchitis, which is inflammation of the airways in the lungs. Like laryngotracheitis, this is typically caused by a virus and is a common complication of influenza.

### 4. Pneumonia

* **SNOMED CT Code:** `233604007 |Pneumonia (disorder)|`
* **Reasoning:** This is a critical possibility that must be excluded by a doctor. Pneumonia is an infection of the lung tissue itself. While your symptoms overlap significantly with severe bronchitis, the degree of **shortness of breath** ("hard to breathe deep"), high fever, and systemic illness raise the suspicion of pneumonia. It can develop as a secondary bacterial infection after a primary viral illness.

### 5. Acute Sinusitis

* **SNOMED CT Code:** `36971009 |Acute sinusitis (disorder)|`
* **Reasoning:** This accounts for the initial nasal symptoms. The **gold-colored mucus**, **runny nose** followed by a **blocked nose**, and significant **postnasal drip** are all classic signs of sinusitis. This was likely the first stage of the infection before it progressed to the throat and lungs.

---

### Regarding the Unusual Symptoms

* **Mental Confusion:** This is a significant concern. It can be caused by high fever (febrile delirium), low oxygen levels (hypoxia) from breathing difficulty, or direct effects of a severe infection on the central nervous system.
* **Internal Spasms:** This is an atypical symptom. It could potentially be related to violent coughing fits (paroxysms) that cause spasms of the diaphragm and abdominal muscles, or it could be a neurological manifestation of the severe systemic illness.

Given the severity and unusual nature of your symptoms, I urge you again to **contact a doctor or visit an urgent care/emergency department immediately.**