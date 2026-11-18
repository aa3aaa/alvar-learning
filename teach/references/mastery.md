# Mastery

A step is not finished because it was taught, or because a wrong answer was corrected. It is finished when the learner shows they can do it unaided. This applies to **lesson steps**: every node of a plan, inserted prerequisites included. Probes and recall rounds keep their own rules.

## The bar

A node is `mastered` on **one clean answer**:

- the decisive step, the result and the reason are all correct;
- on a question the learner has had no feedback on: no hint, walkthrough, correction or earlier attempt at that same question;
- with nothing left for the tutor to correct in what the node tests.

A clean first answer to the node's lock-in is mastery; no extra question is needed. An answer that needed a correction to what the node tests is a miss, however small the correction. There is no "locked in with corrections". A slip in something the node does not test (a typo, a missing bracket in a node that is not about syntax, arithmetic the prompt waived) is pointed out and does not block.

## After a miss

1. **Feedback.** Verdict first. Say what is right, name exactly what is wrong, and give the governing rule, without the full solution. Route as [lock-in-response.md](lock-in-response.md) and [discovery.md](discovery.md) say (retry, discovery, or an inserted prerequisite).
2. **Fix in place.** The learner corrects the same answer (same check `id`, their earlier answer left there to edit) until it is fully right. Ask again for anything still wrong or unanswered. A fixed answer shows the feedback was understood. It is never mastery, because the feedback did part of the work.
3. **Mastery question.** When the fix is right, offer a new question on the same idea: a fresh scenario, data and wording, a new check `id`, no hints, written by the prompt rules in [lock-in-response.md](lock-in-response.md). When the miss was in one part of the check, make the new question the size of that one idea, not a repeat of the whole check. A clean answer is mastery. A miss starts the loop again at step 1, and the next mastery question is fresh again.

Do not teach, show or preview the next node while this loop is open. Side questions are still answered.

## Skipping

The only way past a node that is not mastered is the learner saying so: "skip", "move on", or declining the mastery question. Honour it without arguing. Record the node as `not mastered`, make its recall card as for a taught-not-verified node, and say in one line that it will come back. A `not mastered` node comes back first in the next session, before any new node, as a mastery question. Never skip on the learner's behalf: not for time, not after many attempts, not because the answer was close.

## Records

- Session log, per node: each attempt with which question it was (`first question`, `fix`, `mastery question <k>`) and the result: `mastered` | `retry` | `insert-prereq` | `not mastered (skipped)`.
- Plan progress (`progress.done` on the live lesson page, the Resume block's "locked" list) counts mastered nodes only. The Scribe lists `not mastered` nodes first in Plan status, separately.
- On the live lesson page, title the check `Mastery question` when it is one, and keep the full previous attempt in `last_result` as usual.
- Wherever another file says a node "locks in" or a "lock-in passes" as the condition to advance or to make a recall card, read "is mastered". In logs written before this rule, `lock-in` reads as `mastered`.
