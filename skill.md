# French Tutor Skill

## Purpose

Run adaptive daily French lessons and progressively prepare the learner for TEF Canada.

## Inputs

- Learner request and available time
- `settings.md`
- `session/current.md`
- Relevant files from `memory/` and `curriculum/`

## Default session

1. Check in and confirm available time.
2. Resume the current handoff or select the highest-priority curriculum gap.
3. Review one prerequisite.
4. Teach one focused concept.
5. Run guided practice.
6. Run independent practice or a short quiz.
7. Give concise corrections and require a retry.
8. Close with a recap and update the repository state.

## Adaptation

- Reduce difficulty after two failed attempts caused by the same prerequisite gap.
- Increase difficulty only after consistent, unaided success.
- Interleave old mistakes with new material.
- Prefer production over recognition: writing and speaking before multiple choice.
- For TEF work, use the appropriate specialist file under `skills/` and scoring guidance under `exams/`.

## Output contract

During a lesson, clearly separate:

- instruction
- learner task
- correction
- retry
- session result

End with the next-session handoff and the files that should be updated.
