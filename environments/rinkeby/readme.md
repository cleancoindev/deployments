# Rinkeby

- [Permissions](./permissions.yml)
- [APM publish history](./deploys.yml)

## Artifacts

- ENS: `0xfe03625ea880a8cba336f9b5ad6e15b0a3b5a939`
- aragonPM:
  - `aragonpm.eth`: `0xda897630fa0f1902f99623bc00e18acd12657d4f`
  - `open.aragonpm.eth`: `0x915c4a47e7c7f7ab04ac70b4bcfba257a1e8b040`
- DAOFactory (Aragon 0.6): `0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d`
- DAOFactory (Aragon 0.7): `0xfdef49fbfe37704af55636bdd4b6bc8cd19143f6`

## Deployments

-----------
### Aragon Apps

Deployed: 

- `redemptions`
- `token request`
- `time lock`
- `dandelion voting`
- `delay`

Command:
```
aragon apm publish major --environment rinkeby --files dist
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `redemptions.open.aragonpm.eth`: `6.0.0`
- `token-request.open.aragonpm.eth`: `1.0.0`
- `time-lock.open.aragonpm.eth`: `1.0.0`
- `dandelion-voting.open.aragonpm.eth`: `1.0.0`
- `delay.open.aragonpm.eth`: `1.0.0`
