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
  <img width="576" height="501" alt="image" src="https://github.com/user-attachments/assets/f811b8ce-a733-4e72-9f72-b412634a567d" />

- CPU temperature:
```bash

vcgencmd measure_temp
```
- CPU usage in `htop`

📁 Save results in `results/cpu.txt`
