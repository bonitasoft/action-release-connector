# action-release-connector

Github actions to release Bonita connectors.
Since version 2.0.0, connectors are compiled with Java 17.
Though, they still have a java.version property with value 11, to ensure compatibility with maintenance releases <= 9.0 (2023.2).
