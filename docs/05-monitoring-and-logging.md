# Monitoring and Logging

## Windows Security Event Logs

Security logging was validated on `DC01` using Windows Event Viewer.

The lab captured successful logons, failed logons, and Active Directory group membership changes.

## Successful Logon Event

Event ID `4624` shows a successful account logon.

![DC01 Successful Logon Event 4624](images/monitoring/dc01-security-event-4624.png)

## Failed Logon Event

Event ID `4625` shows a failed logon attempt caused by an incorrect username or password.

![DC01 Failed Logon Event 4625](images/monitoring/dc01-security-event-4625.png)

## Security Group Change Event

Event ID `4728` shows a user being added to a security-enabled global group.

This proves that Active Directory group membership changes are being logged.

![DC01 Group Change Event 4728](images/monitoring/dc01-security-event-4728-group-change.png)

## Skills Demonstrated

- Windows Event Viewer usage
- Security log review
- Successful logon auditing
- Failed logon auditing
- Active Directory group change auditing
- Basic incident investigation evidence collection
