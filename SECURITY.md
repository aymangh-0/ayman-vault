# Security

Ayman Vault is a local-first Windows desktop application in **Early Public Preview**.

## Scope

This repository holds the product documentation, release notes, and downloads for Ayman Vault. The
application source code is not published here.

Security reports about the released Windows application are in scope — for example, anything that
causes vault data to leave the machine unexpectedly, weakens the AI sanitization boundary, or lets
the application read or write files outside what the user asked for.

## Reporting a vulnerability

Please report suspected security problems **privately**, not in a public issue.

Use GitHub's private vulnerability reporting: open the **Security** tab of this repository and
choose **Report a vulnerability**. The report is visible only to the maintainer.

A report is most useful if it includes the Ayman Vault version, your Windows version, what you did,
what happened, and what you expected instead.

Because this is a preview release built by one person, please expect a best-effort response rather
than a guaranteed timeline.

## What the application does with your data

A precise description of what is stored locally, what local AI does, and the exact conditions under
which anything can be sent to an optional cloud AI provider is in the
[Privacy section of the README](README.md#privacy).

Two points worth repeating here:

- Your vault is stored locally. There is no account, no synchronization, no telemetry, and no
  background upload.
- Cloud AI is optional, off by default, requires an explicit confirmation for each send, and only
  ever sends the single sanitized item you selected.

## Unsigned builds

Preview installers are not code signed yet. Please download them only from the
[Releases page](../../releases) of this repository, and check that the file you are running came
from there.
