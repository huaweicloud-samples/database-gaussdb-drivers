<p align="center">
  <p align="center">
    <a href="README_EN.md"><strong>English</strong></a> | <strong>简体中文</strong>
</p>

本项目的目的是帮助繁荣 [GaussDB](https://www.huaweicloud.com/product/gaussdb.html) 和 [OpenGauss](https://opengauss.org/zh/) 开源生态。

项目包括常见语言的驱动和兼容接入方案，多数基于 PostgreSQL 开源驱动构建；PHP M/ORA 兼容层通过 PDO_ODBC 和 GaussDB 官方 Unicode ODBC 驱动接入。GaussDB开源生态信息参考 [gaussdb-ecosystem](https://github.com/HuaweiCloudDeveloper/gaussdb-ecosystem) 。

> ***如果发现项目能帮助到您，别忘了点击右上角`star`表示鼓励***

# 项目信息

| 语言   | 驱动名称                                                                          | 底层驱动或扩展 | 示例代码                                                                                      | 发布地址                                                                                    |
| ------ | --------------------------------------------------------------------------------- | ------------------------------------------------------------------ |-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| JAVA   | [gaussdb-r2dbc](https://github.com/HuaweiCloudDeveloper/gaussdb-r2dbc)               | [r2dbc-postgresql](https://github.com/pgjdbc/r2dbc-postgresql)        | [示例代码](https://github.com/HuaweiCloudDeveloper/gaussdb-r2dbc-examples)                    | [已发布](https://repo.maven.apache.org/maven2/com/huaweicloud/gaussdb/gaussdb-r2dbc/)      |
| .NET   | [gaussdb-dotnet](https://github.com/HuaweiCloudDeveloper/gaussdb-dotnet)             | [npgsql](https://github.com/npgsql/npgsql)                            | [示例代码](https://github.com/HuaweiCloudDeveloper/gaussdb-dotnet/tree/main/example)          | [已发布](https://www.nuget.org/packages/HuaweiCloud.Driver.GaussDB/)                       |
| Python | [gaussdb-python-async](https://github.com/HuaweiCloudDeveloper/gaussdb-python-async) | [asyncpg](https://github.com/MagicStack/asyncpg)                      | [示例代码](https://github.com/HuaweiCloudDeveloper/gaussdb-python-async/tree/master/examples) | [已发布](https://pypi.org/project/async-gaussdb/)                                          |
| NodeJS | [gaussdb-node](https://github.com/HuaweiCloudDeveloper/gaussdb-node)                 | [node-postgres](https://github.com/brianc/node-postgres)              | [示例代码](https://github.com/HuaweiCloudDeveloper/gaussdb-node/tree/master/examples)         | [已发布](https://www.npmjs.com/package/gaussdb-node)                                       |
| PHP    | [gaussdb-php-driver（M/ORA 兼容层）](https://github.com/huaweicloud-samples/database-gaussdb-php-driver) | [PDO_ODBC](https://github.com/php/php-src/tree/master/ext/pdo_odbc) + GaussDB Unicode ODBC | [示例代码](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/v0.1.0/examples/connect.php) | [已发布](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/releases/tag/v0.1.0) |
| Rust   | [gaussdb-rust](https://github.com/HuaweiCloudDeveloper/gaussdb-rust)                 | [rust-postgres](https://github.com/sfackler/rust-postgres/)           | [示例代码](https://github.com/HuaweiCloudDeveloper/gaussdb-rust/tree/master/examples)         | [已发布](https://crates.io/crates/gaussdb)                                                 |

# 其他参考信息

PHP 兼容层的发行页提供 ZIP、tar.gz 源码包和 SHA-256 校验文件，Windows/Linux 共用 PHP 源码。下载校验见 [发行包使用](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/v0.1.0/docs/releases.md)，环境准备和安装步骤见 [安装指引](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/v0.1.0/docs/installation.md)，业务接入见 [API 使用](https://github.com/huaweicloud-samples/database-gaussdb-php-driver/blob/v0.1.0/docs/usage.md)。发行包不包含预编译 PHP 扩展或厂商 ODBC 安装包。

* [GaussDB和PostgresSQL功能和语法差异](docs/diff-gaussdb-postgres.md)
* [GaussDB和OpenGauss功能和语法差异](docs/diff-gaussdb-opengauss.md)
* [GaussDB、OpenGauss、JDBC驱动已知缺陷](docs/known-bugs.md)
