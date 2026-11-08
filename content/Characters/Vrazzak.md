---
type: article
aliases:
  - Lich
---
An ancient historian who is also a Lich.

---

> [!NOTE]- Mentioned in Sessions
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

