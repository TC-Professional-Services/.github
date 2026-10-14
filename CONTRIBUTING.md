# How we work

Every piece of work is a **ticket** (a GitHub issue) on the organisation's project board. Every
change to code goes in through a **pull request** (PR) linked to its ticket. That way the board
always shows what is being done, by whom, and the code that did it.

## From ticket to merged change

1. **Find or create the ticket.** On the board, use **+ Add item** at the bottom of a column to
   create one, so it lands on the board straight away. Use the **Task** or **Bug** form.
2. **Start work.** Drag the card to **In Progress**. On the ticket, under **Development** in the
   right-hand panel, click **Create a branch**.
3. **Make the change** on that branch. Commit and push.
4. **Open a pull request.** The description starts with `Closes #`. Add the ticket number, for
   example `Closes #12`. If the PR only does part of the ticket, write `Part of #12` instead.
   For a ticket in another repo, use its full name: `Closes TC-Professional-Services/repo-name#12`.
5. **Get it reviewed.** Someone else reads the PR under **Files changed** and comments or approves.
6. **Merge.** The ticket closes and its card moves to **Done** on its own.

## Rules that keep this working

- `main` is what is live. Nothing goes onto it except through a reviewed PR.
- One ticket per piece of work. If a ticket turns out to be two jobs, split it.
- Questions and decisions go as comments on the ticket, not in chat, so they stay with the work.
- Never commit passwords, API keys, logs, database dumps or anyone's personal data.

## GitHub's own guides

- Beginner course, done inside GitHub: https://github.com/skills/introduction-to-github
- About issues: https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues
- Using a project board: https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects
- Creating a branch for an issue: https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-a-branch-for-an-issue
- About pull requests: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
- Linking a pull request to an issue: https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue
- Reviewing a pull request: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request
