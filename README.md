# AVMetaGrabber

Java program which will recurse a directory of audio and video files, extract technical metadata from the files and produce a report summarizing the most important metadata.

The Java GUI should allow the user to select a directory (with or without recursion), process the appropriate files in that directory, analyze the metadata of the files, and produce output to the screen (JTable) and to an exported report.

The actual metadata extraction will probably be performed by either MediaInfo (https://mediaarea.net/en/MediaInfo) or Apache Tika (https://www.tutorialspoint.com/tika/tika_extracting_mp3_files.htm). The remaining code will be the GUI, directory recursion, file identification (by extension), output to GUI, and log creation.

The program will identify and extract information from the formats listed at:

https://mediaarea.net/en/MediaInfo/Support/Formats

The table also lists the metadata elements to be extracted to the JTable.

Possible test datasets can be found at:

https://towardsdatascience.com/a-data-lakes-worth-of-audio-datasets-b45b88cd4ad
