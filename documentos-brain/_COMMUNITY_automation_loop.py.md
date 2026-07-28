---
type: community
cohesion: 0.17
members: 21
---

# automation_loop.py

**Cohesion:** 0.17 - loosely connected
**Members:** 21 nodes

## Members
- [[Actualiza los metadatos de un video existente.]] - rationale - youtube_client.py
- [[Autentica al usuario y devuelve el servicio de YouTube.]] - rationale - youtube_client.py
- [[Genera un título llamativo para el video.]] - rationale - generator.py
- [[Genera una descripción optimizada para el video.]] - rationale - generator.py
- [[Genera una lista de etiquetas relevantes.]] - rationale - generator.py
- [[Sube un video a YouTube.]] - rationale - youtube_client.py
- [[Sube un video y lo programa para una fecha específica.]] - rationale - youtube_client.py
- [[automation_loop.py]] - code - automation_loop.py
- [[configconfig.py]] - code - config/config.py
- [[generate_description()]] - code - generator.py
- [[generate_tags()]] - code - generator.py
- [[generate_title()]] - code - generator.py
- [[generator.py]] - code - generator.py
- [[get_authenticated_service()]] - code - youtube_client.py
- [[get_next_video()]] - code - automation_loop.py
- [[log_message()]] - code - automation_loop.py
- [[main_loop()]] - code - automation_loop.py
- [[schedule_video()]] - code - youtube_client.py
- [[update_video()]] - code - youtube_client.py
- [[upload_video()]] - code - youtube_client.py
- [[youtube_client.py]] - code - youtube_client.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/automation_looppy
SORT file.name ASC
```
