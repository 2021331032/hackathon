## MediGuard AI — 180‑second YouTube Demo Script

**Style note:** Keep the pacing fast, confident, and visual. Show the app on-screen almost the whole time. Use simple language. Mention “Bangladesh-first” and “global-ready.” Avoid claiming medical diagnosis.

---

### 0:00–0:30 — Problem (The Vibe)
**[On screen: quick montage—medicine strips, boxes, caregiver helping parent, scrolling long leaflet text]**  
**Narration:**
“Every day in Bangladesh, people self-medicate or manage medicines for parents and children—often with multiple brands and confusing labels. The biggest risks are simple but dangerous: duplicate ingredients, wrong medicine for a condition like kidney disease or ulcer, and unsafe combinations with other medicines. Existing apps are either too technical, not personalized, or require manual searching. This problem is urgent locally—and it’s global.”

**Key line to end this segment:**  
“We need a fast, personalized safety check that feels like a pocket pharmacist.”

---

### 0:30–1:00 — Solution (What we built)
**[On screen: App home screen + logo “MediGuard AI”]**  
**Narration:**
“This is MediGuard AI—an AI-assisted, profile-based medication safety checker. It’s built for caregivers and everyday users. Instead of searching through long medical text, users select a patient profile and a medicine, tap Analyze, and instantly get a clear result: Green, Yellow, or Red—plus the reasons and next steps in simple language. We’re building OCR scanning next, but the core system is already working end-to-end.”

**Differentiation line:**  
“Our key differentiator is personalization + explainability: the result is based on the patient’s profile and current medicines, and we show exactly why.”

---

### 1:00–2:00 — Demo / Concept Flow (Show it working)
**[On screen: Record screen and do the steps below]**

**Narration + actions:**

**1:00–1:15 — Create/select profile (Caregiver Mode)**  
“First, we choose a profile. Caregiver mode lets you manage multiple family members. Here’s a profile for ‘Mother’—with age group and conditions like kidney disease or ulcer, and her current medicines.”

**[Action: open Profiles → select “Mother” → show conditions + current meds chips]**

**1:15–1:35 — Select medicine (MVP uses dataset; OCR later)**  
“Next, we select a medicine from our curated Bangladesh brand dataset. For this MVP, selection is manual and searchable. OCR scanning will later prefill this field from the packet—but we always keep manual confirmation to prevent mistakes.”

**[Action: open medicine search → select a medicine that triggers risk, e.g., an NSAID-like class in your dataset]**

**1:35–1:55 — Analyze (Stepper + result)**  
“Now we tap Analyze. The app shows what it’s doing step-by-step: preparing profile, normalizing the medicine, checking duplicates, checking condition warnings, checking interactions, then generating an easy summary.”

**[Action: tap Analyze → show stepper loading]**

**1:55–2:00 — Result**  
“And here’s the result: Red—high risk—for this specific profile. We show the reasons clearly and what the user should do next.”

**[Action: show Result screen: status, confidence chip, reasons accordion, recommended action]**

---

### 2:00–2:30 — AI Approach (Real AI thinking, safe)
**[On screen: simple architecture slide: Input → Normalize → Risk Engine → Explanation; show “offline dataset” and “LLM explanation (guardrailed)”]**  
**Narration:**
“Our system is AI-native but safety-first. The core risk decision is deterministic and explainable—based on structured rules like duplicate ingredients, contraindications by condition, and interaction pairs. Then we use an LLM safely as a communication layer: it rewrites the structured output into simple, user-friendly language and Bangla—without inventing medical facts. In the next iteration we’ll add OCR for medicine packets and build a small retrieval layer so the explanation can cite the exact dataset entry used.”

**Key trust line:**  
“AI helps users understand; it does not replace clinicians or hallucinate medical advice.”

---

### 2:30–3:00 — Impact + Next Steps (Scale & KPIs)
**[On screen: “Impact” slide + roadmap: OCR → expand dataset 30→300 → rule packs → Bangla UX → share report]**  
**Narration:**
“The impact is measurable: fewer duplicate dosing events, fewer unsafe combinations, and faster pharmacist-level guidance for families. Our target KPIs are: reduced risky combinations per 100 checks, time saved versus manual searching, and user comprehension in Bangla. Next, we will integrate on-device OCR to prefill medicine selection, expand our Bangladesh brand dataset from 10 to 30 and beyond, and add a shareable report for doctors and pharmacists. MediGuard AI is Bangladesh-first—but the architecture supports country-specific medicine packs, making it globally adaptable.”

**Closing line (strong finish):**  
“We’ve moved from idea to working system. This is MediGuard AI—personalized medication safety, built to scale.”

---
