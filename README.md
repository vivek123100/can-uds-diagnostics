<<<<<<< HEAD
# CAN & UDS Diagnostics – ECU Communication Testing

Learning and portfolio project: simulating ECUs on a CAN network and testing
UDS diagnostic services.

## Feature under test
A door ECU sends status messages on CAN and answers UDS diagnostic requests
(read software version, read DTCs).

## Project structure
| Folder | Content | Status |
|---|---|---|
| `docs/` | Requirements, test specification, traceability | In progress |
| `dbc/` | CAN database (DBC file) | Planned |
| `src/` | Python ECU simulation | Planned |
| `tests/` | Automated tests (pytest) | Planned |
| `reports/` | Test reports | Planned |

## Tools
Python · python-can · cantools · udsoncan · SocketCAN · pytest

## Progress log
- [ ] Requirements written
- [ ] DBC file created
- [ ] ECU simulation on virtual CAN
- [ ] UDS services implemented and tested