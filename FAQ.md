# FAQ

## The `masternode outputs` return an empty object.
```
{
}
```

You must receive the **25000 JEW** for the **masternode** in a single transaction on your **Control Wallet** and wait for at least 1 confirmation.
> If you already have the **25000 JEW** but it came from multiple transactions, you can send the **25000 JEW** back to yourself:
```
docker exec shekel-wallet shekel-cli sendfrom "" YoUrAdDr3Ss JEW
```

## Running a **wallet** or a **masternode** container result in the following error:
```
No such file or directory
```

Ensure the `data` folder is *writable* for the container.
