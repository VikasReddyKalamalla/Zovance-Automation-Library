# Client Deployment Checklist

This document details the standardized pipeline for moving any automation from our library into a client's production environment.

## 1. Discovery Phase
- [ ] Conduct client discovery workshop (see `CLIENT_TEMPLATES/Discovery Questionnaire`).
- [ ] Define the scope of work (SOW).
- [ ] Determine baseline metrics (manual time spent, error rates, frequency).

## 2. Requirements & Setup
- [ ] Gather system access and credentials (see `CREDENTIAL_TEMPLATES`).
- [ ] Finalize configuration mapping in `02_Documentation/Configuration.md`.
- [ ] Complete risk assessment for target integrations.

## 3. Configuration & Logic Build
- [ ] Import base workflow.
- [ ] Insert tailored LLM prompts from `03_Prompts/`.
- [ ] Establish custom error triggers and webhook alerting.

## 4. Quality Assurance & Verification
- [ ] Run automated checks with mock files in `04_Testing/Sample Input.json`.
- [ ] Verify validation checks list.
- [ ] Obtain client review.

## 5. Launch & Handover
- [ ] Perform go-live operations.
- [ ] Deliver client training (using `05_Client/Demo Script.md`).
- [ ] Sign maintenance agreement.
