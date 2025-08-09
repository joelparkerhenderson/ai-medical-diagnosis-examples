# AI medical diagnosis example: Gemini 2.5 Pro

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

Initiating Request Decomposition

I'm starting by dissecting the user's request. My aim is to understand the core need: to provide a detailed medical explanation. Considering my role as an expert doctor and the audience being a junior doctor, I'll need to tailor the explanation for clarity and appropriate depth. I'm focusing on identifying the critical elements the explanation must include to be useful.

Analyzing Symptom Clusters

I'm now diving into the user's provided symptom clusters. The most recent focus has been interpreting the significance of the respiratory symptoms, specifically dyspnea, stridor, and wheezing. The presence of stridor especially demands immediate attention and could be indicative of a serious condition. I'm considering sepsis as a critical differential based on the systemic symptoms (fever, chills, sweats). I'm carefully analyzing how these symptoms interrelate to determine the potential underlying illness.

Developing Differential Diagnoses

I'm now formulating a differential diagnosis list based on the prominent symptoms.  The respiratory distress, especially the stridor and throat-closing sensation, are the immediate priority. I'm leaning heavily towards epiglottitis and severe laryngitis. The systemic symptoms, especially the fever and altered mental status, require me to strongly consider sepsis. I'm weighing the likelihood of anaphylaxis, although the gradual onset challenges this diagnosis.  I must also account for the neurological component.

Outlining the Response Structure

I've been working on structuring the response as a direct training session. The introduction will emphasize the gravity of the situation. I'll focus on the essential "First 60 Seconds" of triage, highlighting key red flags (stridor, dyspnea, throat closing, confusion), and walking through the ABCDE approach. This will cover the most critical, life-saving initial steps.

Developing Patient Communication

I'm now focusing on how to guide the junior doctor in effective patient interaction. The patient's severe anxiety is a central consideration. I plan to emphasize empathy and reassurance as vital starting points. The aim is to build trust while gathering crucial medical history using a clear, structured framework. I'll highlight the need for probing questions to understand the "spasms" and timeline of confusion.

Developing Urgent Treatment Plans

I'm now formulating actionable treatment plans to guide the junior doctor. Key areas of focus include immediate airway management, the initiation of broad-spectrum antibiotics, and the consideration of steroids and epinephrine. The goal is to provide a comprehensive, stepwise approach tailored to the urgency of the patient's presentation. I'll outline the crucial medications, dosages, and monitoring parameters.

Finalizing Diagnostic Protocols

I'm solidifying the diagnostic steps, balancing urgency and thoroughness. The focus is now on labs, specifically FBC, U&Es, LFTs, CRP, and a Lactate level to identify sepsis. I'm also including a chest X-ray and potential CT scan to address respiratory concerns. My goal is to ensure a swift, accurate diagnosis given the patient's serious condition.

Formulating the Treatment Plan

I've been intensely considering the most effective treatment plan, especially the critical aspect of early antibiotic initiation.  Considering the likelihood of sepsis or a severe respiratory infection, I now believe the treatment must involve broad-spectrum antibiotics, steroids, and immediate oxygen therapy. I'm also planning to incorporate fluid resuscitation and vasopressors, if needed, along with careful monitoring of vitals. I need to emphasize the importance of early intervention.

Formulating Triage Protocols

I've been immersed in the immediate actions needed upon a patient's presentation. Key is emphasizing the "First 60 Seconds," including recognizing the critical red flags. The focus now is outlining the ABCDE assessment, outlining the immediate steps, and what initial orders are crucial. I'm prioritizing airway support, including the potential need for advanced airway management.

Developing Actionable Strategies

I'm now prioritizing the most critical "First 60 Seconds" actions. Emphasis now rests on immediate airway interventions. Given the patient's presentation, this includes preparing for a potential "difficult airway" scenario and readying the necessary equipment for intubation. The patient's critical presentation demands swift, decisive action.

## AI output response

Excellent question. Let's break this down. This is a complex presentation with several "red flag" symptoms. As a doctor in the emergency department, your job is to rapidly identify the most life-threatening possibilities while initiating life-saving care. You must be systematic, calm, and efficient.

Here is how we will approach this patient, covering triage, diagnosis, and patient interaction.

***

### 1. Triage and Immediate Actions (The First 5 Minutes)

This patient cannot wait in the waiting room. The combination of shortness of breath, stridor, and mental confusion flags them as requiring immediate attention. When the triage nurse brings this patient back, your initial assessment and actions must be swift.

**Recognise the Red Flags Immediately:**

* **Stridor:** A high-pitched inspiratory sound. This signifies upper airway obstruction. It is a medical emergency.
* **Shortness of Breath (Dyspnea):** Especially with difficulty inhaling, this reinforces the possibility of an airway obstruction or severe respiratory compromise.
* **Near-instant throat closing:** The patient's subjective feeling is critical. It suggests severe laryngeal or pharyngeal inflammation or oedema.
* **Mental Confusion:** This is a sign of systemic illness causing organ dysfunction. The most likely culprits are hypoxia (low oxygen) or sepsis.

**The ABCDE Approach:**

