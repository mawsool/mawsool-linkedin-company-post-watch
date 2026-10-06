# LinkedIn Company Post Monitor

**Watch LinkedIn company pages and get only new posts on the next run. $1 per 1,000 companies each time the schedule runs.**

The first run returns the posts already on the page and marks them `baseline`. Later runs return only posts that were not in that saved list, marked `new_post`. A quiet day still charges the check and adds no new rows.

Schedule it daily in Apify. Reuse the same Watch list ID. Turn on **Start the watch again** to forget the saved posts and take a new baseline.

An optional HTTPS webhook receives new posts only, in batches of 100.

## Who is this for?

Account-based marketing teams who want a morning list of new posts from target accounts, without downloading the same posts every day.

## How much does it cost?

$1.00 per 1,000 companies per run. A daily list of 1,000 companies is about $1 a day. One company is one charge, whether or not it published anything new.

## FAQ

### What is the difference between this and Company Posts?

Company Posts always returns the posts on the page now. This monitor remembers those posts and, on the next run, returns only new ones.

### Does the first run send the webhook?

No. The baseline run saves the current posts. The webhook receives later new posts.

### What if a run stops halfway?

Lists over 200 continue on the next run. Finished companies are not charged again unless you start the watch again.

## Related Actors

Company Posts for a one-time export. Company website and firmographics for the account fields. Job Change Watch for people, not company pages.

## Where to run it

Run the published Actor on Apify, or start from [mawsool.tech](https://mawsool.tech). This repository does not include the lookup address.
