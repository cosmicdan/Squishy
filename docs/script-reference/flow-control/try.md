# TRY

## Usage

**TRY** *STATEMENT;*
**TRY** *STATEMENT; ***ELSE** *STATEMENT; *[**ELSE** *STATEMENT;*] **END**

## Description

The **TRY **statement can be used to either specify an optional, non-critical *STATEMENT* or to specify a series of alternative *STATEMENT(s)* to perform should the previous fail.

The first usage form is a simple prefix to perform optional statements. If *STATEMENT* fails, the squish will not fail and abort.

The second usage is to **TRY** the first *STATEMENT* and, if it fails, attempt the next **ELSE** *STATEMENT(s)* until one of them succeeds. If the **END** keyword is reached, however, the squish will fail and abort.

Only one *STATEMENT* per **TRY**/**ELSE** clause is possible.