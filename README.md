# Liquibase-field-mapping.

## boolean
 
MySQLDatabase: BIT(1)

SQLiteDatabase: BOOLEAN

H2Database: BOOLEAN

PostgresDatabase: BOOLEAN

UnsupportedDatabase: BOOLEAN

DB2Database: SMALLINT

MSSQLDatabase: [bit]

OracleDatabase: NUMBER(1)

HsqlDatabase: BOOLEAN

FirebirdDatabase: SMALLINT

DerbyDatabase: SMALLINT

InformixDatabase: BOOLEAN

SybaseDatabase: BIT

SybaseASADatabase: BIT

## tinyint

MySQLDatabase: TINYINT

SQLiteDatabase: TINYINT

H2Database: TINYINT

PostgresDatabase: SMALLINT

UnsupportedDatabase: TINYINT

DB2Database: SMALLINT

MSSQLDatabase: [tinyint]

OracleDatabase: NUMBER(3)

HsqlDatabase: TINYINT

FirebirdDatabase: SMALLINT

DerbyDatabase: SMALLINT

InformixDatabase: TINYINT

SybaseDatabase: TINYINT

SybaseASADatabase: TINYINT

## int

MySQLDatabase: INT

SQLiteDatabase: INTEGER

H2Database: INT

PostgresDatabase: INT

UnsupportedDatabase: INT

DB2Database: INTEGER

MSSQLDatabase: [int]

OracleDatabase: INTEGER

HsqlDatabase: INT

FirebirdDatabase: INT

DerbyDatabase: INTEGER

InformixDatabase: INT

SybaseDatabase: INT

SybaseASADatabase: INT

## mediumint

MySQLDatabase: MEDIUMINT

SQLiteDatabase: MEDIUMINT

H2Database: MEDIUMINT

PostgresDatabase: MEDIUMINT

UnsupportedDatabase: MEDIUMINT

DB2Database: MEDIUMINT

MSSQLDatabase: [int]

OracleDatabase: MEDIUMINT

HsqlDatabase: MEDIUMINT

FirebirdDatabase: MEDIUMINT

DerbyDatabase: MEDIUMINT

InformixDatabase: MEDIUMINT

SybaseDatabase: MEDIUMINT

SybaseASADatabase: MEDIUMINT

## bigint

MySQLDatabase: BIGINT

SQLiteDatabase: BIGINT

H2Database: BIGINT

PostgresDatabase: BIGINT

UnsupportedDatabase: BIGINT

DB2Database: BIGINT

MSSQLDatabase: [bigint]

OracleDatabase: NUMBER(38, 0)

HsqlDatabase: BIGINT

FirebirdDatabase: BIGINT

DerbyDatabase: BIGINT

InformixDatabase: INT8

SybaseDatabase: BIGINT

SybaseASADatabase: BIGINT

## float

MySQLDatabase: FLOAT

SQLiteDatabase: FLOAT

H2Database: FLOAT

PostgresDatabase: FLOAT

UnsupportedDatabase: FLOAT

DB2Database: FLOAT

MSSQLDatabase: [float](53)

OracleDatabase: FLOAT

HsqlDatabase: FLOAT

FirebirdDatabase: FLOAT

DerbyDatabase: FLOAT

InformixDatabase: FLOAT

SybaseDatabase: FLOAT

SybaseASADatabase: FLOAT

## double

MySQLDatabase: DOUBLE

SQLiteDatabase: DOUBLE

H2Database: DOUBLE

PostgresDatabase: DOUBLE PRECISION

UnsupportedDatabase: DOUBLE

DB2Database: DOUBLE

MSSQLDatabase: [float](53)

OracleDatabase: FLOAT(24)

HsqlDatabase: DOUBLE

FirebirdDatabase: DOUBLE PRECISION

DerbyDatabase: DOUBLE

InformixDatabase: DOUBLE PRECISION

SybaseDatabase: DOUBLE

SybaseASADatabase: DOUBLE

## decimal

MySQLDatabase: DECIMAL

SQLiteDatabase: DECIMAL

H2Database: DECIMAL

PostgresDatabase: DECIMAL

UnsupportedDatabase: DECIMAL

DB2Database: DECIMAL

MSSQLDatabase: [decimal](18, 0)

OracleDatabase: DECIMAL

