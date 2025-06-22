# Aya Website

## Updating the VM

Build the VM from the aya repo

```
mvn package -P web
```

Copy the JS files here

```
cp ~/git/aya/target/javascript/aya.js static/js/
cp ~/git/aya/target/package-stdlib-js/aya-stdlib.js static/js
```

## Deploy

```
bash deploy.sh
```
