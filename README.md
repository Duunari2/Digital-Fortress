# Digital-Fortress
Annonance discreet dot house about houdini as firestarter.

This is entrypoint of this exec.

This applause is for asking help to code something which would save data loss and save from data corruption on BSOD.

Snippet is simple:

Use sensors to detect when cpu temperature is more than 65-celsius. If it is true then scan 4 most top memory usage applications, and kill them by automation set in config or ask manually each one will we sudo kill memory-eater.pid.

That would save the situtations when computer thinks that it has priviledges to use too much gpu, memory and cpu.

Point to sensors to check situation and possible fix slowmoguys mousepointer or complete PC-Freeze-Situation where is no thing to do to save unsaved works.

I would construct architecture like this:

Sleep(2000);
while(1)
{
sensors | grep value over < 65-celsius.
get top 3 memory user applications with pids.
kill them without asking or ask for each one.

will need sudo and my suggestion is start this application on system startup inside screen window.

I could copy some code which helps to start with command's, but not to be sure is this needed to write from start to end.

Mostly important thing: running in backround under screen -R temperature_watchdog

Programming language is guestion for me, i know php and it would be easy for me, but i think libraries are not supported to this kind of operation.

I can learn some python3 and code this from start to end by my self, just need read and read more.

I promise to put code here and all updates about this temperature_watchdog.py -or .php?

Please pull and make request or comment if you have any idea about this.

Yours sincerely,
admin{ at }anothersearchengine.dy.fi
anothersearchengine{ at }duck.com
P
