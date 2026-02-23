# Day 03 - RPO & RTO

## RPO (Recovery Point Objective)

- Maximum acceptable data loss
- Measured in time
- Example: RPO = 15 minutes → You can lose up to 15 minutes of data

Lower RPO = More frequent backups

---

## RTO (Recovery Time Objective)

- Maximum acceptable downtime
- Time to restore systems after failure
- Example: RTO = 1 hour → System must be back in 1 hour

Lower RTO = Faster recovery infrastructure

---

## Why It Matters

In enterprise environments:

- RPO defines backup frequency
- RTO defines recovery speed requirements

Customer Success Engineers must understand RPO/RTO when:
- Designing backup strategies
- Explaining SLAs to customers
- Troubleshooting restore delays