This is your mantra. In a sick patient, you assess and treat simultaneously.

* **A - Airway:**
    * **Assess:** Is the patient speaking in full sentences? Is the stridor audible? Look for signs of accessory muscle use in the neck. Can they handle their own secretions or are they drooling?
    * **Action:** This patient has a threatened airway.
        1.  **Alert Senior Staff:** Immediately call for a senior ED physician and an anaesthetist. State clearly: "I have a patient with stridor and respiratory distress, I need help now."
        2.  **Positioning:** Sit the patient upright. This can help relieve some pressure on the airway.
        3.  **Prepare for a Difficult Airway:** Have the difficult airway trolley brought to the cubicle. This is not a time for hesitation.

* **B - Breathing:**
    * **Assess:** What is their respiratory rate? What are their oxygen saturations ($SpO_2$)? Auscultate the chest – listen for the wheeze they describe, but also for air entry globally. Is it reduced? Are there crackles suggesting pneumonia?
    * **Action:**
        1.  **High-Flow Oxygen:** Apply high-flow oxygen via a non-rebreather mask immediately. Titrate to maintain $SpO_2$ > 94%.
        2.  **Nebulisers:** Given the airway inflammation and wheeze, nebulised medications are critical. Start with **nebulised adrenaline (epinephrine)**. It is a potent vasoconstrictor and can rapidly reduce upper airway oedema causing the stridor. You may also consider a salbutamol nebuliser for the wheeze.

