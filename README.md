# CDx Website - cdx.io

Marketing site for CDx.

## Deploy

The site is 100% static - the `src` directory in the repo is what gets deployed.

To make a new deployment, `git tag` the version you want, and `git push --tags` it. The Github Action will sync the S3 bucket with the `src` directory's content - **it will also delete files that get deleted from the repo**.

The tag name doesn't care - name them whatever you want.
