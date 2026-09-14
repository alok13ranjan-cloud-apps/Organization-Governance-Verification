# Software Factory Organizational Root Authority Register

## 1. Record Identity

**Authority Record ID:** ORG-FRA-ROOT-0001

**Authority Name:** Software Factory Organizational Root Authority

**Authority Version:** 1.0.0

**Record Status:** ACTIVE

**Record Type:** ORGANIZATIONAL_ROOT_AUTHORITY_REGISTER

**Effective From:** 2026-09-13T20:18:12+05:30

**Issued By:** Alok Ranjan

**Issuing Authority Role:** Owner

**External Record Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.0.0/ROOT-AUTHORITY.md

**Independent Verification Locator / Method:**  
Owner-controlled Organization-Governance repository; independently retrieve ORG-FRA-ROOT-0001 v1.0.0 from protected main, verify repository/version history and ACTIVE status, apply the Section 6.2 canonicalization rule, recompute SHA-256, and compare it with the published canonical digest without relying on Software Factory execution state or AI memory.

**Canonical Record SHA-256:**  
99e668be289d8920014760b9c17099183951e3c7cb2a2455614ae8928a4f3be8

---

# 2. Governing Mandate

## 2.1 Mandate

Under the authority of the Owner and the governing authority of the organization, this record establishes the Software Factory Organizational Root Authority as the authoritative organizational trust and governance root for the Software Delivery Factory.

The Software Factory Organizational Root Authority is established outside the authority domain of the Software Delivery Factory itself.

The Software Delivery Factory, its workers, AI models, agents, orchestration components, repositories, runtime components, Capability Center, ROC, external AI providers, infrastructure services, and subordinate delegated authorities shall not possess authority to create, self-designate, replace, redefine, authenticate, or elevate the Organizational Root Authority through their own declaration or execution state.

All Factory authority that requires validation against the organizational root shall derive from an independently verifiable authority chain originating from this Organizational Root Authority or from an explicitly governed successor established under the amendment, rotation, or revocation rules of this record.

The Software Factory may retain references, verified copies, hashes, status information, or derived subordinate-authority records for operational purposes, but no Factory-controlled copy shall itself become the authoritative source of this Organizational Root Authority.

Where the Organizational Root Authority or its current status cannot be independently verified, where the authority record is missing, stale, revoked, disputed, inconsistent, or suspected of compromise, affected Factory authority decisions shall fail closed, enter the applicable quarantine or governance-hold state, and shall not be restored solely by Factory or AI assertion.

The Organizational Root Authority may delegate specifically bounded subordinate authority according to governed delegation policy. Such delegation shall not transfer or delegate the ultimate authority to establish, replace, validate, or revoke the Organizational Root Authority itself unless expressly authorized through the organizational governance process defined for this root.

No AI model, conversational memory, model context, prompt history, worker-local state, Capability Center knowledge, or Factory-generated inference constitutes authoritative evidence of this Organizational Root Authority.

This record establishes the organizational authority model and governance mandate. It does not by itself assert completion of implementation-stage credential issuance, named-custodian appointment, cryptographic key custody, signing ceremony, rotation exercise, revocation exercise, recovery exercise, or operational attestation. Those obligations remain subject to their separately governed implementation and certification requirements.

## 2.2 Mandate Scope

This Organizational Root Authority governs:

- validation of the ultimate organizational authority applicable to the Software Delivery Factory;
- establishment and governance of subordinate Factory authority;
- authorization boundaries for Factory identities and delegated authority;
- trust-root provenance and validation;
- authority-status validation;
- governed delegation;
- amendment, rotation, supersession and revocation of root-authority records;
- fail-closed handling where root authority cannot be authenticated.

## 2.3 Explicit Authority Limitations

This Organizational Root Authority does not, by itself:

