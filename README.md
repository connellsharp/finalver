# Final Versioning Specification

"Final Versioning" or "FinalVer" is a set of rules for determining which version of a given document or spreadsheet should be used if there are multiple in the same folder. It allows authors to keep old versions of documents by simply selecting "Save As" and giving the file a new name, without having to foresee the need for multiple versions when the document is first drafted.

# Rules

In order of precedence:

## Initial Version

### `Document.docx`

First is the initial version, `Document.docx`. You can replace this and all versions below with any file name, where `Document` is the file's original name and `docx` is the file extension.

Always assume that a document that does not have any suffix from this spec is the initial unfinished version.

## Draft Versions

### `Document draft.docx`

This is the stage where you realise you're going to send this document for feedback and you acknowledge there will likely be changes in future. The `draft` suffix sets expectations of senior stakeholders and makes any mistakes more forgivable.

The `draft` suffix is case-insensitive. `Draft` and `DRAFT` correspond to the same version.

### `Document second draft.docx`

After the first round of feedback, you'll get an idea of how bad the first draft was, and can chose to prefix the `draft` suffix with ordinals.

Starting with `second`, then follows `third`, `forth`, `fifth`, `sixth`, `seventh`, `eighth`, `ninth`, `tenth`, `eleventh` and `twelfth`. Obvious incorrect spelling of these such as `fourth` and `twelvth` are also valid and correspond to their respective ordinals.

Numeric notation may also be used, such as `2nd`, `3rd` and `4th`. Incorrect ordinal indicators such as `21th` are valid and correspond to the ordinal with the attached number, but this practice is discouraged and likely to be viewed negatively by reviewers.

## Final Versions

### `Document FINAL.docx`

This is the phase after all draft feedback has been actioned or ignored, or if the author felt confident enough to skip the draft phase for some reason. This version is often sent to a wider audience than the draft versions.

A single `FINAL` suffix indicates that the author has completed modifications and has no intention to further modify the document in future.

The `FINAL` suffix is case insensitive in terms of version precedence, but all caps strongly indicates the desire not to make further revisions. That is, a simple `Document final.docx` corresponds to the same version, but is more prone to feedback.

### `Document FINAL revised.docx`

Inevitably, someone will request more changes. Often someone from the wider audience for whom this is the first version they've seen.

At this point, adding a passive-aggressive `revised` suffix will increment the version once more. The deliberate juxtaposition of the two suffixes and their casing should portray relinquishment and be enough to deter even most heartless of reviewers from providing further feedback.

### `Document FINAL revised again.docx`

A battle of wits is happening at this point. The authors intense reluctance to use numeric versioning after so many revisions clashes with the reviewers' sense of duty to enforce one.

In theory, any words suffixed to `FINAL revised again` will further bump the version beyond this one, for example, `FINAL revised again for the last time I swear.docx`. However, all known authors have succumbed to the next phase before this point.

### `Document FINAL v2.docx`

Numeric versions start from `FINAL v2`. The number `2` is a decimal numerical value which can increase by 1 each version until the number cannot exceed the maximum file length on the OS. Even in versions of Windows before Windows 10, assuming all files are placed directly in the `C:\` drive, this gives a theoretical limit of more than 200 `9` characters.

Keep in mind that when files are sorted alphabetically, `v10` comes before `v2`.

## Actual Final Versions

### `Document ACTUAL FINAL.docx`

To differentiate from the already-named but now-not "final" versions above, a prefix can be used before `FINAL`, analogous to the draft ordinals prefixes above.

Each prefix, however, has no defined order of precedence. Valid prefixes are `ACTUAL`, `REAL`, `TRUE`, `PROPER`, `GENUINE` and `BONA FIDE`.

### `Document ACTUAL FINAL USE THIS ONE.docx`

If changes to the `ACTUAL FINAL` version are required, the suffix `USE THIS ONE` is the one last resort.

This is the biggest version. No further changes can be made beyond this point.