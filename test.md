__As you can see, there is an unwanted gap between the first and second paragraphs, below.  Can we collapse that gap?__

This is the first paragraph.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.

> Example code:

```
import string
all_digits = []
for ch in src:
  if ch in string.digits:
    all_digits.append(ch)
print "".join(all_digits)
```

This is a second paragraph.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.  The quick brown fox jumps over the lazy dog.