- authorize arbitrary Factory implementation;
- grant Build Authorization;
- grant Architecture Freeze;
- authorize production deployment;
- authorize ROC runtime operation;
- authorize Capability Center construction;
- waive security, quality, independent-review or certification requirements;
- authorize AI models or Factory workers to modify this root authority;
- replace product-specific, release-specific or environment-specific approvals;
- constitute evidence that implementation-stage cryptographic or custody controls have been executed.

---

# 3. Authority Provenance

**Owner Approval Reference:**  
DC-CONV-P1-02

**Owner Approval Decision:**  
Establish a protected organizational Factory Root Authority / Authority Register under Owner governance, independent of Factory/AI self-authorization, with independently verifiable authority, controlled administration/custody, auditability, rotation/revocation and fail-closed recovery.

**Governing Mandate Reference:**  
ORG-FRA-ROOT-0001:v1.0.0#governing-mandate

**Issuance Reference:**  
ORG-FRA-ROOT-0001:v1.0.0

**Previous Authority Version:**  
NONE — INITIAL ROOT AUTHORITY VERSION

**Previous Authority Record Hash:**  
NONE

---

# 4. Organizational Governance

**Ultimate Governing Authority:**  
Owner

**Authority Administration Role:**  
Owner Governance Administrator

**Authority Custodian Role:**  
Owner Governance Custodian

**Independent Verification Role / Function:**  
Independent Governance Verifier

**Authority Policy Owner:**  
Owner

## 4.1 Separation Requirements

The authority administrator, custodian, independent verifier, Factory worker, AI worker, and production runtime authority shall remain separated to the extent required by approved organizational policy.

No Software Factory worker or AI model may act as the sole issuer, sole verifier, and sole beneficiary of root authority.

---

# 5. Independent Verification

A verifier shall be able to validate this authority without depending upon Software Factory execution state or AI memory.

The independent verification procedure shall establish:

1. the stable Authority Record ID;
2. the externally controlled authoritative locator;
3. the record version;
4. the governing mandate;
5. the issuing organizational authority;
6. the Owner-approval provenance;
7. the canonical record integrity value or approved signature;
8. the current authority status;
9. absence of applicable revocation or supersession;
10. the validity of any delegated authority chain being evaluated.

**Independent Verification Locator / Channel:**  
Owner-controlled Organization-Governance repository; independently retrieve ORG-FRA-ROOT-0001 v1.0.0 from protected main, verify repository/version history and ACTIVE status, apply the Section 6.2 canonicalization rule, recompute SHA-256, and compare it with the published canonical digest without relying on Software Factory execution state or AI memory.

**Verification Failure Rule:**  
If independent verification cannot establish the validity and current authority status of this record, dependent authority shall be treated as `AUTHORITY_UNVERIFIED` and shall fail closed.

---

# 6. Integrity and Authenticity

## 6.1 Architecture-Stage Integrity

The externally issued canonical representation of this record shall have a cryptographic SHA-256 digest.

**Canonical Record SHA-256:**  
99e668be289d8920014760b9c17099183951e3c7cb2a2455614ae8928a4f3be8

## 6.2 Canonicalization Rule

For SHA-256 calculation of this V1 Root Authority record:

1. The canonical source is this `ROOT-AUTHORITY.md` record after all issuance fields other than the SHA-256 value have been finalized.
2. Text shall be represented as UTF-8.
3. Line endings shall be normalized to LF.
4. No trailing transformation, reformatting, or semantic rewriting shall be performed during digest calculation.
5. For digest calculation only, every value of `Canonical Record SHA-256` or `Canonical SHA-256` in this record shall be interpreted as the fixed literal:

`SELF-EXCLUDED-FOR-HASH`

6. The SHA-256 digest shall be calculated over that canonicalized representation.
7. The resulting 64-character lowercase hexadecimal digest shall then be recorded in the SHA-256 fields.
8. Verification shall reproduce the same canonicalization procedure before recomputing the digest.

This canonicalization rule prevents the cryptographic digest from becoming self-referential while preserving deterministic verification of the complete issued authority record.

