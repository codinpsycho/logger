# logger
Simple logging system for peace of mind

#Features

By default logs will be written to
DEFAULT_LOGFILE "log.txt"

You can log by

1. LOG<<"whatever";

2. LOG.write("%s", "whatever");

You can attach different files in between for maintaining different logs for different systems/programmers

1. LOG.AttachFile("Grpahics.txt");

2. LOG.AttachFile("Log_for_Programmer1.txt");

3. LOG.AttachFile("Log_for_Programmer2.txt"); etc etc


To resume logging to default file simply

LOG.AttachFile(DEFAULT_LOGFILE);

Also theres OUTPUT("%s", "Print to output window the printf style");

