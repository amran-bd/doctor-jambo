# Doctor Jambo — System Requirements Specification

## Purpose

This directory translates the business foundation into testable system requirements for Doctor Jambo, an AI-powered healthcare platform.

## Scope

It covers patient and doctor experiences, AI and voice capabilities, agentic workflows, data, integrations, security, and traceability. It does not prescribe an implementation.

## Actors

Patients, caregivers, doctors, clinic administrators, platform administrators, AI services, and integrated health systems.

## Detailed description

This document defines the enterprise healthcare platform baseline for its stated scope. It is read with the SRS and the business foundation, and remains subject to clinical, privacy, security, and operational governance.

## Requirements

Read [SRS](SRS.md) first, then [Functional Requirements](FunctionalRequirements.md) and [Non-Functional Requirements](NonFunctionalRequirements.md). [Use cases](UseCaseModel.md) and [acceptance criteria](AcceptanceCriteria.md) support validation; the [traceability matrix](TraceabilityMatrix.md) links business goals to system requirements. Review [AI](AIRequirements.md), [Voice](VoiceRequirements.md), and [Agent](AgentRequirements.md) requirements before designing assisted workflows.

## Assumptions

Clinical governance, privacy, and legal review will approve detailed workflows before release.

## Constraints

The platform must not autonomously diagnose, prescribe, or replace emergency services.

## Dependencies

This document depends on approved clinical governance, privacy and security policies, and the related requirements in this directory.

## Future enhancements

Regional rollout, standards-based interoperability, and implementation with Java 25, Spring Boot 4+, Spring AI, LangChain4j, Embabel, MCP, and event-driven services are future design decisions.
