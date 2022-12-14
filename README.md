## Pull the Image ##

```docker push nikitapatel29/nikita_blockchain_x21224811:latest```


## Run an image ##

```docker run --name ncilab02 -p 8090:8080 nikitapatel29/nikita_blockchain_x21224811:latest ```

## Run the curl command ##

This transfers ETH:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C", "amount":"0.05"}' http://localhost:8090/eth```

This transfers token:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C"}' http://localhost:8090/token```




Thank you