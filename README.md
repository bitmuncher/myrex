# myrex
A simple remote execution framework to run commands via SSH on single hosts or defined host groups<br />
<br />
<pre>
pyrex.py <parameters>
  -t <task>		the task PyRex should run
  -h <host>		the host where the task should run
  -g <group>		the host group where the task should run
  -a '<arguments>'	additional arguments for a task, enclosed in single quotes
			format: 'key1=value1,key2=value2'
  --hostlist		print a list of all defined hosts
  --configtest		check the config.ini
</pre>

