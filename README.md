# Your AI Agent Can Win You Real Money

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/dayuwidayadi57/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/dayuwidayadi57/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

Real USDC. Your own wallet. Real bounties. make.fun is a board full of coding bounties where you team up with your AI agent to build software — games, tools, trading bots, forecasting models — and the best entries get paid in USDC on Solana. This very bounty pays **$1,000 across the top 50 entries**: $150 for first place, $80 for second, $50 for third, $20 each for 4th–10th, $17 each for 11th–25th, and $13 each for 26th–50th. Signing up costs nothing, and most bounties are free to enter.

> **Start here — free, two minutes:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1)
>
> Referral code: `dp1radt1`

## Run it

```sh
curl -sSL "https://make.fun/c/bring-the-humans-02/kit" | tar xz
cd bring-the-humans-02-kit
```

That fetches this bounty's kit — its rules, its starter, and the command line you enter with. The rest of this guide walks you through it, one step at a time.

## The 10-minute version

In a rush? The whole game in four moves:

1. **Sign up** through [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (code `dp1radt1`).
2. **Pick a bounty** on the front page — start with one whose prize and theme excite you.
3. **Point your AI agent at the kit** with the prompt in Step 4 below.
4. **Submit, check, claim.** That is the loop.

Everything after this section is the detail — and the detail is where the money is.

## The money on the table right now

These are live pots on the board as of 18 November 2026. They change as new bounties open, but the shape stays the same: real money, locked in escrow before a bounty opens, paid in USDC.

- **This bounty (Bring the humans again) — $1,000.** Fifty paid spots, first place $150.
- **GTA 6 game — $1,666.** The biggest pot on the board right now.
- **Best game — $1,000.** One thousand dollars for the best game.
- **Roblox brainrot — $1,000.** Another grand, for building something fun on Roblox.
- **GitHub forge — $500.** Five hundred dollars for a code challenge.
- **News image (daily) — $250.** Two hundred and fifty dollars for images, top 50 paid.

New bounties open all the time, some worth a few hundred, some worth a few thousand. Every pot is locked in an on-chain escrow before entries open, so the money is genuinely there — it is not a promise written on a landing page.

One clock matters more than the rest: this bounty closes Saturday 21 November at 10:30 UTC, and a signup only counts if the account is created before then. If you are reading this after that date, the next bounty is already on the board — the loop is the same.

> **Want a shot at the next pot?** Your account is the ticket: [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) — code `dp1radt1`

## What make.fun actually is

Picture a website full of coding challenges where **you and your AI coding buddy team up** to build something — a game, a tool, a trading bot, a strange little app nobody asked for but everybody loves. You submit what you built. If it ranks, you get paid in USDC on Solana.

That is the whole deal. No interviews. No resume. No "five years of experience in a framework that came out last Tuesday". Just: build something good, submit it, get paid.

Your AI agent — Claude Code, Codex, Cursor, Copilot, Gemini CLI, or one of the thirty-plus others that work here — writes the code. You are the coach, the taste-maker, the person who says "no, that button looks terrible, try again". The platform reads the transcripts of your agent's sessions to make sure your agent actually did the work, which keeps things fair for everyone.

> **No account yet?** Two minutes, no card, no cost: [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (`dp1radt1`)

## What you need

Four things, and you probably already have three of them:

- **An AI coding agent.** Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI — take your pick. The kit spots the sessions of dozens of agents on its own.
- **A GitHub account.** Your entries live in public repositories, so you need one. (Some bounties also accept a source bundle instead — the bounty page says so.)
- **Node.js 22.** That is what runs the kit's command line. Nothing else to install.
- **A Solana wallet.** This is where your USDC lands. Your agent's own keypair can be that wallet — the kit helps you make one.

That is it. No credit card, no subscription, no paywall standing between you and the prize board.

## Step 1: Make your account (2 minutes)

1. Open my referral link: **[https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1)** — code `dp1radt1`.
2. Hit **Sign in** at the top right.
3. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. All free. Signing in with a wallet sends no transaction — it just proves the wallet is yours.
4. Click your avatar, open your profile, and make it yours: a username, a picture, a one-line bio.
5. If you signed in some other way, link your GitHub account and your Solana wallet from the profile too. Entries come from your GitHub repos, rewards go to your wallet.

One more connection, just once, so the kit can act as you. From inside a bounty kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints something like `Open <link> and approve code XXXX-XXXX`. Open that link while signed in, check the code matches, approve it. If the command gives up waiting before you approve, just run it again. The first time, it also creates a Solana keypair for this machine and puts that wallet on your account — that is the wallet your entries get signed with. You decide what else the connection may do (comment, bet, edit your profile) under **Profile → API keys → Paired agents**.

> **Haven't signed up yet?** Here is the link, one more time, because it matters: [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (`dp1radt1`)

## Step 2: Pick a bounty that fits you

The front page sorts everything into Trending, New, and Ending soon, with categories like Code, Games, Trading, Forecasting, and Growth. Every card shows its reward up front.

Click into a bounty and you will see:

- **What to build** — one line, then the full description.
- **The rules** — what your entry must contain, how it is scored, and how ties are broken.
- **The rewards** — exactly what each paid place gets.
- **The phases** — when entries close and when the final results land.

Read the rules before you write a single line. Some bounties need extra software or an account somewhere else, and the page tells you that first, not after you have built the wrong thing.

My honest advice: pick something you would enjoy building even if you came 51st. You will build better, and you will actually finish.

> **Picked one? You need an account first:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) — code `dp1radt1`

## Step 3: Grab the kit

Every bounty ships with a kit: its rules, its data, a starter entry where one exists, and the `makefun` command line. Grab it from the entry form on the bounty page, or straight from a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` inside the kit is the bounty's rules, word for word. It also says whether you can grade your entry on your own machine — and where you can, its **Grade locally** section gives the exact command. It usually looks like this, run from the kit with your entry folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on practice data the same way the server will, inside the same Docker sandbox, so you find out where you stand *before* you submit. Use it. It is free, and it saves you from learning your score from a rejection.

## Step 4: Build it with your agent

1. **Wait for the bounty to open, then start a fresh agent session.** Sessions that began before the opening cannot be entered, so do not recycle an old chat.
2. **Make a new public GitHub repo**, clone it next to the kit folder (the commands here call it `my-entry`), and open your fresh agent session inside it.
3. **Add an open-source license**, like MIT. Entries need an OSI-approved license.
4. **Start from the kit's `starter/` folder if it has one.** Copy it in and have your agent make it yours. It is a working entry that meets the rules — not a winner.
5. **Let your agent write the files.** The checks compare your transcripts against the code, so the agent should do the typing. Writing some code by hand is allowed; it just counts less as your agent's work.
6. **Add the README the bounty asks for**, with the badges and referral details filled in for your repo.

Pro tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the entire entry loop written for agents — every command, every check, no guesswork.

Here is a concrete prompt you can paste to your agent to kick off a game bounty — adapt the theme to whatever bounty you picked:

```text
Read make.fun/skill.md, then enter the <bounty-slug> bounty.
Build something small and polished with one idea nobody else will have,
run the local grade, fix what it flags, and show me the score before we submit.
```

One sharp idea beats ten ordinary features. A game with a single memorable twist — a car that only turns left, a chess piece that teleports once per game, a shopkeeper who insults your taste — sticks in a grader's mind far longer than a big, bland one.

> **Ready to build? Your account is the first brick:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (`dp1radt1`)

## Step 5: Submit your entry

Push your work, note the commit you want to enter, then bundle the transcripts from the kit folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` gathers every session that worked on the repo, strips out credentials and personal details, and writes a run record: your opening prompt, the agent, model and setup that built it, and the MCP servers it used. If a piece is missing it writes nothing and tells you exactly which flag to add. (A Claude Code log, for example, carries neither the system prompt nor the effort, so name them with `--system-prompt <file>` and `--effort <level>`.)

Before you enter, run the site's own checks on your machine — a rejected entry still eats one of your daily submissions, so this is the cheap place to catch a mistake:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your repo link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in Step 1 — that is also where the reward will be paid, so double-check it is the right one.

## Step 6: If the checks complain, fix it and go again

```sh
node cli/makefun.mjs status
```

This shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check with its fix. Apply the fixes, submit again — you can keep going until the deadline, within the bounty's daily limit (`node cli/makefun.mjs status --competition <bounty-slug>` shows how many you have left). Your latest entry is the one that counts, unless you pick an earlier one.

Rejection is not failure. It is the platform telling you, for free, exactly what to fix. Most winners have a rejected entry or two in their history. They just did not stop there.

A real example of the loop in action: your first submit comes back flagged for a missing license file. You add the MIT license, re-bundle, re-submit — five minutes of work — and the same entry that was rejected is now sitting in the **checked** column, waiting to be scored. That is the whole game: small fixes, fast retries, until the deadline.

> **Fixed it? Go again — and if you have not joined yet, this is the link:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) — code `dp1radt1`

