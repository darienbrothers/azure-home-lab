# ADR-001: Primary Azure Region
**Status:** Approved
**Date:** August 3, 2026
## Context
Brothers Technology Group (BTG) is beginning its Azure Enterprise Transformation.
The Cloud Engineering team must select a primary Azure region for Phase 1 deployments.
## Decision
BTG will use **East US 2 (EUS2)** as the primary Azure region.
## Rationale
- BTG headquarters is located in Boston, Massachusetts.
- East US 2 is a mature Azure region with broad service availability.
- The region aligns well with Microsoft's recommended deployment practices for many enterprise workloads.
- A single primary region simplifies initial architecture and documentation.
## Consequences
- All Phase 1 deployments will target East US 2 unless a documented business or technical requirement justifies another region.
- Future phases may introduce additional regions to support disaster recovery, high availability, or geographic expansion.
