# true

[![GuardRails badge](https://badges.production.guardrails.io/moul/true.svg)](https://www.guardrails.io)

```console
$ docker run --rm multiarch/true:linux_amd64 2>/dev/null; echo $?
0
$ docker run --rm multiarch/true:linux_386 2>/dev/null; echo $?
0
$ docker run --rm multiarch/true:linux_arm 2>/dev/null; echo $?
1
```
