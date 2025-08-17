# AI medical diagnostics examples: Grok 4

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses xAI Grok 4.

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
- Yesterday, a sensation that I couldn't breathe in, like the wind knocked out of me. 
- Today, near-instant throat closing.

Strange issues that are wholly different than any of my previous illnesses:
- Total loss of appetite.
- Spasms of internal contractions, like an imploding feeling, pulling inwards.
- Mental confusion for 15 minutes, bad enough that I couldn't understand my wife.
```

## AI output response

As an expert medical doctor training a junior doctor, let’s walk through the systematic approach to triaging, diagnosing, and interacting with a patient presenting to the urgent care emergency department (ED) with the described symptoms. This case involves potentially life-threatening symptoms, so the process must be thorough, efficient, and patient-centered. Below is a structured guide for the junior doctor, broken into key components: triage, initial assessment, diagnostic workup, and patient interaction.

---

### 1. Triage in the Emergency Department
**Objective**: Quickly assess the severity of the patient’s condition to prioritize care.

**Steps**:
- **Immediate Assessment**: Use the **triage system** (e.g., Emergency Severity Index, ESI) to categorize the patient. This patient’s symptoms—particularly **near-instant throat closing**, **shortness of breath**, **stridor**, and **mental confusion**—suggest an **ESI Level 1 or 2** (critical or high-risk), indicating immediate or urgent attention.
  - **Red flags**: Throat closing and stridor raise concerns for airway compromise (e.g., anaphylaxis, epiglottitis, or laryngeal edema). Mental confusion suggests possible hypoxia, sepsis, or neurological involvement. These require rapid intervention.
- **Vital Signs**: Instruct triage staff to obtain vital signs immediately (heart rate, respiratory rate, oxygen saturation, blood pressure, temperature). Low oxygen saturation (<92%), high respiratory rate (>24 breaths/min), or fever (>100.4°F/38°C) would escalate urgency.
- **Airway, Breathing, Circulation (ABCs)**: Assess airway patency. Stridor and throat closing suggest partial airway obstruction, so prepare for potential airway management (e.g., intubation or cricothyroidotomy if needed).
- **Disposition**: Move the patient to a resuscitation bay or high-acuity area of the ED for immediate evaluation. Notify the attending physician and respiratory therapist if airway concerns are present.

**Teaching Point**: Triage is about identifying life-threatening conditions quickly. Stridor, throat closing, and confusion are “can’t miss” symptoms. Always prioritize airway and breathing issues, as they can deteriorate rapidly.

---

### 2. Initial Assessment
**Objective**: Perform a focused history and physical exam to narrow the differential diagnosis and guide immediate interventions.

**Steps**:
- **Primary Survey (ABCs)**:
  - **Airway**: Assess for stridor, drooling, or voice changes (hoarse or muffled). Inspect the oropharynx cautiously (avoid if epiglottitis is suspected, as it may trigger complete obstruction). If throat closing is worsening, prepare for airway intervention (e.g., call anesthesia or ENT).
  - **Breathing**: Check oxygen saturation and respiratory effort. Administer supplemental oxygen if SpO2 <94%. Auscultate lungs for wheezing, crackles, or diminished breath sounds.
  - **Circulation**: Assess for tachycardia, hypotension, or signs of shock (e.g., pale, clammy skin). Start IV access for fluids or medications.
- **History Taking (SAMPLE mnemonic)**:
  - **Symptoms**: Clarify onset, duration, and progression of symptoms (e.g., when did throat closing start? Any triggers for spasms or confusion?). Confirm the 6-day timeline and progression from nasal symptoms to systemic and airway issues.
  - **Allergies**: Ask about new allergens, foods, or medications (anaphylaxis risk).
  - **Medications**: Inquire about recent antibiotics, steroids, or over-the-counter remedies.
  - **Past Medical History**: Check for asthma, COPD, allergies, or prior infections.
  - **Last Oral Intake**: Note loss of appetite and last food/fluid intake to assess dehydration risk.
  - **Events**: Explore exposures (sick contacts, travel, animals) or trauma.
- **Focused Physical Exam**:
  - **HEENT**: Inspect throat (if safe), check for uvula deviation, tonsillar swelling, or erythema. Palpate for cervical lymphadenopathy. Assess nasal passages for discharge or obstruction.
  - **Lungs**: Listen for wheezing, stridor, or crackles. Note respiratory effort (use of accessory muscles).
  - **Neurological**: Evaluate mental status (Glasgow Coma Scale, orientation). Confusion lasting 15 minutes is concerning for hypoxia, sepsis, or encephalitis.
  - **Skin**: Check for rashes, cyanosis, or diaphoresis (sweats/chills suggest systemic infection).
  - **Abdomen**: Palpate for tenderness or distension (spasms may suggest GI involvement).

**Teaching Point**: The primary survey ensures immediate threats to life are addressed. For this patient, airway and neurological symptoms take precedence. A focused history and exam help refine the differential while avoiding delays in critical interventions.

---

### 3. Diagnostic Workup
**Objective**: Order targeted tests to confirm or rule out life-threatening diagnoses and guide treatment.

**Differential Diagnosis** (based on symptoms):
- **Airway-related**:
  - **Anaphylaxis**: Throat closing, wheezing, and systemic symptoms (less likely given 6-day duration but possible if new trigger).
  - **Epiglottitis**: Throat closing, stridor, fever (more common in adults than previously thought, especially with bacterial causes like *Haemophilus influenzae*).
  - **Laryngeal edema**: Secondary to infection or allergy.
- **Respiratory**:
  - **Pneumonia**: Fever, cough, shortness of breath, possible confusion (especially in severe cases or elderly).
  - **Bronchitis or asthma exacerbation**: Wheezing, cough, shortness of breath.
  - **Pulmonary embolism**: Shortness of breath, cough, systemic symptoms (less likely but possible with spasms).
- **Systemic Infections**:
  - **Sepsis**: Fever, chills, confusion, and systemic symptoms suggest possible bacterial infection (e.g., from sinusitis or pneumonia).
  - **Influenza or COVID-19**: Fever, cough, confusion, and loss of appetite are common.
- **Neurological**:
  - **Hypoxic encephalopathy**: Confusion from low oxygen levels due to airway/lung issues.
  - **Encephalitis or meningitis**: Confusion, fever, systemic symptoms (less likely without headache or neck stiffness).
- **Other**: Angioedema, severe dehydration, or metabolic disturbances (e.g., electrolyte imbalances causing spasms or confusion).

**Diagnostic Tests**:
- **Immediate**:
  - **Pulse oximetry and arterial blood gas (ABG)**: Assess oxygenation and acid-base status (hypoxia or respiratory acidosis from airway obstruction).
  - **ECG**: Rule out cardiac causes of shortness of breath or confusion.
  - **Chest X-ray**: Evaluate for pneumonia, pneumothorax, or pulmonary edema.
  - **Blood work**: Complete blood count (CBC) for infection (elevated white count), basic metabolic panel (BMP) for electrolytes/dehydration, lactate for sepsis, and inflammatory markers (CRP, ESR).
- **Airway-specific**:
  - **Neck X-ray or CT neck (soft tissue)**: If epiglottitis or abscess is suspected (e.g., “thumbprint sign” for epiglottitis).
  - **Laryngoscopy**: Performed by ENT if airway obstruction is suspected (do not delay if patient is deteriorating).
- **Infection workup**:
  - **Nasal/throat swab**: For influenza, COVID-19, or bacterial cultures (e.g., strep or *H. influenzae*).
  - **Blood cultures**: If sepsis is suspected.
- **Neurological**:
  - **Head CT**: If confusion persists or focal neurological signs appear (rule out stroke or mass).
  - **Lumbar puncture**: If meningitis/encephalitis is suspected (after ruling out increased intracranial pressure).

**Teaching Point**: Order tests based on the differential, but prioritize those that address immediate threats (e.g., airway imaging, oxygenation). Avoid over-testing; focus on high-yield diagnostics. For example, a CT neck is urgent if epiglottitis is suspected, but a head CT can wait unless neurological symptoms worsen.

---

### 4. Initial Management
**Objective**: Stabilize the patient while awaiting diagnostic results.

**Steps**:
- **Airway/Breathing**:
  - Administer **high-flow oxygen** (e.g., via non-rebreather mask) if SpO2 <94%.
  - If anaphylaxis is suspected (throat closing, wheezing), give **epinephrine** (0.3–0.5 mg IM, repeat every 5–15 minutes if needed), **antihistamines** (e.g., diphenhydramine 50 mg IV), and **steroids** (e.g., methylprednisolone 125 mg IV).
  - If epiglottitis is suspected, avoid throat manipulation and prepare for **intubation** or **cricothyroidotomy** in a controlled setting (call anesthesia/ENT).
  - For wheezing, administer **albuterol** (2.5–5 mg nebulized) and consider **steroids** (e.g., prednisone 40–60 mg PO or IV equivalent).
- **Circulation**:
  - Start **IV fluids** (e.g., normal saline 500 mL bolus) for dehydration or suspected sepsis.
  - Monitor for hypotension; if present, escalate to vasopressors after fluid resuscitation.
- **Infection**:
  - If bacterial infection (e.g., pneumonia, epiglottitis) is suspected, start **broad-spectrum antibiotics** (e.g., ceftriaxone 2 g IV + azithromycin 500 mg IV) after cultures.
  - If influenza or COVID-19 is suspected, consider **antivirals** (e.g., oseltamivir 75 mg PO BID for influenza, pending test results).
- **Symptom control**:
  - Antipyretics (e.g., acetaminophen 1 g IV/PO) for fever.
  - Monitor and reassess mental status; address hypoxia or metabolic causes promptly.

**Teaching Point**: Treat life-threatening conditions empirically while awaiting test results. For example, give epinephrine for possible anaphylaxis even if the diagnosis isn’t confirmed, as delaying can be fatal. Always reassess after interventions to ensure the patient is stabilizing.

---

### 5. Patient Interaction
**Objective**: Communicate effectively to build trust, gather information, and keep the patient informed.

**Steps**:
- **Introduce Yourself**: “Hello, I’m Dr. [Name], and I’m here to help you. Can you tell me what brought you in today?” Use a calm, reassuring tone.
- **Active Listening**: Let the patient describe symptoms in their own words. Acknowledge their distress: “It sounds like you’ve been feeling very unwell, especially with your throat and breathing.”
- **Explain Actions**: “We’re concerned about your breathing and throat symptoms, so we’re going to check your oxygen levels, give you some oxygen, and do a few tests to figure out what’s going on.”
- **Empathy**: Validate their experience: “I can see how scary it must be to feel your throat closing or to have trouble understanding things.”
- **Involve Family**: If the patient’s wife is present, ask her for collateral history (e.g., details of the confusion episode) while respecting patient autonomy.
- **Updates**: Keep the patient and family informed: “We’ve started oxygen and ordered a chest X-ray. We’ll update you as soon as we have results.”
- **Cultural Sensitivity**: Be mindful of the patient’s background, language, or health literacy level when explaining diagnoses or procedures.

**Teaching Point**: Clear communication reduces anxiety and builds trust. Always explain what you’re doing and why, especially in emergencies. Use simple language for complex concepts (e.g., “Your throat swelling might be closing off your airway, so we’re giving medicine to open it up”).

---

### 6. Monitoring and Reassessment
**Objective**: Continuously evaluate the patient’s response to treatment and adjust the plan.

**Steps**:
- **Reassess ABCs**: Check airway patency, respiratory rate, and oxygen saturation every 5–15 minutes in a critical patient.
- **Monitor Mental Status**: Use a simple scale (e.g., AVPU: Alert, Voice, Pain, Unresponsive) to track confusion.
- **Review Test Results**: Adjust treatment based on imaging, labs, or specialist input (e.g., ENT for laryngoscopy).
- **Escalation**: If the patient deteriorates (e.g., worsening stridor, hypoxia), escalate to ICU or surgical intervention.

**Teaching Point**: Never assume stability in a patient with airway or neurological symptoms. Reassess frequently and be ready to pivot if the clinical picture changes.

---

### Summary for Junior Doctor
This patient’s presentation is concerning for a potentially life-threatening condition due to **throat closing**, **stridor**, **shortness of breath**, and **mental confusion**. Triage them as ESI Level 1 or 2, prioritize airway management, and perform a rapid primary survey. Order targeted tests (e.g., chest X-ray, neck imaging, blood work) to rule out epiglottitis, anaphylaxis, pneumonia, or sepsis. Start empirical treatments (oxygen, epinephrine, antibiotics) based on the most likely diagnoses. Communicate clearly and empathetically, keeping the patient and family informed. Reassess frequently, as airway and neurological symptoms can deteriorate rapidly.

**Key Teaching Takeaways**:
1. **Prioritize the airway**: Stridor and throat closing are emergencies until proven otherwise.
2. **Think broadly but act quickly**: Consider infectious, allergic, and systemic causes, but don’t delay life-saving interventions.
3. **Communicate effectively**: Build trust and reduce anxiety through clear, empathetic explanations.
4. **Reassess constantly**: Critical patients can change status in minutes.

If you have follow-up questions about specific diagnostics, treatments, or communication techniques, let me know, and we can dive deeper!

_Disclaimer: Grok is not a doctor; please consult one. Don't share information that can identify you.
