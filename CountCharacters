# A simple script to count characters in a text
# and assignment it to a str called countCh
# pprint() module is displays a dictionary value cleanly
# the pformt() returns a string value of this output

import pprint

message = '''Some long text here or short one'''

count = {}

for character in message.upper():
    count.setdefault(character, 0)
    count[character] = count[character] + 1
    
countCh = pprint.pformat(count)
print(countCh)
