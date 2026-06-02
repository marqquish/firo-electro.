---
name: Industrial Precision
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#43474f'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#415f8f'
  primary: '#001430'
  on-primary: '#ffffff'
  primary-container: '#002855'
  on-primary-container: '#7490c3'
  inverse-primary: '#aac7fd'
  secondary: '#a04100'
  on-secondary: '#ffffff'
  secondary-container: '#fe6b00'
  on-secondary-container: '#572000'
  tertiary: '#111518'
  on-tertiary: '#ffffff'
  tertiary-container: '#26292c'
  on-tertiary-container: '#8d9094'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aac7fd'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#284775'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb693'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#e0e2e6'
  tertiary-fixed-dim: '#c4c7ca'
  on-tertiary-fixed: '#191c1f'
  on-tertiary-fixed-variant: '#44474a'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for high-stakes reliability and immediate action. It caters to homeowners and facility managers who require urgent, expert intervention for critical infrastructure like HVAC and electrical systems. 

The visual style is **Corporate / Modern** with a lean toward industrial efficiency. It prioritizes clarity over decoration, using high-contrast elements to guide the user toward contact and service scheduling. The aesthetic evokes the feeling of a well-organized toolkit: every element has a purpose, is easy to find, and functions perfectly under pressure. The interface must feel established, authoritative, and fast.

## Colors

The palette is built on the tension between stability and urgency. 

*   **Primary (Deep Dark Blue):** Used for headers, footers, and primary navigation to establish a foundation of professional trust and institutional knowledge.
*   **Secondary (Electric Orange):** Reserved strictly for "Call to Action" (CTA) elements, urgent alerts, and status indicators. This color represents the "Heat" and "Energy" aspects of the business while demanding immediate visual attention.
*   **Neutrals:** A range of clean whites and cool grays ensure the interface feels clinical and modern. Surface backgrounds use a very slight cool tint (#F8FAFC) to reduce eye strain while maintaining a "clean" feel.

## Typography

Typography is used as a hierarchy tool. **Montserrat** provides an authoritative, geometric weight to headlines, suggesting the strength of industrial components. **Hanken Grotesk** is used for all functional text and body copy; its contemporary grotesque proportions offer exceptional legibility in data-heavy service lists or technical descriptions. 

Uppercase labels are used for categories and service statuses to increase scannability. For mobile views, headline sizes are aggressively scaled down to ensure that "Book Now" prompts and phone numbers remain above the fold.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain a contained, professional appearance, transitioning to a fluid model for mobile devices. 

*   **Desktop:** 12-column grid with a 1200px max-width.
*   **Tablet:** 8-column grid with 24px gutters.
*   **Mobile:** 4-column grid with 16px gutters and margins.

Spacing follows a strict 8px rhythmic scale. Generous vertical padding (lg and xl units) is used between service sections to prevent the UI from feeling cluttered, which is vital when a user is in a "stress state" looking for a repair service.

## Elevation & Depth

Depth is used to signify "interactivity" and "importance." The design system employs **Ambient Shadows** to create a tiered hierarchy:

1.  **Level 0 (Flat):** Page backgrounds and decorative containers.
2.  **Level 1 (Soft Border):** Standard input fields and inactive cards. Uses a 1px border (#E5E7EB) instead of a shadow.
3.  **Level 2 (Interaction):** Hover states and navigation bars. A subtle shadow with a slight Blue tint (10% opacity) helps elements feel grounded.
4.  **Level 3 (Priority):** Urgent service cards and "Active" repair requests. These use deep, diffused shadows (20px blur, 10% opacity) to "lift" the card toward the user, making it the most touch-friendly element on the screen.

## Shapes

The shape language is **Soft (Level 1)**. 

A 0.25rem (4px) base radius is applied to small components like checkboxes and small buttons. Larger components like service cards and primary CTA buttons use a 0.5rem (8px) radius. This provides a subtle modern touch without sacrificing the "serious" and "technical" nature of the brand. Fully rounded shapes (pills) are avoided to maintain the structured, industrial aesthetic, except for status badges.

## Components

### Buttons
*   **Primary CTA:** Electric Orange background with White text. Bold weight. Used for "Call Now" or "Emergency Repair."
*   **Secondary:** Deep Dark Blue background with White text. Used for "View Services" or "Request Quote."
*   **Ghost:** Transparent background with Primary Blue border and text. Used for secondary navigation.

### Cards
Service cards feature a top-aligned icon (Electric Orange). The card container uses a white background, a Level 2 shadow, and an 8px corner radius. Headlines within cards must be Montserrat SemiBold.

### Input Fields
Inputs are structured with a 1px gray border. On focus, the border shifts to Deep Dark Blue with a 2px outer glow. Labels are always visible above the field in Hanken Grotesk Medium.

### Service Icons
Icons should be stroke-based (2px weight) to match the technical feel of the typography. They are always rendered in Electric Orange to act as visual anchors for the different service lines (Electricity, Water, Air).

### Status Chips
Small, rounded-pill indicators for "Available Now," "In Progress," or "Fixed." These use low-saturation background tints with high-saturation text for maximum legibility without distracting from the main CTA.