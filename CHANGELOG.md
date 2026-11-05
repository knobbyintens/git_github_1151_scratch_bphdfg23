# Nova Workspace Release Board

All notable changes to the Nova Workspace platform are tracked in this file. The release queue is re-triaged against the issue tracker before every release cut.

## [Unreleased]

<!-- UNRELEASED:START -->
- UQ-001 | NVA-201 | Bulk export of audit logs | P1
- UQ-002 | NVA-202 | Single sign-on for mobile clients | P2
- UQ-003 | NVA-203 | Offline mode for the field app | P1
- UQ-004 | NVA-204 | Custom report builder | P2
- UQ-005 | NVA-205 | Usage metering dashboard | P2
- UQ-006 | NVA-206 | Granular webhook retries | P3
- UQ-007 | NVA-209 | CSV import validation preview | P3
- UQ-008 | NVA-211 | In-app release notes feed | P3
- UQ-009 | NVA-299 | Legacy invoice sync bridge | P3
<!-- UNRELEASED:END -->

## Recently Shipped (2.9.0)

<!-- SHIPPED:START -->
- [NVA-190] Dark-mode theme for the admin console
- [NVA-192] Faster workspace search indexing
<!-- SHIPPED:END -->

## [2.8.0] - 2026-10-14

### Added
- [NVA-180] Bulk invitation management
- [NVA-184] Audit log retention policies

### Fixed
- [NVA-187] Timezone drift in scheduled exports

## [2.7.0] - 2026-09-30

### Added
- [NVA-167] API key rotation reminders
- [NVA-171] Workspace archiving

## Release Operations

Release branches are cut from `main`; frozen maintenance branches receive security fixes only.
