## TCP Ping Test Policy

Policy type representing a test case specification for a TCP ping test.

| Name | URI | Version | Derived From |
|:---- |:--- |:------- |:------------ |
| `TcpPingTest` | `radon.policies.testing.TcpPingTest` | 1.0.0 | `radon.policies.testing.Test` |

### Properties

| Name | Required | Type | Constraint | Default Value | Description |
|:---- |:-------- |:---- |:---------- |:------------- |:----------- |
| `port` | `true` | `integer` |   |   | The port to ping during the test |
| `hostname` | `true` | `string` |   |   | The host to ping during the test |