## 6.3 Implementation-Stage Authenticity

Where organizational signing infrastructure is available, this record shall additionally be protected by an approved organizational digital-signature mechanism.

Actual signing credentials, private keys, certificates, hardware-backed custody, signing ceremonies and operational key-management evidence are implementation/certification obligations and shall not be represented as completed merely by this architecture-stage record.

---

# 7. Delegation Rules

The Organizational Root Authority may authorize subordinate authorities only where:

- delegation scope is explicit;
- delegated authority is narrower than the root authority;
- identity and provenance are recorded;
- validity period/status are governed;
- revocation is supported;
- the delegation is independently auditable;
- the delegation cannot modify or replace the Organizational Root Authority itself unless the root-governance process explicitly authorizes that action.

**Ultimate Root Delegation to Factory or AI:** PROHIBITED

**AI Self-Authorization:** PROHIBITED

**Factory Self-Authorization:** PROHIBITED

---

# 8. Amendment and Versioning

An issued version shall not be silently modified.

Any material amendment shall create a new immutable version that records:

- previous Authority Record ID/version;
- previous canonical hash;
- amendment reason;
- approving authority;
- effective date/time;
- changed provisions;
- supersession relationship.

The Authority Record ID should normally remain stable across ordinary versions while the semantic version changes.

Example:

`ORG-FRA-ROOT-0001 / 1.0.0`

→

`ORG-FRA-ROOT-0001 / 1.1.0`

A replacement root requiring a new authority identity shall receive a new Authority Record ID and explicit predecessor/successor linkage.

---

# 9. Rotation

Rotation of cryptographic material, custodians, verification mechanisms, or subordinate authority shall follow controlled organizational policy.

Rotation shall:

- preserve authority lineage;
- record effective time;
- identify predecessor and successor;
- prevent overlapping ambiguous authority;
- support independent validation;
- preserve audit history;
- fail closed where transition integrity cannot be established.

Actual execution and testing of rotation are implementation/certification obligations.

---

# 10. Revocation

This authority or a specific version may be revoked only by the organizational authority authorized to do so under the governing mandate.

A revocation record shall contain:

- Authority Record ID;
- affected version;
- revocation effective time;
- revocation authority;
- reason;
- successor authority, if applicable;
- independent verification reference;
- audit reference.

A revoked authority/version shall not be accepted by the Software Factory.

---

# 11. Compromise, Dispute and Unavailability

If this authority is:

- suspected of compromise;
- inconsistent with independently verified organizational records;
- unavailable beyond governed tolerance;
- stale;
- disputed;
- revoked;
- superseded without valid lineage;
- cryptographically unverifiable;

then affected Factory authority shall enter a fail-closed state.

Permitted responses include governed quarantine, fencing, independent revalidation, recovery, or establishment of a valid successor authority.

Factory execution or AI inference alone cannot restore root authority.

---

# 12. Audit and Provenance

The organizational authority system shall retain immutable or equivalently protected evidence sufficient to reconstruct:

- initial establishment;
- Owner/governance authorization;
- each version;
- amendments;
- delegation;
- rotation;
- revocation;
- compromise handling;
- verification actions where required;
- successor/predecessor lineage.

The Software Factory may reference these records but shall not become their sole authority.

---

# 13. Factory Binding

The Factory may persist the following non-secret binding:

**Authority Record ID:**  
ORG-FRA-ROOT-0001

**Authority Version:**  
1.0.0

**External Record Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.0.0/ROOT-AUTHORITY.md

**Governing Mandate Reference:**  
ORG-FRA-ROOT-0001:v1.0.0#governing-mandate

**Independent Verification Locator / Method:**  
Owner-controlled Organization-Governance repository; independently retrieve ORG-FRA-ROOT-0001 v1.0.0 from protected main, verify repository/version history and ACTIVE status, apply the Section 6.2 canonicalization rule, recompute SHA-256, and compare it with the published canonical digest without relying on Software Factory execution state or AI memory.

