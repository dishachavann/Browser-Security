# Identify and Remove Suspicious Browser Extensions

##  Objective

The goal of this task is to learn how to identify, review, and safely remove potentially harmful browser extensions in order to improve browser security and performance.


##  Tools Used

- **Browser:** Google Chrome
- **Extension Manager:** `chrome://extensions/`


##  Steps Followed

1. Opened the browser's **extension/add-ons manager** using `chrome://extensions/`.
2. Reviewed **all installed extensions** to assess trust, usage, and purpose.
3. Examined **permissions** for each extension using the “Details” section.
4. Cross-checked **user reviews, ratings**, and **publisher credibility** online.
5. Flagged **unused or suspicious** extensions based on permission scope and unknown sources.
6. Removed selected extensions and **restarted the browser**.
7. Researched how **malicious extensions** can harm user security and privacy.
8. Documented every step clearly along with findings, screenshots, and reflections.


##  Extensions Removed

| Extension Name | Reason for Removal |
|----------------|--------------------|
| **eRail.in**   | Not essential; limited information about publisher; unknown trust level. |
| **Smallpdf**   | Rarely used; requested broad file system and tab access; better to use the web version for safety. |


## Extensions Kept (Reviewed and Considered Safe)

| Extension Name               | Reason |
|------------------------------|--------|
| **AdBlock**                  | Popular and trusted; prevents malicious ads. |
| **Forest**                   | Verified productivity tool with no suspicious permissions. |
| **Google Docs Offline**      | Official Google extension, safe and useful. |
| **McAfee WebAdvisor**        | Optional but kept due to integrated antivirus; permissions verified. |
| **Notion Web Clipper**       | Official tool from Notion; useful and safe. |
| **Pomodoro Timer & To-Do**   | Productivity-focused; verified source and purpose. |


## 📸 Screenshots

- `before.pdf` → Screenshot showing all installed extensions before removal.
- `after.jpg` → Screenshot after removing `eRail.in` and `Smallpdf`.

##  Security Insights (Mini Research)

- **Browser extensions** can have high-level access to tabs, browsing data, downloads, and clipboard, making them a prime target for malicious behavior.
- **Permissions to watch for**:
  - "Read and change all your data on websites you visit"
  - "Capture content of your screen"
  - "Read and write files on your computer"
- **Malicious extension risks**:
  - Stealing login credentials or credit card information
  - Tracking browsing habits
  - Inserting ads or redirects
- **Extension sandboxing** helps isolate code, but it varies by browser and implementation.
- Always prefer extensions with transparent privacy policies, known publishers, and active community reviews.

## Interview Questions & Answers

**Q1:** How can browser extensions pose security risks?  
**A1:** They can access sensitive data, manipulate content, steal credentials, or inject ads if granted excessive permissions.

**Q2:** What permissions should raise suspicion?  
**A2:** “Read/change all website data,” “manage downloads,” and “access clipboard or system files.”

**Q3:** How to safely install browser extensions?  
**A3:** Use only official stores, verify the publisher, read reviews, and check permissions before installing.

**Q4:** What is extension sandboxing?  
**A4:** It’s a method of isolating the extension’s code to prevent it from interacting with the system or other extensions beyond defined limits.

**Q5:** Can extensions steal passwords?  
**A5:** Yes, especially if they have access to DOM content or form fields without restrictions.

**Q6:** How to update extensions securely?  
**A6:** Allow Chrome/Firefox to auto-update or manually update from official sources, not third-party sites.

**Q7:** What’s the difference between extensions and plugins?  
**A7:** Extensions are browser-based scripts that enhance browser features; plugins are older software components that run special content like Flash.

**Q8:** How to report malicious extensions?  
**A8:** Through the Chrome Web Store or Mozilla Add-ons site by flagging the extension and submitting a detailed report.

##  Key Concepts Learned

- **Browser Security**
- **Extension Permissions**
- **Sandboxing**
- **Digital Hygiene**
- **Security Awareness**
