

JS_OUTPUT := main.js
all: $(JS_OUTPUT)


SRCS = $(wildcard src/*.gren ../../src/*.gren)


main.js: $(SRCS)
	gren make --output=$@ Main

.PHONY: clean
clean:
	rm -f $(JS_OUTPUT)
