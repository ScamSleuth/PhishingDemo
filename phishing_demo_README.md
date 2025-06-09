# PhishingDemo

⚠️ **This is an educational simulation tool to demonstrate how phishing websites can capture user data in real time.**  
It is designed for security awareness training, demonstrations, and research purposes only.

## 🔍 What It Shows

PhishingDemo simulates a fake credit card input form that captures:

- Typed input (keystroke logging)
- Copy-paste actions
- Autofilled form data
- Live changes (edits, deletions, field replacements)
- Credit card brand detection (VISA, MasterCard, etc.)
- Luhn algorithm validation (valid vs invalid card structure)
- Behavioral interaction history (field-by-field)

## 🎯 Purpose

This tool illustrates how sophisticated phishing kits operate behind the scenes.  
Even if users **delete** or **change** values, or **don't submit** the form, data can still be collected and reconstructed.

It helps:

- Cybersecurity educators demonstrate phishing tactics
- Red teamers simulate realistic data capture
- End-users understand how seemingly safe actions can still leak data

## ⚠️ Disclaimer

This project is intended for ethical use only.  
**Do not deploy, adapt, or distribute this code in any harmful or deceptive context.**  
Always obtain informed consent when using this in simulations or demonstrations.

## 📁 Contents

- `phishing_demo.html` – The core simulation page with tracking and live logging
- Inline JavaScript – Handles keylogging, input capture, validation, and activity logging
- Visual alert banner – Warns visitors about the risks and context

## 📚 Related Topics

- Phishing kits & infrastructure
- Autofill abuse
- Credential harvesting techniques
- Social engineering defense training
