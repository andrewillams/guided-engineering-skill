# Deployment Template

Use this template for `docs/engineering/DEPLOYMENT.md`.

## 1. Release identity
- Version/tag:
- Commit:
- Artifact:
- Target environment:

## 2. Preconditions
- [ ] Required tests passed or accepted exceptions documented
- [ ] Required approvals obtained
- [ ] Environment/configuration validated
- [ ] Secrets exist in target environment (never record secret values here)
- [ ] Backup/recovery requirement handled
- [ ] Migration impact reviewed
- [ ] Rollback path is executable

## 3. Configuration changes
| Item | Environment | Change | Validation |
|---|---|---|---|

## 4. Migration steps
| Order | Step | Expected result | Reversible? |
|---|---|---|---|

## 5. Deployment procedure
1. 

## 6. Smoke tests
| Test | Expected result | Status | Evidence |
|---|---|---|---|

## 7. Monitoring
- Health endpoint/dashboard:
- Logs:
- Key error signals:
- Key business signal:

## 8. Rollback
### Trigger conditions
- 

### Rollback procedure
1. 

### Data rollback/reconciliation
- 

## 9. Deployment record
- Started:
- Finished:
- Operator:
- Result:
- Deployed version/commit:
- Incidents/deviations:
