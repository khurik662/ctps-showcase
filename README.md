# CTPS

**Gaming club operations, from opening a station to closing the day.**

CTPS is a local operations prototype that brings station sessions, checkout, and inventory into one workspace. Cashiers handle the floor and customer transactions, while owners manage pricing, stock, and daily reporting.

## What the demo shows

| On the floor | At checkout | In the owner workspace |
| --- | --- | --- |
| See station availability and start a play session. | Add products to a bill and settle a completed session. | Configure zone pricing, review inventory and see daily totals. |

A typical walkthrough starts with an available station, follows the session through checkout, and ends with the owner reviewing the day's activity. The demo runs locally and uses sample transactions.

## Verified outcome

| Check | Result |
| --- | --- |
| Fresh demo | Built and started on an Apple silicon Mac and in Ubuntu CI. |
| Application availability | The home page loaded and the service reported healthy on a clean Mac setup. |
| Automated checks on Mac | 21 launcher tests and 146 Django tests against PostgreSQL passed. |

**Status:** Private alpha, evaluated with sample data.
