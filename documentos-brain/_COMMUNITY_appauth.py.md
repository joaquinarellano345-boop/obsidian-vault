---
type: community
cohesion: 0.16
members: 16
---

# app/auth.py

**Cohesion:** 0.16 - loosely connected
**Members:** 16 nodes

## Members
- [[Session]] - code
- [[appauth.py]] - code - CosmoHub/app/auth.py
- [[appmain.py]] - code - CosmoHub/app/main.py
- [[client()]] - code - CosmoHub/tests/conftest.py
- [[conftest.py]] - code - CosmoHub/tests/conftest.py
- [[create_access_token()]] - code - CosmoHub/app/auth.py
- [[database.py]] - code - CosmoHub/app/database.py
- [[db_session()]] - code - CosmoHub/tests/conftest.py
- [[fixture]] - code
- [[get]] - code
- [[get_current_user()]] - code - CosmoHub/app/auth.py
- [[get_db()]] - code - CosmoHub/app/database.py
- [[get_password_hash()]] - code - CosmoHub/app/auth.py
- [[read_root()]] - code - CosmoHub/app/main.py
- [[timedelta]] - code
- [[verify_password()]] - code - CosmoHub/app/auth.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/app/authpy
SORT file.name ASC
```

## Connections to other communities
- 1 edge to [[_COMMUNITY_.run]]
- 1 edge to [[_COMMUNITY_models.py]]

## Top bridge nodes
- [[database.py]] - degree 5, connects to 1 community
- [[timedelta]] - degree 2, connects to 1 community