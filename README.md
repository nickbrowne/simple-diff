Simple Diff is based on Diff Match and Patch.

There are quite a few structual changes to the code. The match and patch functionality has been completely removed. There is now only a single accessible method (render). It no longer implements the original API.

## Usage

```
simple_diff = new simple_diff()
html = simple_diff.render(text1, text2)
```
