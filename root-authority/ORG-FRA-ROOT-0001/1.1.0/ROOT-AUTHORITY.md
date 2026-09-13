# Software Factory Organizational Root Authority Register — Corrective Successor

## 1. Identity and Issuance Control

**Authority Record ID:** ORG-FRA-ROOT-0001

**Authority Name:** Software Factory Organizational Root Authority

**Authority Version:** 1.1.0

**Record Status:** ACTIVE

**Record Type:** ORGANIZATIONAL_ROOT_AUTHORITY_REGISTER

**Effective From:** 2026-09-13T22:33:09+05:30

**Issued By:** Alok Ranjan

**Issuing Authority Role:** Owner

**Original Owner Approval Reference:**  
DC-CONV-P1-02

**Digest-Correction Approval Reference:**  
DC-CONV-P1-02-CORR-01

**External Authoritative Record Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.1.0/ROOT-AUTHORITY.md

**Independent Verification Surface:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance-Verification

**Independent Verification Role / Function:**  
Independent Organizational Authority Verifier

**Canonical Record SHA-256:**  
5f95b2669912870982b762a05929b38191382b7d2300c75ffb98fa77aa0188dc

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

# 3. Corrective Amendment Provenance and Lineage

**Original Owner Approval Reference:**  
DC-CONV-P1-02

**Digest-Correction Approval Reference:**  
DC-CONV-P1-02-CORR-01

**Approving Authority:**  
Owner

**Previous Authority Record ID / Version:**  
ORG-FRA-ROOT-0001 / 1.0.0

**Previous Issued Record Identity:**  
Git blob `91c6155b478f775d2115644cf16e442479de23fe`; issuance commit `d2db009924843716e0e247f7756b13162945f603`; merged PR #1.

**Previous Published Canonical SHA-256 — Defective:**  
99e668be289d8920014760b9c17099183951e3c7cb2a2455614ae8928a4f3be8

**Section 6.2 Recalculation of Issued v1.0.0 Bytes:**  
20a62108b074c6fc9eddd4c819e89ae62016abeeab37e378b5931718d1eaa620

**Correction Reason:**  
Issued v1.0.0 contains published canonical-digest values that do not equal the result obtained by independently applying its own Section 6.2 canonicalization rule to the issued bytes. The original method used to derive the published v1.0.0 digest is undocumented. v1.0.0 therefore remains preserved exactly as issued and its integrity defect is disclosed rather than corrected in place.

**Changed Provisions:**  
Version identity, current status, integrity value, amendment/correction provenance, predecessor/successor lineage, issuance references and independent-verification route.

**Unchanged Provision:**  
The Section 2 Governing Mandate remains unchanged.

**Supersession Relationship:**  
ORG-FRA-ROOT-0001 v1.1.0 supersedes ORG-FRA-ROOT-0001 v1.0.0 as the current issued authority record. v1.0.0 remains immutable historical evidence and shall not be silently modified.

**Supersession Reference:**  
ORG-FRA-ROOT-0001:v1.0.0→v1.1.0

**Effective Date / Time:**  
2026-09-13T22:33:09+05:30

---

# 4. Independent Verification

**Independent Verification Role / Function:**  
Independent Organizational Authority Verifier

**Independent Verification Surface:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance-Verification

The verification surface is Owner-controlled and outside Software Factory authority/control.

It shall publish only non-secret evidence necessary to independently validate this authority, including:

- exact current issued Root Authority v1.1.0;
- exact immutable predecessor v1.0.0 or sufficient immutable predecessor evidence;
- v1.0.0 → v1.1.0 lineage and supersession evidence;
- current authority status;
- governing mandate;
- relevant Owner approval references;
- Section 5.2 canonicalization instructions;
- published v1.1.0 canonical SHA-256;
- immutable issuance/merge provenance;
- independent verification instructions.

It shall not publish:

- private keys;
- passwords;
- Personal Access Tokens;
- MFA or recovery secrets;
- signing secrets;
- custody secrets;
- unrelated private governance material;
- production credentials.

The independent verifier shall establish:

1. Authority Record ID;
2. issued version;
3. current status;
4. governing mandate;
5. Original Owner Approval provenance;
6. Digest-Correction Approval provenance;
7. predecessor identity;
8. supersession lineage;
9. protected issuance provenance;
10. Section 5.2 canonicalization;
11. independently recomputed SHA-256;
12. equality between independently recomputed and published canonical digest.

If any required element cannot be independently established, dependent authority shall be treated as `AUTHORITY_UNVERIFIED` and shall fail closed.

---

# 5. Integrity and Authenticity

## 5.1 Canonical Integrity

**Canonical Record SHA-256:**  
5f95b2669912870982b762a05929b38191382b7d2300c75ffb98fa77aa0188dc

The digest above was finalized only after all non-digest fields in this v1.1.0 candidate were fixed.

It does not reuse:

- the defective published v1.0.0 digest;
- the independently recalculated v1.0.0 digest;
- any earlier draft v1.1.0 digest.

## 5.2 Canonicalization Rule

For SHA-256 calculation of this v1.1.0 Root Authority record:

