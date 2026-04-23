#project overview
Educational cybersecurity tool for demonstrating social engineering attacks
Simulates phishing scenarios to request camera access
Shows risks of blindly granting permissions
Helps in learning ethical hacking and penetration testing basics
Promotes cybersecurity awareness and safe online behavior
Intended for use in controlled and legal environments only

#features
Generates phishing links
Captures camera images (with user permission)
Works on multiple devices (Android, PC, etc.)
Uses tunneling services (like Ngrok/Cloudflare)

#Installation
git clone https://github.com/yourusername/camphish.git
cd camphish
bash camphish.sh

#project structure
camphish/
│── camphish.sh
│── sites/
│── templates/
│── README.md

#How it works
Creates a fake webpage
Sends link via social engineering
Requests camera permission
Captures image if user allows

#security instruction
Why you should not click unknown links
Risks of granting permissions blindly
Importance of cybersecurity awareness
