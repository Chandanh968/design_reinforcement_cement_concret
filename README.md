# RCC Beam Design Studio — Activity 1

## Scope
Preliminary design of a simply supported, singly reinforced rectangular RCC beam under uniformly distributed gravity loads. Uses M20/M25/M30 concrete and Fe415/Fe500 steel. It is an academic tool, not a construction drawing or professional certification.

## Run

Install Node.js 20+, then run `npm install`, `npm run workbook`, and `npm start`. Open the shown local URL. Run `npm run build` for a production check.

## Inputs

Span (m); beam width/depth and cover (mm); additional dead, finish and live loads (kN/m); concrete strength and steel yield strength (N/mm²); main-bar diameter (mm). Values must be positive; unsupported grades and a section beyond singly-reinforced capacity are rejected.

## Outputs

Factored UDL, moment, effective depth, required/provided tensile steel, basic development length, a basic span/depth check and pass/fail status. Verify shear, stirrups, deflection modification factors, development length, anchorage and detailing manually under IS 456 before submission.

## Workbook

`deliverables/RCC_Beam_Design.xlsx` has Inputs (yellow), Calculations (formula cells) and Outputs. Open it in desktop Excel to recalculate and protect formulas before submission. Clauses shown are study references: IS 456:2000 Clauses 23.2, 26.5.1.1, 26.2.1, Table 19; IS 875 Parts 1 and 2.