* **C - Circulation:**
    * **Assess:** Check heart rate, blood pressure, capillary refill time, and temperature. The fever, sweats, and chills strongly suggest an infective process. Tachycardia and hypotension would be profound signs of septic shock.
    * **Action:**
        1.  **IV Access:** Secure large-bore intravenous (IV) access. Two large cannulas if possible.
        2.  **Blood Work:** Draw blood immediately. We'll discuss which tests shortly.
        3.  **IV Fluids:** Start an IV fluid bolus (e.g., 500ml of Hartmann's solution or normal saline) if they are tachycardic or hypotensive.

* **D - Disability:**
    * **Assess:** Quantify their confusion. What is their Glasgow Coma Scale (GCS) score? Are they alert, responding to voice, responding to pain, or unresponsive? Check their pupils.
    * **Action:**
        1.  **Check Blood Glucose:** A finger-prick blood sugar test is mandatory in any patient with altered mental status. Hypoglycaemia is an easily reversible cause.

* **E - Exposure:**
    * **Assess:** Respectfully remove the patient's clothing to perform a full examination, looking for rashes (e.g., meningococcal sepsis) or other clues. Keep them covered with a blanket to maintain dignity and prevent heat loss from the sweats.

***

### 2. Developing a Differential Diagnosis

While the ABCDEs are happening, your mind is working to build a list of possible causes. You must prioritise the most dangerous.

**Top Tier - Immediate Life-Threats:**

1.  **Epiglottitis / Supraglottitis:** In an adult, this is a bacterial infection (often *Haemophilus influenzae*, *Staphylococcus aureus*) of the epiglottis and surrounding structures. It perfectly explains the stridor, burning throat pain, sensation of throat closing, and systemic signs of infection. The confusion could be from hypoxia. This is a top differential.
2.  **Sepsis secondary to Pneumonia:** The cough, shortness of breath, fever, and confusion are a classic picture for severe community-acquired pneumonia leading to sepsis. Sepsis is defined as "life-threatening organ dysfunction caused by a dysregulated host response to infection." The confusion is the organ dysfunction. The stridor could be from severe associated tracheitis or laryngitis.
3.  **Anaphylaxis:** While less likely given the 4-5 day prodrome, the "near-instant throat closing" keeps it on the list. It could be a biphasic reaction or a new exposure.

**Second Tier - Serious Conditions:**

4.  **Severe Viral Infection (Influenza, COVID-19, RSV):** These viruses can cause a severe laryngotracheobronchitis, leading to all the symptoms described, including the systemic features and confusion in a severe case. The gold-coloured mucus is non-specific; it simply indicates the presence of white blood cells and does not reliably distinguish between viral and bacterial causes.
5.  **Retropharyngeal or Peritonsillar Abscess:** A deep space neck infection could cause airway compromise, fever, and pain, though stridor is more common with epiglottitis.
6.  **Diphtheria:** Extremely rare in the UK due to vaccination, but it classically causes a "pseudomembrane" in the throat leading to airway obstruction. Keep it in the back of your mind.

The "strange issues" (appetite loss, spasms, confusion) are most likely part of the systemic septic picture. Total loss of appetite is common in severe illness. The "imploding spasms" need clarification but could be severe rigors (shivering) or myoclonus related to the septic encephalopathy (confusion).

***

### 3. Focused History, Examination, and Patient Interaction

Now that you've stabilised the patient, you can gather more details. Your interaction here is key.

**How to Talk to the Patient:**

The patient is frightened. Your calm confidence is therapeutic.

* **Introduce Yourself:** "Hello, I'm Dr. [Your Name], one of the doctors in the emergency department. I can see you're having a very difficult time breathing. We're giving you some oxygen and medication to help with that right now. We're going to take very good care of you."
* **Acknowledge Their Fear:** "It must be very frightening to feel like you can't breathe. We are right here with you."
* **Ask Closed Questions First:** A breathless patient cannot give a long history. Start with yes/no questions. "Any allergies?" "Any regular medications?"
* **Involve the Wife:** The wife is a crucial source of information, especially regarding the episode of confusion. Ask her to describe it. Was he slurring his words? Did he seem "not himself"? How long did it last?

**Key History Questions:**

* **Clarify the "Throat Closing":** "When you say your throat closed, what did that feel like? Was it hard to breathe in, out, or both?" (Difficulty breathing *in* points to extrathoracic/upper airway obstruction).
* **PMHx:** Any history of asthma, COPD, or previous airway problems? Is he immunocompromised? Any recent surgeries?
* **Medications & Allergies:** Any new medications? Known allergies?
* **Social:** Smoking history? Any recent travel?

**Focused Physical Exam:**

* **Throat:** **DO NOT** attempt to examine the back of the throat with a tongue depressor if you strongly suspect epiglottitis. This can provoke laryngospasm and complete airway closure. A gentle look with a light source from a distance is acceptable.
* **Neck:** Feel for lymphadenopathy and any tenderness or swelling that might suggest an abscess.
* **Lungs:** A thorough auscultation is vital to map out the location of the wheeze, stridor, and any crackles.

***

### 4. Diagnostic Workup and Management

Your treatment has already begun with the ABCDE approach. Now you refine it based on your findings.

**Investigations:**

* **Laboratory:**
    * **Venous Blood Gas (VBG) or Arterial Blood Gas (ABG):** Essential. This will tell you their oxygen level ($PaO_2$), carbon dioxide level ($PaCO_2$), and lactate. A high lactate is a key marker for sepsis and tissue hypoperfusion.
    * **Full Blood Count (FBC):** Look for a high white cell count.
    * **Urea & Electrolytes (U&Es):** Assess kidney function (organ dysfunction in sepsis).
    * **C-Reactive Protein (CRP):** A key inflammatory marker.
    * **Blood Cultures:** Two sets from two different sites before antibiotics, if possible without delaying treatment.
    * **Sputum Culture & Viral Swabs:** For influenza, COVID-19, RSV.

* **Imaging:**
    * **Portable Chest X-Ray (CXR):** To look for pneumonia or other lung pathology.
    * **Lateral Neck X-Ray (Soft Tissue):** Can be done if the patient is stable enough. Look for the "thumbprint sign," which is a swollen epiglottis. However, if the patient is unstable, do not delay transfer for imaging. A CT scan is more sensitive.

**Therapeutics (Continuing Management):**

* **IV Antibiotics:** Do not delay. Start broad-spectrum IV antibiotics as per your hospital's sepsis protocol. A good choice would be **Ceftriaxone** (covers typical community pathogens) plus **Azithromycin** or a Doxycycline (covers atypical pathogens).
* **IV Corticosteroids:** Administer **IV Dexamethasone** or Hydrocortisone. Steroids are crucial for reducing airway inflammation and oedema from any cause, be it infectious or allergic. They are a cornerstone of treating croup and epiglottitis.
* **Continued Monitoring:** This patient needs continuous cardiac and $SpO_2$ monitoring in a resuscitation bay.

***

### 5. Disposition: The Final Step

This patient is critically unwell and requires admission to the hospital. The question is, to what level of care?

* **Intensive Care Unit (ICU):** If the stridor persists despite nebulised adrenaline, if they are hypotensive requiring ongoing fluid or vasopressors, if their GCS is low, or if their work of breathing is high, they need to go to the ICU. The anaesthetist you called earlier will be key in making this decision, as the patient may require intubation to secure their airway.
* **High Dependency Unit (HDU) / Medical Ward:** If they respond well to the initial treatment (stridor resolves, oxygen requirement decreases, they become more alert), they may be admitted to a closely monitored bed on an HDU or a respiratory ward.

**Communicating with the Family:**

Once the immediate crisis is managed, find the wife.
"We've started treatment to help his breathing with oxygen, some medication through a mask, and some antibiotics and steroids through his drip. The main concern right now is significant swelling in his upper airway, which is making it hard for him to breathe. He is very sick, and he will be staying in the hospital. The specialists from intensive care are here to help us make the best decisions. We are doing everything we can."

### Summary for the Junior Doctor

1.  **Trust Your Gut:** A patient who looks sick *is* sick. Stridor, dyspnea, and confusion are a potentially lethal combination.
2.  **Systematic Approach:** Use ABCDE. It keeps you grounded and ensures you don't miss anything when under pressure.
3.  **Call for Help Early:** There is no shame in asking for senior help. It is a sign of a safe doctor.
4.  **Treat and Diagnose Simultaneously:** Start life-saving treatments (Oxygen, Nebs, IV access, Fluids, Antibiotics, Steroids) based on the red flags before you have a definitive diagnosis.
5.  **Communicate:** Keep the patient and family informed with calm, clear language.

This is a challenging but manageable case if you are systematic and aggressive in your initial management. Well done for thinking it through. Now, let's go see the patient.