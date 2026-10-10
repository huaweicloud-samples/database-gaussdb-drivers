<p align="center">
  <p align="center">
    <a href="README.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>

The purpose of this project is to foster the growth of the [GaussDB](https://www.huaweicloud.com/product/gaussdb.html) and [OpenGauss](https://opengauss.org/zh/) open-source ecosystem.

The project includes drivers and compatibility adapters for common programming languages. Most are based on PostgreSQL open-source drivers; the PHP M/ORA adapter uses PDO_ODBC and the official GaussDB Unicode ODBC driver. For details on the GaussDB open-source ecosystem, refer to [gaussdb-ecosystem](https://github.com/HuaweiCloudDeveloper/gaussdb-ecosystem).

> ***If you find this project helpful, don't forget to click the `star` in the top-right corner to show your support!***

# Project Information

| Language   | Driver Name                                                                          | Underlying Driver or Extension | Code Sample                                                                                      | Release Location                                                                             |
| ------ | --------------------------------------------------------------------------------- | ------------------------------------------------------------------ |--------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| JAVA   | [gaussdb-r2dbc](https://github.com/HuaweiCloudDeveloper/gaussdb-r2dbc)               | [r2dbc-postgresql](https://github.com/pgjdbc/r2dbc-postgresql)        | [Code Sample](https://github.com/HuaweiCloudDeveloper/gaussdb-r2dbc-examples)                    | [Released](https://repo.maven.apache.org/maven2/com/huaweicloud/gaussdb/gaussdb-r2dbc/)      |
| .NET   | [gaussdb-dotnet](https://github.com/HuaweiCloudDeveloper/gaussdb-dotnet)             | [npgsql](https://github.com/npgsql/npgsql)                            | [Code Sample](https://github.com/HuaweiCloudDeveloper/gaussdb-dotnet/tree/main/example)          | [Released](https://www.nuget.org/packages/HuaweiCloud.Driver.GaussDB/)                       |
| Python | [gaussdb-python-async](https://github.com/HuaweiCloudDeveloper/gaussdb-python-async) | [asyncpg](https://github.com/MagicStack/asyncpg)                      | [Code Sample](https://github.com/HuaweiCloudDeveloper/gaussdb-python-async/tree/master/examples) | [Released](https://pypi.org/project/async-gaussdb/)                                          |
| NodeJS | [gaussdb-node](https://github.com/HuaweiCloudDeveloper/gaussdb-node)                 | [node-postgres](https://github.com/brianc/node-postgres)              | [Code Sample](https://github.com/HuaweiCloudDeveloper/gaussdb-node/tree/master/examples)         | [Released](https://www.npmjs.com/package/gaussdb-node)                                       |
| PHP    | [gaussdb-php-driver (M/ORA adapter)](https://github.com/huaweicloud-samples/database-gaussdb-php-driver) | [PDO_ODBC](https://github.com/php/php-src/tree/master/ext/pdo_odbc) + GaussDB Unicode ODBC | [Code Sample](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/main/examples/connect.php) | [Source Available](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/tree/main) |
| Rust   | [gaussdb-rust](https://github.com/HuaweiCloudDeveloper/gaussdb-rust)                 | [rust-postgres](https://github.com/sfackler/rust-postgres/)           | [Code Sample](https://github.com/HuaweiCloudDeveloper/gaussdb-rust/tree/master/examples)         | [Released](https://crates.io/crates/gaussdb)                                                 |

For PHP setup on Linux/Windows, see the [installation guide](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/main/docs/installation.md); for application integration, see [API usage](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/main/docs/usage.md). These guides are in Chinese. The project provides source code, not precompiled PHP extensions or vendor ODBC installers.
