# gitbook-test
## Here's what I learned:
- Create a GitHub repo to store the GitBook information
- Set up GitHub Sync on the GitBook page (instructions on their page are documented well)
- Set up "first synchronization" to GitHub instead of GitBook (don't worry; this is bidirectional)
- Create a branch, add a file, and submit a PR
- Merge PR to main. You will now see the new files in the GitBook page after a few seconds/minutes depending on server load

## Misc notes:
- All headings are currently used to name each link. There are no subdirectories for this test
- The initial README file uploads as the home directory "/" instead of "/README"

## Future testing:
- I need to test how this looks on a pre-existing GitBooks site. If I were to sync with a current site, would all the MD files appear on GitHub?
- Robustness. The current site only has one layer of headings, so everything is arranged in one level. With subdirectories, how would this work? (I believe this test would require a premium site)
