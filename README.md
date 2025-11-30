30th November, Sunday, 2025.
Version: 1.0.0
Use: Documentation
Extension: Markdown
# RFX (Reflexive)
RFX is a jit compiled coding language in ANSI C, made for extreme natural readability flow and for coding beginners. RFX uses multiple brilliant workarounds as of the current version. 
## Language Philosophy
RFX believes code should read like natural language while maintaining computational precision.
## Core Principles
- **Readability First**: Code should be understandable at a glance
- **Beginner Friendly**: Gentle learning curve with immediate results  
- **Mobile Native**: Born and bred in Termux on Android devices
# Assignments
release(integer) = 30
release(string) = "hello!"
# Basic I/O
release(input) = io("prompt : ") //replace prompt with any text you want
write("Input = " :: input)
# CONDITIONALS
so variable == value do
    # code block
stop
# STRING OPERATIONS
write("Hello " :: "World")  # Concatenation
# COMMENTS
# Single line comment
^^ single line
[[ Multi-line
   comment block ]]
# Loops
release(true) = 1

so true == 1 do
  ...
    so true == 1 do
    ...
        so true == 1 do
      ...
        stop
    stop
stop
# Test
release(true) = 1
write("Michael Myers: ... ")
so true == 1 do
    release(input) = io("User: ")
    so input == "hi" do
        write("Michael Myers: *trips and rolls*")
        release(input) = io("User: ")
    stop
    so input == "why" do
        write("Michael Myers: *keeps staring*")
        release(input) = io("User: ")
   stop
stop
# Implementation
1. download binary (rfx-named file)
2. go to your terminal
3. cp rfx /$PREFIX/bin
4. chmod +x rfx
5. rfx script.rfx
# Credits
- DeepSeek (doc helper guy)
Thank you for using RFX. It's a great honor to be used world-wide and recognized.
