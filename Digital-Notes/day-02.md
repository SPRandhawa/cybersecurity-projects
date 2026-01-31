# Types of Computer Viruses

A **computer virus** is a malicious program that attaches itself to files or programs and spreads from one system to another.

## 1. File Infector Virus

Attaches itself to executable files (.exe, .com).  
It spreads when the infected program is opened.

## 2. Boot Sector Virus

Infects the boot sector of a storage device and runs when the computer starts.

## 3. Macro Virus

Spreads through documents containing macros (e.g., Word or Excel files).

## 4. Resident Virus

Installs itself in system memory and infects files as they are opened or executed.

## 5. Direct Action Virus

Does not stay in memory; it infects files immediately when executed and then stops.

## 6. Polymorphic Virus

Changes its code every time it spreads, making detection difficult.

## 7. Metamorphic Virus

Completely rewrites its code to avoid detection by antivirus programs.

## 8. Multipartite Virus

Infects both boot sectors and files, spreading in multiple ways.

## 9. Overwrite Virus

Overwrites file content, destroying original data.

## 10. Companion Virus

Creates a malicious program with the same name as a legitimate one so it runs first.

---

## Summary

Computer viruses differ in how they infect systems, spread, and avoid detection, but all aim to damage or control systems

---

# Computer Threats: Viruses vs Malware & Phishing

In cybersecurity, it is important to distinguish **traditional computer viruses** from other types of threats such as **malware, trojans, ransomware, and phishing attacks**.  

- **Traditional Viruses:**  
  These are self-replicating programs that attach themselves to files or programs. They spread when the infected file is executed. Examples include **file infector viruses, boot sector viruses, macro viruses, polymorphic viruses**, etc.  
  - They primarily **damage files, programs, or the system itself**.
  - They require some form of **user action** (like opening a file) to spread.  

- **Modern Malware & Phishing:**  
  Modern threats are broader than just viruses. They include programs or attacks designed to **steal data, take control of systems, extort money, or manipulate users**.  
  - These may **not self-replicate**, unlike viruses.
  - They often spread through **downloads, emails, networks, or social engineering**.
  - Examples include **trojans, worms, ransomware, spyware, adware, and phishing attacks**.  

---

## 1. Malware (Malicious Software)

**Malware** is the umbrella term for all harmful software, including viruses, worms, trojans, ransomware, spyware, etc.  

### Examples

- **Virus:** Infects files or programs and spreads when executed.  
- **Worm:** Self-replicates and spreads automatically across networks without user action.  
- **Trojan Horse:** Appears legitimate but hides malicious code; does **not self-replicate**.  
- **Ransomware:** Encrypts your files and demands payment to unlock them.  
- **Spyware:** Secretly monitors your activity and steals sensitive information.  
- **Adware:** Displays unwanted advertisements, sometimes tracking your behavior.  

---

## Real World Example: Love Letter Virus (ILOVEYOU)

The **Love Letter Virus**, also known as the **ILOVEYOU virus**, was one of the most destructive malware outbreaks in history, discovered in the year 2000.

### How it worked

- It spread through email with the subject line **"ILOVEYOU"**.
- The email contained an attachment named **LOVE-LETTER-FOR-YOU.txt.vbs**.
- When opened, the script infected the computer.
- It automatically sent itself to all contacts in the victim's email address book.

### Classification

The Love Letter attack is best classified as:

- A **worm**, because it automatically spread through email.
- A **virus-like malware**, because it modified and overwrote files.
- A **Trojan-like attack**, because it tricked users into opening it.

### Damage caused

- Overwrote image and music files.
- Stole passwords.
- Spread rapidly worldwide.
- Caused billions of dollars in damage.

### Why it succeeded

It succeeded mainly due to **social engineering**, as users trusted and opened a message that appeared to be a love letter.

---

## 2. Phishing

- **Phishing** is not a virus or malware, but a **social engineering attack**.  
- Its goal is to **trick users into giving sensitive information** like passwords, credit card numbers, or personal data.  
- Common phishing methods include **fake emails, malicious links, and fraudulent websites**.

---

## 3. Difference Between Virus and Other Malware

| Type            | Self-replicates? | How it spreads                   | Damage / Effect                      |
|-----------------|----------------|---------------------------------|-------------------------------------|
| **Virus**       | Yes            | Files, programs                 | Corrupts files, slows system        |
| **Worm**        | Yes            | Networks                        | Network overload, system damage     |
| **Trojan Horse**| No             | Downloads, email attachments    | Steals information, backdoor access |
| **Ransomware**  | No/Yes         | Email, downloads, network       | Encrypts files, demands ransom      |
| **Phishing**    | No             | Emails, messages, fake websites | Steals credentials, identity theft  |
| **Spyware**     | No             | Downloads, ads                  | Tracks behavior, steals data        |
| **Adware**      | No             | Downloads, ads                  | Displays unwanted ads, tracks users |

---

### ✅ Summary

- **Viruses** are just one type of malware; they spread by attaching to files or programs.  
- **Malware** is a broader category that includes viruses, worms, trojans, ransomware, spyware, and adware.  
- **Phishing** is a method of tricking users to steal information and may be used to deliver malware.  
- Understanding the differences helps in **preventing infections and protecting sensitive data**.

---

## 4. Attackers

**Threat Actors** are individuals or groups that intentionally cause harm to systems or data.

### Types

- **Cybercriminals:** Financial gain (fraud, ransomware, data theft)  
- **Hacktivists:** Political or social motives  
- **Nation-State Attackers:** Cyber espionage, cyber warfare  
- **Insiders:** Employees/contractors misusing access  
- **Script Kiddies:** Inexperienced hackers using ready-made tools

### Goals

- Financial gain  
- Data theft, especially **PII (Personally Identifiable Information)** and **SPII (Sensitive PII)**  
- Service disruption  
- Political or ideological objectives  

---

## 5. Defenders

**Security Analysts** are cybersecurity professionals who protect systems, networks, and data.

### Responsibilities

- Monitor networks for suspicious activity  
- Investigate security incidents  
- Implement security measures  
- Conduct vulnerability assessments  
- Respond to attacks  
- Protect **PII/SPII** from unauthorized access  

### Skills

- Networking and OS knowledge  
- Malware and attack understanding  
- Incident response  
- Security tools usage  
- Policy and compliance knowledge  

### Goal

- Detect, prevent, and respond to threats, keeping systems and sensitive data safe.

---

## 6. Relation to PII & SPII

- **PII (Personally Identifiable Information):** Names, emails, phone numbers, etc.  
- **SPII (Sensitive PII):** Social security numbers, passport numbers, financial data, medical records.  

Cyber threats like viruses, ransomware, phishing, and trojans often **target PII/SPII** for theft or misuse.  
**Security Analysts** focus on **protecting these sensitive data types** to prevent identity theft, financial loss, and privacy violations.

---

### Summary Flow

**Threat Actors → Malware / Phishing Attacks → Target Systems & PII/SPII → Security Analysts Defend Systems**
