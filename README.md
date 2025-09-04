## ✅ Phase 3: Audit Logging  

This phase adds an **audit logging system** that records important actions into a log file. It provides accountability by keeping track of who did what and when.  

### Features  
- Logs are stored in `audit_log.json`.  
- Each log entry includes:  
  - Date  
  - Time  
  - Username  
  - Action performed  
  - Outcome (success or denied).  
- Automatically creates a log file if it does not already exist.  
- Prints confirmation in the terminal each time an action is logged.  

### Usage  
Run the script:  
```bash
python phase3_audit_logger.py
