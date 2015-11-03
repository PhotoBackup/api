# PhotoBackup API's documentation
The file [api.raml](api.raml) describes the different versions of the PhotoBackup's API.
Here are details on its evolution and compatibilities with current servers and clients.


## APIs compatibility

| API                                                      | [Python (bottle)](https://github.com/PhotoBackup/server-bottle)            | [JS (Node)](https://github.com/PhotoBackup/server-node)          | [Go](https://github.com/lupine/photobackup-server-go)                  | [Perl](https://github.com/PhotoBackup/server-perl)                    | [Android](https://github.com/PhotoBackup/client-android)                    | [Python](https://github.com/PhotoBackup/client-python)                     | [PHP](https://github.com/PhotoBackup/server-php) |
|:--------------------------------------------------------:|:--------------------------------------------------------------------------:|:------------------------------------------------------------------------:|:----------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| [v1](https://github.com/PhotoBackup/api/releases/tag/v1) | [v0.1.0](https://github.com/PhotoBackup/server-bottle/releases/tag/v0.1.0) | [v0.1.0](https://github.com/PhotoBackup/server-node/releases/tag/v0.1.0) | [v0.1.0](https://github.com/PhotoBackup/server-go/releases/tag/v0.1.0) | [v0.11](https://github.com/PhotoBackup/server-perl/releases/tag/0.11) | [v0.6.4](https://github.com/PhotoBackup/client-android/releases/tag/v0.6.4) | [v0.1.1](https://github.com/PhotoBackup/client-python/releases/tag/v0.1.1) | rc1 |
| [v2](https://github.com/PhotoBackup/api/releases/tag/v2) | [v0.1.1](https://github.com/PhotoBackup/server-bottle/releases/tag/v0.1.1) | - | [v0.1.0](https://github.com/PhotoBackup/server-go/releases/tag/v0.1.0) | - | - | - | - |


## Versions

### API

| Version                                                  | Features      | Date       |
| :------------------------------------------------------: | :-----------: | :--------: |
| [v1](https://github.com/PhotoBackup/api/releases/tag/v1) | First version | 2015-07-10 |
| [v2](https://github.com/PhotoBackup/api/releases/tag/v2) | Add 409, 500 statuses ; use of bcrypt for stored password | 2015-11-03 |


### Server implementations

| Language      | Maintainer      | API version |
|:-------------:|:---------------:|:-----------:|
| [Python (bottle)](https://github.com/PhotoBackup/server-bottle) | [Stéphane Péchard](https://github.com/stephanepechard) | v1 |
| [Javascript (Node)](https://github.com/PhotoBackup/server-node) | [Stéphane Péchard](https://github.com/stephanepechard) | v1 |
| [Go](https://github.com/lupine/photobackup-server-go)           | [Nick Thomas](https://github.com/lupine) | v2 |
| [Perl](https://github.com/PhotoBackup/server-perl)              | [Dave Webb](https://github.com/d5ve) | v1 |
| [PHP](https://github.com/PhotoBackup/server-php)                | [Martijn van der Ven](https://github.com/Zegnat) | rc1 |

### Client implementations

| Platform     | Maintainer      | API version |
|:-------------:|:---------------:|:-----------:|
| [Android](https://github.com/PhotoBackup/client-android)  | [Stéphane Péchard](https://github.com/stephanepechard) | v1 |
| [Python](https://github.com/PhotoBackup/client-python)  | [Stéphane Péchard](https://github.com/stephanepechard) | v1 |
