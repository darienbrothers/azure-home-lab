# Azure Foundation

**Project:** BTG Azure Enterprise Transformation

**Document Owner:** Cloud Engineering

**Status:** Draft

---

# Purpose

This document defines the foundational Azure architecture for Brothers Technology Group (BTG).

The goal is to establish a secure, scalable, and well-organized Azure environment before any production resources are deployed.

---

# Azure Organizational Hierarchy

The BTG Azure environment will follow Microsoft's recommended organizational hierarchy.

Tenant

└── Management Group

    └── Subscription

        └── Resource Group

            └── Resources

---

# Initial Azure Design Decisions

## Tenant

BTG will use a single Microsoft Entra tenant to centrally manage users, groups, applications, and identity.

## Management Groups

No Management Groups will be created during Phase 1. The environment currently contains a single subscription, so additional management layers are unnecessary at this stage.

## Subscription

A single Azure subscription will be used during Phase 1 of the Enterprise Cloud Simulation.

As BTG grows, additional subscriptions may be introduced for Production, Development, Security, and Disaster Recovery.

## Resource Groups

Resources will be organized into logical Resource Groups based on workload and business purpose rather than placing every resource into a single container.

This approach improves organization, management, and scalability.

---

# Engineering Principle

Understand before you build.

Every Azure resource deployed during this simulation must support a documented business requirement.
 
