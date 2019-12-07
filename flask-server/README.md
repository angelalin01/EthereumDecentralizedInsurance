# Oracle Flask Server

## Description

Creates web API using Python Flask, which serves as the Oracle that the smart contract calls periodically to determine whether the parameter is above or below the parameter threshold. Currently, the web API is hosted on a local server but next steps will include migrating to an AWS server. The web API routes the HTTP GET request to the path /[localhost]/get-contract-winner 
and makes a call to an external weather API giving input parameters of location and and weather temperature threshold. When the smart contract calls our web API, the Oracle, it passes in theses input parameters. Once our Oracle calls the weather API, passing in the location. parameter, it fetches the data in JSON format, parses through it and compares the actual data with the expected threshold to see if the weather temperature is above or below it.   

## Install

## Run
