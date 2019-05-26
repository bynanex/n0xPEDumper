# n0xPEDumper

Example: pe -pid 12440 -a 0x1060000 -o c:\dumps\ -CXni

n0xPEDumper is a windows reverse-engineering command-line tool to dump malware memory components back to disk for analysis. Often malware files are packed and obfuscated before they are executed in order to avoid AV scanners, however when these files are executed they will often unpack or inject a clean version of the malware code in memory. A common task for malware researchers when analyzing malware is to dump this unpacked code back from memory to disk for scanning with AV products or for analysis with static analysis tools such as IDA.
