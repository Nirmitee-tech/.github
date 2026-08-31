# Nirmitee.io

**Healthcare interoperability engineering.** We build and integrate the systems that move clinical and claims data between EHRs, payers, clearinghouses and national health exchanges.

Our team works day to day in HL7 v2, FHIR R4, X12 EDI, SMART on FHIR, Mirth Connect and ABDM. The repositories below are the parts of that work we've been able to open-source — reference implementations, test harnesses and integration recipes taken from production deployments.

[nirmitee.io](https://nirmitee.io) · [Blog](https://nirmitee.io/blog) · [Contact us](https://nirmitee.io/contact)

---

## US interoperability & revenue cycle

| Project | What it is |
|---|---|
| [**fhir-prior-auth-engine**](https://github.com/Nirmitee-tech/fhir-prior-auth-engine) | FHIR-native prior-authorization workflow engine — a reference implementation of orchestration, async holds, human-in-the-loop review and event sourcing for CMS-0057 / Da Vinci (CRD · DTR · PAS). Kotlin + Spring Boot. |
| [**clearinghouse-simulator**](https://github.com/Nirmitee-tech/clearinghouse-simulator) | A drop-in stand-in for a real clearinghouse SFTP/EDI integration. 120 scenarios across 270/271, 278, 837, TA1/999, 277CA, 835 and 276/277, validated against a production corpus. |
| [**openmirth-console**](https://github.com/Nirmitee-tech/openmirth-console) | Open-source operations layer for Mirth Connect and OIE — modern web admin, clinical observability and channel CI/CD. |
| [**mirth-connect-cookbook**](https://github.com/Nirmitee-tech/mirth-connect-cookbook) | Production-grade Mirth Connect recipes, transformers, channels and scripts — tested in real deployments. |

## FHIR platforms

| Project | What it is |
|---|---|
| [**headless-ehr-fhir**](https://github.com/Nirmitee-tech/headless-ehr-fhir) | A headless EHR platform built on FHIR R4 — multi-tenant, HIPAA-ready, with ABAC authorization, SMART on FHIR, field-level encryption and bulk `$export`. Go. |
| [**nirmitee-rpm**](https://github.com/Nirmitee-tech/nirmitee-rpm) | Open-source Remote Patient Monitoring platform — multi-tenant workspaces, RBAC, care plans and vitals monitoring. |

## ABDM / India Digital Health

| Project | What it is |
|---|---|
| [**abdm-v3-postman-collection**](https://github.com/Nirmitee-tech/abdm-v3-postman-collection) | Complete Postman collection for the ABDM V3 APIs — every endpoint, with sandbox and production environments. |
| [**abdm-v3-error-catalog**](https://github.com/Nirmitee-tech/abdm-v3-error-catalog) | Every ABDM V3 error code, its actual cause and the fix — in one place. |
| [**abdm-fhir-bundle-examples**](https://github.com/Nirmitee-tech/abdm-fhir-bundle-examples) | Production-ready FHIR R4 bundles for all six ABDM hiTypes: OPConsultation, Prescription, DiagnosticReport, DischargeSummary, ImmunizationRecord, WellnessRecord. |
| [**abdm-sdk-node**](https://github.com/Nirmitee-tech/abdm-sdk-node) | TypeScript SDK for the ABDM APIs — ABHA, HIP, HIU, consent and health-information exchange. |

## Engineering tooling

| Project | What it is |
|---|---|
| [**integration-mock-server-template-mountebank**](https://github.com/Nirmitee-tech/integration-mock-server-template-mountebank) | Template for a dynamic API mock server — MongoDB-backed config, Handlebars templating, webhooks and a web UI, for testing integrations without the upstream. |
| [**health-components**](https://github.com/Nirmitee-tech/health-components) | React + TypeScript component library for clinical UIs, styled with Tailwind CSS. |

---

## What we do commercially

- **Interoperability builds** — HL7 v2, FHIR R4, X12 EDI and CCDA integrations between EHRs, payers and third-party systems.
- **Mirth Connect / OIE** — channel development, migration off legacy engines, and ongoing operations.
- **Revenue cycle integration** — eligibility, claims, remittance and clearinghouse connectivity.
- **EHR integration** — Epic, Cerner and SMART on FHIR app launch, certification and go-live support.
- **Regulatory readiness** — CMS-0057, Da Vinci IGs, ONC (g)(10) and ABDM milestone certification.

If you are building health software and hit an integration wall, [get in touch](https://nirmitee.io/contact).
