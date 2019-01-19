# EX2

```bash
helm install ex2
```

```bash
helm ls
```

```bash
helm upgrade --set scale=7,tag="1.12" loitering-markhor ex2/
```

```bash
helm rollback loitering-markhor 1
```

```bash
helm delete loitering-markhor
```
