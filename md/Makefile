DIR=../source/doc
  
source=$(wildcard *.md)
target=$(patsubst %.md,$(DIR)/%.rst,$(source))

all: $(target)

$(DIR)/%.rst: %.md
	pandoc $< -o $@
