## Mocking

- Android uses different bytecode.
- Spock uses CGLib (bytecode generator)
- Custom specification that overrides createMock 
- DexMaker, Problem solved!
- Automatic Getters/Setter on mocks don't work (java.bean)
