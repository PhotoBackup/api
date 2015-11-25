# PhotoBackup API's documentation
This describes the REST API of the communication between a PhotoBackup client and a PhotoBackup server. Clients and servers of same API version should be interchangeable for all operations. This effort tries to guarantee it.

API description are located in `api.raml` files. Here are details on evolution and compatibilities of the API versions with servers and clients versions.


## Versions

### API

| Version                                                  | Features      | Date       |
| :------------------------------------------------------: | :-----------: | :--------: |
| [v1](https://github.com/PhotoBackup/api/releases/tag/v1) | First version | 2015-07-10 |
| [v2](https://github.com/PhotoBackup/api/releases/tag/v2) | Add 409, 500 statuses | 2015-11-03 |


### Server implementations compatibility

| Language      | Maintainer      | Last version | API version |
|:-------------:|:---------------:|:------------:|:-----------:|
| [Python (bottle)](https://github.com/PhotoBackup/server-bottle) | [Stéphane Péchard](https://github.com/stephanepechard) | [v0.1.0](https://github.com/PhotoBackup/server-bottle/releases/tag/v0.1.0) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |
| [JS (Node)](https://github.com/PhotoBackup/server-node)         | [Stéphane Péchard](https://github.com/stephanepechard) | [v0.1.0](https://github.com/PhotoBackup/server-node/releases/tag/v0.1.0) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |
| [Go](https://github.com/lupine/photobackup-server-go)           | [Nick Thomas](https://github.com/lupine) | [v0.1.0](https://github.com/PhotoBackup/server-go/releases/tag/v0.1.0) | [v2](https://github.com/PhotoBackup/api/releases/tag/v2) |
| [Perl](https://github.com/PhotoBackup/server-perl)              | [Dave Webb](https://github.com/d5ve) | [v0.11](https://github.com/PhotoBackup/server-perl/releases/tag/0.11) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |
| [PHP](https://github.com/PhotoBackup/server-php)                | [Martijn van der Ven](https://github.com/Zegnat) |  [v1.0.0](https://github.com/PhotoBackup/server-php/releases/tag/v1.0.0) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |


### Client implementations compatibility

| Platform      | Maintainer      | Last version | API version |
|:-------------:|:---------------:|:------------:|:-----------:|
| [Android](https://github.com/PhotoBackup/client-android) | [Stéphane Péchard](https://github.com/stephanepechard) | [v0.6.5](https://github.com/PhotoBackup/client-android/releases/tag/v0.6.5) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |
| [Python](https://github.com/PhotoBackup/client-python) | [Stéphane Péchard](https://github.com/stephanepechard) | [v0.1.1](https://github.com/PhotoBackup/client-python/releases/tag/v0.1.1) | [v1](https://github.com/PhotoBackup/api/releases/tag/v1) |
