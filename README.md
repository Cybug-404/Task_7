# Task_7 Identify and remove suspicious browser extensions

## 🔍 Objective
 Learn to spot and remove potentially harmful browser extensions
## 🛠 Tools Used
- Firefox (Browser)
- Linux (OS)

## 🧪 Steps Performed
1. Installed firefox using command **sudo apt install firefox**
2. Analyze all browser extension available on the browser
3. Verify the permissions of each extension
4. Removed vulnerable and auto-startup extensions (requesting too much permissions)
5. Clear browser cache and cookies.
6. Restart the browser

## 📊 Output
- Removed vulnerable browser extensions
- Vulnerable extensions keep storing user data publically


## 🧠 Learnings
  
  ### File System Access and Downloads
   Though extensions can't directly access local files, some use social engineering to: 
  - Trigger file downloads containing malware. 
  - Upload files via drag-and-drop from users (resume upload on job sites).

   ### Keystroke Logging
   Extensions with permissions to access all pages can:
  - Capture keystrokes entered in input fields (usernames, passwords).
  - Log typed messages and confidential data in enterprise systems.

   ### Phishing
  - Redirect you to lookalike phishing sites.
  - You search Google but get redirected to a fake banking site.

   ### Ad Injection and Click Fraud
  - Inject ads into web pages to earn revenue fraudulently.
  - Auto-click on ads (click fraud) using your browser in the background.

   ### Monitoring and Tracking
  - Track all browsing behavior (sites visited, time spent, clicks).
  - Build detailed profiles of users and sell the data. 

