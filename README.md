# BA.com Shop &amp; Order (NDC) examples

## How to use

### Search for flights

```bash
curl -X POST -H "Soapaction: AirShoppingRQ" -H "Client-Key: <your_key>" -H "Content-Type: text/xml" --data @AirShoppingRQ.xml "https://test.api.ba.com/selling-distribution/AirShopping/V1"
```

### Check current flight price

```bash
curl -X POST -H "Soapaction: FlightPriceRQ" -H "Client-Key: <your_key>" -H "Content-Type: text/xml" --data @FlightPriceRQ.xml "https://test.api.ba.com/selling-distribution/FlightPrice/V1"
```

### Create an order

```bash
curl -X POST -H "Soapaction: OrderCreateRQ" -H "Client-Key: <your_key>" -H "Content-Type: text/xml" --data @OrderCreateRQ.xml "https://test.api.ba.com/selling-distribution/OrderCreate/V1"
```

### Retrieve an existing order

```bash
curl -X POST -H "Soapaction: OrderRetrieveRQ" -H "Client-Key: <your_key>" -H "Content-Type: text/xml" --data @OrderRetrieveRQ.xml "https://test.api.ba.com/selling-distribution/OrderRetrieve/V1"
```