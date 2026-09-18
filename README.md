# Satchel plugins (moved)

The Satchel plugin catalog now lives in the main repository: <https://github.com/NeerajG03/satchel>. This repository is archived and will not get new versions.

If you added this catalog before, switch over:

```sh
# Claude Code
claude plugin uninstall satchel@satchel
claude plugin marketplace remove satchel
claude plugin marketplace add NeerajG03/satchel
claude plugin install satchel@satchel
```

```sh
# Codex
codex plugin remove satchel@satchel
codex plugin marketplace remove satchel
codex plugin marketplace add NeerajG03/satchel
codex plugin add satchel@satchel
```

Your sign-in to the Satchel service is kept. The service address did not change.
