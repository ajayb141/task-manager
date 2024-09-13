# Task Manager

Don't forget to do this...

### In Terminal:

```bash
from app import db, app
with app.app_context():
     db.create_all()
exit()