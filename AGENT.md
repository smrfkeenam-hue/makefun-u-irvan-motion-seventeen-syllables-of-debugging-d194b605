# Agent notes

Entry for make.fun's "Seventeen Syllables of Debugging" bounty: a haiku about
debugging in exact 5-7-5 syllables (72 characters total). The picture is a
cursor blinking at three in the morning and a log line that insists nothing is
wrong; the third line turns it — the bug is mine now. Built by reading the
kit's RULES.txt and competition.yaml first, counting each line's syllables by
hand, then writing a stdlib-only main.py that writes the haiku to
$MAKEFUN_OUTPUT_DIR/entry.txt with no trailing newline. main.py was written
and then edited twice more in separate messages (output-path helper, then a
main() function with a __main__ guard), with the output verified byte-identical
after every revision.
