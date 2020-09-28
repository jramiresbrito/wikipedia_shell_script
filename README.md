# Wikipedia Shell Script with Ruby

This simple shell script written in Ruby receives a Wikipedia URL as param, scrap it's content cleaning the paragraphs and returning them.

Its usefull to use by piping to Linux <code>xclip</code> MacOS <code>pbcopy</code> or WSL2 <code>clip.exe</code>.

First give the execution permission to the script: <code>chmod -x wikipedia_shell_script</code>

Then run it providing the Wikipedia URL as param and pipe it to your clipboard app:  
<code>./wikipedia_shell_script https://pt.wikipedia.org/wiki/Ruby_\(linguagem_de_programa%C3%A7%C3%A3o\) | clip.exe</code>

## Requirements

In order to run this script you must have both [Ruby](https://www.ruby-lang.org/pt/) and [Nokogiri](https://nokogiri.org/) gem installed.
