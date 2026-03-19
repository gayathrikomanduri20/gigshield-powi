# GigShield – Proof-of-Work Insurance (PoWI)

AI-powered parametric insurance for gig workers that verifies real work effort instead of relying on GPS, preventing fraud and ensuring fair payouts.

---

## 1. Problem Statement

Gig workers lose income due to external disruptions such as heavy rain, extreme heat, pollution, and floods.

- There is no system that automatically compensates income loss.
- Existing solutions rely on GPS, which can be easily spoofed.
- This leads to fraud and unfair payouts.
- Current parametric insurance systems fail due to GPS spoofing, enabling coordinated fraud and financial loss.

---

## 2. Proposed Solution

**GigShield – Proof-of-Work Insurance (PoWI)**

AI-powered insurance that verifies real work effort instead of trusting GPS.

---

## 3. Persona

**Ravi – Swiggy Delivery Partner**

- City: Hyderabad  
- Weekly Income: ₹7000  
- Working Hours: 8 hours/day  

---

## 4. Disruptions Covered

- Heavy Rain  
- Extreme Heat  
- Severe AQI  
- Flood Alerts  

---

## 5. System Workflow

User registers  
→ AI monitors environment + effort signals  
→ Disruption detected  
→ Effort vs Expected Effort calculated  
→ Payout triggered automatically  

---

## 6. Core Innovation

### Proof-of-Work Insurance (PoWI)

**Payout = f(real effort + disruption impact)**

- System does NOT rely on GPS  
- System introduces a behavior-based Proof-of-Work layer that validates real delivery effort before triggering payouts  

---

## 7. Effort Score Model

Effort Score =  
0.4 × Movement  
+ 0.3 × Order Activity  
+ 0.3 × App Usage  

---

## 8. AI/ML Usage

- Risk prediction  
- Effort vs expected effort gap analysis  
- Fraud scoring  
- AI computes an Effort Gap Score to measure the difference between expected and actual work under disruption conditions  

---

## 9. Adversarial Defense & Anti-Spoofing Strategy

### Differentiation

- Multi-signal verification  
- Behavior-based validation instead of GPS  

### Data Used

- Movement patterns  
- Order logs  
- Device integrity  
- IP vs GPS mismatch  
- Historical behavior  

### Fraud Detection

fraud_score > threshold → flag claim  

### Coordinated Fraud Detection

The system detects group-level fraud by identifying multiple users showing identical location patterns, claim timing, and low activity signals, indicating organized spoofing attacks.

### UX Balance

- Low risk → Auto approve  
- Medium risk → Soft verification  
- High risk → Hold and verify  
---
## 10. Tech Stack

- Frontend: React  
- Backend: Node.js  
- AI: Python (Scikit-learn)  
- Database: MongoDB  
- APIs: Weather API, AQI API  
---
## 11. Architecture
Frontend → Backend → AI Risk & Fraud Engine → External APIs → Parametric Trigger → Payout System  
---
## 12. Future Scope

- Dynamic premium pricing  
- Real-time analytics dashboard  
- Integration with delivery platforms  
---
## 13. Team Details
**Team Name:** Code Cruisers  
**Members:**
- Gayathri  
- Varshika  
- Jayasri  
- Bindhu  
