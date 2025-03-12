# gitbook-test
## Here's what I learned:
- Create a GitHub repo to store the GitBook information
- Set up GitHub Sync on the GitBook page (instructions on their page are documented well)
- Set up "first synchronization" to GitHub instead of GitBook (don't worry; this is bidirectional)
- Create a branch, add a file, and submit a PR
- Merge PR to main. You will now see the new files in the GitBook page after a few seconds/minutes depending on server load

## Misc notes:
- As of this current test, there can only be one heading 1 level. This will be the first link on your site
- Subsequent headings (level 2) are sublinks

## Future testing:
- I need to test how this looks on a pre-existing GitBooks site. If I were to sync with a current site, would all the MD files appear on GitHub?
- Robustness. The current site only has one layer of headings, so everything is arranged in one level. With subdirectories, how would this work? (I believe this test would require a premium site)
