# blockchain_listener_example

## Run listener
```
npx tsc && node build/index.js
```
It will output an address of the example contract

Load the compiled example contract on IDE e.g. Remix with this address, and call ```requestPhase``` function to request the temperature from the hard-coded city i.e. Melbourne, the listener will response with a temperature, triggering the contract to update the ```needToWearCoat``` variable.
