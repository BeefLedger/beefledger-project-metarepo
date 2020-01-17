# BeefLedger project metarepo

This repository exists to orchestrate setup of the full project stack, including (for now) a Holochain backend dependent on Holo-REA.

**To begin, just run `init.sh`.** Now, go make a coffee while you wait 'cos this will take a long time.

If you contribute only to one of the projects mentioned in `.gitmodules`, you do not need this repository. It is for developers working on Holo-REA and BeefLedger code simultaneously.

Note that it is expected to see output like `(modified content)`, `(new commits)` in the `git status` output for this repository. This is because `init.sh` is used to bootstrap all repos from their master branches, and the versions of the modules tracked within *this* repository are not typically kept up to date.

You should deal with every submodule provided by this repository as its own entirely independent git repository, just as if you were working on them individually. Don't fiddle around with this parent repository unless you really know what you're doing (;
