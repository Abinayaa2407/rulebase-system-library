---

### 🧩 Contributor Notes

This project was developed as a group submission for the *AI Research and Development* module at Sheffield Hallam University.  

**My contributions:**
- Conducted research on rule-based modeling of psychological processes
- Designed the user interface for rule input
- Assisted in Django integration and testing

# How it works

Run the command:
```
pip install RulebaseProductionSystem
```

Import `planner` method from the library in yout python project
```
from RulebaseProductionSystem import planner
```
Use the planner method from library
```
plan = planner.planner(initial_state=[], final_state=[], positions={}, constraints=[], facts=[], iteration_limit=1000)
``` 
