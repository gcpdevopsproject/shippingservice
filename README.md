# Shipping Servic

The Shipping service provides price quote, tracking IDs, and the impression of order fulfillment & shipping processe

## Local

Run the following command to restore dependencies to `vendor/` directory:

    dep ensure --vendor-only

## Build

From `src/shippingservice`, run:

```
docker build ./
```

## Test

```
go test .
```
