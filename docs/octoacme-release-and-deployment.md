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
- Release notes drafted (Release Manager coordinates)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Support team briefed and knowledge base updated (Support Lead)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Release Manager coordinates go/no-go decision
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Release Manager)
- [ ] Support Lead confirms readiness and monitors initial feedback

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Release Manager coordinates rollback decision
  - Rollback to last known-good release if necessary
  - Support Lead monitors user impact and provides feedback
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

See also: [Release Readiness Checklist](templates/release-readiness-checklist.md) for comprehensive pre-release validation.
