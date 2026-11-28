# Meaning Ledger — sapiensOS · Constitutio Intermundia v1.22

Required by 0.C Custos Sensus, clause 2. Release: v1.22 (draft prepared 28.11.2026; three additive clarifying sentences added 28.11.2026 17:00; Terran explicit yes 17:01; full-scope yes 28.11.2026 17:11 to publish the complete draft, all 92 changes, plus those three sentences). Tag: `v1.22`. Canonical `sapiensos.md` `SHA-256: 477d3750ee9123022b3a3de451f954f71545b48e6caab294222bf06f71f9281b`. Base: v1.21 (`fd24b17`, 27.11.2026, `SHA-256: e3dc5c6da87c0b724d6390912bf93aa81ea6c59b4818065af2939e2d9682af55`).

## Drafters (named, as 0.C requires)
| Role | Name | Tool / make and version | Date |
|---|---|---|---|
| Commissioner / Approver | Terran (human-terran) | — | 28.11.2026 16:22 (draft commissioned); 28.11.2026 17:01 (explicit yes: three additive clarifying sentences); 28.11.2026 17:11 (full-scope yes: publish the complete Gemini draft, all 92 changes / 59 rooms, plus the three sentences) |
| Text & branch drafter — draft PR only | Gemini (Antigravity) | Gemini (Antigravity) | 28.11.2026 16:30 |
| Auditor of the draft PR | Radu IT | Grok Bot; audit PASS on scope approved by Terran (PR36-AUDIT.md) | 28.11.2026 17:13 |
| Mechanical insertion and commit of three sentences authored verbatim by Terran (no wording drafted by the inserter) | Alexandru (Code Guardian bot) | Grok Bot | 28.11.2026 17:00 |
| Publisher (merge, tag, release) | human-terran (executed by Radu IT after Terran's explicit yes and final checks) | _pending_ | _DD.MM.YYYY HH:MM_ |

## Second Reader (independent; not a drafter, not a machine of the same make as any drafter; at least one named human)
| Second Reader | Human or machine | Result | Date |
|---|---|---|---|
| Terran (human-terran) | human | pass (explicit yes 28.11.2026 17:01 + full-scope yes 17:11, via Grok Bot chat) | 28.11.2026 17:13 |

## Meaning check (0.C Custos Sensus, OLD = v1.21, NEW = v1.22)
- **Lost rooms:** none (`0`).
- **Renamed room titles or Glossary terms:** none (`0`).
- **Lost LEX tags:** none (`0`).
- **`0.C Custos Sensus` (`L90–112`, `LEX 61PR–66PR`):** `100%` byte-for-byte unchanged.
- **Rooms:** `305` → `311` (`6` new Kernel rooms: `0.D Ordo Canonis`, `II.35 Incrementum Demes`, `III.25 Mensura Potentiae`, `IV.30 Catena Interstellaris`, `VII.10j Ordo Terminalis`, `VIII.33 Regimen Insulae`; `8` existing rooms elevated `Module → Kernel`: `II.13`, `III.4`, `IV.26`, `IV.29`, `VII.3`, `VII.29`, `VII.47`, `VIII.23`). Kernel `83` → `97`, Module `222` → `214`.
- **LEX lines:** `842` → `868` (unique tags `836` → `862`).
- **Glossary cells:** `226` → `233` (`7` added, `0` removed).
- **Words:** `78,878` → `83,153` (`Bytes: 502,093` → `531,611`; `SHA-256: 477d3750ee9123022b3a3de451f954f71545b48e6caab294222bf06f71f9281b`).

### Additive clarifications (28.11.2026 17:00, Terran's explicit yes)
- `VII.10j Ordo Terminalis`, end of clause 5: one sentence (renewal under the bridge expires at once on withdrawal, failed milestone, or no seal activity for one short clock).
- `VIII.33 Regimen Insulae`, end of clause 1: one sentence (quorum collapses to `VIII.14 Ultimus` when `L_surv < 2` or `m_surv = 1`).
- `III.25 Mensura Potentiae`, end of clause 1: one sentence (`Ed(t)` re-computed on every signed meter interval reporting plant status; a stale `Ed(t)` is void).
- Three lines were extended in place; `0` lines removed, `0` words removed. `0.C Custos Sensus` and the binary-sex lock (`Sex is binary forever: male (XY) and female (XX)`, `LEX 64PR`) are byte-identical before and after; `SHA-256` of the `0.C` room: `1efe1258b6bf2deaf0a3f6b86dc5135bdf7b1178d082b9b3e85358f632014a91`.

### Flagged removals and their answers
| Room | Removed text (v1.21) | Coverage | Answer |
|---|---|---|---|
| Version line (line 3) | `**Public Release v1.21**` | release tag | Updated to `**Public Release v1.22**`. Zero body sentences in any room fall below `0.50` token coverage. |

### Before/after meaning, by change
The complete room-by-room table of before/after texts and engineering reasons is in [`CHANGES-v1.22.md`](CHANGES-v1.22.md) (`92` entries):
- **New structural `KERNEL` rooms (`6`):** `0.D Ordo Canonis` (meta-precedence above `I.V`, pre-Entityhood `VII.53` audit verification, `I.12` Module-sunset ledger rule), `II.35 Incrementum Demes` (singleton `Node Zero` vault-diversity deme credit when `0` peers exist), `III.25 Mensura Potentiae` (pins `Ed(t)` to online dual-method capacity & `N × BOT_local × k_design` closing the `3.157×` `Ω*` inflation exploit; floors `BOT_local ≥ BOT_earth` in shielded bunkers; anchors offline mint to pre-outage baseline; bounds `VCI` `d_t ≥ k_min`), `IV.30 Catena Interstellaris` (relativistic star-system broadcast chains, `(M-1) ≥ N` Oracle co-signing on single-root revocation, 500-year clean-room AI/firmware, active `V.21`/`VIII.32` vault non-publication), `VII.10j Ordo Terminalis` (`2h` prima-facie transducer materiality check + `P3a` pause across live `7.10c`/`Nefas`, `Patronus Causae` vs `VII.58` seat-payers, `8h` concurrent `VI.12 Vindicta` window, `P7–P20` Kernel bounds, `900d` `Aequitas` Root bridge), and `VIII.33 Regimen Insulae` (monotone shard-boot quorum closing the `[140, 280]` Pigeonhole trap & `2–6` survivor deadlock, `2-of-3` threshold-unique VRF + `Insula` Sortition, Day-811 sealed-habitat containment of all `≥99.9%` `7.10c` and violent/sexual `Nefas` offenders, threat-silent `Ultimus` beacon, trailing `1-CEC` per-specialty `Furca` training bond).
- **Kernel elevations (`8`) & `I.9` closure sync:** `II.13`, `III.4`, `IV.26`, `IV.29`, `VII.3`, `VII.29`, `VII.47`, `VIII.23`, plus all twelve Axioms and `P7–P20` bounds added to `I.9`.
- **In-place mathematical, Rank-2 Glossary, Rank-6 table & three-layer harmonizations (`82`):** `B. Glossary` (`Neutralization`, `Nefas`, `Short clock`, `Planetary Cycle Vector`, `Vector Breach`, `Compressed Capital Docket`, `Patronus`, `BOT` floor, `7` new cells), `B.1 Usus`, `A. Ordo`, `I.IV`, `I.VIII`, `I.13`, `I.15`, `II.1`, `II.29` (`LEX 114CR`), `III.1`–`III.6`, `IV.2`, `IV.5`, `IV.10`, `IV.22`, `IV.26`, `IV.29`, `V.14`, `V.16`, `V.21`, `V.27`, `V.32`, `V.44`, `VI.2`, `VI.6`, `VI.12`, `VI.15`, `VI.23`, `VII.1`, `VII.3`, `VII.7`–`VII.10g`, `VII.11`, `VII.14`, `VII.16` (`H_maint = 0` when `S ≤ 0`), `VII.25`, `VII.29`, `VII.37`, `VII.45` (`LEX 208AX`), `VII.47`, `VII.52`, `VII.56`, `VII.59`, `VII.63`, `VII.66`, `VIII.1`, `VIII.5`, `VIII.14`, `VIII.20`, `VIII.23`, `VIII.26`, and `IX.1`.
- **Ideological vocabulary check:** Zero ideological, activist, DEI, or woke wording added; zero locked biological, sex, family, or speech rules altered.
