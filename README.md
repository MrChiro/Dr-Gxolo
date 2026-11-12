# Dr. Ingar Gxolo – Sports & Exercise Medicine Prototype

> **Art Direction**: "Elite Sports Medicine meets Modern Tech"  
> **Aesthetic Benchmark**: The athletic energy of Nike / Red Bull blended with the clinical precision of Apple Health.  
> **Physician**: Dr. Ingar Gxolo (MBChB UFS | HPCSA Registered)  
> **Location**: 6 Batting Road, Beacon Bay, East London, 5241  
> **Direct Contact**: 074 367 7401 | ingargxolo8@gmail.com  

---

## 🚀 Live Demo & Quick Start

### 1. Run the Local Prototype Server (Zero Dependencies)
A dedicated, lightweight local server is included in the project root:
```bash
node server.js
```
The prototype runs at **`http://127.0.0.1:3000`**.

### 2. Deploy to Vercel
The repository includes a ready-to-deploy configuration:
- Configured with `vercel.json` for 1-click zero-config deployment.
- Also includes the complete **Next.js App Router** structure in `src/app/` (`page.tsx`, `layout.tsx`, `globals.css`).

To deploy via Vercel CLI:
```bash
npx vercel
```

---

## 🎨 Design System & Visual Tokens

- **Primary Emerald/Teal**: `#0B4A3F` (Extracted from the practice flyer)
- **Deep Obsidian Backgrounds**: `#051411` & `#04120F`
- **Electric Lime / Neon Green Accent**: `#A3E635` & `#B7F347` (Signifying kinetic athletic energy & biological recovery)
- **Clinical White & Off-White**: `#FFFFFF` & `#F4F7F6`
- **Typography**: 
  - Geometric Athletic Headings: `Montserrat` & `Outfit`
  - High-Legibility Clinical Body: `Plus Jakarta Sans`

---

## ⚡ Core Sections & Interactive Features

1. **Preloader**:
   - Custom SVG electrocardiogram (ECG) heartbeat line drawing animation.
   - Practice monogram logo "DG | Sports & Exercise Medicine".
2. **Hero Section (Above the Fold)**:
   - Split layout with athletic typography and metrics ticker.
   - Cutout image of Dr. Ingar Gxolo walking with Springbok medical kit (`dr-gxolo-hero.png`), alpha-feathered to seamlessly blend into the obsidian gradient.
   - 3D interactive mouse perspective tilt.
   - Floating glass badges: *Concussion Certified* & *Pitchside Match Care*.
   - Magnetic primary CTA button with cursor attraction.
3. **Comprehensive Clinical Services**:
   - 8 Glassmorphism cards extracted from the flyer:
     1. Concussion Assessment & Management (SCAT5)
     2. Diagnosis & Treatment of Sports Injuries
     3. Exercise Prescription Advice
     4. Performance & Physical Health Optimisation
     5. Comprehensive Family Medicine
     6. General Check-ups & Vital Screenings
     7. Laboratory Testing (Blood Work)
     8. Family Planning & Contraception
   - Category filtering (Sports & Concussion, Performance, Family Medicine).
   - Click-to-open **Interactive Clinical Protocol Deep-Dive Modal** with symptom checklists and direct booking.
4. **Return-to-Play & Philosophy Section**:
   - Full-width background featuring the rugby pitchside action shot (`rugby-action.jpg`).
   - "Movement is Medicine" signature quote.
   - **Interactive 6-Stage Graduated Return-to-Play Protocol (GRTP)**:
     - Real-time tab switcher for Stages 1 to 6.
     - Live criteria, heart-rate exertion ceilings, and recovery telemetry bar.
5. **About Dr. Ingar Gxolo**:
   - Circular headshot (`dr-gxolo-headshot.png`) with animated rotating dashed pulse rings.
   - MBChB from the University of the Free State (UFS).
   - "Citizen - Continuous Improvement" philosophy card.
6. **Modern Facility & Telemetry Showcase**:
   - High-performance sports medicine clinic interior in East London.
   - Biomechanical & concussion telemetry dashboard.
7. **Contact, Location & Booking Form**:
   - Practice details, phone, email, and Google Maps directions link.
   - Interactive pre-launch booking form with validation.
   - Realistic confirmation state generating `#GX-xxxx` booking reference ticket and 1-click WhatsApp confirmation launcher.
8. **Footer & Compliance**:
   - Mandatory emergency medical disclaimer (*"In an emergency, call 10177"*).
