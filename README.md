# filecoin-message-mix data: calibration network

Messages on the Filecoin **calibration network**, counted by receiving actor type and method, for the
[filecoin-message-mix](https://dire-states.github.io/filecoin-message-mix/) site
([source](https://github.com/dire-states/filecoin-message-mix)). This file is generated on every update.

Covered: height 4230161 (2026-11-09 13:33 UTC) to 4284161 (2026-11-28 07:33 UTC).
Last update: 2026-11-28 07:43 UTC.
Gaps (heights the node no longer had): 4237973-4250320.

## Last 30 days

| Day (hourly CSV) | Messages | Top methods |
|---|---|---|
| [2026-11-28](days/2026/11/2026-11-28.csv) | 23,976 | evm.InvokeContract 23,967, miner.SubmitWindowedPoSt 4, account.Send 4 |
| [2026-11-27](days/2026/11/2026-11-27.csv) | 75,757 | evm.InvokeContract 75,662, account.Send 42, ethaccount.Send 17 |
| [2026-11-26](days/2026/11/2026-11-26.csv) | 76,101 | evm.InvokeContract 75,927, account.Send 63, eam.CreateExternal 47 |
| [2026-11-25](days/2026/11/2026-11-25.csv) | 76,075 | evm.InvokeContract 75,970, eam.CreateExternal 38, account.Send 32 |
| [2026-11-24](days/2026/11/2026-11-24.csv) | 75,974 | evm.InvokeContract 75,794, eam.CreateExternal 63, account.Send 54 |
| [2026-11-23](days/2026/11/2026-11-23.csv) | 89,830 | evm.InvokeContract 89,572, account.Send 109, ethaccount.InvokeContract 60 |
| [2026-11-22](days/2026/11/2026-11-22.csv) | 88,225 | evm.InvokeContract 88,137, account.Send 53, ethaccount.Send 19 |
| [2026-11-21](days/2026/11/2026-11-21.csv) | 87,562 | evm.InvokeContract 87,459, account.Send 67, ethaccount.Send 20 |
| [2026-11-20](days/2026/11/2026-11-20.csv) | 87,282 | evm.InvokeContract 87,103, account.Send 73, ethaccount.Send 47 |
| [2026-11-19](days/2026/11/2026-11-19.csv) | 86,919 | evm.InvokeContract 86,667, account.Send 92, ethaccount.InvokeContract 79 |
| [2026-11-18](days/2026/11/2026-11-18.csv) | 84,698 | evm.InvokeContract 84,536, account.Send 85, ethaccount.Send 27 |
| [2026-11-17](days/2026/11/2026-11-17.csv) | 82,200 | evm.InvokeContract 82,049, account.Send 58, ethaccount.Send 37 |
| [2026-11-16](days/2026/11/2026-11-16.csv) | 36,309 | evm.InvokeContract 36,168, ethaccount.Send 60, account.Send 53 |
| [2026-11-12](days/2026/11/2026-11-12.csv) | 32,698 | evm.InvokeContract 32,689, account.Send 5, miner.SubmitWindowedPoSt 4 |
| [2026-11-11](days/2026/11/2026-11-11.csv) | 118,269 | evm.InvokeContract 118,168, account.Send 39, ethaccount.Send 17 |
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
