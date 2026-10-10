# How to contribute

## Rules

1. One entry is one line: `- [Title](https://link) - why it helps us, 5-20 words.` Write in English.
2. Add entries to the end of the file. After a file has sections: to the end of a section.
3. No duplicate links in the whole list.
4. A pull request changes one file and adds 1-2 entries.
5. Branch name: `<your-github-login>/<topic>`, for example `ana/anki`.
6. A commit message says what changed, for example `Add Anki to study.md`.
7. Never push to `main`. Every change goes through a pull request.

## Steps

1. Create a branch, add your entries, commit, push.
2. Open a pull request.
3. A classmate reviews it. Answer comments with new commits.
4. After a human approve, the bot checks the rules. Fix what it finds.
5. When the last commit has a human approve and a bot approve, merge the pull request yourself.
6. If the pull request has a conflict: merge `main` into your branch on your computer, resolve the conflict, push.

## Review

- Pull requests without review: [is:pr is:open review:none](https://github.com/pe-teaching/sdt2026-awesome-list-sandbox/pulls?q=is%3Apr+is%3Aopen+review%3Anone).
- Check the rules, the link, and the section. Is the entry useful? Is the description true?
- Leave at least one line comment: an error or a question. Approve after the answer or the fix.
- An approve counts only on the last commit.

## Points

Two boxes, 0-10 each: author and reviewer. 20 points in total: you are done. A penalty comes from its box; one more pull request or review wins the points back.

| Event | Box | Points |
|---|---|---|
| Your pull request is merged with a human approve and a bot approve on the last commit (one per file) | author | +5 |
| Your pull request is merged without one of these approves | author | -2 |
| You pushed to `main` directly | author | -3 |
| Your merge lost an entry of another person | author | -3 per entry |
| The bot rates your commit message as bad | author | -1 |
| You approved after your own line comment (one per author) | reviewer | +5 |
| You approved with no comment | reviewer | -2 |
| The bot found a rule violation after your approve | reviewer | -2 |

⭐ for a review when your reviewer box is full.
