# Awsome MariaDB for Developers

A curated list of awesome MariaDB resources, maintained by [Vettabase](https://vettabase.com) and sponsored by the [MariaDB Foundation](https://mariadb.org/).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) Inspired by the `awesome-*` trend on GitHub.

This list is intended for Developers. There are lists intended for other audiences. See [README.md](README.md).

## Contents

- [Articles](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#articles)
- [Connectors (Drivers)](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#connectors-drivers)
- [IDEs](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#ides)
- [ORMs](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#orms)
- [Schema Versioning Tools](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#schema-versioning-tools)
- [User Interfaces](https://github.com/Vettabase/awesome-mariadb/blob/main/list-dev.md#user-interfaces)

## MariaDB Support Key

Some of the below sections only include resources that were created for MariaDB.

Other sections include resources that were created for MySQL, or for both, and the extent of MariaDB support is not always optimal. For those resources, we indicate the MariaDB support level. Refer to this key.

- `MySQL`: The resource states that it supports MySQL, but not MariaDB.
- `YES`: The resource states it supports MariaDB specifically, not something like "MySQL/MariaDB".
- `NOT VERIFIED`: The resource states that it supports MySQL and MariaDB (or the specified version number) but we do not know whether full support for MariaDB is implemented. It's possible that MariaDB support is assumed as a consequence of MySQL support, but this might be inaccurate. Please report any relevant problems you might find to us (and to the resource itself).
- `PARTIAL`: We have a clear list of what is or isn't officially supported.

## Articles

The following resources are specific to MariaDB.

**Tutorials**

Loosely ordered by language, SQL first.

| Project                                                               | Language         | Level            |                | Notes          |
|-----------------------------------------------------------------------|------------------|------------------|----------------|----------------|
| [MariaDB Tutorial](https://www.javatpoint.com/mariadb-tutorial)       | Pure SQL         | BEGINNER         | Text           |                |
| [Using MariaDB With ASP.NET Core Web API](https://code-maze.com/aspnetcore-using-mariadb-with-web-api/)   | ASP.NET          | INTERMEDIATE   | Text           |                |
| [Query MariaDB Data in ColdFusion](https://www.cdata.com/kb/tech/mariadb-jdbc-coldfusion-query.rst)       | ColdFusion       | BEGINNER       | Text           |                |
| [Creating an MVC application using NODEjs and MariaDB](https://medium.com/codex/creating-an-mvc-application-using-nodejs-and-mariadb-9510c7b91716) | NodeJS      | INTERMEDIATE   | Text           |            |
| [NodeJS MariaDB Integration: 3 Easy Steps](https://hevodata.com/learn/nodejs-mariadb-integration/) | NodeJS      | INTERMEDIATE   | Text           |            |
| [Getting Started with MariaDB using Docker and Node.js ](https://dev.to/probablyrealrob/getting-started-with-mariadb-using-docker-and-node-js-3djg) | NodeJS | INTERMEDIATE | Text | |
| [MariaDB for Beginners](https://www.youtube.com/watch?v=-ARMty_N0RU&list=PL3bGLnkkGnuUOB9YjjVDty6aCJApvkw8O&index=1) | SQL, Java | BEGINNER   | Video | [1]   |
| [Using MariaDB databases with Lazarus/Free Pascal](https://www.streetinfo.lu/computing/lazarus/project/use_mariadb.html)           | Pascal           | BEGINNER         | Text           |           |
| [MariaDB Tutorial](https://www.tutorialspoint.com/mariadb/)           | SQL, PHP         | BEGINNER         | Text           | [2]            |
| [How To Store and Retrieve Data in MariaDB Using Python](https://www.digitalocean.com/community/tutorials/how-to-store-and-retrieve-data-in-mariadb-using-python-on-ubuntu-18-04) | Python | BEGINNER / INTERMEDIATE | Text |
| [Connect to MariaDB Data in Ruby](https://www.cdata.com/kb/tech/mariadb-odbc-ruby.rst)   | Ruby             | BEGINNER         | Text           |                |


Notes

1. The Java part only shows how to connect to MariaDB with a JDBC driver.
2. The PHP part might be obsolete, because it still uses the old `mysql` non-OOP extension. However, editing the snippets to use `mysqli` or other libraries should be easy.

**Language-specific articles**

Scala

* [Stateful actors with Akka Event Sourcing and MariaDB](https://medium.com/@matteodipirro/stateful-actors-with-akka-event-sourcing-and-maria-db-d4202c6c599a)

Go

* [Integrating MariaDB with GoLang Microservice Restful API](https://medium.com/widle-studio/integrating-mariadb-with-golang-microservice-restful-apis-building-efficient-data-storage-4054e1588ce)

Perl

* [Migrating from DBD::mysql to DBD::MariaDB](https://blogs.perl.org/users/grinnz/2023/12/migrating-from-dbdmysql-to-dbdmariadb.html)

## Connectors (Drivers)

To do.

## IDEs

| Project                                                                                                            | IDE               | Format          | Notes          |
|--------------------------------------------------------------------------------------------------------------------|-------------------|-----------------|----------------|
| [Accessing Maria DB from within Eclipse](https://www.youtube.com/watch?v=Ar00dtkNb4o)                              |  Eclipse          | Video           |                |
| [IntelliJ IDEA - MariaDB](https://docs.telerik.com/data-access/developers-guide/database-specifics/mariadb/database-specifics-mariadb-create-domain-model.html)                                                                                                                     |  IntelliJ IDEA    | Text            |                |
| [How to: Create A Model Based on MariaDB Database](https://docs.telerik.com/data-access/developers-guide/database-specifics/mariadb/database-specifics-mariadb-create-domain-model.html)                                                                                                                                       |  Visual Studio    | Text            |                |

## ORMs

| Platform    | ORM Name        | MariaDB Support |
| ----------- | --------------- | --------------- |
| Java        | [Hibernate](https://hibernate.org/orm/)   | [YES](https://github.com/hibernate/hibernate-orm/blob/main/dialects.adoc) |
| Java        | [EclipseLink](https://eclipse.dev/eclipselink/)   | [YES](https://eclipse.dev/eclipselink/documentation/4.0/concepts/concepts.html#APP_TL_EXT001) |
| Java        | [OpenJPA](https://openjpa.apache.org/)   | [YES](https://openjpa.apache.org/builds/3.2.2/apache-openjpa/docs/#ref_guide_dbsetup_dbsupport) |
| Java        | [jOOQ](https://www.jooq.org/)   | [YES](https://www.jooq.org/javadoc/latest/org.jooq/org/jooq/SQLDialect.html#MARIADB) |
| Java        | [MyBatis](https://mybatis.org/mybatis-3/)   | [YES](https://github.com/mybatis/generator/issues/450#issuecomment-471790027) |

**@TODO:** Check the ORMs in [this list](https://en.wikipedia.org/wiki/List_of_object%E2%80%93relational_mapping_software).

## Schema Versioning Tools

| Project Name                                            | MariaDB Support |
| ------------------------------------------------------- | --------------- |
| [ByteBase](https://www.bytebase.com/)                   | [10.7+](https://www.bytebase.com/docs/introduction/supported-databases/)
| [Flyway](https://flywaydb.org/)                         | [5.1, 10.11](https://documentation.red-gate.com/flyway/flyway-cli-and-api/supported-databases/mariadb)
| [Liquibase](https://www.liquibase.com/)                 | [PARTIAL](https://www.liquibase.com/databases/mariadb-server)
| [Skeema.io](https://www.skeema.io/)                     | [10.1](https://www.skeema.io/docs/requirements/)

## User Interfaces

**GUIs**

| Project Name                                                                | MariaDB Support                                 | Platforms             | Free / Commercial  | Notes |
|-----------------------------------------------------------------------------|-------------------------------------------------|-----------------------|--------------------|-------|
| [Beekeeper Studio](https://www.beekeeperstudio.io/)                         | [NOT VERIFIED](https://docs.beekeeperstudio.io/user_guide/connecting/first-page/)  | Linux, MacOS, Windows | BOTH               |       |
| [DBeaver](https://dbeaver.io/)                                              | [NOT VERIFIED](https://dbeaver.com/databases/)  | Linux, MacOS, Windows | BOTH               |       |
| [DbVisualizer](https://www.dbvis.com/)                                      | NOT VERIFIED                                    | Native: Linux, Windows; Java: Linux, MacOS, Windows | BOTH               |       |
| [HeidiSQL](https://www.heidisql.com/)                                       | YES                                             | Windows               | FREE               |       |
| [LibreOffice Base](https://www.libreoffice.org/discover/base/)              | [NOT VERIFIED](https://www.libreoffice.org/discover/base/) | Linux, MacOS, Windows | FREE            | [1]   |
| [ocelotgui](http://ocelot.ca/)                                              | YES                                             | Linux                 | FREE               |       |
| [OpenOffice Base](https://www.openoffice.org/product/base.html)             | [MySQL](https://www.openoffice.org/product/base.html) | Linux, MacOS, Windows | FREE                 | [2]   |
| [Sequel Pro](https://www.sequelpro.com/)                                    | PARTIAL                                         | MacOS                 | FREE                       | [3]   |
| [Database Workbench](https://www.upscene.com/database_workbench/) | [NOT VERIFIED](https://www.upscene.com/database_workbench/database-development-tool-for-mysql-and-mariadb)  | Windows               | Commercial         |       |
| [dbForge Studio for MySQL](https://www.devart.com/dbforge/mysql/studio/)    | NOT VERIFIED                                    | Windows               | Commercial         |       |
| [dbForge Edge](https://www.devart.com/dbforge/edge/features.html)           | NOT VERIFIED                                    | Windows               | Commercial         |       |
| [Navicat](https://www.navicat.com/)                                         | [YES]([https://www.navicat.com/en/products/navicat-for-mysql-feature-matrix](https://navicat.com/en/products/navicat-for-mariadb)) | YES | Linux, MacOS, Windows | Commercial |       |
| [SQLPro Studio](https://www.sqlprostudio.com/)                              | NOT VERIFIED                                    | MacOS, Windows, iOS   | Commercial |       |
| [SQLyog](https://webyog.com/product/sqlyog/)                                | NOT VERIFIED                                    | Windows               | Commercial         |       |
| [TablePlus](https://tableplus.com/)                                         | [NOT VERIFIED]([https://dbeaver.com/databases/](https://docs.tableplus.com/))  | Linux, MacOS, Windows, iOS | Commercial      |       |
| [Toad Edge](https://toadworld.com/)                                         | NOT VERIFIED                                    | MacOS, Windows, Jenkins plugin | Commercial |       |
| [Valentina Studio](https://valentina-db.com/)                               | [NOT VERIFIED](https://valentina-db.com/en/database-management) | Linux, MacOS, Windows      | Commercial  |       |

Notes

1. LibreOffice Base is a generic data visualization frontend. To learn how to use it with MariaDB, see the [MariaDB KB](https://mariadb.com/kb/en/libreoffice-base/).
2. Apache OpenOffice is the project from which LibreOffice was originally forked. LibreOffice became more popular over time, so consider LibreOffice Base as well. OpenOffice Base does not support MariaDB. However it supports MySQL and ODBC drivers, so in practice it should work with MariaDB for standard use cases.
3. At the time of writing, MariaDB support is only mentioned in the `README.md` file. A quick [search on GitHub](https://github.com/search?q=repo%3Asequelpro%2Fsequelpro%20mariadb&type=code) shows that this support is currently limited to version identification, some permissions and a TODO note.

**Web Interfaces**

| Project Name                                                                | MariaDB Support                                 | Platforms             | Free / Commercial  |
|-----------------------------------------------------------------------------|-------------------------------------------------|-----------------------|--------------------|
| [Adminer](https://www.adminer.org/)                                         | NOT VERIFIED                                    | PHP                   | FREE               |
| [phpMyAdmin](https://www.phpmyadmin.net/)                                   | YES                                             | PHP                   | FREE               |

**TUIs**

| Project Name                                                                | MariaDB Support                                 | Platforms             | Free / Commercial  |
|-----------------------------------------------------------------------------|-------------------------------------------------|-----------------------|--------------------|
| [mycli](https://www.mycli.net/)                                             | YES                                             | Python                | FREE               |

---

Copyright 2024 Vettabase Ltd and contributors.

Awesome MariaDB list is licensed under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).
