# git

This repository is meant to consolidate instructions and configuration files needed to setup a developer environment. The [.gitignore](.gitignore) file enables you to clone as many repositories as you want in this directory without being included as submodules - any new folders or files can be added if needed.

## Setup

### Windows (optional)

1. Install WSL using the instructions [here](https://learn.microsoft.com/en-us/windows/wsl/install).

### Git

1. Install Git using the instructions [here](https://github.com/git-guides/install-git).

2. Configure Git with your information:

```bash
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
```

3. Create an SSH key using the guide [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

4. Add the SSH key to Github.com using the guide [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

## Usage

1. Clone this repository inside your home directory:

```bash
git clone https://github.com/edgorman/git
```

2. Change into the directory:

```bash
cd git
```

3. TODO: configure vscode with files in `.vscode/`...

4. Clone your repositories in to the `git` directory.
