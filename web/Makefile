.PHONY: build install_markdown

build:
	echo 'building'
	rm -f text.html
	cat head.html > text.html
	cat white_fragility_web_edit.md | ./Markdown_1.0.1/Markdown.pl >> text.html
	cat tail.html >> text.html

install_markdown:
	curl -O http://daringfireball.net/projects/downloads/Markdown_1.0.1.zip
	unzip Markdown_1.0.1.zip
