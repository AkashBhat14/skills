---
"mattpocock-skills": patch
---

`wizard` template `open_url` opens URLs via `cmd.exe //c start` on Windows, so Git Bash no longer hangs on the mangled `/c` switch nor prints a false "couldn't open a browser" warning (#963).
