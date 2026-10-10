<div align="center">

<img src="counter-banner.svg" alt="Counter — Every unit accounted for" width="100%"/>

<br/>

<p align="center">
  <strong>A precision-built inventory management system.</strong>
  <br /><br />
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-C45B61?style=for-the-badge" alt="In development" />
  <img src="https://img.shields.io/badge/DOMAIN-INVENTORY%20MANAGEMENT-9299A5?style=for-the-badge" alt="Inventory management" />
  <img src="https://img.shields.io/badge/PRINCIPLE-ACCOUNTABILITY-76B69A?style=for-the-badge" alt="Accountability" />
</p>

<br/>

<a href="#overview">OVERVIEW</a>　<span style="color:#C45B61">/</span>　
<a href="#features">FEATURES</a>　<span style="color:#C45B61">/</span>　
<a href="#design">DESIGN</a>　<span style="color:#C45B61">/</span>　
<a href="#architecture">ARCHITECTURE</a>　<span style="color:#C45B61">/</span>　
<a href="#roadmap">ROADMAP</a>

</div>

---

<div align="center">

### <span style="color:#C45B61">01 /</span> KNOW WHAT YOU HAVE.
### <span style="color:#C45B61">02 /</span> KNOW WHAT CHANGED.

*Every unit accounted for. Every movement recorded.*

</div>

## <span style="color:#C45B61">01</span> &nbsp; OVERVIEW

**Counter is an inventory management system built around one principle: stock should be accounted for, not merely counted.**

Products enter, products leave, and quantities change. Counter provides a structured way to manage these operations, monitor stock, and trace the movements behind every balance.

Instead of treating inventory as editable numbers, Counter treats stock as a record of transactions.

<table>
<tr>
<td width="50%" valign="top">

<h3><span style="color:#C45B61">▤</span> THE INVENTORY</h3>

- Product and SKU records
- Categories and suppliers
- Quantities and reorder thresholds
- Search, sorting, and filtering
- Stock valuation

</td>
<td width="50%" valign="top">

<h3><span style="color:#76B69A">↔</span> THE LEDGER</h3>

- Stock receipts and issues
- Quantity adjustments
- Timestamped movement history
- Product-level audit trails
- Traceable corrections

</td>
</tr>
</table>

> [!NOTE]
> Counter is a work in progress. The features and technologies below describe the intended direction, not necessarily completed functionality.

## <span style="color:#C45B61">02</span> &nbsp; FEATURES

<table>
<tr>
<td width="42" align="center" valign="top"><span style="color:#C45B61">▤</span></td>
<td>

**01 — Product Registry**

Manage products, unique SKUs, categories, suppliers, costs, quantities, and reorder thresholds in one searchable catalogue.

</td>
</tr>
<tr>
<td align="center" valign="top"><span style="color:#C45B61">↔</span></td>
<td>

**02 — Stock Operations**

Record receipts, issues, and adjustments with quantities, timestamps, reasons, and optional references.

</td>
</tr>
<tr>
<td align="center" valign="top"><span style="color:#76B69A">≡</span></td>
<td>

**03 — Movement Ledger**

Inspect chronological stock changes and trace the history behind a product's current balance. Correct posted movements through additional records rather than silently rewriting history.

</td>
</tr>
<tr>
<td align="center" valign="top"><span style="color:#C45B61">!</span></td>
<td>

**04 — Stock Awareness**

Identify low-stock and out-of-stock products through clear, actionable indicators.

</td>
</tr>
<tr>
<td align="center" valign="top"><span style="color:#9299A5">⌕</span></td>
<td>

**05 — Search & Retrieval**

Find products quickly, combine filters, sort records, and move directly from a catalogue entry to its details and history.

</td>
</tr>
<tr>
<td align="center" valign="top"><span style="color:#76B69A">▦</span></td>
<td>

**06 — Overview & Reporting**

Surface useful metrics such as product counts, stock value, low-stock items, and recent movements, with future support for exports and movement summaries.

</td>
</tr>
</table>

## <span style="color:#C45B61">03</span> &nbsp; DESIGN IDENTITY

<div align="center">

**INDUSTRIAL RESTRAINT × ENGINEERED PRECISION**

</div>

Counter draws on Stripe's compositional discipline and Render's crisp geometry, paired with the interaction polish of premium software.

The interface is dark, structured, and deliberately restrained. Strong typography, aligned grids, fine borders, and carefully layered surfaces do the work — not excessive cards, gradients, or glow.

### The palette

<div align="center">

<table>
<tr>
<td align="center" width="25%">
<img src="https://placehold.co/220x80/0B0D10/0B0D10.png" width="140" alt="Carbon"/>
<br/><strong>CARBON</strong>
<br/><code>#0B0D10</code>
</td>
<td align="center" width="25%">
<img src="https://placehold.co/220x80/12151A/12151A.png" width="140" alt="Graphite"/>
<br/><strong>GRAPHITE</strong>
<br/><code>#12151A</code>
</td>
<td align="center" width="25%">
<img src="https://placehold.co/220x80/292E36/292E36.png" width="140" alt="Structure"/>
<br/><strong>STRUCTURE</strong>
<br/><code>#292E36</code>
</td>
<td align="center" width="25%">
<img src="https://placehold.co/220x80/ECEEF2/ECEEF2.png" width="140" alt="Precision white"/>
<br/><strong>PRECISION WHITE</strong>
<br/><code>#ECEEF2</code>
</td>
</tr>
<tr>
<td align="center">
<img src="https://placehold.co/220x80/C45B61/C45B61.png" width="140" alt="Velvet red"/>
<br/><strong>VELVET RED</strong>
<br/><code>#C45B61</code>
</td>
<td align="center">
<img src="https://placehold.co/220x80/9299A5/9299A5.png" width="140" alt="Titanium"/>
<br/><strong>TITANIUM</strong>
<br/><code>#9299A5</code>
</td>
<td align="center">
<img src="https://placehold.co/220x80/76B69A/76B69A.png" width="140" alt="Operational green"/>
<br/><strong>OPERATIONAL GREEN</strong>
<br/><code>#76B69A</code>
</td>
<td align="center">
<img src="https://placehold.co/220x80/191D23/191D23.png" width="140" alt="Raised graphite"/>
<br/><strong>RAISED GRAPHITE</strong>
<br/><code>#191D23</code>
</td>
</tr>
</table>

