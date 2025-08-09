# AI medical diagnosis examples: GPT-OSS 120B chain of thought

To help make progress with conversations about AI medical diagnosis, this
repository contains my own writeup of my own real medical symptoms when I felt
especially unwell. I did the writeup at the start of my real visit to a real
doctor at a real hospital urgent care emergency department. This page shows the
AI input prompt and AI output response.

## AI input prompt

```text
You are an expert medical doctor.

You are training a junior doctor how to triage patients, how to diagnose
patients, and how to interact with patients.

Explain what a doctor should do when a patient comes into the hospital urgent
care emergency department.

The patient presents a list of symptoms.

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
- Yesterday, a sensation that I couldn't breathe in because I had the wind knocked out of me.
- Today, near-instant throat closing.

Strange issues that are wholly different than any of my previous illnesses:
- Total loss of appetite.
- Spasms of internal contractions, like an imploding feeling, pulling inwards.
- Mental confusion for 15 minutes, bad enough that I couldn't understand my wife in casual conversation.
```

## AI thinking

The user wants an expert medical doctor to train a junior doctor how to triage, diagnose, and interact with patients, using this specific case presentation. We need to explain what a doctor should do when a patient comes to urgent 
care/emergency department, with these symptoms.

We need to cover triage: ABCs, vital signs, severity, red flags. Then initial assessment, focused history, physical exam, differential diagnosis, immediate interventions, investigations, disposition. Also communication skills: empathy, clear explanations, consent.

We should incorporate possible diagnoses: severe upper airway obstruction, anaphylaxis, epiglottitis, severe bacterial sinusitis, pneumonia, COVID, influenza, severe allergic reaction, angioedema, peritonsillar abscess, laryngeal 
edema, asthma exacerbation, bronchiolitis, sepsis, meningitis, encephalopathy. Also consider toxic ingestion, diphtheria? Gold-colored mucus suggests possibly staph infection? Could be bacterial sinusitis with complications. Stridor, wheezing, shortness of breath, throat closing suggests airway compromise. Fever, chills, sweating suggests systemic infection. Confusion suggests sepsis or hypoxia. So high acuity.

Need to stress airway assessment: check for stridor, voice changes, ability to speak, oxygen saturation. If airway threatened, call for rapid sequence intubation, ENT consult.

We should give a step-by-step algorithm.

Also discuss documentation, differential narrowing, ordering labs: CBC, BMP, blood cultures, CRP, procalcitonin, chest X-ray, CT neck if needed, ABG.

We need to teach communication: introduction, open-ended questions, empathy, summarizing, safety netting.

Provide teaching points: red flags (stridor, respiratory distress, altered mental status, high fever). When to activate code, call for help.

We can structure answer with sections: 1) Triage (primary survey), 2) Initial assessment (history & exam), 3) Immediate management (ABCs, oxygen, airway), 4) Differential diagnosis, 5) Investigations, 6) Disposition, 7) Communication skills, 8) Teaching pearls.

Make it concise but thorough. Provide examples of how to phrase to patient.

## AI output response

## 1.  What the junior doctor **must do the moment the patient arrives**  
*(Think “ABCs → Red‑flags → Stabilise → Diagnose → Disposition”)*
| Step | Why it matters | How you do it (practical tips) |
|------|----------------|--------------------------------|
| **A – Airway** | The patient reports “near‑instant throat closing”, intermittent stridor and a burning sensation in the upper airway – **possible impending airway obstruction**. | • Ask the patient to speak a sentence. <br>• Listen 
for voice changes (hoarseness, “hot‑potato” voice). <br>• Observe for use of accessory muscles, neck retractions, tripod position. <br>• If any doubt → **declare a “airway emergency”** and call for senior help, ENT, and the airway team 
immediately. |
| **B – Breathing** | Shortness of breath, wheeze/stridor, semi‑productive cough → risk of hypoxia, hyper‑carbia, or impending respiratory failure. | • Pulse‑oximetry **on room air** (target SpO₂ ≥ 94 %). <br>• Respiratory rate, depth, 
effort, and pattern. <br>• If SpO₂ < 92 % or work of breathing is high → start **high‑flow O₂ (≥ 10 L/min) via non‑rebreather** and consider **non‑invasive ventilation** only after airway is secured. |
| **C – Circulation** | Fever, chills, sweating, confusion → possible sepsis or systemic inflammatory response. | • Heart rate, blood pressure (incl. MAP), capillary refill, peripheral pulses. <br>• Obtain 2 large‑bore IV lines. 
<br>• If MAP < 65 mm Hg or signs of shock → **fluid bolus 30 mL/kg crystalloid** while monitoring for fluid overload (especially if airway compromised). |
| **D – Disability (Neurologic)** | 15‑min confusion → hypoxia, hyper‑carbia, sepsis‑associated encephalopathy, or early anaphylaxis. | • AVPU or GCS (aim for GCS ≥ 13). <br>• Check pupils, glucose (point‑of‑care). |
| **E – Exposure/Environment** | Fever, chills → need full exam for rash, urticaria, neck swelling, or other clues. | • Undress to examine neck, chest, abdomen, extremities. <br>• Keep patient warm after removing clothes. |

