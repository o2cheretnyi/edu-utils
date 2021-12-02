TARGET_APP := helloworld

all: $(TARGET_APP)

install: $(TARGET_APP)
	install -m 755 $(TARGET_APP) /usr/bin

$(TARGET_APP): *.c
	$(CC) -o $@ $^

.PHONY: clean
clean:
	rm -f $(TARGET_APP)
