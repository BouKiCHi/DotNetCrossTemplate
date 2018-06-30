TARGET = Program.exe
CSC = C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe
SRCS = Program.cs 
# SRCS += Test.cs

TARGET_PATH = ../$(TARGET)

all : $(TARGET_PATH)

$(TARGET_PATH) : $(SRCS)
	$(CSC) /define:RELEASE /out:$(TARGET) $^
	mv $(TARGET) $(TARGET_PATH)

clean : 
	rm -f $(TARGET_PATH)