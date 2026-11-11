# filecoin-message-mix data: calibration network

Messages on the Filecoin **calibration network**, counted by receiving actor type and method, for the
[filecoin-message-mix](https://dire-states.github.io/filecoin-message-mix/) site
([source](https://github.com/dire-states/filecoin-message-mix)). This file is generated on every update.

Covered: height 4230161 (2026-11-09 13:33 UTC) to 4235342 (2026-11-11 08:44 UTC).
Last update: 2026-11-11 08:54 UTC.

## Last 30 days

| Day (hourly CSV) | Messages | Top methods |
|---|---|---|
| [2026-11-11](days/2026/11/2026-11-11.csv) | 44,025 | evm.InvokeContract 43,991, ethaccount.InvokeContract 12, account.Send 10 |
| [2026-11-10](days/2026/11/2026-11-10.csv) | 118,689 | evm.InvokeContract 118,393, ethaccount.InvokeContract 152, ethaccount.Send 47 |
| [2026-11-09](days/2026/11/2026-11-09.csv) | 50,332 | evm.InvokeContract 50,296, account.Send 16, ethaccount.Send 12 |

Months: [2026-11](days/2026/11)

## Files

- `daily.csv`: `date,actor,method,messages` for the whole history, one row per day and method.
- `days/YYYY/MM/YYYY-MM-DD.csv`: `hour,actor,method,messages`, hourly rows for one UTC day.
- `index.json`: covered heights, gaps, days, and totals per method (read by the site).

Messages count at the height of the tipset that includes them; hours and days are UTC. `actor` is the
receiver's actor type (`unknown` if it no longer exists), and method `Send` is a plain transfer.
Methods that are not in the current builtin actors show as `#<number>`.
