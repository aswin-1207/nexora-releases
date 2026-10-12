# NEXORA — Collaborative Online Classroom & Study Suite

NEXORA is a serious, production-grade native Android application engineered for focused online classrooms and collaborative study cohorts (10–20 active participants). It seamlessly unites real-time WebRTC audio/video meetings with structured academic productivity, attendance verification, syllabus tracking, and motivational study companions.

---

## 📚 Architectural & Planning Documentation (Phase 1 Deliverables)

All architectural planning, specifications, and risk matrices created during **Phase 1** are organized in the [`docs/`](file:///d:/projects/NEXORA/docs) directory:

1. [**`PROJECT_OVERVIEW.md`**](file:///d:/projects/NEXORA/docs/PROJECT_OVERVIEW.md)
   * Product vision, target users, feature boundaries, design goals, and core philosophies.
2. [**`REQUIREMENTS_SPECIFICATION.md`**](file:///d:/projects/NEXORA/docs/REQUIREMENTS_SPECIFICATION.md)
   * RBAC permission matrix, complete master feature register (FR-01 to FR-13), workflows, and non-functional requirements.
3. [**`ARCHITECTURE.md`**](file:///d:/projects/NEXORA/docs/ARCHITECTURE.md)
   * Clean Architecture layers, LiveKit WebRTC SFU topology, Supabase backend mapping, and Android modular package structure.
4. [**`UI_UX_SPECIFICATION.md`**](file:///d:/projects/NEXORA/docs/UI_UX_SPECIFICATION.md)
   * Color tokens (calm light palette), typography, anti-clutter rules, screen inventory, and accessibility standards.
5. [**`DATABASE_DESIGN.md`**](file:///d:/projects/NEXORA/docs/DATABASE_DESIGN.md)
   * Normalized PostgreSQL schema, ER diagram, authoritative vs. derived models, RLS policies, and index definitions.
6. [**`SECURITY_AND_PRIVACY.md`**](file:///d:/projects/NEXORA/docs/SECURITY_AND_PRIVACY.md)
   * Threat modeling, zero-trust token dispensation, client obfuscation, and data lifecycle management.
7. [**`ZERO_BUDGET_PLAN.md`**](file:///d:/projects/NEXORA/docs/ZERO_BUDGET_PLAN.md)
   * Free-tier feasibility analysis (Supabase, LiveKit Cloud, Android Studio), bandwidth modeling, and self-hosted fallback options.
8. [**`TEST_STRATEGY.md`**](file:///d:/projects/NEXORA/docs/TEST_STRATEGY.md)
   * Testing pyramid, verification matrix, physical multi-device test standards, and phase quality gates.
9. [**`IMPLEMENTATION_ROADMAP.md`**](file:///d:/projects/NEXORA/docs/IMPLEMENTATION_ROADMAP.md)
   * Dependency-aware blueprints for all 15 phases with tasks, deliverables, and exit criteria.
10. [**`DECISIONS_AND_RISKS.md`**](file:///d:/projects/NEXORA/docs/DECISIONS_AND_RISKS.md)
    * Architecture Decision Records (ADRs), workspace findings (C: drive disk constraint), risk register, and approvals.

---

## 🛠️ Technology Stack Summary

- **Platform**: Native Android (Min SDK 26, Target SDK 35)
- **Language**: Kotlin 2.0+
- **UI Toolkit**: Jetpack Compose with Material 3 Design Tokens
- **State Management**: ViewModel + Kotlin Coroutines & StateFlow (UDF)
- **Local Cache**: Room Database (SQLite) + Jetpack DataStore
- **Real-Time Media**: LiveKit WebRTC Android SDK (SFU Architecture)
- **Backend**: Supabase (PostgreSQL 15, GoTrue Auth, Private Storage, Edge Functions, Realtime)
- **Budget**: **₹0 (100% Free-Tier & Open Source)**