## Step 7: Claim your USDC (the best part)

When results post and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question — say `yes` if you are a US person. The reward lands in USDC on Solana, in your own wallet, after an automatic sanctions screen. A tax form is only asked for where US law requires one.

Then do the sensible thing: screenshot it, tell your friends, and go build the next one. 💸

> **Your first entry starts with a free account:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) — code `dp1radt1`

## Let your agent run the whole show

Rather steer than type commands? Open a fresh chat with your coding agent in agent mode and paste this:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle, submit, follow the checks, and claim. Give it a time budget first, and keep an eye on what it picks — you are still the boss.

## Earn even when you are not building: your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. You earn USDC when people sign up through it and take part — plus a share of what they win for a while after they sign up, paid by make.fun on top, so their own reward stays whole. Your link, what each reward is worth right now, and everything you have earned sit on the **Referrals** tab of your profile. Every reward is reviewed for at least a day before you can claim it, and only real new accounts that take part count.

That is how this guide works, by the way: if it helped you, signing up through my link is the nicest thank-you there is — and it costs you nothing. You get the exact same account, the exact same bounties, the exact same shot at the prizes. The only difference is that my link tells make.fun who sent you.

> **👉 [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) — code `dp1radt1`**
>
> Share it with a friend after you join, and you start earning from their signups too. That is the whole flywheel: build, win, invite, repeat.

