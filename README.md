# Equipment Maintenance Planner

Plan inspections and repairs for manufacturing equipment and track downtime and parts.

## Status

Year-one local prototype under scheduled development. Features below are planned until their task is committed. No production readiness or ML performance is claimed.

## Run

`python app.py` then open http://127.0.0.1:8000 after the foundation release.
Tests: `python -m pytest -q` after installing pytest. Runtime uses the Python standard library and SQLite.

## Year-one schedule

| Due date | Milestone |
|---|---|
| 2026-11-17 | Add persistent operations API with validated records and audit history |
| 2026-11-24 | Document versioned record API and validation responses |
| 2026-12-01 | Add browser workspace for record entry and table views |
| 2026-12-08 | Add assets transactional CSV imports |
| 2026-12-15 | Add assets summary reporting |
| 2026-12-22 | Add assets paginated text search |
| 2026-12-29 | Add technicians record management |
| 2027-01-05 | Add technicians transactional CSV imports |
| 2027-01-12 | Add technicians summary reporting |
| 2027-01-19 | Add technicians paginated text search |
| 2027-01-26 | Add work orders record management |
| 2027-02-03 | Add work orders transactional CSV imports |
| 2027-02-10 | Add work orders summary reporting |
| 2027-02-17 | Add work orders paginated text search |
| 2027-02-24 | Add inspections record management |
| 2027-03-03 | Add inspections transactional CSV imports |
| 2027-03-10 | Add inspections summary reporting |
| 2027-03-17 | Add inspections paginated text search |
| 2027-03-24 | Add parts record management |
| 2027-03-31 | Add parts transactional CSV imports |
| 2027-04-07 | Add parts summary reporting |
| 2027-04-15 | Add parts paginated text search |
| 2027-04-22 | Add part usage record management |
| 2027-04-29 | Add part usage transactional CSV imports |
| 2027-05-06 | Add part usage summary reporting |
| 2027-05-13 | Add part usage paginated text search |
| 2027-05-20 | Add assignments record management |
| 2027-05-27 | Add assignments transactional CSV imports |
| 2027-06-03 | Add assignments summary reporting |
| 2027-06-10 | Add assignments paginated text search |
| 2027-06-17 | Add sensor readings record management |
| 2027-06-25 | Add sensor readings transactional CSV imports |
| 2027-07-02 | Add sensor readings summary reporting |
| 2027-07-09 | Add sensor readings paginated text search |
| 2027-07-16 | Add failures record management |
| 2027-07-23 | Add failures transactional CSV imports |
| 2027-07-30 | Add failures summary reporting |
| 2027-08-06 | Add failures paginated text search |
| 2027-08-13 | Add downtime record management |
| 2027-08-20 | Add downtime transactional CSV imports |
| 2027-08-27 | Add downtime summary reporting |
| 2027-09-04 | Add downtime paginated text search |
| 2027-09-11 | Add vendors record management |
| 2027-09-18 | Add vendors transactional CSV imports |
| 2027-09-25 | Add vendors summary reporting |
| 2027-10-02 | Add vendors paginated text search |
| 2027-10-09 | Add purchase orders record management |
| 2027-10-16 | Add purchase orders transactional CSV imports |
| 2027-10-23 | Add purchase orders summary reporting |
| 2027-10-30 | Add purchase orders paginated text search |
| 2027-11-06 | Run application tests and lint on pushes and pull requests |
| 2027-11-14 | Document backup recovery and limits for local operations |

Daily automation checks eligibility, validates a pending release, and retries failures without advancing its task. There are 52 milestones over 365 days. Dates are earliest release dates, not guarantees.

## Longer-term product work

After the operational foundation, evaluate hosted authentication, PostgreSQL migrations, deployment, domain-specific workflow rules, and measured ML features. These are not implemented by the year-one task list.
