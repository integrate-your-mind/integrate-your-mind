# Public resume validation

Date: 2026-10-25

## Artifact

The reviewed artifact is `Romy-Mondello-Resume.pdf` from the supplied cv-polish worktree. SHA-256: `f486219a3b4ebe1020f5ad1a65885f1641c6a028fb0d55144b512073aa1fa2a9`.

The PDF was extracted with `pdftotext -layout` into a local ignored work file. The raw extraction remains uncommitted and is not reproduced here.

## Validator result

The current `resume-fact-contract.mjs` validator returned `ok: false` with two issues:

1. The PDF does not contain the canonical six-year professional software-engineering statement.
2. The PDF does not contain the canonical phone number.

The file does contain the canonical name, email, Somerville location, Knox Financial, 2020 start year, and Associate of Science education. It contains no unsupported bachelor-degree wording.

## Public-safe claim corrections required

- Add a concise canonical experience statement such as “Six years of professional software-engineering experience since joining Knox Financial in 2020.” Keep independent AI work separate from paid employment.
- Restore the canonical phone contact if this public resume is intended to satisfy the current resume contract.
- Replace the Agent Cloud sentence claiming that a job “resumes after a crash.” Current canonical evidence supports a private/local prototype with Temporal orchestration, PostgreSQL-authoritative state, durable outbox delivery, fenced workers, policy/cost controls, and explicit cancellation/recovery boundaries. It does not establish automatic post-loss recovery or production deployment.
- Keep `Further` as February through April 2025 or use the exact February 10 through April 14 dates. Keep Verizon’s title as `Customer Solutions`.
- The QQ bullet accurately describes merged PR #72, but newer public merged work exists in PRs #333 and #319. Root should decide whether the public resume needs a fresh attributable-contribution line. Do not claim full QQ ownership, deployment, or a complete end-to-end reliability result.

## Current public CV status

The public CV is stale relative to the current canonical safety boundary. Its Agent Cloud recovery and scale wording should be narrowed before publication. The reviewed PDF is not publish-ready under the current fact contract until the two validator failures and the Agent Cloud overclaim are corrected.

## Unresolved current-source limits

No public-safe Ghost Data or Pele claim was established in the canonical sources reviewed. JEV provider validation was unavailable and was not retried. The private career checkout contained unrelated uncommitted changes and was not modified.

## Existing validated future-use candidate

Candidate: `/Users/romanmondello/career/output/typesafe-model-capabilities-2026-09-26/romy-mondello-resume-v3-one-page.pdf`

SHA-256: `68c57b225c316dcefad6c7cbfe1237fdcbd978d2b809dc1e772ed2852e567811`.

Receipt: `/Users/romanmondello/career/output/typesafe-model-capabilities-2026-09-26/validation-v3-one-page.json`; it reports one page, 42 claims checked, factual `ok:true`, and no issues. The current validator also returns `ok:true` for this exact PDF. It contains the canonical six-year statement and phone, but the phone is private contact data and is not a reason to add a phone to the public version.

This candidate is not current enough to publish unchanged. Its text still says Agent Cloud “so a job resumes after a crash” and describes QQ as new open/unmerged `#189`; current public-safe wording should describe a bounded local prototype with explicit cancellation/recovery boundaries and use verified merged QQ PR #333/#319 evidence instead. It also predates the current JEV Codex+Claude wording. It is a useful validated base, not an accepted replacement artifact.

## HTML candidate review

Reviewed `/Users/romanmondello/Documents/Codex/2026-10-15/pl/work/cv-polish-20261025/index.html` at commit `fcd341ebc68317c67dd7a6d433f9cc45323d92b1`; exact blob `de10a83e778a704ec8c7e602c956d199868d8df1`.

The HTML candidate is employer-facing and public-safe in the reviewed content: email only, no street address or phone, six-year statement, bounded local Agent Cloud prototype wording, JEV explicitly labeled open-source Codex + Claude Code plugin, and QQ links to merged PR #72, #333 (held-tool cancellation/restart recovery), and #319 (shared JEV protocol/provenance). It avoids production, scale, customer-adoption, or full-loop claims.

The download target `assets/Romy-Mondello-Resume.pdf` still hashes to `f486219a3b4ebe1020f5ad1a65885f1641c6a028fb0d55144b512073aa1fa2a9`; its extracted text contains the unsupported crash-resumption claim. The HTML therefore passes content review only if the linked PDF is replaced or corrected before publication. Broad research wording (“code verification, exploit research, CTFs, prompt injection, and jailbreak evaluation”) is generic and privacy-safe, but should remain bounded to research/prototypes and not imply product security ownership.
