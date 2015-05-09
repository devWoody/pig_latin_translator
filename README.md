# pig_latin_translator
#
# Code Starts next line
pyg = 'ay'
# ask's the user for a word
original = raw_input('Enter a word:')
# makes sure there are letters and no numbers
if len(original) > 0 and original.isalpha():
    print original
else:
    print 'empty'
# makes the work lowercase
word = original.lower()
first = word[0]
# adds the first letter and "ay" to the end
new_word = word + first + pyg
# takes off the first letter
s = new_word 
new_word = s[1:]
print new_word[1:]
