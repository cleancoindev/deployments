# Staging

- [Permissions](./permissions.yml)
- [APM publish history](./deploys.yml)

## Artifacts

- ENS: `0x98df287b6c145399aaa709692c8d308357bc085d`
- aragonPM:
  - `aragonpm.eth`: `0xda897630fa0f1902f99623bc00e18acd12657d4f`
  - `open.aragonpm.eth`: `0x915c4a47e7c7f7ab04ac70b4bcfba257a1e8b040`
- DAOFactory (Aragon 0.6): `0x2298d27a9b847c681d2b2c2828ab9d79013f5f1d`
- DAOFactory (Aragon 0.7): `0xfdef49fbfe37704af55636bdd4b6bc8cd19143f6`

## Deployments

-----------

### Aragon Apps

Deployed: `redemptions-staging`

Command:
```
aragon apm publish major --environment staging --files dist
```

Details of the deployment can be found in [`deploys.yml`](./deploys.yml)

Final versions:

- `redemption-staging.open.aragonpm.eth`: `3.0.0`