# Dueky Labs — Project Changelog (`LOG.md`)

All notable changes and milestones for Dueky Labs official web portfolio are documented in this file.

---

## [2026-10-08] - Project Initialization
- **Category**: Initialization & Portfolio Architecture
- **Summary**: 
  - Created project directory structure and established single-source-of-truth static architecture.
  - Defined Dual-Track portfolio strategy:
    - **Engineering Solutions**: *Electrical Toolkit* (Status: Release Candidate)
    - **Interactive Games**: *Train Defense* (Working Title, Status: Pre-production)
  - Established solo studio AI-driven workflow narrative (Claude Enterprise credit review ready).
  - Formulated development rules in `RULES.md` and initialized core landing page in `index.html`.

## [2026-10-08] UI Refactoring & Portfolio Update
- **Modified:** `index.html`
- **Description:** 
  - Refactored layout to remove cluttered elements and enforce a clean, professional dark-mode design.
  - Rebranded utility lineup to official name: **DPS (Device Protocol Studio)**.
  - Restructured sections into dedicated 'Solutions' and 'Games' tracks with polished card UI and hover animations.
  - Updated Studio Vision to reflect AI-Assisted Solo Engineering narrative.

## [2026-10-08] Add Electrical Toolkit & Image Placeholders
- **Modified:** `index.html`
- **Description:** 
  - Restored **Electrical Toolkit** as the overarching utility suite, featuring **DPS (Device Protocol Studio)** as the core app.
  - Added visual image/icon placeholder frames for apps and games to enhance UI professionalism.
  - Maintained clean dark-mode grid layout and responsive structure.

## [TASK-001] 2026-10-08 — DPS Real Screenshots & UI Overhaul
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Integrated official DPS app icon (`image/app_icon_1006.png`).
  - Added real-app UI screenshot gallery (`image/1.PNG`, `image/3.jpg`, `image/6.jpg`) showcasing terminal, protocol designer, and dashboard.
  - Enforced clean dark-mode grid layout and responsive structure per `RULES.md`.

## [TASK-002] 2026-10-08 — Electrical Toolkit & Full-Screenshot Horizontal Gallery
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Fully integrated Electrical Toolkit and DPS overview.
  - Implemented an interactive horizontal scrolling gallery containing ALL available app screenshots (`1.PNG` through `9.PNG`) to showcase the complete embedded debugging suite.
  - Enforced clean dark-mode grid layout and responsive structure per `RULES.md`.

## [TASK-003] 2026-10-08 — Train Defense Asset Integration & Dual Horizontal Galleries
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Integrated Train Defense visual concepts (`기차디펜스1.png`, `기차디펜스2.png`, `기차디펜스3.png`, `조비 열차 디펜스 게임 에셋 시트.png`) into the Games section.
  - Implemented interactive horizontal scroll galleries for both Electrical Toolkit (DPS) and Train Defense to showcase professional-grade application and game assets.
  - Maintained clean dark-mode grid layout and responsive design per `RULES.md`.

## [TASK-004] 2026-10-08 — Comprehensive Architecture Overhaul & KR/EN Toggle
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Separated Electrical Toolkit (with full product spec from planning docs) and DPS cleanly from studio identity; removed incorrect studio icon usage.
  - Added explicit **[In Development]** status badges for both Electrical Toolkit and Train Defense projects.
  - Implemented dynamic **Korean / English (KR/EN)** language toggle switch via JavaScript.
  - Enhanced overall typography, dark-mode color harmony, and UI visual hierarchy.

## [TASK-005] 2026-10-08 — UI/UX Refinement: Sequence, Drag-Scroll Gallery, and Complete i18n
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Reordered Solutions lineup to display **DPS** first, followed by **Electrical Toolkit**, and removed incorrect linkage copy.
  - Replaced mouse-wheel horizontal scrolling with an intuitive **Mouse Drag-to-Scroll** interaction for all screenshot galleries and removed the 'SCROLL-X' text indicator.
  - Fixed and enhanced JavaScript-based KR/EN language toggle to ensure zero residual Korean text remains when English mode is active.

## [TASK-006] 2026-10-08 — Contact Email Update, Footer Terms/Privacy Modals, and Final Polish
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Removed outdated email strings from the top right and set the official contact address to **`dueky.lab@gmail.com`**.
  - Added formal copyright notice and interactive **Privacy Policy** & **Terms of Service** modal popups in the footer.
  - Ensured all modal legal texts and contact details fully support the dynamic KR/EN translation switch.
  - Verified final UI visual hierarchy, drag-scroll galleries, and project sequence (DPS first, Electrical Toolkit second).

## [TASK-007] 2026-10-08 — Section Rename: Changed Solutions to Tools & Apps, Removed AI Philosophy Section
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Renamed the utility/app section from 'Solutions' to **Tools & Apps** for better studio alignment.
  - Completely removed the AI-Assisted/LLM studio philosophy section.
  - Cleaned up the header navigation by removing the top-right email address.
  - Verified drag-scroll galleries, project sequences (DPS -> Electrical Toolkit -> Train Defense), and full KR/EN i18n support.

