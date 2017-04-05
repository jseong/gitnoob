# Interactive Git Tutorial
A (rather) fun introduction to Git with song.

## Commit message subject tags
* BUG Bug fix
* DEP Deprecate something or remove something previously deprecated
* DOC Write or change doc strings or comments
* ENH Enhance or add functionality
* REF Refactor: Modify the internals of a function or class without changing inputs or outputs. No functional changes.
* MAINT Maintenance: includes, for example, updating versions of dependencies or modifying code to account for dependency updates. No functional changes to existing code.
* PROD Production: Changes pertaining to the run-time environment, e.g. Dockerfile modifications
* PERF Performance improvement
* REV Revert an earlier commit
* STY Style changes (e.g. PEP8 compliance). No functional changes.
* TST Add, modify, or fix tests.

## Example of a commit message
>DEP Remove unused code
>The `expected_attributes` check was a holdover from when we read dictionary inputs here. This check has since moved to `HETEModel.load_data`.
