# parallel_toolset
Some tools that do things in parallel and work on folders rather than single files.

 useful for the cases you need to count how many lines a Sqoop extract from Hadoop has, and then validate against your process if you loaded or processed all the lines.

The first tool is *plc* which runs a parallel line count with as many threads as cores your server has.
(I have used a much smaller version to count billions of lines, from cat taking ~6.5 hours to plc taking ~ 5 minutes)