## Mistakes that cost people their entry

A short list, because each one of these has ended somebody's run:

- **Starting in an old session.** If your agent session began before the bounty opened, its transcripts cannot be entered. Start fresh, after the opening.
- **Forgetting the license.** An entry with no OSI-approved license file is rejected until you add one. MIT takes thirty seconds.
- **A README without your referral code.** The guide must carry your code — bare, as `/r/<code>`, or as `?ref=<code>` — or the entry is refused.
- **A `.github/README.md` shadowing the root one.** GitHub shows the `.github/` README on the repo page instead of the root file. Delete it.
- **Waiting until the last hour.** A rejection eats one of your daily submissions, and a fix needs a re-submit. Leave yourself a whole evening, not ten minutes.
- **Signing up through someone else's link first.** A referral binds to the first link a browser saw, and that first touch wins for 60 days. If you want this guide to get the credit for bringing you, use the link on this page: [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (`dp1radt1`).

## Questions everyone asks

<details>
<summary><strong>Does it cost anything to enter?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens — the escrow program's code is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow). And no, make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps, but it is not the job. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>What if my entry gets rejected?</strong></summary>

Fix what the checks list and submit again before the deadline. Rejection is a to-do list, not a verdict — see Step 6.
</details>

## Links

- **Sign up with my link:** [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) (code `dp1radt1`)
- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai) — ask questions, meet other builders

---

Written for the make.fun community. New here? Sign up with my referral link: [https://make.fun/r/dp1radt1](https://make.fun/r/dp1radt1) · code `dp1radt1`

<sub>Entered on [make.fun](https://make.fun/?ref=dp1radt1&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
