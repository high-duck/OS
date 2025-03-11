<h1>add_command</h1>
  Adds a command run on terminal to a history list.Only the commands that run and exit successfully are added to the list , others are discared.
  The list resides in kernel space and persists as long as the kernel is shutdown.Max number of commands in history is 128 by default but can be changed.
  
<h1>chmod</h1>
  Changes the file permissions. Usage chmod "filename" "mode". Use 1 for read-only , 2 for write-only and 6 for execute only. eg chmod cats.txt 0

<h1>gethistory</h1>
  Print the commands executed on the system untill now on the terminal.Only the commands that have exited are printed.Behaviour can be changed.
  
<h1>block</h1>
  Block any syscall for all child processes of a process.Does not include shell specific commands like ls , echo etc.
  eg. block 6 , blocks sys_kill.
  
<h1>unblock</h1>
  Unblock any blocked syscall.
