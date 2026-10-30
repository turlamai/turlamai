# Product documentation policy

This policy applies to first-party product READMEs, product websites, user guides, and public help pages. It is a writing standard, not a feature or release claim.

## Product-first, no unsolicited promotion

- Explain what our product does, its limitations, supported platforms, installation and recovery paths.
- Do not advertise or compare against unrelated commercial products in introductory copy, comparison tables, slogans, or outbound promotional links.
- Retain strictly necessary mentions of third-party software when describing real integrations, supported input formats, build tools, dependencies, compatibility, license obligations, security disclosures, or platform requirements. Such mentions must be neutral and factual.
- Do not remove attribution, license notices, copyright, or required upstream documentation.
- Avoid benchmarks or superiority claims unless reproducible and dated.

## Text-first, screenshot-independent user guides

Document user tasks rather than pixel positions:

1. **Goal:** State what the user is trying to accomplish.
2. **Prerequisites:** Required version, permission, file, environment, or account.
3. **Action:** Use stable feature names, commands, menu labels, keyboard shortcuts, or accessibility labels. Explain platform differences inline.
4. **Expected result:** Give an observable success condition.
5. **Recovery:** State how to undo, cancel, retry, or troubleshoot.
6. **Applicability:** State affected versions/platforms and known limitations.

Screenshots are optional supplemental evidence only; no essential instruction may depend on an image. Avoid "click the blue button" or "as shown below". Prefer concise Markdown tables for options, copyable CLI commands with expected outputs, and Mermaid for workflows (always include equivalent text). Accessibility names and UI terminology should be stable or tested where practical.

## README structure

1. Product identity and honest one-paragraph purpose.
2. Capabilities currently shipped; separate planned work.
3. Install / quick start, including supported platforms.
4. Task-focused documentation index.
5. Privacy, data location, backup/recovery, and relevant third-party service disclosures.
6. Development / testing (if applicable).
7. License and support.

## Review checklist

- No unnecessary competitor publicity or implied endorsement.
- Genuine dependencies, service providers, and mandatory notices remain accurate.
- Every user task is comprehensible without an image or video.
- Instructions describe behavior in the *currently shipped* version; not aspirations.
- Menu labels, keyboard shortcuts, CLI flags, and file paths checked against product implementation.
- Platform differences, limitations, privacy, and failure states are explicit.
- Links and anchors are valid; English and Chinese guides remain aligned where both exist.
- Significant UI changes trigger documentation review, but never require mass screenshot re-capture.
