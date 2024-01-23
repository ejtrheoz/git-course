# Git and Github Course

Crash course Git

```mermaid
graph LR;

untracked -- "git add" --> staged;
staged -- "git commit" --> commited/tracked;
staged -- "git restore --staged <file>" --> "cancel changes";

```

```mermaid
graph LR;
"requests username/password" -- "git remote set-url origin git@github.com:<user>/<repo>.git" -- "SSH applied";

```