1. The canonical source is this `ROOT-AUTHORITY.md` record after all issuance fields other than the SHA-256 value have been finalized.
2. Text shall be represented as UTF-8.
3. Line endings shall be normalized to LF.
4. No trailing transformation, reformatting, or semantic rewriting shall be performed during digest calculation.
5. For digest calculation only, every value corresponding to `Canonical Record SHA-256` or `Canonical SHA-256` in this record shall be interpreted as the fixed literal:

`SELF-EXCLUDED-FOR-HASH`

6. The SHA-256 digest shall be calculated over that canonicalized representation.
7. The resulting 64-character lowercase hexadecimal digest shall then be recorded in every canonical SHA-256 field.
8. Verification shall reproduce exactly the same canonicalization procedure before recomputing the digest.
9. A second independent calculation shall be performed from the same frozen final candidate before protected issuance.
10. After the resulting digest is inserted, the canonicalization and digest verification shall be performed again to confirm that the published record reproduces the same digest.

This rule prevents digest self-reference while providing deterministic verification.

## 5.3 Implementation-Stage Authenticity

Implementation-stage signatures, private keys, named custody, credential rotation, revocation exercises, recovery exercises and operational attestation remain unresolved Class-C obligations.

This v1.1.0 correction does not assert those obligations as completed.

---

# 6. Amendment and Versioning

An issued version shall not be silently modified.

A material correction or amendment shall create a new immutable version containing:

- stable Authority Record ID;
- predecessor version;
- predecessor integrity/provenance;
- amendment reason;
- approving authority;
- effective time;
- changed provisions;
- supersession relationship;
- independently reproducible canonical integrity.

The stable authority identity remains:

`ORG-FRA-ROOT-0001`

The current corrective successor version is:

`1.1.0`

---

# 7. Factory Binding and Limitations

The Software Factory may retain a non-authoritative reference to this issued authority.

The Factory may not establish, modify, validate, replace, revoke or supersede this Organizational Root Authority through its own assertion.

Factory-controlled copies do not become authoritative merely because they contain the same values.

This record does not grant:

- Architecture Freeze;
- Build Authorization;
- implementation authorization;
- release authorization;
- production deployment authorization;
- Capability Center construction authorization;
- ROC runtime authorization.

**Authority Record ID:**  
ORG-FRA-ROOT-0001

**Current Issued Version:**  
1.1.0

**Current Status:**  
ACTIVE

**External Authoritative Record Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.1.0/ROOT-AUTHORITY.md

**Independent Verification Surface:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance-Verification

**Original Owner Approval Reference:**  
DC-CONV-P1-02

**Digest-Correction Approval Reference:**  
DC-CONV-P1-02-CORR-01

**Supersession Reference:**  
ORG-FRA-ROOT-0001:v1.0.0→v1.1.0

**Canonical SHA-256:**  
5f95b2669912870982b762a05929b38191382b7d2300c75ffb98fa77aa0188dc

---

# 8. Canonical Issuance

**Issued By:**  
Alok Ranjan

**Issuer Role:**  
Owner

**Issued At:**  
2026-09-13T22:33:09+05:30

**Authority Record ID:**  
ORG-FRA-ROOT-0001

**Issued Successor Version:**  
1.1.0

**Current Status:**  
ACTIVE

**Original Owner Approval Reference:**  
DC-CONV-P1-02

**Digest-Correction Approval Reference:**  
DC-CONV-P1-02-CORR-01

**Predecessor:**  
ORG-FRA-ROOT-0001 / 1.0.0

**Supersession Reference:**  
ORG-FRA-ROOT-0001:v1.0.0→v1.1.0

**External Authoritative Record Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance/blob/main/root-authority/ORG-FRA-ROOT-0001/1.1.0/ROOT-AUTHORITY.md

**Independent Verification Surface Locator:**  
https://github.com/alok13ranjan-cloud-apps/Organization-Governance-Verification

**Canonical SHA-256:**  
5f95b2669912870982b762a05929b38191382b7d2300c75ffb98fa77aa0188dc

---

# 9. Issuance Declaration

Under Owner correction approval `DC-CONV-P1-02-CORR-01`, this record preserves issued v1.0.0 unchanged and establishes v1.1.0 as its governed corrective successor for canonical-integrity/provenance correction and independent verification.

The Governing Mandate remains unchanged.

v1.1.0 supersedes v1.0.0 as the current authority version, while v1.0.0 remains immutable historical issuance evidence.

This correction does not constitute Architecture Freeze, Build Authorization, implementation authorization, release authorization, production authorization, ROC authorization, or Capability Center construction authorization.

---

# 10. Confidentiality and Secret Handling

This record contains governance metadata only.

The following shall not be embedded in this record or its public verification surface:

- private keys;
- passwords;
- Personal Access Tokens;
- MFA secrets;
- recovery codes;
- signing secrets;
- confidential custody material;
- production credentials.

Such material remains governed separately under applicable Class-C controls.

---

# END OF SOFTWARE FACTORY ORGANIZATIONAL ROOT AUTHORITY REGISTER — v1.1.0
