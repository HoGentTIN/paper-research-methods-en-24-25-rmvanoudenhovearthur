# Phase 2. Work environment setup

In this course you will make use of different software packages and tools. In this phase we will install and configure the necessary applications for an efficient work environment.

## Software Installation

To install the necessary software for LaTeX, follow the instructions in our [LaTeX guide](https://hogenttin.github.io/latex-hogent-gids/). In addition, make sure you have a Git client and a Github account (you should normally have used these previously for other courses).

## Configuration Git, Github

Normally, you should have already made a Github-account and personal Github repository via the Github Classroom link that you can find on the Chamilo platform.

### Basic configuration

Before you will use Git on your laptop it is important to configure some **basic settings**. If you won't, your commits will not always be pushed correctly to github in your name. Especially for group assignments, this is a problem as it is impossible to distinguish between your contributions and your fellow students'!

- Connect your **HoGent email address** to you Github account (you can register multiple addresses). This way, you can claim a [Github student developer pack](https://education.github.com/pack), allowing free access to some paying products and services.
- [Generate an SSH key pair](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) if you haven't already and [register it on Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).
- Set up your name and (HOGENT-) email. Using the CLI:

    ```console
    git config --global user.name "Pieter Stevens"
    git config --global user.email pieter.stevens.u12345@student.hogent.be
    git config --global github.user PieterStevens
    ```

- Adapt [some basic settings](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) :

    ```bash
    git config --global push.default simple
    git config --global pull.rebase true
    git config --global rebase.autoStash true
    git config --global init.defaultBranch main
    ```

    Please go through the [documentation](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) to find out what these commands do.

- Make a clone of your Github repo on your laptop and fill out the table at the top of the README.md file with the correct data. Each team member should do this separately to check that everything is set up correctly. Of course, avoid merge conflicts! Commit, push to Github and check if the changes are correctly on Github and that the authors of the commits are recognizable.

### Recommendations

We assume that you are able to work with Git/Github! Some recommendations:

- **Avoid** using the **Github webinterface** for adding/adapting file content. Clone your repository locally onto your laptop and use the command-line or a decent GUI.
- **Commit and push** as often as possible!
- Create [**atomic commits**](https://dev.to/cbillowes/why-i-create-atomic-commits-in-git-kfi). Your github-repository is a backup that helps you from losing your work in progress.
- Provide a clear description for your commits in the [**commit messsage**](https://cbea.ms/git-commit/).
- The standard for formatted text on Github is [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Please take your time to learn how to write a **Markdown document** and explore its layout (in an editor or on Github).

## Testing the LaTeX installation

To test proper functioning of your LaTeX setup, you can use the template for the paper ( `paper/SurnameFirstnameYearRM.tex`). Copy the template to a new file with the name(s) of the author(s) and the current year (e.g. `DeSmetJan2022RM.tex` or `AkinDeSmet2024RM.tex`).

## Write the introduction

If you chose a final topic in the previous phase, you can write the introduction of the paper in the LaTeX document in the `paper/` directory (which you should have renamed to match your own name(s)).

## Checklist

- [x] The necessary software is installed.
- [x] The basic Git settings are adapted where required. On committing, it is obvious who the author is. 
- [x] TeXstudio or VS Code are configured for use.
- [x] The template compiles without errors, in the generated PDF the (example) bibliography is present.
- [x] You've written out the introduction of your research subject
