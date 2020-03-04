# KeyDB JSON
A JSON module for Redis and KeyDB

## Design Overview
This module will focus on JSON serialization/deserialization of native Redis and KeyDB types along with traditional querying of JSON objects.

## API Reference
(In Progress)

SERIALIZE [key] - Produce a JSON dump of the specified key

DESERIALIZE [destination key] [json string] - Store the JSON object into the specified key.  If the JSON was produced by SERIALIZE it will be a duplicate copy of the serialized key.  If the JSON text is arbitrary it will be stored in a new "JSON" value type

