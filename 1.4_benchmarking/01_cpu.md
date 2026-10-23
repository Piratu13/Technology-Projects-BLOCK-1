# 🧪 Task 1 — CPU Speed Test

### 1️⃣ Run this Python script:
```python
import time

def cpu_stress(n=5_000_000):
    total = 0
    for i in range(n):
        total += i*i
    return total

start = time.perf_counter()
cpu_stress()
end = time.perf_counter()
print('Execution time:', end - start, 'seconds')
```

### 2️⃣ Record:
- Execution time
- CPU temperature:
```bash
<img width="576" height="501" alt="image" src="https://github.com/user-attachments/assets/8f8f17b5-afdb-4764-9330-edf5b953d4e6" />

vcgencmd measure_temp
```
- CPU usage in `htop`

📁 Save results in `results/cpu.txt`
