---
aliases:
---


---

> [!NOTE]- Appeared in Sessions
> 
> ```base
> filters:
>   and:
>     - type == "session"
>     - file.hasLink(this.file)
> views:
>   - type: list
>     name: List
>     sort:
>       - property: file.name
>         direction: DESC
> ```

