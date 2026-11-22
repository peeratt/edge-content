# edge-content

Blog posts and social captions for **edgemanagementapp.com**.

## How it works

1. Three times a week (Mon, Wed, Fri), Claude drafts a blog post plus Instagram and Facebook captions.
2. The draft arrives as a **pull request** (a proposed change waiting for approval). GitHub sends you a notification.
3. You review it in the GitHub app:
   - **Approve:** tap **Merge pull request**, then **Confirm merge**. The post goes live on the website.
   - **Ask for changes:** leave a comment saying what to change. Claude picks it up on the next run.
   - **Reject:** tap **Close pull request**.
4. Captions are in the `social/` folder. Copy them into Meta Business Suite to schedule them.

## Folders

| Folder | What's in it |
|---|---|
| `posts/` | Published blog posts. The website reads these. |
| `social/` | Instagram and Facebook captions for each post |
| `guide/` | The writing rules and topic plan Claude follows |
| `notes/` | Your stories, photos and numbers for Claude to use (optional, but it makes posts much better) |

## Adding your own input

Drop a quick note in `notes/`, for example "Shop in Newcastle wasted 3 rolls of 1mm white a month before tracking". Write it on your phone in the GitHub app with **Add file → Create new file**. Claude works one note into the next suitable post and then moves it to `notes/used/`.
