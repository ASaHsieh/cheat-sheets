# [Byobu](https://www.byobu.org/)
## How to kill a byobu session? 
- Ref.: https://askubuntu.com/questions/891518/how-to-kill-a-byobu-session
- Steps:
  1. 	You can list byobu current sessions with:
  ```
  byobu list-session
  ```
  2. You should see something like this: 
  ```
  session_1: 1 windows (created Tue Feb 6 18:05:35 2018) [237x49]
  session_2: 1 windows (created Tue Feb 6 18:05:44 2018) [237x49]
  session_3: 1 windows (created Tue Feb 6 18:06:05 2018) [237x49]
  ```
  3. The first word in every line is the session name. So, to kill a single session you can do:
  ```
  byobu kill-session -t <session_name>`
  ```
  4. To kill `session_2` in previous list, you can do:
  ```
  byobu kill-session -t session_2
  ```
###### tags: `shortcut_and_cheatsheet`