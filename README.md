# elfutils

This branch contains the GitHub Actions workflows that generates the missing headers
needed for cross-compilation.

This branch exists because a bug in elfutils that makes cross-compile fail:

- https://sourceware.org/bugzilla/show_bug.cgi?id=28891
- https://www.mail-archive.com/elfutils-devel@sourceware.org/msg03801.html
- https://lists.fedorahosted.org/archives/list/elfutils-devel@lists.fedorahosted.org/thread/TK47UHJMSDVHMJB5W4A3SLVKHLF7JEGA
- https://lists.fedoraproject.org/archives/list/elfutils-devel@lists.fedorahosted.org/thread/HIAWS54V54NROT2OYBLFHWIROAULHWII

# Usage

Trigger GitHub action with a tag name from upstream elfutils repo.
Then the action will generate the missing headers and push a tag to this repo.
