<b>NIST CSF 2.0 Assessment Tool</b><br>

<b>Feature Summary</b><br>
<b>Framework Coverage</b><br>
- Complete NIST Cybersecurity Framework 2.0 implementation<br>
- 6 Functions: Govern, Identify, Protect, Detect, Respond, Recover<br>
- 22 Categories and 106 Subcategories with official descriptions<br>
- 4-tier maturity model: Partial, Risk Informed, Repeatable, Adaptive<br>
<br><b>Assessment Wizard</b><br>
- Sidebar navigation across all 6 functions with completion counters<br>
- Expandable/collapsible category cards<br>
- Per-subcategory Current Tier and Target Tier selection (N/A through T4)<br>
- Notes/evidence field per subcategory<br>
- Real-time progress bar tracking overall completion<br>
<br>
<b>Intelligent Target Tier Profiles</b><br>
- 5 company sizes: Micro (<10), Small (10-249), Medium (250-999), Large (1K-5K), Enterprise (5K+)<br>
- 4 assessment scopes: Enterprise-wide, Business Unit, System/Application, Third Party<br>
- Auto-calculates recommended target tiers per category using base + scope adjustment matrix<br>
- Auto-applies when both size and scope are selected<br>
- Manual per-subcategory override with preservation across profile changes<br>
- "Reset to Recommended" to reapply defaults<br>
<br>
<b>Visualizations</b><br>
- Heat Map: Color-coded grid of all 106 subcategories by tier, with hover tooltips<br>
- Radar Chart: 6-axis spider chart comparing current scores vs target tiers<br>
- Dashboard: Summary score cards per function with bar charts and overall composite score<br>

<b>Gap Analysis</b><br>
- Identifies subcategories where current tier falls below target<br>
- Sorted by gap severity with color-coded badges (red/yellow/blue)<br>
- Shows function, current tier, target tier, gap size, and notes<br>
<br>
<b>Export & Persistence</b><br>
- Excel Export: 3-sheet workbook (Assessment Details, Summary Scores, Gap Analysis) with conditional formatting<br>
- JSON Save/Load: Full state persistence including company size, scope, manual overrides, and all responses<br>
<br>
<b>Technical</b><br>
- Standalone HTML - single file, no build step, no dependencies<br>
- Dark theme UI, responsive layout<br>
- Works offline in any modern browser<br>
