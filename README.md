## Hi there 👋

## 🚀 Open Source Contributions 

### 🧵 Concurrency & Systems Reliability 

- **kyverno/kyverno** — Deadlock prevention in `imageContext.Get`  
  PR: https://github.com/kyverno/kyverno/pull/15404  
  Prevented a read/write lock deadlock caused by an early return without releasing `RLock`, improving concurrency safety.
