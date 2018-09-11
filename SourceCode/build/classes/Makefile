JC = javac

.SUFFIXES: .java .class
.java.class:
	$(JC) $*.java

CLASSES = \
	SenderPane.java\
	ReceiverPane.java

default: classes

classes: $(CLASSES:.java=.class)

clean:
	$(RM) *.class
