# Red Team Collaboration with Obsidian and Git
This repository is designed to be a quick-start for small Red teams/Penetration Testing teams to develop a note taking system. The goal is for teams to set this up and import old notes and build notes from engagements for a one-stop shop for new & current team members. This was built using Obsidian on Kali (using the current AppImage) 

This method of note taking has the added benefit of keeping a backup+change controlled copy of engagement notes within your own environment. Plus it adds a way to access control notes and potential malware/exploit samples that teams don't want readily available.

## Prerequisites
This project requires some knowledge of Git and the following installed on the machines that will participate in the shared notes.
```
1) Git
2) Obsidian
	1) Git Plugin
	2) Pandoc Plugin
	3) Slash Commands
```

## Get Started

Screenshots are linked within this document.
### Command Line Tasks

**Clone this example project**
```bash
git clone https://github.com/shawnstephens517/RTCOG
```


**Remove Current GIT directory**
```bash
rm -rf .git
```


### Obsidian Tasks

**Open the Vault**
```python
Open the vault from the Application.

Note: This will be where you performed the git clone to.
```
![[open_obsidian.png]]
**Verify Plugins**
```python
Ensure the 'Git' and 'Pandoc'  community plugins are enabled

Ensure the Slash commands 'core plugins' enabled
```

![[plugin_verify.png]]
## Collaboration Method
At this point, a slight greater knowledge is required by at least one member of the team to keep the notes in check. I image the branching strategy to ensure that things remain consistent and maintainable. This is just a suggestion and should be tailored to your own team needs.

![[Branching_Strategy.png]]


### Git
Use the following `slash` commands within one of your notes. This will initialize the repo for your environment.
![[init_git.png]]

[Review the documentation to the Git plugin ](https://publish.obsidian.md/git-doc/Features) for additional details on how to work with Git within Obsidian. New branches, local commits, and pushes to remote repos (Github, Gitlab, etc...)

