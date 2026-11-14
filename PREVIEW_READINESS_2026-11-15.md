# EPIC Network / Echo Protocol Z — Development Preview Readiness

**Target:** November 15, 2026, 3:00 PM Pacific (PST)
**Scope:** Public development preview, **not** audited production launch, token offering, or permission to move funds.

## Confirmed in repository (November 14)
- [x] Homepage includes a link to `echo-protocol-z-whitepaper.html`.
- [x] Whitepaper v0.2 documents Echo Logic, fragmentation, ZK-STP, VDF research, routing economics, security assumptions, and roadmap.
- [x] Homepage offers a developer interest contact link.
- [x] Public language distinguishes Amoy development from mainnet production authorization.

## Manual live-site checks — not yet confirmed
- [ ] Homepage returns HTTP 200 from a public browser and renders on desktop/mobile.
- [ ] Whitepaper page returns HTTP 200 and shows Version 0.2 and Echo Logic sections.
- [ ] Homepage whitepaper link opens the intended page.
- [ ] Developer interest link opens a correctly addressed email draft; verify recipient and privacy expectations.
- [ ] Review mobile navigation, contrast, reduced-motion behavior, and broken links.
- [ ] Confirm GitHub Pages deployment is green and latest main commit is deployed.

## Security release gates — blockers for production, not for a clearly labeled preview
- [ ] Reproduce clean checkout builds and full test suite from a pinned commit.
- [ ] Investigate and independently verify Groth16 zkey / trusted-setup artifacts (prior 'INVALID: Invalid alpha1').
- [ ] Triage dependency audit findings and remediate or document mitigations.
- [ ] Independently review smart-account authorization, owner/admin paths, nullifiers, delegation, token allowances, and all asset-moving paths.
- [ ] Obtain independent Solidity and Circom audit, remediate findings, rerun tests.
- [ ] Require explicit approval before any new mainnet deployment or fund-moving action.

## Preview talking points
1. What Echo Protocol Z is attempting: contextual, zero-knowledge-gated authorization.
2. What has been tested: developer-reported V3/V4 Amoy contract integration and 403 Hardhat passing tests on a frozen development environment.
3. What is proposed rather than implemented: full fragmented multi-hop transport, hardware-rooted time/location, VDF integration, and Proof-of-Routing incentives.
4. What remains before production: trusted-setup integrity, reproducible builds, dependency remediation, and independent audit.
5. Next action for interested developers: read the whitepaper and use the interest contact link.

## Go / no-go
**Go for development preview** only after public website and links are checked and claims remain accurate. **No-go for production authorization activation** until security gates are closed.
