# Spring Cloud Function using AWS Adapter example

## Exposed Function as API Endpoint using AWS API Gateway
`Hello.java` is exposed as function to the AWS Request Handler using `SpringBootRequestHandler`.
`APIGatewayProxyRequestEvent` is the input object and `APIGatewayProxyResponseEvent` is the response object.

### Command used:

```
curl -X POST -H 'Content-Type: text/plain' <API_GATEWAY_URL> -d 'TechPrimers' -i

curl -X POST -H 'Content-Type: text/plain' https://b9jdy30ao4.execute-api.eu-west-1.amazonaws.com/default/Spring-Cloud-Function-Lambda -d 'Maaa' -i
```