# FHIRcast Endpoints

<small>*FHIR&reg; is the registered trademark of HL7 and is used with the permission of HL7.*</small>

This document describes the needed communication endpoints for the actors involved in a FHIR cast communication.

## HUB

A FHIR Cast Hub ist hosted at *`http://host:port/whatever`*, known as the base url.  The Hub needs at least the following endpoints, the context path names are not specified (yet?).

| Endpoint | Description |
|---|---|
|[base]/{subscription}| This endpoint handles the subscribe / unsubscribe requests from the clients|
|[base]/{notification}| Endpoint to process the event notification requests |

## Client

A client needs also to provide an endpoint to interact with the Hub.

| Endpoint | Description |
|---|---|
|[base]/{callback}| This is the endpoint to receive the subscription verification notification requests from the Hub.

