# Day 02 - Block vs Object Storage

## Block Storage

- Data stored in fixed-size blocks
- Used by operating systems
- Appears as a disk (e.g., /dev/sda)
- High performance
- Suitable for databases and virtual machines

Examples:
- SAN
- iSCSI
- AWS EBS

---

## Object Storage

- Data stored as objects
- Each object has metadata + unique ID
- Accessed via HTTP/REST APIs
- Highly scalable
- Suitable for backups and large data storage

Examples:
- AWS S3
- Cloud backup systems

---

## Key Differences

Block Storage:
- Low latency
- Structured
- Used for active workloads

Object Storage:
- Scalable
- Metadata-rich
- Used for backups and archives

---

## Why This Matters

Backup and data protection platforms rely heavily on object storage for scalability and resilience.

Understanding the difference is critical for enterprise storage and cloud data security roles.
