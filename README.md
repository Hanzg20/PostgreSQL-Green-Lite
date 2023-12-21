# PostgreSQL-Green: Lightweight PostgreSQL Distribution

This repository contains a lightweight distribution of PostgreSQL, optimized for efficient performance and resource utilization.

## Features

- **Multi-CPU Support**: Optimized for various CPU architectures.
- **Multi-OS Compatibility**: Works seamlessly across different operating systems.

## Included Architectures

- **aarch**:
  - FeiTeng
  - KunPeng

- **alpha**:
  - ShenWei

- **mips**:
  - Loongson

- **x86**:
  - HaiGuang
  - ZhaoXin

**Windows**:
  - AMD x86 architecture support on Windows.

## Built-in Users

- **admin/admin** - Limited to local machine login.
- **guest/guest** - Allows login from any IP address.

## Built-in Database

- **testdb**

## Start/Stop Commands

- **Linux**:
  - Start: `pg_start`
  - Stop: `pg_stop`

- **Windows**:
  - Start: `start_pg.bat`
  - Stop: `stop_pg.bat`

## Command-Line Access

- **Linux**: `pg_cmd.sh` (Prompts for the `guest` user by default)
- **Windows**: `cmd_pg.bat` (Prompts for the `guest` user by default)

Feel free to customize, enhance, and contribute to this PostgreSQL-Green setup. Your feedback and contributions are highly appreciated!
