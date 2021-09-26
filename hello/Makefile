TARGET_APP := helloworld

all: $(TARGET_APP)

$(TARGET_APP): *.c
	$(CC) -o $@ $^

.PHONY: clean
clean:
	rm -f $(TARGET_APP)
