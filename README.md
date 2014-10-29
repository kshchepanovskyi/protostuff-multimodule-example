# Protostuff multi-module project code generation example

This example shows how you can import message declarations from `proto` file in other module. 

1. Module `common` contains declaration of `KeyValue` message in the [common.proto](common/src/main/resources/common.proto).
2. Module `foo` uses `KeyValue` from [common.proto](common/src/main/resources/common.proto), see [foo.proto](common/src/main/resources/foo.proto).
