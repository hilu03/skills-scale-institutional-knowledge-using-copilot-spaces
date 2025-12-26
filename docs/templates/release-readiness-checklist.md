# Release Readiness Checklist

Use this checklist to ensure all release requirements are met before deployment.

## Code & Quality (1 Week Before Release)
- [ ] **Developers**: All PRs merged to release branch
- [ ] **Developers**: Code freeze communicated and enforced
- [ ] **QA/Testing**: All acceptance criteria validated
- [ ] **QA/Testing**: Regression tests passed
- [ ] **Developers**: CI/CD pipeline green (all tests passing)
- [ ] **Developers**: Security scans completed with no critical issues
- [ ] **Developers**: Performance testing completed (if applicable)

## Documentation & Communication (3-5 Days Before)
- [ ] **Release Manager**: Release notes drafted and reviewed
- [ ] **Product Manager**: Feature documentation updated
- [ ] **Support Lead**: Knowledge base articles created/updated
- [ ] **Support Lead**: Support team briefed on new features and changes
- [ ] **Release Manager**: Stakeholder communication sent
- [ ] **Data Analyst**: Analytics and tracking verified in staging

## Deployment Preparation (2-3 Days Before)
- [ ] **Release Manager**: Deployment window scheduled and communicated
- [ ] **Developers**: Database migrations tested (if applicable)
- [ ] **Developers**: Rollback plan documented and tested
- [ ] **Release Manager**: Backup/snapshot completed (if needed)
- [ ] **Developers**: Environment variables and configuration reviewed
- [ ] **Release Manager**: On-call rotation confirmed for release window

## Staging Verification (1-2 Days Before)
- [ ] **Release Manager**: Code deployed to staging environment
- [ ] **QA/Testing**: Smoke tests executed on staging
- [ ] **UX Designer**: UI/UX review completed on staging
- [ ] **Product Manager**: Feature functionality validated on staging
- [ ] **Data Analyst**: Analytics tracking verified on staging

## Go/No-Go Decision (Day Before or Day Of)
- [ ] **Release Manager**: Facilitate go/no-go meeting
- [ ] **Project Manager**: Confirm no blocking risks or issues
- [ ] **Developers**: Technical readiness confirmed
- [ ] **Product Manager**: Business readiness confirmed
- [ ] **Support Lead**: Support readiness confirmed
- [ ] **Release Manager**: Final approval obtained from stakeholders

## Deployment Day
- [ ] **Release Manager**: Execute deployment following runbook
- [ ] **Developers**: Monitor deployment progress and logs
- [ ] **Release Manager**: Run post-deployment smoke tests
- [ ] **Data Analyst**: Verify metrics and monitoring dashboards
- [ ] **Release Manager**: Confirm successful deployment
- [ ] **Release Manager**: Send release announcement
- [ ] **Support Lead**: Monitor support channels for issues

## Post-Release (24-48 Hours After)
- [ ] **Support Lead**: Review initial user feedback and support tickets
- [ ] **Data Analyst**: Review adoption metrics and success criteria
- [ ] **Developers**: Monitor error rates and performance metrics
- [ ] **Release Manager**: Document any issues or lessons learned
- [ ] **Project Manager**: Update project status and timeline

## Rollback Criteria
If any of these occur, consider rollback:
- Critical functionality is broken
- Security vulnerability discovered
- Performance degradation exceeds acceptable thresholds
- Data integrity issues detected
- Excessive error rates or support escalations

**Rollback Decision**: Release Manager coordinates with Project Manager, Product Manager, and Developers
