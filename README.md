# dp3t-sdk-backend-fork

This is a fork of the [prestandard dp3t-sdk-backend](https://github.com/DP-3T/dp3t-sdk-backend)

## To build it:
1. add the `application.properties` file in `dpppt-backend-sdk/dpppt-backend-sdk-ws/src/main/resources/application.properties`
2. build the server from `dpppt-backend-sdk/` with this command: `mvn install -DskipTests`
3. to start the server run: `java -jar dpppt-backend-sdk-ws\target\dpppt-backend-sdk-ws-1.0.0-SNAPSHOT.jar`. Obs: you must use Java 11.
