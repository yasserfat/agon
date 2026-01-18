# Agon – AI-Powered Personalized Sports Nutrition Platform

## Overview

**Agon** is a modern, mobile-friendly web application built for athletes, fitness enthusiasts, and active individuals who want **science-based, personalized nutrition** without manual calculations.

All **meal plans**, **daily and weekly menus**, **macro distributions**, **supplement suggestions**, **blood-test-based adjustments**, and **nutritional analysis** are generated and continuously improved by **AI**.

As users update their profile (training load, goals, blood results, preferences, feedback), the AI automatically adapts recommendations in real time.

Agon also includes an **AI-powered chat**, allowing users to ask questions, modify meals, or generate new plans using natural language.

---

## Important Note

I (Yasser) **do not own** this project.  
I designed and developed **Agon** while working as a developer at **DevFlows**, a low-code/no-code and AI-focused agency.

---

## Tech Stack

- **Frontend:** WeWeb  
- **Backend & Database:** Xano  
- **Automations & Workflows:** n8n  
- **Payments:** Stripe & PayPal  
- **Emailing:** Brevo (Sendinblue)  
- **AI:** Meal plan generation, nutrition analysis, blood biomarker interpretation, supplement recommendations, conversational chat

---

## Key Features

### 1. GDPR-Compliant Onboarding
- Explicit health data consent
- Step-by-step profile setup:
  - Age, gender, height, weight → **BMR calculation**
  - Sport type, frequency, intensity → **TDEE calculation**
  - Goal selection: fat loss, maintenance, or muscle gain
  - Diet style, allergies, food preferences, deficiencies, health notes
- AI-generated summary and validation before completion
- Login via google auth, meta or email password.
<div style="display: flex; gap: 150px; align-items: center ; width:100% ">
  <img src="images/V1 - Vue admin.png" alt="2023 Robot"  style="object-fit: contain;"/>
  <img src="images/V2 - Vue admin.png" alt="2023 Robot"  style="object-fit: contain;"/>
  <img src="images/V3 - Vue admin.png" alt="2023 Robot"  style="object-fit: contain;"/>
</div>

---

### 2. Smart Dashboard
- Live BMR and goal-adjusted TDEE
- Weight tracking with trend visualization
- AI-recommended macro distribution (editable)
- Today’s AI-generated menu preview
- Quick access to:
  - Blood test ordering
  - Nutritionist booking
  - AI chat

---

### 3. AI Meal Plan Engine (Core Feature)
- **Basic mode:** Average daily calorie needs
- **Advanced mode:** Daily calories adjusted based on planned training sessions
- AI dynamically adjusts macros:
  - Higher carbs before endurance training
  - Higher protein after strength training
- Fully respects allergies, preferences, and deficiencies
- One-click actions:
  - Regenerate meals
  - ❤️ Like foods (increase frequency)
  - 👑 Favorite foods (always included)
- Automatic shopping list (categorized)
- PDF export
- AI-based supplement suggestions when deficiencies are detected

---

### 4. Blood Test Integration (Premium)
- Home blood test kit ordering
- Color-coded results with simple explanations
- AI analysis automatically updates:
  - Meal plans
  - Macro targets
  - Supplement recommendations
- Historical data and progress tracking

---

### 5. Smart Reminders & Retention
- Email and push notifications for:
  - Weight updates
  - Menu regeneration
- Custom frequency settings
- Escalation if reminders are ignored
- Snooze and pause options

---

### 6. Monetization
- **7-day Premium trial** (no credit card required)
- **Free plan:** Basic daily menu
- **Premium plan (monthly/yearly):**
  - Weekly meal plans
  - Advanced training-based calculations
  - Blood test features
  - Priority AI chat
  - Coach/manager access

---

### 7. Additional Features
- French & English support
- Dark and light modes
- Public/private profile toggle (future social features)
- Coach dashboard for team monitoring
- Educational content via blog and podcasts
- Automated 7-day onboarding email sequence
- Direct AI chat for questions, explanations, and meal generation

---



