Simple Diff is based on Diff, Match and Patch.

There are quite a few structual changes to the code. The match and patch functionality has been completely removed. There is now only a single accessible method (render). It no longer implements the original API.

The original Diff, Match and Patch library can be found [here](http://code.google.com/p/google-diff-match-patch/)

### Usage

```
simple_diff = new simple_diff()
html = simple_diff.render(text1, text2)
```

### License


Modifications are available under the The MIT License (MIT). 

The original Diff, Match and Patch library is licenesed under the Apache License, Version 2.0. 

See source for full license.
