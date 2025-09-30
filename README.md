# Task6_Password_Strength_Evaluation

# 🔒 Task 6: Password Strength Evaluation and Best Practices

## 🎯 Objective
To evaluate the factors contributing to password strength and demonstrate understanding of secure authentication practices by testing various password structures using online tools.

## 🛠️ Tools Used
* **Tool 1:** Delinea Password Strength Checker
* **Tool 2:** Security.org Password Strength Checker
* **Tool 3:** PSONO Password Strength Checker
* **Operating System:** Windows 10/11

## ⚙️ Password Evaluation Results

The following test passwords were used to demonstrate the difference between weak and strong authentication keys.

| Password Description | Length | Complexity | Score/Time to Crack (Example from Screenshot) | Learning Point |
| :--- | :--- | :--- | :--- | :--- |
| **Weak Example** | 9 | Low (4, 3) | 3 weeks | Too short, contains common dictionary words. |
| **Strong Passphrase** | **[14]** | High (1, 9, 3, 1) | **[6055437 Years]** | Length and character diversity are the primary factors in strength. |

## ✅ Deliverables (Screenshots)

Verification of the password strength analysis is provided by the attached screenshots from two separate professional tools:

* `[Delinea_Strong_Password_Result]`
* `[SecurityOrg_Password_Result]`
* `[PSONO_Pass@_check]`

## 💡 Key Findings and Security Best Practices

Password complexity directly affects resistance to attacks. The primary defenses against common password attacks are:

### 1. Common Password Attacks
* **Brute Force Attack:** An attacker systematically tries every possible character combination until the correct one is found. The time this takes is the core metric measured by strength checkers.
* **Dictionary Attack:** An attacker uses a list of common words, phrases, and leaked passwords to guess the correct password quickly. **Strong Passphrases** are effective against this.

### 2. How Complexity Affects Security
* **Length is King:** Every character added exponentially increases the number of possible combinations. The industry standard recommends a minimum of **12 to 14 characters** for general use.
* **Character Diversity:** Using a mix of uppercase, lowercase, numbers, and symbols (Special Characters) increases the size of the "character set," making brute-force attacks take significantly longer.
* **Passphrases over Passwords:** Creating a long, memorable phrase (like a sentence) with complexity is stronger and easier to remember than a complex, random short password.

### 3. Essential Best Practices
* **Use Unique Passwords:** Never reuse the same password across multiple accounts.
* **Use Multi-Factor Authentication (MFA):** This is the most critical defense. Even if the password is breached, MFA requires a second factor (like a code from a phone) to gain access.
* **Use a Password Manager:** Tools like LastPass or Bitwarden generate and store long, random, unique passwords for every account, eliminating the need to memorize them.
