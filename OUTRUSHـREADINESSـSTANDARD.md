# OUTRUSH READINESS STANDARD

**Asset:** EVOutrush.com
**Document class:** Category Artifact · Reference Specification
**Version:** 1.0
**Status:** Governing
**Steward:** Sohadot · agent@sohadot.com

---

## 1. Canonical Definition

> **Outrush Readiness is the actual-readiness layer for reverse energy flow from electric vehicles — the measured distance between declared capability and a flow that is permitted, supported, safe, directed, operated, and economically governed.**

This definition is canonical. It is reproduced verbatim wherever the asset speaks — site, repository, correspondence, and public signals. Variations are not permitted; paraphrase dilutes ownership.

## 2. Position Relative to Existing Language

The reverse-flow field already has established vocabulary: **V2G, V2H, V2B, V2L, V2X** describe *directions and interfaces* of vehicle energy export, and standards such as **ISO 15118** and **OCPP** govern *communication and protocol capability*.

The Outrush Readiness Standard does not compete with, replace, or re-define any of these. It sits **above** them and asks a question none of them answers:

> **V2X tells you what is possible. Outrush Readiness tells you what is ready.**

The industry's persistent gap is the distance between a bidirectional capability printed on a specification sheet and an energy flow that actually runs — lawfully, safely, and under settled economics — at a specific site, today. That distance has no established name and no established classification. This standard names and classifies it.

## 3. Scope and Non-Scope

**In scope.** A classification vocabulary (the O-Scale) and a dimensional checklist (the Six Readiness Dimensions) for describing the readiness state of a *specific, described configuration*: one vehicle or fleet, one export path, one site, one jurisdiction, at one point in time.

**Out of scope — permanently:**

- **No measurement.** The standard defines states; it does not measure, score, weight, or index anything. There is no composite number, no "Outrush Index," and no ranking.
- **No certification.** The standard does not certify, audit, approve, or endorse any product, vendor, site, or program. No party may claim to be "Outrush certified."
- **No verdicts on subjects.** Following the Artifact–Subject Separation principle: the standard classifies *configurations as described*, never companies, brands, or products as such. A classification is a statement about a described configuration, not a judgment of its owner.
- **No field data.** The standard cites no market statistics, adoption figures, or investment totals. Empirical claims about the EV market belong to their primary sources, not to this specification.

This boundary is what makes the standard durable. A specification that starts performing verdicts, scores, or market commentary contaminates its own authority.

## 4. The O-Scale — Six States of Outrush Readiness

Each level is defined by a **boundary condition** (what must be true to enter the level) and an explicit **non-implication** (what the level does *not* mean). A configuration holds the highest level whose boundary condition — and all lower boundary conditions — it satisfies.

### O0 · Declared Capability
- **Boundary condition:** Bidirectional or export capability is claimed for the vehicle and/or equipment by its manufacturer or specification sheet. Nothing beyond the claim is established.
- **Does not imply:** That any export path physically exists, is permitted, or has ever operated.

### O1 · Hardware Path
- **Boundary condition:** A complete physical export path exists — vehicle, connector, and export-capable supply equipment are present, compatible, and installed at the site.
- **Does not imply:** That exporting energy at this site is lawful or authorized.

### O2 · Permitted Flow
- **Boundary condition:** The authorization layer is settled — the interconnection permission, utility agreement, or regulatory allowance required for export at this site and jurisdiction exists and covers this configuration.
- **Does not imply:** That the destination, protections, or metering of the flow are defined.

### O3 · Directed Flow
- **Boundary condition:** The destination of the export is explicitly defined and configured — home, building, grid, emergency load, or fleet application — with the protection and metering arrangement that destination requires in place.
- **Does not imply:** That the flow is managed within battery, safety, and scheduling constraints over time.

### O4 · Operated Flow
- **Boundary condition:** The flow runs under active operational management — battery-impact limits (including warranty terms), scheduling, safety interlocks, and monitoring are defined and in force.
- **Does not imply:** That anyone is accountable for the economics or that the flow is compensated.

### O5 · Governed Flow
- **Boundary condition:** The flow operates under explicit contractual and economic governance — a contract or tariff defines compensation or settlement, and operational and economic risks are explicitly allocated between parties.
- **Non-implication note:** O5 is a state of a configuration at a point in time, not a permanent status. Any change in equipment, permission, destination, operation, or contract re-opens the classification.

**Reading of the scale:** O0–O1 are *capability* states. O2–O3 are *authorization and definition* states. O4–O5 are *operation and governance* states. The industry's marketing language lives almost entirely at O0; the industry's working reality is decided at O2 and above.

## 5. The Six Readiness Dimensions

The O-Scale answers "what state is this configuration in." The Six Dimensions answer "what must be examined to say so." Each dimension is a question, not a metric:

| # | Dimension | The question it asks |
|---|-----------|----------------------|
| D1 | **Permission** | Is this outward flow allowed — by regulator, utility, and site authority? |
| D2 | **Equipment** | Does the full charger/supply path support export, end to end? |
| D3 | **Battery** | Can the battery bear this flow — within warranty, degradation, and thermal terms? |
| D4 | **Destination** | Is the destination defined — home, building, grid, emergency load, fleet — with its required protections? |
| D5 | **Operation** | Is the flow operated — limits, schedules, interlocks, monitoring? |
| D6 | **Economics** | Are the economics and risks of the flow explicitly settled between parties? |

The dimensions carry **no weights and no scores**. They are examination headings. A classification statement cites the dimensions examined and the level concluded — nothing more.

## 6. Classification Statement Format

A conformant classification statement has exactly this form:

> *"Configuration [description], at [site/jurisdiction], as described on [date], classifies as **O[n]** under the Outrush Readiness Standard v1.0. Dimensions examined: [list]. Basis: [the described facts satisfying each boundary condition up to O(n)]."*

A statement that omits its basis, its date, or its configuration description is not conformant. A statement applied to a brand or product in general — rather than a described configuration — is not conformant.

## 7. Governance

- **Change control.** The canonical definition (§1), the O-Scale boundary conditions (§4), and the specification-only boundary (§3) may change only by explicit versioned amendment recorded in this document's history. No silent edits.
- **Precedence.** Where any public page, post, or summary of this asset conflicts with this document, this document governs.
- **Provenance.** The version history of this file constitutes the priority record of the category definition and the O-Scale.
- **Income boundary.** Any future commercial use of the asset must extend the authority of the specification; it must never contaminate it (no paid certifications, no sponsored classifications, no scored rankings for hire).

## 8. Amendment History

| Version | Date | Change |
|---------|------|--------|
| 1.0 | 2026-07-02 | Initial governing version. Canonical definition, O0–O5 scale, six dimensions, specification-only scope. |
