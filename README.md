# git-clean-branch
A plugin for oh-my-zsh that cleans up dead git branches

## Installing
Simply clone the repo into your `.oh-my-zsh/custom/plugins` folder:

```sh
git clone https://github.com/gobriansteele/git-clean-branch.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/git-clean-branch
```

Then add `git-clean-branch` to your plugins in `.zshrc`:

```sh
plugins=(git yarn brew git-clean-branch)
```

To use, simply navigate into any git directory and run `git-clean-branch`.
