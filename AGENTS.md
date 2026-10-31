# Node package authority assay service

This package owns one read-only capability: observe manager declarations,
lockfiles, installation markers, workspace admission, and build-script policy
for Node packages without invoking npm, pnpm, yarn, or a package lifecycle.

It reports conflicts; it never chooses a manager, installs, deletes locks, or
rewrites package manifests.