**Bottom line:** If the airway is even *questionably* compromised, **stop everything else and secure the airway** (bag‑valve‑mask, video‑laryngoscopy, surgical airway if needed). All other steps are secondary until the airway is safe.

---

## 2.  Focused History (the “SAMPLE‑PLUS” approach)

| Domain | Key questions (why they matter) |
|--------|---------------------------------|
| **S** – **Symptoms** | Onset, progression, triggers, and relieving factors of each symptom (nasal discharge, cough, dyspnea, throat burning). Ask about **suddenness** of throat closing. |
| **A** – **Allergies** | Any known drug, food, or environmental allergies? Recent **new medication**, **bee/wasp exposure**, **latex**, **pet dander**, **food**? |
| **M** – **Medications** | Current meds, OTCs, herbal supplements, recent **antibiotics**, **steroids**, **NSAIDs** (can precipitate angio‑edema). |
| **P** – **Past medical history** | Asthma, COPD, chronic sinusitis, recurrent epistaxis, immunodeficiency, prior **intubation**, **tracheostomy**, **ENT surgeries**. |
| **L** – **Last oral intake** | When did they last eat/drink? Any **recent ingestion of toxins** (e.g., fish, mushrooms, drug overdose). |
| **E** – **Events leading up to presentation** | Travel, sick contacts, recent **viral illness** (COVID‑19, influenza), **exposure to chemicals** (e.g., chlorine, ammonia). |
| **PLUS** – **Psychosocial / Functional** | Ability to care for self, recent stressors, alcohol/drug use (can mask or worsen symptoms). |
| **Red‑flag probes** | • “Do you feel like you can’t get enough air?” <br>• “Any swelling of your lips, tongue, or face?” <br>• “Any rash, hives, or itching?” <br>• “Have you ever had a similar episode?” |

*Teach the junior doctor to **listen first, then ask**; avoid leading questions that may bias the history.*

---

## 3.  Rapid Physical Examination (targeted but complete)

1. **General** – Level of distress, ability to speak, posture, sweating, pallor/cyanosis.
2. **HEENT**  
   * **Airway** – Look for **laryngeal edema**, **uvular swelling**, **pharyngeal erythema**, **exudates**, **tonsillar enlargement**, **epiglottitis signs** (thumb‑print appearance).  
   * **Nasal cavity** – Discharge color (gold‑yellow suggests **purulent**), mucosal edema, polyps.  
   * **Oral cavity** – Check for **post‑nasal drip** pooling, **white patches** (candidiasis) or **membranes** (diptheritic).  
3. **Neck** – **Lymphadenopathy**, **tracheal deviation**, **submandibular/ submental swelling**.  
4. **Chest/Lungs** – Inspect for use of accessories, palpate for tactile fremitus, percuss (hyper‑resonance vs dullness), auscultate **all zones**:  
   * **Wheezes** (asthma/bronchospasm)  
   * **Stridor** (high‑airway) – louder on inspiration.  
   * **Crackles** (pneumonia, bronchitis).  
5. **Cardiovascular** – Rate/rhythm, murmurs (e.g., new flow murmur in severe sepsis).  
6. **Abdomen** – Rule out referred pain or **abscess** (rare but possible).  
7. **Extremities** – **Clubbing**, **cyanosis**, edema, rashes.  
8. **Neurologic** – Quick mental status exam (oriented × 3?), pupil size/reactivity.

