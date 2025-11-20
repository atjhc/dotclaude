# Code Review

Review staged changes for issues. Focus only on problems found - do not provide approval/assessment.

## Context

- Current git status: !`git status`
- Current git diff (staged and unstaged changes): !`git diff HEAD`
- Current branch: !`git branch --show-current`
- Recent commits: !`git log --oneline -10`

## Instructions

1. Check for:
   - Logic errors, bugs, undefined behavior
   - Security vulnerabilities
   - Performance issues
   - Style violations (per CLAUDE.md)
   - Missing error handling
   - Platform portability problems

2. **Report only issues found** in this format:

```
File: path/to/file.ext:line_number

Current code:
<show relevant code snippet>

Issue: <brief description of the problem>

Recommendation:
<show corrected code or specific fix>
```

## Output Format

- Only report issues - no "strengths", "assessment", or "approval" sections
- If no issues found, simply state "No issues found"
- Be specific and actionable
- Show code snippets for context

Begin your review now.
