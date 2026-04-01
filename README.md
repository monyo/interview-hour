# interview-hour

A Claude Code skill for interview preparation and candidate evaluation.

**Core belief:** The hard part is not knowledge gaps — it's the stories you think
you can tell but actually can't. Find the gaps before the interviewer does.

## What it does

Two modes:

**Practice mode** — You are preparing for an upcoming interview. The AI plays a
demanding hiring manager who has read your resume and researched the company. It
drills your real experience layer by layer, finds the gaps you didn't know you had,
and gives you a concrete debrief at the end.

**Eval mode** — A real candidate is sitting in front of a prepared computer. The AI
conducts the interview and produces a structured report for the hiring manager.
The candidate does not see the report.

## Why it's different

Most interview prep tools give you a list of common questions to memorize. This one
pressure-tests your actual experience the same way a good interviewer would:

- Reads your resume before you say a word, and has questions ready
- Researches the company so questions are grounded in real context
- Watches for "we" when you should be saying "I"
- Presses on skipped steps (e.g. "you said you got approval — how exactly did you do that?")
- Evaluates technical claims against current knowledge — a method that was standard
  in 2010 but obsolete by 2018 is a signal
- Has no social cost — asks the questions a human interviewer might swallow to avoid
  looking foolish or offending a candidate with a prestigious background

## Install

```bash
git clone https://github.com/monyo/interview-hour.git ~/.claude/skills/interview-hour
```

Or use the setup script:

```bash
git clone https://github.com/monyo/interview-hour.git
cd interview-hour
./setup
```

Restart Claude Code. Then type `/interview-hour` to begin.

## Usage

Start a new Claude Code session and type:

```
/interview-hour
```

You will be asked for:
1. Role, level, and company you are interviewing for
2. Job description (paste text or provide a URL)
3. Resume (paste text or provide a file path — PDF is supported)

The AI will read your resume, research the company, then begin.

## Requirements

- [Claude Code](https://claude.ai/code)
- No other dependencies
