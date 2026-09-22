<!-- Template: this file is authored per repository. The sections below are what a typical
     library needs, not a fixed list — drop any that do not apply to this library, and add a
     section for anything it has that is not covered here. Fill each section with the actual
     design and delete the TODO lines. Design rationale and constraints live here and nowhere
     else — GUIDELINES.md covers how code is written, AGENTS.md points here rather than
     restating it. Delete this comment when done. -->

# Architecture

The design decisions behind {{Project name}} and the reasoning that holds them together. This
document answers **why** the library is shaped the way it is. For **how** to write code that fits
— naming, ordering, idioms — see [`GUIDELINES.md`](GUIDELINES.md).

It is read by humans and by AI agents alike, to ground design choices in this project's
constraints rather than generic patterns.

## Overview

<!-- TODO: what the library is, who consumes it, and the two or three properties every module is
     built to preserve (e.g. safe defaults, composability, auditability). -->

## Repository layout

<!-- TODO: the package/module map — one line per top-level unit saying what it owns and what it
     depends on. Name the boundaries that are also audit boundaries. -->

## Core design principles

<!-- TODO: one `###` subsection per principle. State the rule, the reason, and what it rules out.
     Typical candidates: access-control model, ownership and custody model, composability with
     the ecosystem's transaction primitives, bounded state, fail-closed defaults. -->

## State and storage model

<!-- TODO: how state is represented and where it lives, size and growth bounds, what is
     immutable after creation, and the invariants that must hold across every public entry
     point. -->

## Asset handling

<!-- TODO: how value is held, moved and accounted for; who can move it and under which
     capability; the rounding and conservation rules; what is checked on every transfer. -->

## Upgrade and versioning

<!-- TODO: whether and how modules can be upgraded, who holds the authority, what is frozen,
     how storage compatibility is preserved across versions, and how consumers pin versions. -->

## Testing architecture

<!-- TODO: how the test suite is organised to mirror the module map, which invariants have
     dedicated tests, how failure paths are exercised, and what integration or end-to-end tests
     exist beyond unit tests. The conventions themselves live in GUIDELINES.md. -->

## Constraints and non-goals

<!-- TODO: platform limits the design works around, features deliberately not provided and why,
     and known trade-offs a reviewer should not re-open. -->
