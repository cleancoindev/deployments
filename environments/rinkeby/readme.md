# Rinkeby

- [Permissions](./permissions.yml)
- [APM publish history](./deploys.yml)

## Artifacts

- ENS: `0x98df287b6c145399aaa709692c8d308357bc085d`
- aragonID: `0x3665e7bfd4d3254ae7796779800f5b603c43c60d`
- aragonPM:
  - `aragonpm.eth`: `0xda897630fa0f1902f99623bc00e18acd12657d4f`
  - `hatch.aragonpm.eth`: `0x5e4083cad6950a1290cc74fd2ebb873bec9a3a01`
  - `open.aragonpm.eth`: `0x915c4a47e7c7f7ab04ac70b4bcfba257a1e8b040`
- DAOFactory: `0x89d87269527495ac29648376d4154ba55c4872fc`
- MiniMeTokenFactory: `0x6ffeb4038f7f077c4d20eaf1706980caec31e2bf`

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
