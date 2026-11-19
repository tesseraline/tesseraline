<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tesseraline/invariants/production/assets/mark-dark.png">
    <img src="https://raw.githubusercontent.com/tesseraline/invariants/production/assets/mark-light.png" alt="tesseraline" width="200">
  </picture>
</p>

Tesseraline gives developers control over what AI changes and what AI agents do, with a record of every check that audit tools can read.

## Projects

**[invariants](https://github.com/tesseraline/invariants)**: know when a change breaks a business rule. A function
states what its output may contain, for example never a credential, and a check runs it on many generated inputs to test the promise.

```console
$ pip install tesseraline-invariants
```

**[airlock](https://github.com/tesseraline/airlock)**: a gateway for the tools of an LLM agent. A policy decides
every call, the keys stay in the gateway, and requests leave only to hosts on a list.

```console
$ pip install tesseraline-airlock
```

## How the projects are kept

Releases are built by GitHub Actions and published to PyPI with provenance attestations; each GitHub release carries its files signed with Sigstore. Security reports go privately through the Security tab of each repository.

The code is free for noncommercial use under the PolyForm Noncommercial License 1.0.0. Using it to train AI models is not permitted. Companies can ask for a commercial licence by opening an issue in either repository.
