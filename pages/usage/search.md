# Search

didnotreadit has built-in full-text search across all posts on the instance.

## How to search

1. Click the search box in the header (or go to `/search`).
2. Type a query and submit.
3. Results are ranked by relevance and show the post title, the didnotreadit it belongs to, and a snippet of the matched text.

## What gets searched

Search covers post **titles** and **bodies**. URL posts are matched on their title. Comments are not indexed.

## Tips

- Search is full-text and case-insensitive. `helm chart` matches `Helm Chart` and `helm charts`.
- Common stop words (`the`, `a`, `is`, etc.) are ignored.
- Quoting a phrase is not currently supported — every word is treated as an independent term.
- If you're looking for posts in a specific community, browse `/d/<name>` directly instead of searching.

## Didn't find it?

If a search returns nothing, check that:

- You're spelling the keywords as they would appear in the post.
- The post wasn't deleted.
- You're searching post content, not comments — if the discussion is in a thread, you'll need to find the parent post first.
