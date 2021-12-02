TARGET_APP := helloworld

all: $(TARGET_APP)

install: $(TARGET_APP)
	install -d $(DESTDIR)$(bindir)
	install -m 755 $(TARGET_APP) $(DESTDIR)$(bindir)

$(TARGET_APP): *.c
	$(CC) -o $@ $^

.PHONY: clean
clean:
	rm -f $(TARGET_APP)
