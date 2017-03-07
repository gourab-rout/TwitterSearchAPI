# POC FHIR

This is a POC to connect FitBit and 23andMe api.

## FitBit API 
This API returns heart rate time series data by calling a Fitbit endpoint.
The Fitbit endpoint is OAuth2 secured. The access token is currently hard-coded as mule community edition 
does not provide oauth2 module. The token expires after some interval may result in 'Response code 401
unauthorized' error

## Testing FitBit API
The cloud url for testing - http://pocfhir.cloudhub.io/api/fitbit

## 23andMe API
This API returns genotype data by calling a 23andMe endpoint

## Testing 23andMe API
The cloud url for testing - http://pocfhir.cloudhub.io/console/

## Deployment

The API is deployed in mulesoft anypoint cloud platform. 