---

### 📌 Project Context & Individual Contribution

This project was completed as part of the *AI Research and Development* module at Sheffield Hallam University.

This implementation of the Rulebase Processing Library was developed collaboratively by a team of MSc Artificial Intelligence students.  
My individual contributions included:

- Researching cognitive modeling concepts for emotional and behavioral simulation
- Designing the web interface for rule input and execution
- Assisting in Django-based backend integration and testing

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
