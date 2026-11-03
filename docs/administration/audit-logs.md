# Audit Logs

This guide explains how administrators can review and interpret audit logs in Sentinel Data Protection. Audit logs provide visibility into administrative activities, user actions and security-related events.

## Overview

Audit logs maintain a record of selected activities performed within an organisation's environment.

Administrators can use audit information to:

- Monitor administrative and user activities.
- Investigate unexpected changes to system settings.
- Review access-related events.
- Support security investigations.
- Maintain operational accountability.

!!! info "Portfolio demonstration"
    Audit logging capabilities and examples described in this guide are illustrative. They do not represent verified functionality of an actual commercial product.

## Audit Log Events

Audit records may contain information about the following categories of activity.

| Event category | Description | Example |
|---|---|---|
| Authentication | Records authentication-related activity. | Successful or unsuccessful sign-in |
| User management | Records changes to user accounts. | User account created or disabled |
| Access control | Records changes to roles and permissions. | Administrator updates a user role |
| Configuration | Records changes to product settings. | Security policy updated |
| Administrative activity | Records selected administrator actions. | Administrative settings modified |

The actual events captured depend on the product's audit logging implementation.

## Audit Record Information

An audit record may contain the following fields:

| Field | Description | Example |
|---|---|---|
| Timestamp | Date and time when the event occurred. | 2026-11-03 10:30:00 |
| Event ID | Unique identifier assigned to the event. | EVT-10025 |
| User | Account associated with the activity. | [admin@example.com](admin@example.com) |
| Event type | Category of the recorded activity. | Configuration update |
| Description | Summary of the activity. | Security policy modified |
| Source | Originating IP address or system identifier, where available. | 192.0.2.10 |
| Status | Outcome of the recorded event. | Successful |

!!! note "Example audit record"
    The field names, identifiers, timestamps and values in this guide are fictional examples. Actual audit record fields may differ between implementations.

## Access Audit Logs

Administrators should have the appropriate permissions before accessing audit information.

To review audit logs:

1. Sign in using an authorised administrator account.
2. Open the administration area.
3. Navigate to the Audit Logs section.
4. Review the available audit records.
5. Select an event to inspect its details, if supported.

!!! warning "Access permissions"
    Audit records may contain sensitive operational information. Restrict access to authorised personnel and follow your organisation's information security policies.

## Search and Filter Audit Records

Filtering helps administrators locate relevant events without reviewing the entire audit history.

Common filtering criteria may include:

- Date and time range
- User account
- Event category
- Event status
- Event identifier

### Example investigation

An administrator wants to investigate a recent change to a security policy.

The administrator can:

1. Open the Audit Logs section.
2. Select the relevant date range.
3. Filter the records by the Configuration event category.
4. Identify the event associated with the policy change.
5. Review the event details and associated user.
6. Record the findings according to the organisation's investigation process.

## Review an Audit Event

When investigating an event, review the available information to understand what happened and when it occurred.

Use the following procedure:

1. Identify the event that requires investigation.
2. Review its timestamp and event category.
3. Identify the associated user or system.
4. Examine the event description and available details.
5. Compare the event with related administrative activities.
6. Document the investigation findings.

!!! tip "Investigation best practice"
    Review related events before drawing conclusions. A single audit record may not provide sufficient context to explain an activity.

## Export Audit Records

Where supported, administrators may export audit records for reporting, investigation or compliance-related activities.

Before exporting audit information:

1. Identify the records required for the investigation.
2. Apply the appropriate filters.
3. Verify that the selected records are relevant.
4. Use an authorised export mechanism, where available.
5. Store exported records in an approved secure location.

!!! warning "Protect exported information"
    Exported audit records may contain user identifiers, IP addresses and other sensitive information. Apply appropriate access controls and retention requirements.

## Audit Log Retention

Audit log retention determines how long audit information remains available.

Organisations should establish retention requirements based on applicable legal, regulatory, contractual and internal security policies.

Administrators should consider:

- Retention duration.
- Storage capacity.
- Access restrictions.
- Secure disposal requirements.
- Preservation of records required for active investigations.

The retention period and available retention controls depend on the product implementation and organisational policy.

## Troubleshooting

| Issue | Possible explanation | Recommended action |
|---|---|---|
| Audit Logs section is unavailable | The account may not have the required permissions. | Verify the assigned administrator role. |
| Expected event is missing | The event may not be captured or may fall outside the selected date range. | Review filters and available logging settings. |
| Search returns no results | Search criteria may be too restrictive. | Broaden the date range and review the selected filters. |
| Export is unavailable | The account may lack export permissions or the feature may not be supported. | Verify permissions and available product capabilities. |
| Event details appear incomplete | The audit record may not include all contextual information. | Review related records and available event details. |

For additional guidance, see [Common Issues](../troubleshooting/common-issues.md).

## Security and Administration Best Practices

Follow these recommendations when working with audit information:

- Restrict audit log access to authorised administrators.
- Review security-related events periodically.
- Investigate unexpected administrative changes.
- Protect exported audit records.
- Follow organisational retention and disposal policies.
- Avoid sharing sensitive audit information through unsecured channels.
- Document investigation findings according to internal procedures.

## Related Documentation

- [User Management](user-management.md)
- [Access Control](access-control.md)
- [Configuration](../configuration.md)
- [Common Issues](../troubleshooting/common-issues.md)