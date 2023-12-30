<div align="center">

# 📃 License Generator
*A POSIX compliant shell script that generates license for your open source projects*

![gen-license-preview](https://github.com/SamIsTheFBI/license-generator/assets/70562711/6a1b5d1f-5714-4057-99b9-0fdedd1334c7)

</div>

Generate license for your next open source projects right from the comfort of your terminal. The licenses are generated using GitHub's API so you can be assured these licenses are legit!

## Dependencies  
- <samp>curl</samp> &nbsp;or &nbsp; <samp>wget</samp> &nbsp;or &nbsp; <samp>aria2</samp>
- <samp>fzf</samp>
- <samp>sed</samp>
- <samp>jq</samp>

## Installation
Copy `gen-license` to your desired bin directory. Make it executable by running `sudo chmod a+rx gen-license`. Make sure to update PATH variable.

## Usage
```bash
gen-license
```

## Purpose behind making this 
Whenever I start a project, I don't go to create a new GitHub repository first. I instead open my terminal, `git init`, `vi .` and start with the coding process (no I don't use vi, that's my shell alias for nvim). When I'm satisfied with what I've written, then only do I go to GitHub and make a new repository. Now, GitHub asks if you want to add a license file which I would then have to pull to my local repository, commit and then push over all my other codes. This feels kinda annoying so I made this. For someone living inside a terminal, this is just perfect.