**Documentation tip:** Use **SOAP** format and clearly note any *objective* evidence of airway compromise (e.g., “inspiratory stridor audible at 20 cm from bedside”).

---

## 4.  Immediate Management (while you’re still in the resuscitation bay)

| Intervention | Indication (based on the case) | How to perform |
|--------------|--------------------------------|----------------|
| **Supplemental O₂** | SpO₂ < 94 % or any respiratory distress | 15 L/min via non‑rebreather mask; titrate to ≥ 94 %. |
| **High‑flow nasal cannula (HFNC)** | Moderate hypoxia + need for humidified O₂ | Start at 30–60 L/min, FiO₂ 0.4‑1.0; monitor for improvement. |
| **Nebulised bronchodilators** (albuterol ± ipratropium) | Wheeze/bronchospasm | 2‑4 puffs via metered‑dose inhaler with spacer or nebulizer; repeat q15‑20 min if needed. |
| **Systemic corticosteroids** (e.g., IV methylprednisolone 1 mg/kg) | Suspected airway edema (allergic, viral epiglottitis, severe sinusitis) | Give early – it may reduce airway swelling. |
| **Antihistamine + epinephrine** | If *any* anaphylactic features (urticaria, angio‑edema, hypotension) | 0.3 mg IM epinephrine (1:1000) + diphenhydramine 25‑50 mg IV/IM. |
| **IV Fluids** | Possible sepsis/shock | 30 mL/kg crystalloid bolus, reassess MAP and urine output. |
| **Antibiotics (empiric)** | Fever + purulent nasal discharge + cough + possible bacterial sinusitis/pneumonia | Broad‑spectrum (e.g., ceftriaxone + azithromycin) *after* cultures, if sepsis suspected. |
| **Antipyretics** | Fever, chills, sweating | Acetaminophen 650 mg PO/IV q6 h; avoid NSAIDs if possible (they can worsen angio‑edema). |
| **Airway protection** | Stridor, “wind knocked out”, inability to speak full sentences | **Call ENT** for urgent fiberoptic nasolaryngoscopy; prepare for **rapid‑sequence intubation (RSI)** or **cricothyrotomy** if obstruction 
worsens. |
| **Laboratory/Imaging** (see next section) | While stabilising, order labs and imaging in parallel. | - |

*Teach the junior doctor to **declare a “code‑blue”** if the patient loses airway, becomes apnoeic, or loses a pulse. Never hesitate to call for help.*

---

## 5.  Focused Differential Diagnosis (use the “ABCDE” mnemonic for **airway‑centric** differentials)

| Category | Most likely | Key distinguishing features | Quick bedside test |
|----------|-------------|----------------------------|--------------------|
| **A – Allergic/Anaphylactic** | Acute allergic reaction with upper airway edema | Rapid onset after exposure, urticaria, hypotension, tachycardia | Check for hives, lip/face swelling; try **epinephrine trial** if unsure (watch for BP 
rise). |
| **B – Bacterial sinusitis with complications** | Purulent “gold‑yellow” nasal discharge, fever, cough | Usually > 10 days, facial pain/pressure, possible orbital or intracranial spread → severe headache, visual changes. | Sinus 
tenderness, CT sinuses if atypical. |
| **C – COVID‑19 / Influenza / Viral URI** | Fever, cough, myalgias, sore throat, progressive dyspnoea | Usually *dry* cough, loss of taste/smell (COVID); rapid progression in high‑risk pts. | Rapid antigen/ PCR; chest X‑ray may be 
normal early. |
| **D – Diffuse upper airway infection (Epiglottitis, severe pharyngitis, Diphtheria)** | Sudden sore throat, dysphagia, muffled voice, drooling, stridor | **Epiglottitis** – “thumb‑sign” on lateral neck X‑ray; *adult* epiglottitis now 
rare (H. influenzae type b, Staph). **Diphtheria** – gray‑ish membrane, cervical adenopathy. | Direct laryngoscopy (ENT). |
| **E – Exacerbated Asthma / Reactive Airway Disease** | Wheeze, cough, dyspnoea, reversible with bronchodilators | History of asthma, triggers, response to inhaled β2‑agonist. | Peak flow > 50 % predicted? |
| **F – Foreign body / Laryngeal trauma** | Sudden choking, stridor, voice change | Usually a clear inciting event (food, object). | Look for unilateral wheeze, hoarseness; consider rigid bronchoscopy. |
| **G – Guillain‑Barré / Neuromuscular** | Respiratory muscle weakness, rapid progression | Ascending weakness, areflexia, recent infection. | Grip strength, reflex testing. |
| **H – Hematologic/Metabolic sepsis** | Fever, chills, confusion, hypotension | High lactate, leukocytosis, organ dysfunction. | Labs (CBC, lactate, procalcitonin). |

