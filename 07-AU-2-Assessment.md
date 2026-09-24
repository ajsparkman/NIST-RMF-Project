# AU-2 - Event Logging Assessment

## Control

AU-2 - Event Logging

## Purpose

The purpose of this control is to ensure that important system and security events are recorded so they can be reviewed during troubleshooting, monitoring, or security investigations.

## Assessment Question

Does Sparkman Systems LLC record the system and security events necessary to detect and investigate suspicious activity?

## Evidence Requested

To assess AU-2, the following evidence would be requested:

- Windows event logging configuration
- Active Directory audit settings
- Microsoft 365 audit logging settings
- VPN authentication logs
- Firewall logs
- Log retention settings

## Evidence Reviewed

The following fictional evidence was reviewed:

- Windows security event logging was enabled on company laptops and servers
- Active Directory logged successful and failed sign-in attempts
- Microsoft 365 audit logging was enabled
- VPN authentication events were logged
- The perimeter firewall retained connection logs
- Most logs were retained for only seven days
- No centralized log management or SIEM solution was in use

## Assessment Result

Status: Partially Satisfied

## Finding

Sparkman Systems LLC has event logging enabled across several key systems, but most logs are retained for only seven days and are not centrally collected.

## Risk

Short retention periods and decentralized logs may limit the company’s ability to investigate security incidents that are discovered after several days.

## Recommendation

Increase log retention and consider implementing centralized log collection so security-relevant events can be reviewed from one location.