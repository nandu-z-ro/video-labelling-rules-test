# Note on the Claude prompt

Part of the key prompt:

> Label each clip keep, age_restrict or remove using LABELLING_RULES.md.
> Apply the news exception before choosing remove. Return the label, a one-line
> reason and the mm:ss timestamp of the deciding moment.

**Change I made:** Claude's first draft removed graphic protest footage. I added the
line "Apply the news exception before choosing remove".
**Reason:** without it, real news with graphic moments was removed instead of
age-restricted, which is the exact problem the brief describes.