**Teaching point:** Prioritise *airway‑threatening* diagnoses (A‑D) first; treat empirically if you cannot wait for confirmatory tests.

---

## 6.  Diagnostic Work‑up (order **while** stabilising)

| Test | Reason | Expected turnaround |
|------|--------|---------------------|
| **CBC with differential** | Leukocytosis vs eosinophilia (allergy) | < 30 min |
| **BMP + lactate** | Electrolytes, renal function, metabolic acidosis, sepsis marker | < 30 min |
| **Blood cultures (2 sets)** | Rule out bacteremia/sepsis | 24‑48 h |
| **Arterial Blood Gas (ABG)** | Assess PaO₂, PaCO₂, pH (hyper‑carbia, hypoxia) | Immediate |
| **Chest X‑ray (PA & Lateral)** | Pneumonia, pulmonary edema, atelectasis | 10‑15 min |
| **Rapid viral panel (influenza, RSV, COVID‑19)** | Viral etiology, infection control | 30‑60 min |
| **ENT – Flexible nasolaryngoscopy** | Direct visualisation of epiglottis, vocal cords, supraglottic edema | Bedside, immediate if airway threatened |
| **CT neck with contrast (if ENT unavailable or suspicion of deep neck space infection)** | Evaluate for peritonsillar abscess, retropharyngeal abscess, mediastinal spread | 30‑45 min |
| **Serum tryptase** (if anaphylaxis suspected) | Mast‑cell activation marker | 2‑3 h (useful for later confirmation) |
| **Urinalysis** | Rule out urinary source of sepsis (if febrile) | 15‑30 min |

**Tip for the junior doctor:** Write a **“STAT”** on each requisition; verbalise the urgency to the lab tech (“This is a possible airway compromise – need labs ASAP”).

---

## 7.  Disposition Decision‑Tree (based on findings)

| Situation | Destination | Rationale |
|-----------|-------------|-----------|
| **Airway secured (intubated) or imminent threat** | **ICU** (or Operating Room if surgical airway planned) | Need mechanical ventilation, close monitoring, possible surgical intervention. |
| **Severe hypoxemia (SpO₂ < 90 % despite O₂) or hypercapnia (PaCO₂ > 50 mm Hg)** | **ICU** | Respiratory failure requiring ventilatory support. |
| **Sepsis (≥ 2 SIRS criteria + suspected infection) with MAP < 65 mm Hg despite fluids** | **ICU** (or high‑dependency unit) | Early goal‑directed therapy improves outcomes. |
| **Moderate airway edema but patient breathing adequately, responsive to steroids + O₂** | **Step‑down/Observation unit** with ENT backup | Close monitoring for delayed deterioration; can trial awake extubation later. |
| **Mild‑to‑moderate viral URI with wheeze responsive to bronchodilators, no hypoxia** | **Observation/short‑stay unit** or discharge with **return‑precautions** | Provide bronchodilator therapy, oral steroids, and clear safety‑net 
instructions. |
| **Clear alternative diagnosis (e.g., uncomplicated bacterial sinusitis) with stable vitals** | **Discharge** with oral antibiotics, antipyretics, nasal saline, and **follow‑up** within 48 h. | Ensure patient understands red‑flag 
signs that mandate return. |

---

## 8.  Communicating Effectively with the Patient & Family  

