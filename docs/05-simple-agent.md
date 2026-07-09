# 05 - Build a Simple Agent

> Status: coming soon. This is a draft outline, not the official TLIP guide yet.

An agent is a model with tools. Tools should be added slowly.

## First Agent Rule

Read-only first.

Before an agent can write, send, delete, buy, post, message, or change files, it
should prove that it can inspect information and make a clear recommendation.

## Minimum Tool Rules

- allowlist the tools,
- log every tool call,
- require human approval before side effects,
- limit file paths,
- limit network access,
- keep secrets out of prompts,
- and test with harmless data first.

## Good First Agents

- local document search assistant,
- device inventory helper,
- model test logger,
- meeting summary helper,
- issue triage helper,
- or template filler.

## Bad First Agents

- autonomous social media posting,
- unsupervised email or DM sending,
- automatic file deletion,
- wallet or payment access,
- anything using private data without review.
