# How to use envsubst

## 1. Look at template.conf

## 2. Export variables

```
export SERVER_NAME=example.com
export PORT=1234
```

## 3. Run envsubst , and send output to the file you want to create

```
cat template.conf | envsubst > server.conf
```

## 4. Look at server.conf
