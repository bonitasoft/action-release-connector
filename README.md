# action-release-connector

Github actions to release Bonita connectors.
Since version 2.0.0 of this action, connectors are compiled with Java 17.
Though, connectors definitions may still have a java.version property with value 11, to ensure compatibility with Bonita maintenance releases <= 9.0 (2023.2).
