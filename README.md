# FVC2004

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FFVC2004-181717?logo=github)](https://github.com/biometric-community/FVC2004)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://bias.csr.unibo.it/fvc2004/)

**FVC2004** — tbiom catalog packaging for `fvc2004` (fingerprint; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/FVC2004
- **Upstream source**: http://bias.csr.unibo.it/fvc2004/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `fvc2004` |
| Category | `fingerprint` |
| Access | `register` |
| Upstream homepage | http://bias.csr.unibo.it/fvc2004/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Fingerprint Verification Competition 2004.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/FVC2004.git
cd FVC2004
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_fvc2004.sh
```

Place licensed archives under `projects/datasets/fvc2004/` (gitignored).

## Dataset structure

```text
FVC2004/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://bias.csr.unibo.it/fvc2004/
- Packaging: https://github.com/biometric-community/FVC2004/issues