HsqlDatabase: DECIMAL

FirebirdDatabase: DECIMAL

DerbyDatabase: DECIMAL

InformixDatabase: DECIMAL

SybaseDatabase: DECIMAL

SybaseASADatabase: DECIMAL

## number

MySQLDatabase: numeric

SQLiteDatabase: NUMBER

H2Database: NUMBER

PostgresDatabase: numeric

UnsupportedDatabase: NUMBER

DB2Database: numeric

MSSQLDatabase: [numeric](18, 0)

OracleDatabase: NUMBER

HsqlDatabase: numeric

FirebirdDatabase: numeric

DerbyDatabase: numeric

InformixDatabase: numeric

SybaseDatabase: numeric

SybaseASADatabase: numeric

## blob

MySQLDatabase: LONGBLOB

SQLiteDatabase: BLOB

H2Database: BLOB

PostgresDatabase: BYTEA

UnsupportedDatabase: BLOB

DB2Database: BLOB

MSSQLDatabase: [varbinary](MAX)

OracleDatabase: BLOB

HsqlDatabase: BLOB

FirebirdDatabase: BLOB

DerbyDatabase: BLOB

InformixDatabase: BLOB

SybaseDatabase: IMAGE

SybaseASADatabase: LONG BINARY

## function

MySQLDatabase: FUNCTION

SQLiteDatabase: FUNCTION

H2Database: FUNCTION

PostgresDatabase: FUNCTION

UnsupportedDatabase: FUNCTION

DB2Database: FUNCTION

MSSQLDatabase: [function]

OracleDatabase: FUNCTION

HsqlDatabase: FUNCTION

FirebirdDatabase: FUNCTION

DerbyDatabase: FUNCTION

InformixDatabase: FUNCTION

SybaseDatabase: FUNCTION

SybaseASADatabase: FUNCTION

## UNKNOWN

MySQLDatabase: UNKNOWN

SQLiteDatabase: UNKNOWN

H2Database: UNKNOWN

PostgresDatabase: UNKNOWN

UnsupportedDatabase: UNKNOWN

DB2Database: UNKNOWN

MSSQLDatabase: [UNKNOWN]

OracleDatabase: UNKNOWN

HsqlDatabase: UNKNOWN

FirebirdDatabase: UNKNOWN

DerbyDatabase: UNKNOWN

InformixDatabase: UNKNOWN

SybaseDatabase: UNKNOWN

SybaseASADatabase: UNKNOWN

## datetime

MySQLDatabase: datetime

SQLiteDatabase: TEXT

H2Database: TIMESTAMP

PostgresDatabase: TIMESTAMP WITHOUT TIME ZONE

UnsupportedDatabase: datetime

DB2Database: TIMESTAMP

MSSQLDatabase: [datetime]

OracleDatabase: TIMESTAMP

HsqlDatabase: TIMESTAMP

FirebirdDatabase: TIMESTAMP

DerbyDatabase: TIMESTAMP

InformixDatabase: DATETIME YEAR TO FRACTION(5)

SybaseDatabase: datetime

SybaseASADatabase: datetime

## time

MySQLDatabase: time

SQLiteDatabase: time

H2Database: time

PostgresDatabase: TIME WITHOUT TIME ZONE

UnsupportedDatabase: time

DB2Database: time

MSSQLDatabase: [time](7)

OracleDatabase: DATE

HsqlDatabase: time

FirebirdDatabase: time

DerbyDatabase: time

InformixDatabase: INTERVAL HOUR TO FRACTION(5)

SybaseDatabase: time

SybaseASADatabase: time

## timestamp

MySQLDatabase: timestamp

SQLiteDatabase: TEXT

H2Database: TIMESTAMP

PostgresDatabase: TIMESTAMP WITHOUT TIME ZONE

UnsupportedDatabase: timestamp

DB2Database: timestamp

MSSQLDatabase: [datetime]

OracleDatabase: TIMESTAMP

HsqlDatabase: TIMESTAMP

FirebirdDatabase: TIMESTAMP

DerbyDatabase: TIMESTAMP

InformixDatabase: DATETIME YEAR TO FRACTION(5)

SybaseDatabase: datetime

SybaseASADatabase: timestamp

## date

MySQLDatabase: date

