# Doctor Jambo — System Requirements Specification

## Purpose

This directory translates the business foundation into testable system requirements for Doctor Jambo, an AI-powered healthcare platform.

## Scope

It covers patient and doctor experiences, AI and voice capabilities, agentic workflows, data, integrations, security, and traceability. It does not prescribe an implementation.

## Actors

Patients, caregivers, doctors, clinic administrators, platform administrators, AI services, and integrated health systems.

## Requirements

Read `SRS.md` first, then Functional and NonFunctional requirements. Use cases and acceptance criteria support validation; the traceability matrix links business goals to system requirements.

## Assumptions

Clinical governance, privacy, and legal review will approve detailed workflows before release.

## Constraints

The platform must not autonomously diagnose, prescribe, or replace emergency services.

## Future considerations

Regional rollout, standards-based interoperability, and implementation with Java 25, Spring Boot 4+, Spring AI, LangChain4j, Embabel, MCP, and event-driven services are future design decisions.
