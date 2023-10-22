
# Port of Oberon A2 base libs for BBCB2

This is port of Oberon A2 libs from https://gitlab.inf.ethz.ch/felixf/oberon to Black Box Component Builder.
Code converted from Active Oberon to Component Pascal using OberonParser tool https://github.com/hodzanassredin/OberonParser.



	
You can use this classes in your code, but it is not recommended, because they will be replaced by more idiomatic BB implementations in future.




# AosBigNumbers
Big numbers lib

# AosBIT
Helper methods for bit manipulations

# AosClock
Time lib

# AosCommStreams
Adpter which wraps CommStreams.Stream and represent it as AosReader Writer pair.

# AosCompat
Helper classes, mainly support for unsigned numbers.

# AosCompatDebug
Helper classes, mainly support for unsigned numbers, more slow than AosCompat but more safe to use, mainly used to debugging purposes.

# AosCompatTests
Tests

# AosConfiguration
Aos configuration interface stub

# AosDates
Aos dates implementation

# AosFileStreams
Adpter which wraps Files.File  and represent it as Aos Reader Writer pair.

# AosIP
Helper classes to work with IP

# AosPipes
Aos implementation of bounded buffer. But in this version writing is not bounded.

# AosRandom
Random numbers generator

# AosRealConversions
Real numbers helper lib.

# AosRealConversionsTests
Tests.

# AosStdLogStream
Adpter which wraps StdLog  and represent it as Aos Writer.

# AosStreams
Aos bufferd writer and reader abstractions. Main building block for everything in aos.

# AosStrings
String manipulations library

# AosTCP	
Adpter which wraps CommTCP  and represent it as Aos Reader Writer pair.

# AosTFClasses
Generic containers lib.

# AosTFLog
Logging library