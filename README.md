Luna Cycle: Product Vision & Roadmap
1. Executive Summary
Luna Cycle is a high-performance, privacy-focused Telegram Mini App (TMA) designed for menstrual cycle tracking. It combines an aesthetic "Glassmorphism" UI with the security and accessibility of the Telegram ecosystem.

2. Product Vision
The Problem
Privacy Concerns: Most health trackers sell user data or store it on insecure servers.

App Fatigue: Users don't want to download yet another 100MB app for simple logging.

Complexity: Existing apps are cluttered with ads and social features.

The Solution
Privacy-First: Data is handled within a secure environment, leveraging Telegram's authentication.

Instant Access: Zero-install friction. Works anywhere Telegram works.

Clean UX: A focused, "zen" interface that provides only what's necessary: tracking, predictions, and notes.

3. Key Features (Current)
Cycle & Period Tracking: Log cycles with a high-performance native-feel calendar.

Smart Predictions: Automated calculation of upcoming periods and fertile windows.

Haptic Interface: Deep integration with mobile vibration motors for physical feedback.

Cross-Platform Sync: Instant data availability across Telegram Desktop and Mobile via Supabase.

Premium Subscription: Unlock advanced analytics, custom visual themes, and cycle export via Telegram Stars — no external payments required.

Advanced Analytics: Cycle length trends, menstruation duration, symptom frequency, and phase-based symptom breakdown.

Cycle Export: Full cycle history delivered as a structured HTML report directly to your Telegram bot chat.

Offline Support: The app detects connectivity loss and gracefully notifies the user without crashing.

4. Technical Stack
Frontend: React 18, Vite 7 (High-speed build & render).

Backend: Supabase (PostgreSQL) with Row Level Security (RLS).

API: Telegram Web Apps API.

QA & Stability: Integrated validation logic for overlapping periods and cycle consistency.

5. Team Experience
Lead Developer / QA: Sergei, Senior/Middle QA Automation Engineer.

Focus: The project is built with a "test-first" mentality, ensuring high stability, performance optimization, and rigorous data validation.

6. Roadmap & Future Growth
Phase 1: Launch & Foundation (✅ Completed)
Telegram Apps Center Debut: Official release and initial user acquisition.

Localization: Support for English and Russian based on Telegram's user.language_code.

Premium via Telegram Stars: In-app purchases with no external payment providers — analytics, themes, and export unlocked.

Advanced Analytics & Export: Phase-based symptom breakdown, cycle trends, and full history export as HTML report.

Stability & UX Polish: Haptic feedback, glassmorphism UI, offline support, and bottom-sheet navigation.

Phase 2: Engagement & Notifications (Q2–Q3 2026)
Bot Notification Service: Opt-in reminders for upcoming cycles and ovulation phases via a dedicated Telegram Bot.

Encrypted Notes: Optional client-side encryption for daily symptom logging.

Phase 3: Partner Mode & Ecosystem (Q3–Q4 2026)
Partner Mode: Share your calendar and current cycle phase with a partner via a unique Telegram link — read-only access, no account required.

TON Payments: Alternative payment method via TON blockchain for Premium subscription.
