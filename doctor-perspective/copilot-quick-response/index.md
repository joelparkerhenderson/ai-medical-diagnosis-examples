# AI medical diagnosis example: Copilot Quick Response

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
- Yesterday, a sensation that I couldn't breathe in, like the wind knocked out of me.
- Today, near-instant throat closing.

Strange issues that are wholly different than any of my previous illnesses:
- Total loss of appetite.
- Spasms of internal contractions, like an imploding feeling, pulling inwards.
- Mental confusion for 15 minutes, bad enough that I couldn't understand my wife.
```

## AI thinking

Absolutely—this is a critical teaching moment for any junior doctor. When a patient presents to the emergency department with this constellation of symptoms, the approach must be swift, structured, and safety-focused. Here's how to guide a junior doctor through triage, diagnosis, and patient interaction in this scenario.

## AI output response

Absolutely—this is a critical teaching moment for any junior doctor. When a patient presents to the emergency department with this constellation of symptoms, the approach must be swift, structured, and safety-focused. Here's how to guide a junior doctor through triage, diagnosis, and patient interaction in this scenario:

---

## 🏥 Step 1: Triage — Prioritize Safety First

**Goal:** Identify life-threatening conditions and determine urgency.

### 🔴 Red Flags in This Case:
- **Throat closing sensation** → Possible airway obstruction or anaphylaxis.
- **Stridor and wheezing** → Upper airway compromise.
- **Shortness of breath + cough** → Possible pneumonia, asthma exacerbation, or COVID-19.
- **Mental confusion** → Could indicate hypoxia, sepsis, or neurological involvement.
- **Fever with chills and sweats** → Suggests systemic infection.

### 🧭 Immediate Actions:
- **Call for senior support** if airway compromise is suspected.
- **Place patient in resuscitation bay** if unstable.
- **Initiate ABC assessment**:
  - **Airway**: Is it patent? Any signs of obstruction?
  - **Breathing**: Respiratory rate, oxygen saturation, auscultation.
  - **Circulation**: Heart rate, blood pressure, perfusion.

---

## 🧪 Step 2: Diagnostic Workup — Build a Differential Diagnosis

**Goal:** Identify the underlying cause using clinical reasoning and investigations.

### 🧠 Differential Diagnoses to Consider:
| System | Possible Conditions |
|--------|---------------------|
| Respiratory | Acute viral or bacterial pneumonia, COVID-19, asthma exacerbation, anaphylaxis, epiglottitis |
| ENT | Sinusitis, postnasal drip syndrome, allergic rhinitis |
| Neurological | Sepsis-related encephalopathy, hypoxia-induced confusion |
| GI/Systemic | Sepsis, systemic inflammatory response syndrome (SIRS) |

### 🧪 Investigations:
- **Vitals**: Temp, HR, BP, RR, O2 sat.
- **Bloods**: CBC, CRP, procalcitonin, blood cultures, renal/liver function.
- **Imaging**: Chest X-ray or CT if pneumonia or obstruction suspected.
- **Throat exam**: Look for swelling, erythema, exudate.
- **COVID-19/flu swab**.
- **Pulse oximetry and ABG** if hypoxia suspected.

---

## 🗣️ Step 3: Patient Interaction — Communicate with Compassion and Clarity

**Goal:** Build trust, gather accurate history, and reassure the patient.

### 🧑‍⚕️ Tips for Junior Doctors:
- **Start with open-ended questions**: “Can you walk me through how this started?”
- **Use active listening**: Repeat back key symptoms to confirm understanding.
- **Validate distress**: “It sounds like this has been really frightening for you.”
- **Explain your plan clearly**: “We’re going to check your breathing and run some tests to understand what’s going on.”
- **Avoid medical jargon** unless the patient is medically literate.

---

## 🚨 Step 4: Management — Stabilize and Treat

**Goal:** Address immediate threats and begin targeted therapy.

### 🧯 Initial Management:
- **Oxygen therapy** if O2 sat < 94%.
- **Nebulized bronchodilators** if wheezing/bronchospasm.
- **Steroids** if airway inflammation suspected.
- **Empirical antibiotics** if pneumonia or sepsis suspected.
- **IV fluids** if hypotensive or dehydrated.
- **Monitor closely** for deterioration.

---

## 🧠 Teaching Pearls for Junior Doctors

- Always **triage based on airway, breathing, circulation**—never delay.
- **Confusion in a febrile patient** is a red flag for sepsis or hypoxia.
- **Stridor and throat closing** are airway emergencies until proven otherwise.
- **Postnasal drip and gold mucus** suggest sinus involvement, but are not the priority if airway is compromised.
- **Document everything clearly**—especially red flags and escalation steps.

---

Would you like a printable checklist or simulation scenario to help train junior doctors on this kind of case?

## AI input prompt

```prompt
yes
```

## AI output response

Great! Here's a **printable-style checklist and simulation scenario** designed to help junior doctors practice triaging and managing a complex emergency department case like the one you described.

---

## 🧾 Emergency Department Triage & Diagnosis Checklist

### 🔍 Initial Triage Assessment
- [ ] **Assess Airway**: Look for stridor, throat closing, inability to speak/swallow
- [ ] **Assess Breathing**: Check respiratory rate, oxygen saturation, auscultate lungs
- [ ] **Assess Circulation**: Measure BP, HR, capillary refill
- [ ] **Assess Disability**: Check mental status (AVPU or GCS), confusion, responsiveness
- [ ] **Expose & Examine**: Look for fever, sweating, skin signs

### 🚨 Red Flag Symptoms
- [ ] Throat closing sensation
- [ ] Stridor or wheezing
- [ ] Shortness of breath
- [ ] Mental confusion
- [ ] Fever with chills/sweats
- [ ] Burning throat sensation

### 🧪 Investigations
- [ ] Vitals: Temp, HR, BP, RR, O2 sat
- [ ] Bloods: CBC, CRP, U&E, LFTs, blood cultures
- [ ] Chest X-ray or CT thorax
- [ ] COVID-19/flu PCR
- [ ] ABG if hypoxia suspected
- [ ] Throat swab or visual exam

### 🩺 Initial Management
- [ ] Oxygen therapy if O2 sat < 94%
- [ ] Nebulized bronchodilators if wheezing
- [ ] IV steroids if airway inflammation suspected
- [ ] Empirical antibiotics if infection suspected
- [ ] IV fluids if hypotensive or dehydrated
- [ ] Escalate to senior if airway compromise or deterioration

---

## 🧠 Simulation Scenario: “The Burning Throat”

**Setting:** Emergency Department, Resus Bay  
**Patient:** 42-year-old presenting with 4-day history of respiratory and systemic symptoms.

### 🧾 Presenting Complaints:
- Gold-colored nasal mucus → runny then blocked nose
- Persistent postnasal drip
- Fever, chills, soaking sweats
- Shortness of breath, wheezing, stridor
- Burning sensation in throat
- Throat closing sensation today
- Mental confusion episode yesterday
- Loss of appetite, internal spasms

### 🎯 Learning Objectives:
1. Recognize airway compromise and initiate emergency management.
2. Build a differential diagnosis for respiratory distress with systemic symptoms.
3. Communicate effectively with a distressed patient.
4. Prioritize investigations and escalate appropriately.

### 🗣️ Roleplay Prompts:
- Patient is anxious and struggling to breathe.
- Partner is present and worried, asking questions.
- Junior doctor must explain what they’re doing and why.
- Senior doctor available for escalation.

---

Would you like me to turn this into a training module outline or add roleplay scripts for teaching sessions?
