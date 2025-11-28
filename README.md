# **AI Clinic Receptionist – Voice Automation (n8n + ElevenLabs + Cal.com)**

An end-to-end **AI voice receptionist** that automates patient calls, identifies intent, books or reschedules appointments, retrieves patient information, and routes calls to the correct department using **n8n**, **ElevenLabs Agents**, **GPT-4o**, and **Cal.com**.

---

## 🚀 **Key Features**

* **AI voice agent** built with ElevenLabs (natural, real-time conversations)
* **LLM decision logic** to classify caller intent and branch workflows
* **Full appointment automation**: book, reschedule, cancel via Cal.com API
* **Patient lookup** by phone number or name
* **Emergency, billing & doctor routing**
* **Webhook-based orchestration** between ElevenLabs → n8n → Cal.com
* **Automatic logging** for CRM or dashboard use

---

## 🧩 **How It Works**

1. Caller speaks with the **ElevenLabs voice agent**.
2. ElevenLabs sends input to **n8n via webhook**.
3. n8n triggers the LLM to determine intent:

   * New patient → qualification → booking
   * Existing patient → locate appointment → reschedule or cancel
   * Emergency → direct transfer
   * Billing/finance → route to staff
4. n8n interacts with **Cal.com** to manage appointment data.
5. The AI responds back to the caller through ElevenLabs.

---

## 🛠️ **Tech Stack**

* **n8n** (workflow automation)
* **ElevenLabs Agents** (voice AI)
* **GPT-4o / LLMs** (reasoning & classification)
* **Cal.com API** (scheduling)
* **Google Sheets / DB** for patient data (optional)

## 📸 **Screenshots**