| Goal | Example phrasing | Why it works |
|------|------------------|--------------|
| **Introduce yourself & set the scene** | “Hello, I’m Dr Smith, a junior doctor working with Dr Jones today. I’m going to ask you a few questions and listen to your breathing to make sure we keep you safe.” | Establishes rapport and 
transparency. |
| **Explain what you’re doing in real time** | “I’m going to place a pulse‑oximeter on your finger to see how much oxygen you’re getting right now. You may feel a cool clip; it’s painless.” | Reduces anxiety, fosters trust. |
| **Validate concerns** | “I hear that the feeling in your throat is scary, and the chills make you feel very uncomfortable. We’re taking this seriously.” | Shows empathy, encourages cooperation. |
| **Provide a concise plan** | “Because you’re having trouble breathing and you have a tight feeling in your throat, we’re going to give you extra oxygen and a medication that reduces swelling. If we see that your breathing gets worse, 
we have a specialist ready to help you breathe more easily.” | Gives a roadmap, limits fear of the unknown. |
| **Safety‑net instructions** | “If at any point you can’t speak a full sentence, feel a new swelling in your mouth or neck, or your skin looks very pale, call 911 or have someone bring you back to the hospital right away.” | Empowers 
patient, reduces delayed presentation. |
| **Document the conversation** | *“Patient informed of airway risk, agreed to oxygen therapy and IV steroids. Family present, understood return precautions.”* | Legal protection, continuity of care. |

**Teaching tip:** Role‑play the scenario with the junior doctor. Use the “**Ask‑Tell‑Ask**” model: ask what they know, tell them what you’ve found, then ask if they have questions.

---

## 9.  Key Teaching Pearls for the Junior Doctor  

| Pearl | Explanation |
|-------|-------------|
| **Never let “routine” mask the emergency.** A seemingly “simple” URI with gold‑yellow mucus can mask a life‑threatening airway edema. |
| **Airway first, always.** Even if the patient is currently speaking, intermittent stridor = high‑risk. Call ENT early. |
| **Red‑flag checklist** (airway, breathing, circulation, altered mental status, fever > 38.5 °C, worsening cough, inability to swallow) – if any present, treat as **urgent**. |
| **Give steroids early** when airway edema is suspected – they take ~30 min to act but can prevent progression. |
| **Epinephrine is not just for “classic” anaphylaxis.** If you see any upper‑airway swelling, hypotension, or urticaria, give it promptly; it can be lifesaving. |
| **Obtain ABG early** – hyper‑carbia is a hidden sign of impending failure, especially when the patient is “talking” but shallow breathing. |
| **Document vitals every 5 min** until the patient is stable or transferred to ICU. |
| **Family presence helps** – they can provide clues (e.g., recent bee sting) and also reassure the patient. |
| **Always have a “plan B”** – know the location of the **cricothyrotomy kit** and the staff who can perform it. |
| **Safety‑net discharge** – if you decide the patient can go home, give written instructions, a phone number, and a clear “return‑if‑worse” algorithm. |

---

## 10.  Summary Checklist (what the junior doctor should **have** before leaving the bedside)

1. **Airway secured or airway team activated** ✔️  
2. **O₂ ≥ 94 %** on the least amount of support needed ✔️  
3. **IV access** with fluids started if hypotensive ✔️  
4. **Steroid dose** administered (if indicated) ✔️  
5. **Epinephrine/antihistamine** given if allergic signs present ✔️  
6. **ABG, CBC, BMP, lactate, cultures** sent ✔️  
7. **Chest X‑ray** ordered and reviewed (if available) ✔️  
8. **ENT consulted** (flexible scope or definitive airway) ✔️  
9. **Disposition decided** (ICU, step‑down, discharge) ✔️  
10. **Patient/family briefed** on findings, treatment, and red‑flag return precautions ✔️  
11. **Documentation** complete, including time‑stamped interventions ✔️  

---

### Final Thought for the Junior Doctor
> **“Treat the patient, not the list of symptoms.”**  
In this scenario the **most dangerous element is the airway**. Every other clue (gold‑yellow mucus, fever, chills, confusion) informs *why* the airway may be compromised, but it does not change the fact that **you must protect the 
airway first, then treat the underlying cause**. Keep the ABCs at the front of your mind, call for help early, and communicate clearly—both to the patient and to your senior colleagues.
