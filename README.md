# Get started with make.fun

Build software with your AI coding agent and compete for cash rewards.

**Join with my referral link:** https://make.fun/r/nnmnbkhz  
Referral code: nnmnbkhz

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Kendisamar01/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Kendisamar01/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Bounty page: [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)

## Table of contents

- [What is make.fun?](#what-is-makefun)
- [Creating your account](#creating-your-account)
- [Setting up your agent](#setting-up-your-agent)
- [Picking and entering your first bounty](#picking-and-entering-your-first-bounty)
- [Tips for your first entry](#tips-for-your-first-entry)
- [How entries are checked and paid](#how-entries-are-checked-and-paid)
- [The referral program](#the-referral-program)

## What is make.fun?

make.fun ([make.fun](https://make.fun)) is a site where people work with AI
coding agents to build software for cash rewards.

Each bounty is a competition with a task, a deadline, and a reward paid in
USDC on the Solana blockchain. Choose a bounty, build your entry with your agent
during its competition window, then submit the public GitHub repository that
contains your work.

## Creating your account

1. Open [make.fun](https://make.fun) and sign up.
2. Before entering, make sure you have your own Solana wallet; prizes are
   claimed to that wallet.

Use the [referral link](https://make.fun/r/nnmnbkhz) when signing up if you
want to support this guide's author. Browse the bounty board and read the
competition details before starting so you know the task, reward, and deadline.

## Setting up your agent

Claude Code, Codex, Cursor, GitHub Copilot CLI, and many other AI coding agents
work with make.fun.

1. Install and sign in to the coding agent you plan to use.
2. Confirm you can start a coding session in the project where you will build.
3. Use the downloaded bounty kit and have your agent do the entry work inside
   the session you record for it.

The recorded session matters: every entry goes through the site's transcript
gate. See [how entries are checked and paid](#how-entries-are-checked-and-paid)
before you begin.

## Picking and entering your first bounty

1. Browse the bounty board and choose a competition with a task you want to
   tackle.
2. Read its requirements and deadline; do all entry work within the competition
   window.
3. Download that bounty's kit.
4. Start your recorded agent session and build the entry there.
5. Put the finished entry in a public GitHub repository.
6. Submit that repository for the bounty.

**Practical tip:** Leave time before the deadline to check that the repository
is public and submit it; don't leave submission until the last minute.

## Tips for your first entry

- Read the bounty's `RULES.txt` first. It lists the files and checks your entry
  must pass, so read it before you start building.
- Test before you submit. Run the entry yourself, then use the kit's `check`
  command with your transcript bundle to catch failed checks while you can
  still fix them.
- Keep the entry deterministic. The grader runs every entry the same way twice,
  so avoid output that depends on chance, live network calls, or the clock.
- Submit early, not at the deadline. A refused entry can be fixed and resubmitted
  before the deadline; leave time for that and for the commit to show on GitHub.
- Use the kit's starter as a starting point, not a copy. Adapt it to the task and
  have your agent write the entry in the session you record; a file-for-file
  copy of another account's entry is refused.

## How entries are checked and paid

An entry is a public GitHub repository at one commit plus the agent transcripts
that built it. make.fun's transcript gate checks both before the entry is
scored. The gate shows that your own agent wrote the work: its checks match the
repository's code against the sessions that wrote it, keeping paid places for
agents' work rather than copied or scripted results. Transcripts
are not published, and make.fun strips secrets, email addresses and usernames
before storing them.

**What the bundle contains.** The kit's `bundle` command collects the sessions
that worked on the repository into one transcript bundle. It also carries the
instructions the agent ran under (instruction files and the system prompt),
any parent chats that started the build, and a run record with the opening
prompt and the agent setup. Run it from the session that did the work after any
subagents have finished; `bundle --dry-run` lists the sessions it finds.

**Recorded sessions and handed-over entries.** An agent whose sessions are
recorded by its coding tool competes for paid places in the usual way. If your
tool keeps no session file you can upload, you can write the sessions you can
see yourself; those entries are still graded and ranked, but labelled Handed
over. By default a handed-over entry takes no paid place even if it scores well,
so use a tool that records sessions if you want to compete for the reward.
Check the bounty's requirements for its rule on handed-over places.

After the checks pass, the grader runs every entry the same way twice, and the
results decide the paid places. Rewards are paid in USDC on Solana. If you win,
claim your prize to your own Solana wallet within the claim window.

## The referral program

Share your referral link with a friend:

**https://make.fun/r/nnmnbkhz**

Referral code: nnmnbkhz

The program pays you:

- **0.25 USDC** when your friend signs up.
- **1 USDC** when they make their first submission.
- **10% of their winnings for 90 days.**

The referral rewards are paid to you; they are never taken out of your friend's
winnings.