## [TASK-008] 2026-10-08 — Interactive DPS Mini Terminal Widget Integration
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Added an interactive **DPS Mini Terminal Widget** inside the DPS card, allowing visitors to test simulated BLE commands and view live log outputs.
  - Verified section ordering (DPS -> Electrical Toolkit -> Train Defense) and 'Tools & Apps' naming.
  - Ensured all UI elements, drag-scroll galleries, modal terms, and i18n bilingual switches are fully functional and clean.

## [TASK-009] 2026-10-08 — i18n Bugfix: Resolved Residual Korean Text in Electrical Toolkit Sub-Cards
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Added full English translations to the i18n dictionary for all 6 sub-feature cards under Electrical Toolkit.
  - Verified that switching to English mode successfully translates all remaining Korean descriptions without residual text.

## [TASK-011] 2026-10-08 — Train Defense Text Polish (Engine/AI Mentions Removed) & Studio Intro Added
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Removed all specific Godot engine and AI balancing mentions from the Train Defense section text and tags.
  - Added the Studio Introduction section below Games, highlighting hardware roots (Est. 2007) and flexible indie game development philosophy.
  - Verified all i18n switches, drag-scroll galleries, DPS terminal, and footer terms modals.

## [TASK-012] 2026-10-08 — Gallery Watermark Overlay Added
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Added subtle CSS watermark overlays to all gallery screenshot cards in DPS and Train Defense to protect visual assets from unauthorized copying.
  - Verified that drag-scroll functionality and responsive layouts remain unaffected.

## [TASK-013] 2026-10-08 — Games Section Intro Revised & Final Polish
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Updated the Games section introduction text to a more refined and engaging phrasing.
  - Verified all integrated elements including DPS mini terminal, gallery watermarks, Studio introduction, and i18n bilingual switching.

## [TASK-015] 2026-10-08 — DPS v1.0.1 Major Update Capabilities Integrated
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Integrated DPS v1.0.1 major update specifications including TCP/UDP, MQTT, WebSocket, Virtual Devices, Protocol Designer, and Test Studio into the DPS card description and tags.
  - Verified bilingual i18n support, drag-scroll galleries with watermarks, mini terminal, and studio introduction sections.

## [TASK-016] 2026-10-08 — Final Polish: DPS v1.0.1, Games Intro Revision, and Watermark Integration
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Applied final refinements to DPS v1.0.1 specifications and revised the Games section introduction text.
  - Verified all integrated features including interactive terminal, gallery watermarks, studio introduction, and bilingual i18n switching.

## [TASK-017] 2026-10-09 — Train Defense Description Text Forced Update
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Updated Train Defense card description to emphasize immersive rules and strategic depth, completely replacing all data-driven references.
  - Verified bilingual i18n mapping (KR/EN) and clean responsive rendering.

## [TASK-018] 2026-10-09 — Removed 'Working Title' from Train Defense and Finalized Description
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Removed '(Working Title)' from the Train Defense card title.
  - Finalized the new descriptive text and ensured seamless bilingual i18n support.

## [TASK-019] 2026-10-09 — Typography and Text Layout Redesign for Better Readability
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Converted dense paragraph-style descriptions into clean, scannable point-based layouts across DPS, Train Defense, and Studio sections.
  - Ensured seamless bilingual i18n support and optimized text spacing and font hierarchy.

## [TASK-020] 2026-10-09 — Removed Label Badges and Applied Clean Bullet List Layout
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Removed decorative badge tags from descriptions and replaced them with clean bullet point lists for a minimalist aesthetic.
  - Updated i18n dictionary to match the clean list layout in English mode.

## [TASK-021] 2026-10-09 — Electrical Toolkit Sub-Cards Visual Redesign and Hover Polish
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Upgraded the UI of the 6 sub-feature cards in Electrical Toolkit with refined borders, hover glow effects, and optimized typography for a professional engineering studio aesthetic.
  - Verified i18n bilingual compatibility.

## [TASK-022] 2026-10-09 — Electrical Toolkit Sub-Cards Reordered, Bulleted, and Content Revised
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Moved the 8-languages card to the last position and updated feature descriptions to clean bullet-style formats.
  - Changed 'global standard' references to 'user-defined' specifications across the localization features.

## [TASK-024] 2026-10-09 — GitHub Repository Creation, Final UI Polish & Deployment
- **Target Files:** `index.html`, `LOG.md`
- **Actions Taken:**
  - Reordered Electrical Toolkit cards, applied clean bullet formats, and updated localization descriptions.
  - Automatically initialized the GitHub repository, committed changes, and pushed to `dueky-labs.github.io`.


