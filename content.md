###Testing MD for python

4 whitespaces indent to auto-detect the language:

    print("Hello, World")
    # some comment
    for letter in "this is a test":
        print(letter)

Specify language-tag using 3 colons:


    :::python
    print("Hello, World")

Highlight specific lines:

    :::python hl_lines="1 5"
    print("highlight me!")
    # but not me!
    for letter in "this is a test":
    print(letter)
    # I want to be highlighted, too!