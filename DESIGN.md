---
name: Apex Auto SaaS
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#2d3449'
  on-tertiary: '#ffffff'
  tertiary-container: '#434b60'
  on-tertiary-container: '#b4bbd5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
  brand-accent-blue: '#2563EB'
  surface-canvas: '#F8FAFC'
  status-completed: '#059669'
  status-completed-subtle: '#ECFDF5'
  status-in-progress: '#D97706'
  status-in-progress-subtle: '#FFFBEB'
  status-danger: '#DC2626'
  status-danger-subtle: '#FEF2F2'
  slate-text-primary: '#0F172A'
  slate-text-secondary: '#475569'
  slate-border: '#E2E8F0'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-lg:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  stat-display:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system embodies a modern, technical, and dependable aesthetic engineered for high-throughput automotive service environments. It balances executive oversight with workshop pragmatism, supporting multi-tenant automotive SaaS workflows across desktop management consoles and ruggedized tablet/mobile shop-floor interfaces.

### Personality & Emotional Resonance
- **Precision & Reliability:** Conveys engineering rigor, operational certainty, and transparency in billing and inventory.
- **Ergonomic Clarity:** Reduces cognitive fatigue in fast-paced bay operations with rapid scanning and touch-friendly target sizing.
- **Modern Industrial Utilitarianism:** Avoids decorative ornamentation in favor of purposeful information density, high data readability, and robust status visibility.

### Design Movement
The aesthetic synthesizes **Modern SaaS Enterprise** with **Tactile Functionalism**. Surfaces leverage crisp structural division, subtle tinted containers, and low-contrast borders rather than deep, disorienting shadows. Status indicators and data attributes carry deliberate visual weight to support glanceable status tracking in bright office lighting or variable workshop bays.

## Colors

The palette employs deep enterprise blues and crisp cool slates to build institutional trust and technical authority. Functional status indicators use vivid, accessible chromatic markers to immediately differentiate vehicle stages (Intake, Quoted, In-Progress, Quality Check, Invoiced, Completed).

### Hierarchy & Role Distribution
- **Primary (`#1E40AF`):** Anchors core actions, navigation headers, focused states, and definitive conversion triggers (e.g., Create Repair Order, Finalize Invoice).
- **Secondary (`#0284C7`):** Powers secondary interactive accents, active tabs, sub-navigation indicators, and informative callouts.
- **Brand Accent Blue (`#2563EB`):** Applied for interactive button hover states, interactive table links, and selection rings.
- **Neutral Canvas (`#F8FAFC`) & Slate Text (`#0F172A`):** Ensures WCAG AAA compliance across dense tabular datasets, service logs, and inventory picklists.
- **Functional States:**
  - `status-completed` (`#059669` / `#ECFDF5`): Ready for handoff, parts inspected, payment settled.
  - `status-in-progress` (`#D97706` / `#FFFBEB`): Technician actively working, parts pending allocation.
  - `status-danger` (`#DC2626` / `#FEF2F2`): Safety critical hold, declined repair, overdue invoice.

## Typography

Typography prioritizes scan speed, high-density clarity, and unambiguous character delineation across alphanumerics.

- **Headlines (Manrope):** Geometric structure with humanized terminals delivers modern authority across dashboard summaries, repair stages, and view titles.
- **Body & Controls (Inter):** Highly legible neutral grotesque engineered for UI density. Tall x-height and clear counters preserve legibility on greasy touchscreens and low-res displays.
- **Technical Readouts (JetBrains Mono):** Reserved for technical identifiers: Vehicle Identification Numbers (VIN), license plate values, OEM part SKUs, torque specs, and diagnostic trouble codes (DTC).

## Layout & Spacing

The layout model utilizes a fluid 12-column grid system anchored by strict horizontal and vertical keylines of 4px and 8px increments.

### Grid & Form Factors
- **Desktop (Manager & Billing Console, $\ge$ 1280px):** 12-column structure with 24px gutters (`gutter-desktop`) and 32px canvas margins (`margin-desktop`). Sidebar navigation remains fixed at 260px; right-hand sliding drawers (for live RO updates) span 420px.
- **Tablet (Shop Floor Station & Service Advisor, 768px – 1279px):** 8-column layout with 16px gutters and 24px margins. Navigation collapses to an icon-rail (64px) to maximize horizontal bay visibility.
- **Mobile (Technician Workstation, $\le$ 767px):** Single-column stack with 16px margins (`margin`). Form controls expand to touch-friendly heights ($\ge$ 48px) with sticky bottom execution bars for quick step sign-off.

