A few small tools I find helpful.

## git-switch-interactive

Lets me pick a local branch. 

### Usage

I have it aliased as `gbp`.

- `gbp`: Runs the interactive picker. On selection, copies branch name to clipboard.
- `gbp -s`: Switches to the selected branch.
- `gbp -d`: Deletes the selected branch.

## sh-branch

Lets me pick a branch from my stories in Shortcut. Requires `SHORTCUT_API_TOKEN` to be available in your environment.

### Usage

I have it aliased as `shb`.

- `shb`: Creates the branch if it doesn't exist, or switches to it if it does.

## git-main-clean

Delete the current (unless `main`) branch and move me to `main`.

### Usage

I have it aliased as `gbdd`.

- `gbdd`: Switch to `main` and delete whatever branch I was on.

