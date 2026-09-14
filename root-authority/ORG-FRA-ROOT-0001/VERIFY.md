# Verify ORG-FRA-ROOT-0001

1. Retrieve `1.1.0/ROOT-AUTHORITY.md` from this public repository. Establish Authority Record ID `ORG-FRA-ROOT-0001`, version `1.1.0`, status `ACTIVE`, approval references `DC-CONV-P1-02` and `DC-CONV-P1-02-CORR-01`, predecessor `1.0.0`, and the supersession lineage. Confirm exact file identity against source blob `ad9a45294c4b3d0469e75edc93656c0bd406709c` and issuance merge commit `7d0fad04a54790a39cdde852160f765a3c6e142a` where the source is accessible.
2. Apply Section 5.2 exactly: interpret the file as UTF-8; normalize CRLF and CR line endings to LF; replace the values in all four current `Canonical Record SHA-256` / `Canonical SHA-256` fields with the literal `SELF-EXCLUDED-FOR-HASH`; make no other transformation.
3. SHA-256 hash the resulting UTF-8 bytes. Require `5f95b2669912870982b762a05929b38191382b7d2300c75ffb98fa77aa0188dc`.
4. Confirm the v1.1.0 ACTIVE status, v1.0.0 SUPERSEDED / HISTORICAL lineage, and approval references `DC-CONV-P1-02` and `DC-CONV-P1-02-CORR-01` against `STATUS.md` and the issued records.
5. On any mismatch, report `AUTHORITY_UNVERIFIED` and fail closed. The private Organization-Governance repository is authoritative; this public copy supports independent verification only.
