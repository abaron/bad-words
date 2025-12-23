# Bad Words & Disallowed Usernames

This project contains a curated list of disallowed words (bad words) and prohibited usernames, categorized for content moderation and input validation purposes.

## Usage Note
**This repository contains raw word lists.** 
The data is intentionally kept clean, consisting only of alphanumeric characters (`a-z`, `0-9`) and spaces (` `).

**Leetspeak & Variations Handling:**
Leetspeak variations (e.g., `5h1t` for `shit`, `b0kep` for `bokep`) and separated characters (e.g., `b_i_t_c_h`) are **not** included. The implementing system is expected to handle character normalization, spacing, or generate variations dynamically based on its specific requirements.

## Categories

Below is the classification of categories for the words:

### 1. Profanity
General swear words, insults, and vulgar language considered impolite in general conversation.
- *Code*: `profanity`

### 2. Hate Speech
Slurs or derogatory terms targeting race, religion, ethnicity, nationality, sexual orientation, gender, or disability.
- *Code*: `hate_speech`

### 3. Sexual & Adult Content
Explicit sexual terms, genitalia references, pornography-related acts, or keywords related to adult content.
- *Code*: `sexual`

### 4. Violence & Threats
Words related to physical harm, terrorism, self-harm/suicide, weapons, or severe criminal acts.
- *Code*: `violence`

### 5. Harassment & Bullying
Terms used specifically to demean, mock, or intimidate individuals.
- *Code*: `harassment`

### 6. Reserved/System Words
Words reserved to prevent impersonation of system roles or administrators (specifically for username validation).
- *Code*: `reserved`
- *Examples*: `admin`, `support`, `root`, `staff`

### 7. Spam & Scam
Words frequently associated with gambling, fraud, or spam promotion.
- *Code*: `spam`

---

## Folder Structure
- `/id`: Word lists in Indonesian
- `/en`: Word lists in English

## Related Repositories
For a comprehensive list of disallowed usernames (reserved, system, or sensitive names), please refer to:
- [abaron/disallowed-usernames](https://github.com/abaron/disallowed-usernames)
