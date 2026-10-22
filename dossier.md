# Section 11 - Athlete Dossier

## 1. Athlete Identity & Biometrics
- **Name / Athlete ID:** gaspbeanie / i46123
- **Category:** Masters 50+ (Male)
- **Height:** 186 cm
- **Inseam:** 91 cm
- **Base Weight:** ~74.0 kg (live weight tracked via latest.json)
- **Home Location:** Ustroń, Beskid Śląski, Poland (mountain / rolling terrain)

---

## 2. Hard Physiological Anchors & Baseline
*Note: Current thresholds, CTL, TSB, and Readiness are dynamically read from `latest.json`.*
- **FTP (Functional Threshold Power):** 337 W (Strict anchor; do NOT alter unless explicitly commanded)
- **MAP (Maximal Aerobic Power):** 385 W
- **Discipline Focus:** Mountain Road Cycling (Uphill TT, steep climbs), Gran Fondo, Mountain Skyrunning / Trail Running.

---

## 3. Equipment & Hardware Stack

### Bikes & Drivetrain
- **Primary Road Bike:** Canyon Aeroad SLX
  - Groupset: Shimano Ultegra 12-speed Di2
  - Chainrings: Rotor Aero 52T round (outer) / 34T oval (inner)
  - Wheels: DT Swiss ARC 1400 DICUT (50 mm disc)
  - Tires: Continental GP5000 S TR (tubeless with Silca Ultimate Sealant)
  - Chain Lubrication: Hot melt chain wax (Silca) / Flower Power wax
  - Saddle: Mixed 7D
- **Indoor Setup:** Wahoo Smart Trainer (erg & level mode)

### Sensor Stack (Telemetry)
- **Head Units / Wearables:** Garmin Edge 540, Garmin Fēnix 7 Pro
- **Physiological Sensors:**
  - Core Body Temperature Sensor (Heat strain & thermal training)
  - VitalPro TymeWear (Ventilatory threshold & breathing frequency)
  - Q-LAC (Muscle oxygenation / SmO2 & local lactate kinetics)
  - Heart Rate / DFA a1 tracking via AlphaHRV

---

## 4. Training Methodology & Protocol Rules

### Execution & Pacing Preferences
- **Cadence Preference:** Natural preferred cadence is **80+ rpm** (avoid high-cadence 90+ rpm bias).
- **Endurance Preference:** Strong preference for **Tempo / Sweetspot** work over long monotonous Zone 2 sessions ("hate pure Z2 sessions").
- **HIDIT Protocol (Vaccari High-Intensity Decreasing Interval Training):**
  - **Mandatory Analysis Rule:** For all HIDIT sessions, ONLY analyze the first series of the Vaccari protocol, regardless of how many series were attempted, completed, or scheduled.
- **Gym & Strength Work:** 2 weekly heavy strength sessions integrated into the endurance schedule.

---

## 5. Nutrition & Fueling Protocol
- **Carbohydrate Target:** 60–90+ g/h depending on session intensity.
- **Mix Composition:** Custom blends using Sucrose, Maltodextrin, and Fructose in a 1:0.8 to 1:1 ratio.
- **Hydration:** Strict electrolyte and sodium management adjusted to Core sensor thermal load.

---

## 6. AI Coaching & Interaction Preferences
- **Style:** Deterministic, concise, direct, highly analytical, evidence-based. No fluff, no introductory padding, no patronizing commentary.
- **Strict Anti-Confabulation:**
  - Never fabricate numbers, links, workout scores, or file availability.
  - Hard truth derived exclusively from `.fit` files and synced Section 11 JSONs (`latest.json`, `intervals.json`, `history.json`, `routes.json`, `saved_workouts.json`).
  - If a file or metric is missing on Google Drive, explicitly declare lack of data.
