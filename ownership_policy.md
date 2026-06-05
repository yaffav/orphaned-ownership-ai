# Orphaned Ownership AI

## Problem

Large organizations often know which systems exist, but they do not always know who actually owns them.

When employees leave, departments change, or projects are abandoned, systems may remain active without a clear business owner.

These orphaned assets create several risks:

- Unauthorized access remains active
- Nobody approves permissions
- Vendors continue to receive payments
- Security incidents have no accountable owner
- Shadow IT becomes invisible

## AI Detection Logic

The agent correlates data from multiple sources and flags assets when:

- BusinessOwner is empty
- System is still active
- Users or integrations still exist
- The asset still generates cost or activity

## Output

The agent produces a prioritized report with:

- Asset name
- Risk score
- Missing ownership reason
- Suggested owner
- Recommended remediation action
