Si on supprime une branche dans laquelle on y est, on va avoir une erreur

on peut voir les differences avec git log


scalpaaaa@Scalpaaaa:~/EfreiB1/xin206/tp3$ git rebase main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not apply 6f8b372... new version readme
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 6f8b372... new version readme


