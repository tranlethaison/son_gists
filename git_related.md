# Windows 10 git log output encoding issue
- https://stackoverflow.com/questions/41139067/git-log-output-encoding-issues-on-windows-10-command-prompt
- Cmd:
  ```cmd
  set LC_ALL=C.UTF-8
  #chcp 65001
  ```
 - Powershell
  ```powershell
  $env:LC_ALL='C.UTF-8'
  ```
