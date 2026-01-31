# Cyber Attack Life Cycle & Common Cyber Attacks

This chapter explains how cyber attacks are carried out step‑by‑step and discusses the most common modern cyber attacks, including **DDoS attacks** and the concept of **SLA**.

---

## 1. Cyber Attack Life Cycle

A cyber attack usually follows a structured process called the **Cyber Attack Life Cycle** (also known as the Cyber Kill Chain).

### Stages of a Cyber Attack

1. **Reconnaissance**
   - Attacker gathers information about the target.
   - Finds vulnerabilities, employee details, or network structure.

2. **Weaponization**
   - Attacker creates malware or exploit tools for the attack.

3. **Delivery**
   - Malware is delivered via email attachments, malicious links, or downloads.

4. **Exploitation**
   - Malware executes and exploits system vulnerabilities.

5. **Installation**
   - Malware installs itself and gains persistence in the system.

6. **Command and Control (C2)**
   - Attacker remotely controls the infected system.

7. **Actions on Objectives**
   - Data theft, disruption, spying, or ransomware deployment occurs.

---

## 2. Importance of Understanding Cyber Attack Life Cycle

Understanding the **Cyber Attack Life Cycle** is critical for cybersecurity professionals. It provides a structured framework to anticipate attacks, plan defenses, and protect sensitive information. Here's why it matters:

### 1. Helps Predict Attacker Behavior and Prepare Defenses

- By studying the stages of an attack (reconnaissance, weaponization, delivery, exploitation, installation, command & control, and actions on objectives), security teams can **anticipate the next steps of an attacker**.  
- **Example:** If an organization detects suspicious email attachments (Delivery stage), proactive scanning and user awareness can prevent malware execution.  
- This allows organizations to **set up targeted defenses**, such as firewalls, intrusion detection systems, and access controls, at vulnerable points in the attack chain.

### 2. Improves Incident Response Efficiency

- Knowledge of the attack life cycle helps **incident response teams act faster** when an attack is detected.  
- **Example:** If malware has reached the Installation stage, analysts know to **isolate infected systems immediately** to prevent further spread.  
- It reduces **downtime, financial loss, and data compromise** by enabling structured, timely responses.

### 3. Allows Better Risk Assessment for Sensitive Data

- Organizations can **map critical assets** (like PII and SPII) to potential attack stages.  
- Understanding which stages of an attack can target sensitive data helps prioritize **risk mitigation measures**.  
- **Example:** Ransomware primarily attacks files (Actions on Objectives stage); knowing this allows organizations to implement **regular backups and encryption** to protect sensitive data.

### 4. Provides Context for Why Certain OS Features Matter in Cybersecurity

- Many attacks exploit **operating system vulnerabilities** (e.g., unpatched Windows systems, weak Linux permissions).  
- By understanding how attacks progress through the life cycle, security professionals can:  
  - Configure OS-level **access controls** to prevent unauthorized actions.  
  - Monitor **logs and system behavior** for early signs of exploitation.  
  - Apply **security patches and updates** proactively to stop attacks at the Exploitation or Installation stages.  
- Essentially, OS knowledge is only effective when combined with **awareness of how attackers operate**.

---

# ✅ Summary

Understanding the Cyber Attack Life Cycle is like having a **roadmap of the attacker’s journey**.  
It empowers security teams to **predict, detect, respond, and protect sensitive data** while leveraging operating system features effectively.  
This foundation is essential before diving into OS-level security practices
---

## Cyber Attack Life Cycle Diagram (Enhanced)

```mermaid
flowchart TD
    A[Reconnaissance 🔍] --> B[Weaponization ⚒️]
    B --> C[Delivery ✉️ / 💾]
    C --> D[Exploitation 💥]
    D --> E[Installation 🖥️]
    E --> F[Command & Control 🌐]
    F --> G[Actions on Objectives 🎯]

    %% Loopback to show continuous attack
    G --> H[Data Exfiltration / Service Disruption 💾⚠️]
    H --> F

    %% Optional side paths
    D --> I[Detection by Security Analysts 🛡️]
    I --> J[Incident Response 🔧]
    J --> E

    %% Node Styles
    style A fill:#ffcc00,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style B fill:#66ccff,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style C fill:#99ff99,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style D fill:#ff9999,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style E fill:#ffcc99,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style F fill:#ff6666,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style G fill:#66ffff,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style H fill:#ff6666,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style I fill:#99ccff,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px
    style J fill:#ffcc66,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,font-size:16px