SQLiteDatabase: date

H2Database: date

PostgresDatabase: date

UnsupportedDatabase: date

DB2Database: date

MSSQLDatabase: [date]

OracleDatabase: date

HsqlDatabase: date

FirebirdDatabase: date

DerbyDatabase: date

InformixDatabase: date

SybaseDatabase: date

SybaseASADatabase: date

## char

MySQLDatabase: CHAR

SQLiteDatabase: CHAR

H2Database: CHAR

PostgresDatabase: CHAR

UnsupportedDatabase: CHAR

DB2Database: CHAR

MSSQLDatabase: [char](1)

OracleDatabase: CHAR

HsqlDatabase: CHAR

FirebirdDatabase: CHAR

DerbyDatabase: CHAR

InformixDatabase: CHAR

SybaseDatabase: CHAR

SybaseASADatabase: CHAR

## varchar

MySQLDatabase: VARCHAR

SQLiteDatabase: VARCHAR

H2Database: VARCHAR

PostgresDatabase: VARCHAR

UnsupportedDatabase: VARCHAR

DB2Database: VARCHAR

MSSQLDatabase: [varchar](1)

OracleDatabase: VARCHAR2

HsqlDatabase: VARCHAR

FirebirdDatabase: VARCHAR

DerbyDatabase: VARCHAR

InformixDatabase: VARCHAR

SybaseDatabase: VARCHAR

SybaseASADatabase: VARCHAR

## nchar

MySQLDatabase: NCHAR

SQLiteDatabase: NCHAR

H2Database: NCHAR

PostgresDatabase: NCHAR

UnsupportedDatabase: NCHAR

DB2Database: NCHAR

MSSQLDatabase: [nchar](1)

OracleDatabase: NCHAR

HsqlDatabase: CHAR

FirebirdDatabase: NCHAR

DerbyDatabase: NCHAR

InformixDatabase: NCHAR

SybaseDatabase: NCHAR

SybaseASADatabase: NCHAR

## nvarchar

MySQLDatabase: NVARCHAR

SQLiteDatabase: NVARCHAR

H2Database: NVARCHAR

PostgresDatabase: VARCHAR

UnsupportedDatabase: NVARCHAR

DB2Database: NVARCHAR

MSSQLDatabase: [nvarchar](1)

OracleDatabase: NVARCHAR2

HsqlDatabase: VARCHAR

FirebirdDatabase: NVARCHAR

DerbyDatabase: VARCHAR

InformixDatabase: NVARCHAR

SybaseDatabase: NVARCHAR

SybaseASADatabase: NVARCHAR

## clob

MySQLDatabase: LONGTEXT

SQLiteDatabase: TEXT

H2Database: CLOB

PostgresDatabase: TEXT

UnsupportedDatabase: CLOB

DB2Database: CLOB

MSSQLDatabase: [varchar](MAX)

OracleDatabase: CLOB

HsqlDatabase: CLOB

FirebirdDatabase: BLOB SUB_TYPE TEXT

DerbyDatabase: CLOB

InformixDatabase: CLOB

SybaseDatabase: TEXT

SybaseASADatabase: LONG VARCHAR

## currency

MySQLDatabase: DECIMAL

SQLiteDatabase: REAL

H2Database: DECIMAL

PostgresDatabase: DECIMAL

UnsupportedDatabase: DECIMAL

DB2Database: DECIMAL(19, 4)

MSSQLDatabase: [money]

OracleDatabase: NUMBER(15, 2)

HsqlDatabase: DECIMAL

FirebirdDatabase: DECIMAL(18, 4)

DerbyDatabase: DECIMAL

InformixDatabase: MONEY

SybaseDatabase: MONEY

SybaseASADatabase: MONEY

## uuid

MySQLDatabase: char(36)

SQLiteDatabase: TEXT

H2Database: UUID

PostgresDatabase: UUID

UnsupportedDatabase: char(36)

DB2Database: char(36)

MSSQLDatabase: [uniqueidentifier]

OracleDatabase: RAW(16)

HsqlDatabase: char(36)

FirebirdDatabase: char(36)

DerbyDatabase: char(36)

InformixDatabase: char(36)

SybaseDatabase: UNIQUEIDENTIFIER

SybaseASADatabase: UNIQUEIDENTIFIER
