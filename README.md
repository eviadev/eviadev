# Evan — developer tools & applied AI

I build software that **explains itself**.

My focus is evidence-first engineering: systems that preserve sources, expose uncertainty, measure quality, and keep humans in control. I enjoy working where backend engineering, product thinking, and applied AI meet.

## Featured builds

### [ReviewReplay](https://github.com/eviadev/review-replay)

**Replay yesterday's bugs to measure today's code-review agents.**

ReviewReplay turns historical bug-fix commits into blind evaluation cases. The reviewer sees a buggy snapshot; the scoring oracle keeps the later fix separate and measures localization precision, recall, and F1.

- provider-independent and fully local;
- task/oracle separation with an explicit leakage threat model;
- one-to-one matching so duplicate findings cannot inflate scores;
- micro and macro metrics across benchmark suites;
- real temporary Git repositories in tests;
- CI on Python 3.11, 3.12, and 3.13.

`Python` · `AI evaluation` · `Git internals` · `CLI` · `Reproducible benchmarks`

### [ClauseScope](https://github.com/eviadev/clause-scope)

**Contract review where every result keeps its evidence.**

ClauseScope is a full-stack review workflow for synthetic PDF and DOCX contracts. It connects exact extracts and locations to version diffs, evaluation metrics, and append-only human decisions.

- detects clauses with extracts, page/section provenance, offsets, and confidence;
- compares added, removed, modified, and unchanged obligations;
- generates a one-click synthetic before/after DOCX demonstration;
- keeps approvals and change requests in an audit trail;
- evaluates 14 annotated cases with per-clause errors and CI quality gates;
- validates 18 backend tests and 30 frontend tests in CI.

`FastAPI` · `React` · `TypeScript` · `SQLAlchemy` · `Document intelligence` · `Human-in-the-loop`

> Synthetic benchmark scores are regression signals, not claims about real-contract accuracy or legal advice.

### [ChangeAtlas](https://github.com/eviadev/change-atlas)

**Software archaeology for answering _why does this code exist?_**

ChangeAtlas reconstructs a file's history across renames and turns Git commits into a deterministic evidence graph. Every explanation remains traceable to the repository instead of becoming an unverifiable summary.

- follows file history through renames;
- traces an exact line to its last-changing commit with `git blame`;
- extracts linked GitHub issues, PRs, and commit references from intent text;
- emits a temporal `commit → file/reference` graph for downstream tools;
- ranks hotspots using commit frequency and churn;
- tests behavior against real temporary Git repositories;
- runs CI on Python 3.11, 3.12, and 3.13.

`Python` · `Git internals` · `CLI` · `Evidence graphs` · `GitHub Actions`

## How I approach engineering

| Principle | What it means in practice |
| --- | --- |
| **Evidence over plausibility** | A useful answer should show where it came from. |
| **Evaluation before demo polish** | Tests and failure cases belong beside the feature. |
| **Human decisions stay explicit** | Review, overrides, and audit trails are product features. |
| **Small trusted core** | Deterministic foundations first; AI is added where it creates measurable value. |
| **Privacy by design** | Local-first and least-privilege defaults whenever possible. |

## Current direction

I am building a portfolio around difficult, under-served problems:

- developer intelligence that connects code to its historical intent;
- document intelligence with exact evidence and human review;
- AI evaluation tools that make failures inspectable rather than invisible.

I am interested in **backend, full-stack, developer tooling, and applied AI roles** where technical depth and product judgment matter.

---

If a project interests you, open its repository: the README explains the problem, the trade-offs, and how to verify it locally.
