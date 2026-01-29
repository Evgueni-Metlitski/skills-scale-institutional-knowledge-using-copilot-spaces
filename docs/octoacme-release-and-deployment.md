# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA/Tester sign-off on test results and quality metrics
- UX/UI Designer verification of design implementation (if applicable)
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared and validated
- Stakeholder communication plan ready

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] QA/Tester validates all tests passing in staging
- [ ] Deploy to staging and run smoke tests
- [ ] PM confirms stakeholder communication is ready
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] UX/UI Designer spot-checks key user flows (if UI changes)
- [ ] Announce release to stakeholders and support
- [ ] Scrum Master facilitates quick release retrospective if needed

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
