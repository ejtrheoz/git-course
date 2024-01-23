# Git and Github Course

Crash course Git

```mermaid
graph LR;

	untracked -- "git add" --> staged;
	staged -- "git commit" --> commited/tracked;

```

```mermaid
graph LR;
    markdown[staged]
    newLines["git restore"]
    result["cancel changes"]
    markdown --> newLines --> result


```

