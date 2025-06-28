# 📱 COVID E-Pass Generation System

A Python-based tool that generates digital e-passes and sends SMS notifications via **Twilio** API. Designed to automate access control during the COVID-19 pandemic.

---

## 🚀 Features

- **E-pass request** via command-line or HTTP endpoint
- **SMS notification** with pass details once approved
- **User validation** and status updates via REST API endpoints

---

## 🛠 Tech Stack

- **Language**: Python 3.x
- **API**: Flask or FastAPI for REST endpoints (if used)
- **Messaging**: Twilio for SMS delivery
- **Environment**: Local development using PyCharm

---

## 🔧 Setup Guide

### Prerequisites

- Python 3.x installed
- Twilio account (SID, Auth Token, and virtual phone number)

### Step-by-Step

```bash
git clone https://github.com/srinivaspaluvayi/Covid_E-pass_generation.git
cd Covid_E-pass_generation
pip install -r requirements.txt
