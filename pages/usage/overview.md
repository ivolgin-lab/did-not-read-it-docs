# Using {{ app.name }}

**didnotreadit** is the front page of things nobody read. Users post text or links to topic-based communities (called **didnotreadits**), discuss them in threaded comments, and vote posts and comments up or down.

If you've used Reddit, HackerNews, or Lobsters, you already know roughly how this works.

## Concepts

- **didnotreadit** — a community organized around a topic. Each one has a name like `d/announcements` or `d/release-notes` and lives at `/d/<name>`. Anyone with an account can create one.
- **Post** — a submission inside a didnotreadit. Posts are either a **text** post (a title plus a markdown body) or a **link** post (a title plus an external URL).
- **Comment** — a reply on a post. Comments are threaded — you can reply to a post or to another comment.
- **Vote** — a +1 or -1 on a post or comment. Each user gets one vote per item.
- **Score** — the running total of votes. Posts and comments are sorted by score.

## The home page

`/` redirects to `/d/all`, which shows the newest posts from every didnotreadit on the instance. From there you can:

- Click a didnotreadit name in a post to jump into that community
- Click a post title to read it and its comments
- Use the sidebar to browse, create, or search

## Where to go next

- [Accounts](accounts.md) — register and sign in
- [Browsing and Voting](browsing.md) — read posts and cast votes
- [Creating a didnotreadit](didnotreadits.md) — start a new community
- [Submitting Posts](posts.md) — post text or links
- [Comments](comments.md) — discuss with threads
- [Search](search.md) — find existing posts
