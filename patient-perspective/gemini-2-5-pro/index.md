# AI medical diagnosis example: Gemini 2.5 Pro

To help make progress with conversations about AI medical diagnosis, this repository contains my own writeup of my own real medical symptoms when I felt especially unwell. I did the writeup at the start of my real visit to a real doctor at a real hospital.

This page shows an AI medical diagnosis example that uses OpenAI ChatGPT 5.

## AI input prompt

```text
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

Thank you for sharing this detailed and well-documented account of your symptoms. It serves as an excellent case study for exploring the capabilities and limitations of AI in the medical domain.

**Important Disclaimer:** I am an AI assistant and not a medical professional. The following analysis is for informational and educational purposes only, intended to contribute to the conversation about AI in medicine. It is not a medical diagnosis, and it does not replace the consultation, diagnosis, or treatment provided by a qualified healthcare provider. The actions you took—seeking a real doctor at a real hospital—were absolutely the correct and necessary steps.

### AI-Powered Analysis of a Patient-Reported Symptom List

Based on the input you provided, here is how an AI can process, structure, and analyze the information to potentially assist a clinician.

---

#### **1. Symptom Structuring and Timeline Extraction**

An AI can quickly parse the free-text input and organize it into a structured format, identifying the timeline and involved systems.

* **Duration of Illness:** 6 days
* **Progression:** Symptoms have changed significantly over the course of the illness.

| System      | Symptoms                                                                                                                                                                     | Duration      |
| :---------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------ |
| **General** | Fever, soaking sweats, shivering chills (systemic signs of infection/inflammation). Total loss of appetite.                                                                   | Unspecified   |
| **Nasal** | Initial gold-colored mucus. Runny nose evolving into a blocked nose. Significant postnasal drip. Blowing nose every few minutes.                                               | 4 days        |
| **Lungs** | Shortness of breath ($dyspnea$), difficulty with deep inspiration. Pervasive, semi-productive cough. Intermittent stridor, wheezing.                                           | 5 days        |
| **Throat** | Burning sensation in the upper throat and posterior oropharynx. Sensation of "wind knocked out" (Day 5). Sensation of near-instant throat closing (Day 6).                      | Last 2 days   |
| **Other** | Spasms of internal contractions ("imploding feeling"). Acute mental confusion lasting 15 minutes.                                                                             | Recent        |

#### **2. Identification of "Red Flag" or High-Acuity Symptoms**

A key function for an AI in triage or clinical decision support is to identify symptoms that suggest a potentially serious or life-threatening condition requiring immediate attention. From your list, the following are significant red flags:

* **Shortness of Breath ($dyspnea$):** Especially described as "hard to breathe in," this points to a significant respiratory compromise.
* **Stridor:** This is a high-pitched, harsh sound during inhalation caused by a partially obstructed upper airway. *Stridor is a medical emergency*.
* **Sensation of Throat Closing:** This suggests severe inflammation and swelling in the pharynx or larynx (e.g., $laryngitis$, $epiglottitis$, or an allergic reaction), which can rapidly lead to a completely blocked airway.
* **Mental Confusion:** An acute change in mental status can be a sign of severe systemic illness, such as $hypoxia$ (low oxygen levels due to breathing difficulty) or $sepsis$ (a life-threatening response to infection).
* **Soaking Sweats and Shivering Chills:** These constitutional symptoms, especially when severe, can be associated with a significant systemic infection and a robust inflammatory response.

#### **3. Potential Differential Diagnosis Pathways**

Based on the combination of symptoms, an AI can generate a list of potential conditions for a clinician to consider. This is not a diagnosis but a list of possibilities based on pattern recognition.

The symptom cluster points strongly toward a **severe upper and lower respiratory tract infection**.

* **Primary Considerations (Infectious):**
    * **Influenza:** Often presents with a rapid onset of high fever, chills, body aches, cough, and sore throat. Severe cases can lead to pneumonia and respiratory distress.
    * **COVID-19:** Known for a wide range of symptoms, including fever, cough, shortness of breath, loss of appetite, and neurological symptoms like confusion ("brain fog").
    * **Respiratory Syncytial Virus (RSV):** Can cause severe respiratory illness, especially in adults with pre-existing conditions. It can affect both the upper and lower airways.
    * **Bacterial Superinfection:** A primary viral infection can be complicated by a secondary bacterial infection, such as bacterial $sinusitis$ (suggested by colored mucus), $bronchitis$, or $pneumonia$. The severity of symptoms might indicate this progression.
    * **Laryngotracheobronchitis (Croup) or Epiglottitis:** While more common in children, severe inflammation of the larynx, trachea, and bronchi can occur in adults. The stridor and throat-closing sensation make these critical considerations.

* **"Strange Issues" Interpretation:**
    * **Spasms:** This could potentially be related to severe coughing fits (paroxysms) or diaphragmatic irritation.
    * **Mental Confusion:** As noted, this is a serious sign, likely secondary to the systemic effects of the infection (e.g., $hypoxia$ or the inflammatory cascade).

#### **4. The Role and Limitations of AI in this Scenario**

This example perfectly illustrates where AI can and cannot help in a clinical encounter.

**Strengths Shown:**

1.  **Data Organization:** AI can rapidly structure a patient's narrative into a clinically relevant format, saving the physician time.
2.  **Pattern Recognition:** It can identify a constellation of symptoms that points toward a specific category of illness (e.g., severe respiratory infection).
3.  **Triage/Urgency Detection:** It can effectively flag "red flag" symptoms like stridor and confusion, alerting a clinician that the situation may be urgent.

**Critical Limitations:**

1.  **No Physical Exam:** The AI cannot perform a physical examination. A doctor would need to:
    * Visually inspect your throat for swelling and redness.
    * Listen to your lungs with a stethoscope ($auscultation$) to characterize the wheezing and check for signs of $pneumonia$.
    * Measure vital signs (oxygen saturation, heart rate, blood pressure, temperature).
    * Assess your level of respiratory distress.
2.  **No Diagnostic Testing:** The AI cannot order or interpret essential tests like a chest X-ray, a throat swab for bacteria or viruses (e.g., Strep, COVID-19, Influenza), or blood work to check for markers of infection and inflammation.
3.  **Lack of Context and Nuance:** A human doctor can gauge the patient's level of distress, ask clarifying questions in real-time, and integrate information about past medical history, medications, and allergies in a nuanced way that is still beyond the scope of current AI.

Your writeup provides a fantastic foundation for a productive discussion on how AI can be integrated into clinical workflows as a powerful assistant, helping to structure information and flag danger signs, while leaving the ultimate diagnosis and treatment plan in the hands of a human expert.