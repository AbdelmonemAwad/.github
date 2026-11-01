# Security

This policy covers every repository of this account that has no security policy of its own. Where
a repository has one, that one applies; os-xgs-npu's is the fullest:
[os-xgs-npu/SECURITY.md](https://github.com/AbdelmonemAwad/os-xgs-npu/blob/main/SECURITY.md).

## Reporting a vulnerability

**Not in a public issue, please.** Report it privately through GitHub - **Report a vulnerability**,
on the repository's Security tab - where only you and the owner see it, and the fix can be prepared
before anything is public. Where a repository does not offer that, or without a GitHub account, write
to **security@npuforge.org**. Either way, include:

- the repository, and what in it is affected;
- the version - a release, or a commit - and where it runs;
- how to reproduce it, and what you saw.

This is one person's work, done in the evenings: expect an answer within days, not hours. A fix is
made in a pull request and named in the changelog of the release that carries it, with the reporter
credited unless they ask not to be. Disclosure is agreed with the reporter once a fix is out.

## What is supported

The newest release and the main branch: fixes go there, with no backports. An archived repository
is no longer maintained.
