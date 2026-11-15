# Synthetic example: distinguish task evidence from model evidence use

This example was invented for this repository. **EvidenceMap and its draft text are fictional.** It contains no private manuscript material, experimental results, or numerical review score. The published comparison paper is real and is linked to its primary source.

## Input

The hypothetical author supplies only this contribution paragraph. It describes a proposed evaluation resource, not a completed experiment.

<a id="c1"></a>
**C1 — invented draft:**

> We propose EvidenceMap, an evaluation set that labels each document question with the passage required to answer it. The labels support grouping questions by evidence location. They also automatically reveal which evidence a model actually used.

**Requested task:** Review the contribution writing, use a relevant published example, and suggest a minimal fix. Do not score or rewrite the entire paragraph.

## Overview

The idea is an evaluation resource that makes task evidence requirements explicit. Keep the clear connection between passage labels and grouping questions by evidence location. The final sentence introduces a different capability: identifying evidence actually used by a model. The supplied text does not connect the task annotations to that model-use claim.

One required fix follows. This is a scope problem in the claim, not a judgement that the proposed resource cannot be useful or that unfinished experiments are a writing defect.

## Required fix: bound what the passage labels establish

**Original location — [C1, final sentence](#c1):**

> They also automatically reveal which evidence a model actually used.

**Problem and impact.** A passage required to answer a question and a passage used by a particular model are different objects. The first describes the task; the second describes model behavior. The paragraph establishes the former as an annotation design but gives no connection to the latter. Narrowing this sentence preserves the proposed labels and question grouping. It withdraws the additional ability to identify a model’s actual evidence use, so this change has a substantive effect on that capability claim.

**How another paper handles a comparable writing task — S1.** In *BigCodeBench*, the abstract and introduction first identify the limits of short, self-contained coding evaluations, then connect diverse library calls and complex instructions to the evaluation tasks the resource provides. This is a **paraphrase** of the [published paper, abstract and §1, pp. 1–3](https://proceedings.iclr.cc/paper_files/paper/2025/file/a6a90bcc2aa470c3871b2d39a67d26e8-Paper-Conference.pdf#page=1). It is an ICLR 2025 main-conference paper, with joint affiliations including Monash University, Singapore Management University, ServiceNow Research, and Hugging Face on p. 1; see the [official proceedings entry](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a6a90bcc2aa470c3871b2d39a67d26e8-Abstract-Conference.html).

The transferable writing move is to connect the resource’s design to the specific evaluation it makes possible. Applied to C1, describe what the passage labels let a reader group or inspect. This comparison supplies a writing example; it does not establish EvidenceMap’s model-use claim.

**Suggested action.** Retain the label definition and grouping purpose. Remove or narrow the final sentence to that established purpose. If the intended contribution really is identifying model evidence use, explain the existing basis for that stronger ability when available; do not invent a mechanism or result to fill the gap. A full replacement paragraph is unnecessary for the requested review.

## Sample index

| ID | Published source | Used for | Original location |
| --- | --- | --- | --- |
| S1 | *BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions*, ICLR 2025 main conference | Connecting resource design to the evaluation capability it enables | [Abstract and §1, pp. 1–3](https://proceedings.iclr.cc/paper_files/paper/2025/file/a6a90bcc2aa470c3871b2d39a67d26e8-Paper-Conference.pdf#page=1); [official venue entry](https://proceedings.iclr.cc/paper_files/paper/2025/hash/a6a90bcc2aa470c3871b2d39a67d26e8-Abstract-Conference.html) |

The paper and its venue entry were checked on 2026-11-15. This single example illustrates the output format; it is not a fixed exemplar list for future reviews. Actual reviews select sources using the current date and writing task.

[Back to English README](../README.md) · [返回中文说明](../README.zh-CN.md)
