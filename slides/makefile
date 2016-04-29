# Configuration options:
# https://github.com/hakimel/reveal.js#configuration

all: 
	pandoc -s --mathjax -i -t revealjs \
	       -V fragments=false \
	       -V controls=false \
	       -V slideNumber=true \
	       slides.md -o slides.html