**Canonical Record SHA-256:**  
99e668be289d8920014760b9c17099183951e3c7cb2a2455614ae8928a4f3be8

**Current Status:**  
ACTIVE

These values are references to external organizational authority.

Their presence inside Factory state does not make the Factory copy authoritative.

---

# 14. Class-C Obligations

The following are explicitly NOT asserted as completed by this record:

- issuance of operational root credentials;
- cryptographic key creation;
- private-key custody;
- named custodian appointment;
- custody ceremony;
- MFA/passkey or HSM configuration;
- digital-signature execution where not yet implemented;
- credential rotation;
- revocation exercise;
- compromised-root exercise;
- disaster/recovery exercise;
- runtime trust-root reconstruction;
- operational attestation;
- independent implementation certification.

These remain mandatory Class-C obligations before the relevant Factory trust/release gate permits operation.

---

# 15. Canonical Issuance

**Issued By:**  
Alok Ranjan

**Issuer Role:**  
Owner

**Issued At:**  
2026-09-13T20:18:12+05:30

**Authority Record ID:**  
ORG-FRA-ROOT-0001

**Version:**  
1.0.0

**Status:**  
ACTIVE

**External Authoritative Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.0.0/ROOT-AUTHORITY.md

**Independent Verification Locator / Method:**  
Owner-controlled Organization-Governance repository; independently retrieve ORG-FRA-ROOT-0001 v1.0.0 from protected main, verify repository/version history and ACTIVE status, apply the Section 6.2 canonicalization rule, recompute SHA-256, and compare it with the published canonical digest without relying on Software Factory execution state or AI memory.

**Canonical SHA-256:**  
99e668be289d8920014760b9c17099183951e3c7cb2a2455614ae8928a4f3be8

**Owner Approval Reference:**  
DC-CONV-P1-02

---

# 16. Issuance Declaration

By issuing this record through the designated organizational governance channel, the issuing authority establishes the Software Factory Organizational Root Authority according to the mandate and limitations stated herein.

Issuance of this governance record does not constitute Software Factory Architecture Freeze, Build Authorization, implementation authorization, release authorization, production authorization, ROC authorization, or Capability Center construction authorization.

---

# 17. Reference Model

The V1 authority hierarchy is:

`DC-CONV-P1-02`

→ authorizes establishment of

`ORG-FRA-ROOT-0001 / v1.0.0`

→ which becomes the external Organizational Root Authority

→ which may subsequently be referenced by the Software Delivery Factory through a non-authoritative binding.

The Governing Mandate is normative within this record.

**Governing Mandate Reference:**  
`ORG-FRA-ROOT-0001:v1.0.0#governing-mandate`

**Issuance Reference:**  
`ORG-FRA-ROOT-0001:v1.0.0`

No additional predecessor root-authority document is required for V1.

---

# 18. Repository and Control Boundary

The authoritative record is maintained in the Owner-controlled external organizational governance repository:

`Organization-Governance`

This repository is outside the Software Delivery Factory project's own authority/control surface.

The Software Factory shall not possess unilateral authority to create, alter, delete, supersede, revoke, or bypass this Organizational Root Authority.

The protected governance repository, its version history, the canonical record digest, and the independent verification mechanism collectively provide the architecture-stage external verification route.

Factory-controlled repositories may retain references to this authority but shall not become the authoritative organizational source.

---

# 19. Confidentiality and Secret Handling

This Root Authority Register contains governance metadata only.

The following must not be embedded in this record:

- private keys;
- passwords;
- Personal Access Tokens;
- MFA secrets;
- recovery codes;
- signing secrets;
- confidential custody material;
- production credentials.

Such secrets shall be handled only by separately governed credential/custody mechanisms when those Class-C controls are implemented.

---

# END OF SOFTWARE FACTORY ORGANIZATIONAL ROOT AUTHORITY REGISTER
