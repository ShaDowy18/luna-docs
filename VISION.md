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

4. Technical Stack
Frontend: React 18, Vite 7 (High-speed build & render).

Backend: Supabase (PostgreSQL) with Row Level Security (RLS).

API: Telegram Web Apps API.

QA & Stability: Integrated validation logic for overlapping periods and cycle consistency.

5. Team Experience
Lead Developer / QA: Сергей, Senior/Middle QA Automation Engineer.

Focus: The project is built with a "test-first" mentality, ensuring high stability, performance optimization, and rigorous data validation.

6. Roadmap & Future Growth
Phase 1: Launch & Foundation (Current)
Telegram Apps Center Debut: Official release and initial user acquisition.

Global Localization: Support for multiple languages (EN, RU, ES) based on Telegram's user.language_code.

Stability & UX Polish: Fine-tuning haptic feedback and glassmorphism UI based on real-world usage.

Phase 2: Engagement & Notifications (Q2 2026)
Bot Notification Service: Opt-in reminders for upcoming cycles and ovulation phases via a dedicated Telegram Bot.

Enhanced Entry Points & Shortcuts: Implementation of home-screen icons and deep-link integration for instant cycle status overview.

Encrypted Notes: Optional client-side encryption for daily symptom logging.

Phase 3: Ecosystem & Monetization (Q3-Q4 2026)
TON Integration: Premium features (advanced analytics, custom themes) accessible via Stars or TON payments.

Partner Mode: Securely share cycle data with a partner/spouse via a unique Telegram link.

Symptom Analytics: Using lightweight statistical models to identify patterns in physical and emotional well-being.
