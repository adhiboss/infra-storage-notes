# Day 04 - Snapshot vs Backup

## Snapshot

- Point-in-time copy of data
- Usually stored in same storage system
- Fast to create
- Not fully independent
- Depends on underlying storage

Used for:
- Quick rollback
- VM restore
- Short-term recovery

---

## Backup

- Independent copy of data
- Stored on separate storage
- Slower than snapshots
- Protects against hardware failure and ransomware

Used for:
- Disaster recovery
- Long-term retention
- Compliance

---

## Key Difference

Snapshot:
- Fast
- Storage-dependent
- Short-term protection

Backup:
- Independent
- Safer
- Long-term protection

---

## Why It Matters

Enterprise backup platforms combine:
- Snapshots for fast recovery
- Backups for long-term resilience
