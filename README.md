### notes

A (very) minimal notes taking tool built on top of git.

### Usage

#### Add a note

```bash
notes add I need a cat.
```

#### And then a couple of days later …

```bash
notes add Maybe I need two cats.
```

#### View notes

```bash
notes view

2015-01-22  Maybe I need two cats.
2015-01-21  I need a cat.
```

See notes since yesterday

```bash
notes view yesterday

2015-01-21  I need a cat.
```

And this works too:

```bash
notes view 2 weeks ago
```

Or this:

```bash
notes view 2015-01-01
```

#### Search notes

```bash
notes search cat

2015-01-22  Maybe I need two cats.
2015-01-21  I need a cat.
```

#### Sync notes

```bash
notes sync
```

This will `git pull --rebase` and then `git push` your notes.

## Enjoy!
