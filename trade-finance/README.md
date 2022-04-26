# Blockchain

## How to install

---

### Build
```
daml build
>>> Created .daml\dist\trade-finance-1.0.0.dar
```

---

### Visualizing Daml Contracts

1- Create dot file
```
daml damlc visual .daml\dist\trade-finance-1.0.0.dar --dot trade-finance.dot
```

2- Dot to Png
```
dot -Tpng trade-finance.dot -o trade-finance.png
```

3- (Optional) Dot to Png via web [here](https://onlineconvertfree.com/convert-format/dot-to-png/)

---

### Deploy on DamlHub

1- Visit [Daml / Hub](https://hub.daml.com/console)

2- New Project or Select loc

3- Deployments and upload dar file

4- After that you can use freely the ledger on Live Data