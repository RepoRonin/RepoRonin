## Hi there 👋

## 🚀 Open Source Contributions 

### 🧵 Concurrency & Systems Reliability 

- **openfga/openfga** — Dynamic TLS cert rotation for HTTP gateway gRPC client  
  PR: https://github.com/openfga/openfga/pull/2951  
  Enabled dynamic TLS certificate reloading for the HTTP gateway’s internal gRPC client, preventing API failures during cert rotation and improving production reliability.

- **kyverno/kyverno** — Deadlock prevention in `imageContext.Get`  
  PR: https://github.com/kyverno/kyverno/pull/15404  
  Prevented a read/write lock deadlock caused by an early return without releasing `RLock`, improving concurrency safety.
