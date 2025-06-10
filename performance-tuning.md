# Performance Tuning

## Key Areas

- Work Process Tuning
- Memory Management
- Database Performance

## Useful Transactions

- **ST02** – Tune Summary (buffer analysis)
- **ST04** – Database Performance
- **SM50/SM66** – Work Process Overview
- **ST03N** – Workload Analysis

## Tips

- Regularly clear old spool requests.
- Monitor database indexes and update statistics.
- Analyze slow transactions with **ST12** (trace).

## Checklist

- Review buffer quality in **ST02**.
- Check expensive SQL in **ST04**.
- Analyze workload distribution in **ST03N**.
