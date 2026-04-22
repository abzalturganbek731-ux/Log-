# Log System

## Description
This project demonstrates a simple logging system that records:
- System events
- Warnings
- Errors

## Features
- Info logs
- Warning logs
- Error logs
- Log file creation

## Code Example

```python
import logging

logging.basicConfig(
    filename='system.log',
    level=logging.INFO,
    format='%(asctime)s - %(levelname)s - %(message)s'
)

logging.info("System started")
logging.warning("Warning message")
logging.error("Error occurred")
```

## Output Example
Example log file:

```text
2026-04-22 12:00:00 - INFO - System started
2026-04-22 12:01:00 - WARNING - Warning message
2026-04-22 12:02:00 - ERROR - Error occurred
```

## Author
Your Name