## Elevation & Depth

This system avoids heavy drop shadows, which cause blurriness on industrial and mobile monitors. Instead, hierarchy is conveyed through **tonal container layering** and **low-contrast structural borders**.

### Layering Architecture
- **Level 0 (Base Canvas):** `#F8FAFC`. Background for entire app frame and dashboard view.
- **Level 1 (Structural Cards & Tables):** `#FFFFFF` paired with a solid 1px border (`#E2E8F0`). Gives flat, architectural containment.
- **Level 2 (Active Modals, Popovers & Floating Actions):** `#FFFFFF` with a 1px border (`#CBD5E1`) and a calibrated ambient shadow: `0 10px 15px -3px rgba(15, 23, 42, 0.06), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Drag States & Service Bay Cards):** Active drag elevation adds an ambient ring: `box-shadow: 0 0 0 2px #2563EB, 0 12px 24px -4px rgba(30, 64, 175, 0.12)`.

## Shapes

The interface employs a **Soft (`1`)** shape language. Tight, restrained corner radiuses emphasize technical precision and maximize inner data real estate for dense inventory matrices and tabular service records.

- **Inputs, Buttons, Badges:** `0.25rem` (4px). Clean, crisp corners reinforce deliberate, reliable actions.
- **Panels, Modals, Cards (`rounded-lg`):** `0.5rem` (8px). Softens modular container edges without looking playful or consumer-centric.
- **Notification Drawers & Popovers (`rounded-xl`):** `0.75rem` (12px). Distinct floating geometry for contextual alerts and checklist overlays.

## Components

### Buttons
- **Primary:** Solid `#1E40AF` fill with `#FFFFFF` text. Hover transitions to `#2563EB`. Active state shifts to `#1D4ED8`. Height: 40px (Desktop), 48px (Mobile technician view). Padding: 12px 20px. Font: `label-md`.
- **Secondary:** White background with 1px border in `#CBD5E1`, text in `#0F172A`. Hover: `#F1F5F9`.
- **Destructive:** Deep crimson (`#DC2626`) fill or ghost container with red text for scrap item/delete ticket actions.

### Status Chips & Badges
- **Structure:** 24px fixed height, inline-flex, 8px horizontal padding, 4px corner radius.
- **Variants:**
  - *In-Progress:* Text `#B45309`, background `#FFFBEB`, border 1px solid `#FDE68A`.
  - *Completed / Paid:* Text `#047857`, background `#ECFDF5`, border 1px solid `#A7F3D0`.
  - *Pending Parts / Alert:* Text `#B91C1C`, background `#FEF2F2`, border 1px solid `#FECACA`.
  - *VIN & Tech IDs:* Font `label-code`, text `#334155`, background `#F1F5F9`, border 1px solid `#E2E8F0`.

### Data Tables & Repair Order Lists
- **Header:** Sticky header with `#F1F5F9` background, 36px height, uppercase `label-md` tracking at 0.05em, text `#475569`.
- **Row Specs:** 48px standard row height (compact 40px for inventory tables). Alternating borders using `#E2E8F0`. Hover creates row tint `#F8FAFC`.

### Form Inputs & Selectors
- **Fields:** 40px height on desktop, 48px on mobile. White surface with 1px `#CBD5E1` border.
- **Focus:** Sharp 2px offset focus ring: `ring-2 ring-[#2563EB] ring-offset-1`.
- **Numeric & Barcode Fields:** Uses `label-code` for license plates, odometer readings, and part quantities.

### Checklists & Bay Inspection Cards
- **Vehicle Checklist Item:** 56px minimum touch targets on mobile. Large tap state with dual confirmation states (Pass [Green Check], Fail [Red Cross], Attention [Amber Flag]).
- **Cards:** Surface white, 1px border `#E2E8F0`, padding 16px. Header features repair order code (`label-code`), client name, vehicle model, and dynamic status chip.