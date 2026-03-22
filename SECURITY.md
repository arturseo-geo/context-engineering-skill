# Security Policy

## Scope

This repository contains documentation and configuration guidance for Claude Code context engineering. It does not contain executable code that handles user data, authentication, or network requests.

## What to Report

- **Prompt injection risks** — Content that could be exploited to manipulate Claude's behavior in unintended ways
- **Credential exposure** — Examples that accidentally include real API keys, tokens, or secrets
- **Dangerous commands** — Recommended commands that could cause data loss or system damage without adequate warning
- **Misleading security guidance** — Instructions that would weaken a user's security posture

## How to Report

For security concerns, please email **arturseo.geo@gmail.com** with:

1. Description of the vulnerability
2. Which file and section is affected
3. Potential impact
4. Suggested fix (if you have one)

You will receive a response within 7 days.

## What Is Not a Security Issue

- Inaccurate token counts or configuration advice (use a bug report instead)
- Claude Code platform vulnerabilities (report to Anthropic directly)
- General questions about context engineering (open a discussion or issue)

## Supported Versions

Only the latest version on the `main` branch is supported. There are no versioned releases to track.
