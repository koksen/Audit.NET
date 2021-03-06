# Changelog
All notable changes to Audit.NET and its extensions will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## [UNRELEASED] - 2018-01
### Added
- Adding NETSTANDARD2.0 support to Audit.NET 

### Changed
- EventLog data provider available on NETCORE 2.0
- EventLog new MessageBuilder property to allow customizing the logged message
- Audit.DynamicProxy: allow setting the creation policy.

## [11.0.1] - 2018-01-28
### Changed
- Audit.MySql: refactor by bgrainger@gmail.com to use MySqlConnector instead of MySql.Data to support real async calls.

## [11.0.0] - 2018-01-14
### Added
- Async support to the AuditScope and all the data providers.
- Async support for Audit.EntityFramework, Audit.WCF, Audit.WebAPI and Audit.MVC extensions.
- Data retrieval methods for most of the data providers.
- New Custom Action OnEventSaved triggered right after the event is saved.

## [10.0.3] - 2017-12-28
### Changed
- Audit.EntityFramework: bug fixing [#92](https://github.com/thepirat000/Audit.NET/issues/92)

## [10.0.2] - 2017-12-25
### Added
- New Audit.NET.log4net extension to log events with Apache log4net.


