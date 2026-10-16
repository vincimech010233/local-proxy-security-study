# Scoped reverse-proxy security study

[Español](README.es.md)

A defensive research exercise examining how identity information moves through a locally isolated proxy chain. The work combined source review, a local laboratory, negative controls, and an internal adversarial review.

## Status and limits

The study produced a **conditional, lab-specific potential security concern**. It has not been reported to a vendor, has no external confirmation, and does not establish a general vulnerability or broad deployment impact. No third-party infrastructure was accessed.

Technical details are withheld while responsible-disclosure decisions remain unresolved. This page does not identify the affected product, configuration, or request pattern. It is not an exploit guide or vendor advisory.

## Evidence

- **VERIFIED within the local lab:** the result was observed only in the tested configuration and versions, with negative controls.
- **INFERRED:** relevance beyond that lab is unknown.
- **NOT_VERIFIED:** prevalence, production impact, vendor interpretation, and duplicate private reports.
