# Launchpad User Manual

All of your questions about Launchpad, answered.

## Ownership and visibility

Every pad on Launchpad is owned by the user that created it. The code and endpoint URL of every pad is publicly visible by anyone that knows the URL. Launchpad is a demo platform, so you should not use it to run critical production code you rely on, or anything you want to keep secret.

## Secrets

We’ve included a feature called secrets that lets the owner of a pad put in API keys and other sensitive information which is hidden from everyone else. So while anyone can read the code and call the endpoint, they can’t extract database passwords or API keys. TK add information about how we do this.

## Fork to edit

If you’re viewing someone else’s pad, you can log in and click “Fork” to make a copy that you own. In the process, any secrets will be deleted, and you will need to provide your own values for those keys. For example, if you fork the MongoDB example, you’ll need to go to a MongoDB hosting provider like mLab, create a database, and put in the new database URL.

## Sharing examples

For  the initial launch, we don’t have a site for browsing and sharing pads. We hope people will discover pads through links around the internet, from package READMEs, documentation, and tutorials. However, to make it a bit easier we’ve put up a repository where you can send a PR with a link and description for your pad to share it with the world! See it here:
