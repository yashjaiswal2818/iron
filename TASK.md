# Iron Man: Stark Industries Bootcamp - Website Implementation Plan

## Project Overview
Transform the current "Gen A.I. Summit" landing page into the official event website for **"Iron Man: Stark Industries Bootcamp"**, organized by Google Developer Groups. The site must retain the premium "Stark Tech" aesthetic.

## Event Identity
- **Title:** Iron Man: Stark Industries Bootcamp
- **Organizer:** Google Developer Groups (GDG)
- **Tagline:** "Stark Industries doesn't recruit... it filters."
- **Visual Style:** Dark, Neon Blue/Red (HUD), Industrial, High-Tech.

## Site Structure & Content Mapping

### 1. Hero / Landing Section (The "Hook")
*   **Current State:** Iron Man 3D Scrollytelling.
*   **Update:**
    *   Change Title to `IRON MAN: STARK INDUSTRIES BOOTCAMP`.
    *   Add Tagline: `"Stark Industries doesn't recruit... it filters."`
    *   Update "Phases" in the scroll animation to be more generic "System Checks" or map them to the event opening context (e.g., "Initiating Filter Protocol").

### 2. Mission Briefing (Abstract & Objectives)
*   **New Section:** "MISSION BRIEFING"
*   **Content:**
    *   The "Abstract" text.
    *   Key Objectives (Logical thinking, Web Dev, UI/UX, etc.) presented as "System Parameters" or "Core Competencies".
    *   Target Audience (Undergrads) framed as "Eligible Recruits".

### 3. The Curriculum (The 5 Stages)
*   **New Section:** "TRAINING MODULES" or "STAGES"
*   **Design:** Grid or Timeline view using HUD aesthetics (Cards with borders, glowing text).
*   **Modules:**
    1.  **Stage 1: Stark Smelter Lab** (Competitive Programming) - *Symbol: Reactor/Core*
    2.  **Stage 2: Jarvis Command Room** (Web Development) - *Symbol: Code/Terminal*
    3.  **Stage 3: Mark UI Design Bay** (UI/UX Design) - *Symbol: Interface/Layout*
    4.  **Stage 4: Friday Logic Core** (Logic & Decision Making) - *Symbol: Brain/Network*
    5.  **Stage 5: Arc Reactor Presentation Pitch** (Communication) - *Symbol: Arc Reactor*

### 4. Registration / Footer
*   **Call to Action:** "REGISTER FOR BOOTCAMP" (Styled as "Initialize Protocol").
*   **Footer:** GDG Branding and copyright.

## Implementation Steps
1.  **Refactor `index.html`**:
    *   Update `<title>` and Hero text.
    *   Create container for new sections below the `scroll-content`.
2.  **Build "Mission Briefing" Section**:
    *   HTML structure for Abstract and Objectives.
    *   CSS for typography and spacing.
3.  **Build "Stages" Section**:
    *   Create cards for the 5 stages.
    *   Implement "Glassmorphism" checks and hover effects.
4.  **Polish**:
    *   Ensure mobile responsiveness.
    *   Check contrast and accessibility.
