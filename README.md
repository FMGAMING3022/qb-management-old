# qb-management

This is an **older version** of `qb-management`. The newer version of QBCore now uses `qb-banking` for financial management. If you prefer, you can still use this older version, as it’s a reliable alternative to `qb-banking` or the updated `qb-management`. 

:small_blue_diamond: **Note**: The only difference in this file is the integration of the society money system; no other changes have been made.
## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-smallresources](https://github.com/qbcore-framework/qb-smallresources) (For the Logs)
- [qb-input](https://github.com/qbcore-framework/qb-input)
- [qb-menu](https://github.com/qbcore-framework/qb-menu)

## Screenshots
![image](https://i.imgur.com/9yiQZDX.png)
![image](https://i.imgur.com/MRMWeqX.png)

## Installation

### Manual
- Download the script and put it in the `[qb]` directory.
- IF NEW SERVER: Import `qb-management.sql` in your database
- IF EXISTING SERVER: Import `qb-management_upgrade.sql` in your database
- Edit config.lua with coords
- Restart Script / Server


If you want to use QB management instead of qb-banking, you need to edit some files.
# Search
```
exports['qb-banking']:
```
Replace With
```
exports['qb-management']:
```
[Original Auther](https://github.com/qbcore-framework)
