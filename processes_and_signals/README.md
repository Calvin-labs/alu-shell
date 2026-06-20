Shell - processes and signals

0-what-is-my-pid: displays its own PID
1-list_your_processes: displays all running processes, user-oriented, with hierarchy
2-show_your_bash_pid: displays process lines containing "bash" (via ps + grep)
3-show_your_bash_pid_made_easy: displays PID and name of processes containing "bash" (via pgrep)
4-to_infinity_and_beyond: displays "To infinity and beyond" indefinitely, sleeping 2s between
5-dont_stop_me_now: stops the 4-to_infinity_and_beyond process using kill
6-stop_me_if_you_can: stops the 4-to_infinity_and_beyond process without kill/killall
7-highlander: loops indefinitely, prints "I am invincible!!!" on SIGTERM instead of dying
67-stop_me_if_you_can: sends SIGTERM to the 7-highlander process (which survives it)
8-beheaded_process: kills the 7-highlander process (SIGKILL)
10-process_and_pid_file: creates a PID file, loops, and handles SIGTERM/SIGINT/SIGQUIT
manage_my_process: writes "I am alive!" to /tmp/my_process every 2 seconds, indefinitely
11-manage_my_process: init-style script to start/stop/restart the manage_my_process daemon
