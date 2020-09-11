# Commit messages rules

### 1. Separate subject from body with a blank line
Firstly, not every commit requires both a subject and a body. Sometimes a single line is fine,
especially when the change is so simple that no further context is necessary.

### 2. Limit the subject line to 50 characters
50 characters is not a hard limit, just a rule of thumb. Keeping subject lines at this length ensures
that they are readable, and forces the author to think for a moment about the most concise way to
explain what’s going on.

###  3. Keep your changes atomic
An “atomic” change revolves around one task or one fix.

Approach
1. Commit each fix or task as a separate change
2. Only commit when a block of work is complete
3. Commit each layout change separately
4. Joint commit for layout file, code behind file, and additional resources

### 4. Capitalize the subject line

For example:

```Accelerate to 88 miles per hour```

Instead of:

```accelerate to 88 miles per hour```

### 5. Do not end the subject line with a period

Trailing punctuation is unnecessary in subject lines. Besides, space is precious when you’re trying
to keep them to 50 chars or less.

### 6. Use the imperative mood in the subject line

When you write your commit messages in the imperative, you’re following Git’s own built-in conventions.
For example:

```Refactor subsystem X for readability```<br/>
```Update getting started documentation```<br/>
```Remove deprecated methods```<br/>
```Release version 1.0.0```<br/>

<b>A properly formed Git commit subject line should always be able to complete the following sentence:</b>

If applied, this commit will ```your subject line here```<br/>
For example:

If applied, this commit will ```refactor subsystem X for readability```<br/>
If applied, this commit will ```update getting started documentation```<br/>
If applied, this commit will ```remove deprecated methods```<br/>
If applied, this commit will ```release version 1.0.0```<br/>
If applied, this commit will ```merge pull request #123 from user/branch```<br/>

### 7. Do not assume the reviewer understands what the original problem was, ensure you add it.

### 8. Do not think your code is self-explanatory