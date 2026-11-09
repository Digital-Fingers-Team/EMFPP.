# EMFPP — GUARD Prototype (Predictive Maintenance Safety Lab)
### نموذج الحارس — معمل أمان الصيانة التنبؤية

Interactive evaluation prototype for **GUARD** (Guaranteed Uncertainty-Aware Risk Decision), featuring conformal prediction-based alert thresholds for predictive maintenance and run-to-failure telemetry.

## Features
- **Bilingual Interface**: Seamless instant toggle between Arabic (RTL) and English (LTR).
- **Interactive Labs**:
  1. **GUARD Calibration Lab**: Conformal threshold calibration under allowable miss rate $\alpha$ and failure count $n$.
  2. **Fleet Shift Stress Test**: Simulates covariate/concept drift and evaluates recalibration with target fleet data.
  3. **Inspection Budget Simulator**: Evaluates failure recall vs. false alarms constrained by inspection capacity.
  4. **Research Findings Summary**: Benchmark comparison against SMART rules and C-MAPSS / Backblaze studies.

## Quick Start
Open `low_error_prototype/index.html` directly in any modern browser, or run a local server:
```bash
cd low_error_prototype
python3 -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).

