# Managing Merge Requests, Using Code Review

## Committing Code (_author_)

Follow these simple steps:

1. Commit often. - _Whenever_ you change a piece of code that is testable and compiles.
1. Push your _working_ branch at the end of each "development session" (before walking away from your computer for lunch).
1. Request a PR/MR (with review) before having more than 100 lines changed.

## Code Review (_reviewer_)

Follow a few simple ideas:

- When approving a merge, you are just as responsible for the changes as the person who made them. So you should understand them just as well.
- Only review changed lines.
- Anyone on the project can raise concerns (blocking) on a PR/MR, even if they are not assigned to it.
- Can be blocked for any reason, including empty line spaces or too many changes in one PR/MR.
- The goal of a PR/MR should ultimately be knowledge transfer.

## FAQ

### How do smaller changes help me and the project?

Smaller changes allow each change to be individually assessed and validating ensuring that specific set of code works exactly as the developer inteneds it to.
It also helps a reviewer of the code, the smaller the change, the faster the reviewer can approve it meaning the faster that change gets added to the shared source allowing all the developers to work with that change.
Later when going though history trying to identify issues, the smaller changes will help identify the direct intention of the code change allowing a developer to identify how the change may relate to the issue they are dealing with.

### Why do code reviews matter?

The primary goal of a code reivew should be collaberation.
The collaberation allows the _reivewer_ and _author_ of the code change to learn more about the project, enabling them both to make better changes to the project in the moment and in the future.

### How do I keep reviews from taking up all my time?

- **Keep the changes small!** If the change is too large and could have been broken appart, reject it.
- **Don't validate the code** in your reivew. Let the pipeline do that work for you. Focus on learning what it is the _author_ is trying to do, and check that what they did makes sense.
- If you don't understand the change, **ask for more details**. Don't spend time trying to figgure it out, it should be simple enough (or explained in comments) to understand in a minute or two.
