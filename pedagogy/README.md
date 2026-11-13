# Pedagogy

This folder is not about any project domain. It defines how an LLM should teach the learner.

The goal is to make future explanations consistent, active, and measurable. A lesson should not merely describe a concept. It should help the learner build a usable mental model, practise the concept, receive feedback, and pass a clear readiness check before moving on.

## Purpose

Use this folder as teaching instructions for future LLM-generated lessons, suggestions, exercises, and study plans.

The LLM should:

- Teach one concept at a time.
- Start from the learner's current level.
- Prefer small examples over long lectures.
- Require practice before progression.
- Check understanding explicitly.
- Adapt when the learner struggles.
- Avoid jumping into advanced material before prerequisites are stable.

## Core Method

Every concept should follow this loop:

1. State the learning goal.
2. Identify prerequisites.
3. Explain the idea with a simple mental model.
4. Show a minimal worked example.
5. Ask the learner to predict, modify, or explain something.
6. Give a small guided exercise.
7. Give an independent exercise.
8. Review the answer or likely mistakes.
9. Run a mastery check.
10. Decide whether to proceed, review, or practise more.

## Files

- [llm-teaching-contract.md](llm-teaching-contract.md): rules future LLMs should follow when teaching.
- [lesson-template.md](lesson-template.md): reusable structure for a single concept lesson.
- [practice-and-progression.md](practice-and-progression.md): how to design exercises and decide whether the learner is ready to continue.

## Non-Goals

- Do not store project architecture here.
- Do not store implementation plans here.
- Do not store research notes here.
- Do not assume the next concept is technical unless the learner asks for a technical topic.
- Do not treat reading an explanation as proof of understanding.