</div>

### Design principles

- <span style="color:#C45B61">**RED**</span> marks primary actions and important emphasis.
- <span style="color:#76B69A">**GREEN**</span> communicates successful operations.
- **TONAL SURFACES** establish hierarchy without visual clutter.
- **PRECISE MOTION** confirms actions and clarifies state changes.
- **FEEDBACK FIRST** — loading, validation, empty, success, and error states are part of the design.

The goal is to make every interaction feel deliberate without making animation the point of the interface.

## <span style="color:#C45B61">04</span> &nbsp; SYSTEM PRINCIPLES

<div align="center">

### THE NUMBER IS THE RESULT. THE MOVEMENTS ARE THE RECORD.

</div>

<table>
<tr>
<td width="50%" valign="top">

**<span style="color:#76B69A">01 / TRACEABILITY</span>**

Every stock change has a recorded reason and history.

</td>
<td width="50%" valign="top">

**<span style="color:#76B69A">02 / CONSISTENCY</span>**

Database transactions keep related operations together.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**<span style="color:#76B69A">03 / INTEGRITY</span>**

Validation and constraints help prevent invalid inventory states.

</td>
<td width="50%" valign="top">

**<span style="color:#76B69A">04 / CLARITY</span>**

Important quantities, warnings, and actions remain easy to find.

</td>
</tr>
</table>

### Inventory in practice

| Movement | Change | Balance |
|:--|--:|--:|
| Opening stock | +50 | 50 |
| Supplier receipt | +20 | 70 |
| Stock issued | −8 | 62 |
| Physical-count adjustment | −2 | 60 |

The resulting balance is **60 units**. The movement ledger explains how it got there.

## <span style="color:#C45B61">05</span> &nbsp; ARCHITECTURE

Counter is planned as a full-stack application with distinct presentation, application, and data layers.

<div align="center">

<table>
<tr>
<td align="center" width="33%">

<strong>01 / PRESENTATION</strong>

<br/>

Interface · Forms · Tables

</td>
<td align="center" width="33%">

<strong>02 / APPLICATION</strong>

<br/>

Validation · Stock logic

</td>
<td align="center" width="33%">

<strong>03 / PERSISTENCE</strong>

<br/>

Database · Transactions

</td>
</tr>
</table>

</div>

### Core data model

- **Products** — names, SKUs, costs, categories, suppliers, and reorder levels.
- **Categories** — product grouping.
- **Suppliers** — contact details and product relationships.
- **Stock movements** — type, quantity, timestamp, reason, and reference.
- **Users / workspaces** — potential future support for authenticated, multi-user access.

Stock balances should be derived from movements or maintained transactionally alongside them, never allowed to drift independently.

### Planned technology direction

| Layer | Technology |
|:--|:--|
| Frontend | React + TypeScript |
| Styling | SCSS modules or Tailwind CSS |
| Backend | FastAPI or NestJS |
| Database | PostgreSQL |
| Quality | Validation, database constraints, automated tests |

*These are planned choices and may change during development.*

## <span style="color:#C45B61">06</span> &nbsp; ROADMAP

<div align="center">

<span style="color:#C45B61">01 FOUNDATION</span>　→　
<span style="color:#9299A5">02 OPERATIONS</span>　→　
<span style="color:#76B69A">03 VISIBILITY</span>　→　
<span style="color:#9299A5">04 REFINEMENT</span>

</div>

- [ ] **Foundation** — Project structure, data model, validation, and design system.
- [ ] **Product Registry** — Product, category, and supplier management.
- [ ] **Stock Operations** — Receipts, issues, adjustments, and movement ledger.
- [ ] **Inventory Overview** — Live metrics and stock alerts.
- [ ] **Reporting** — Valuation, movement summaries, and CSV import/export.
- [ ] **Quality & Deployment** — Tests, responsive layouts, accessibility, and deployment.
- [ ] **Refinement** — Interaction polish and workflow improvements.

The priority is to establish reliable inventory operations before expanding the feature set.

## <span style="color:#C45B61">07</span> &nbsp; PHILOSOPHY

<div align="center">

### PRECISION IS NOT AESTHETIC. IT IS BEHAVIOUR.

</div>

Counter is a personal project exploring practical full-stack engineering and deliberate interface design.

Its scope is intentionally grounded: products need to be recorded, quantities need to be accurate, and changes need to be understandable.

The ambition is not to make inventory management something it isn't. It is to build an ordinary, useful application with enough care that its data model, engineering, interface, and interactions feel like parts of the same system.

**A straightforward tool, engineered with intent.**

---

<div align="center">

<img src="counter-banner.svg" alt="Counter — Every unit accounted for" width="68%"/>

<br/><br/>

<span style="color:#C45B61">▤</span> **COUNTER** <span style="color:#9299A5">/</span> **SYSTEM STATUS: IN DEVELOPMENT**

<sub>INVENTORY MANAGEMENT · PRECISION ENGINEERING · WORK IN PROGRESS</sub>

</div>
