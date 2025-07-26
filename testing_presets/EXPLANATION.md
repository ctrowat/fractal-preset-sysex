# Explanation

I always work in preset number 475 on my device as that was just a convenient empty spot to make some testing presets within.  Currently I am testing on a Fractal FM3 running firmware 10.0

# Preset Descriptions

## Preset-level data:

### 475-actually empty.syx

This is a completely empty new preset.  By default fractal names the preset \<Unnamed\> and I left that alone.

### 475-EMPTY.syx

Same as the above except the name is now completely empty

### 475-a.syx

Same as above, but the name is just a single "a"

### 475-aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.syx

Same as the above preset except the preset name was filled to the maximum length with the character "a"

### 475-aaaaaaaaaaaaaaaaaaaaaaaaaaaaaab.syx

Same as above but the last character of the preset name was changed to "b".  Hoping to isolate checksum values and check byte ordering with this

### 475-aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa-z.syx

Back to all "a"s except now there is a single scene with its name having only a single "z"

### 475-aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa-zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz.syx

Same as above but scene 1's name is now fully filled out with "z" characters

### 475-a-zxywvuts.syx

Same as above, but scenes 2-8 are now filled out with single characters, descending (i.e. 1 is all z, 2 is all y, ...)


## Block-level data:


### 475-in1-test-empty.syx

The name has been changed to "in1-test", no blocks present

### 475-in1-test-top(left|right).syx

Same as above, with an In 1 block in the top left or right space

### 475-in1-test-topsecondleft.syx

Same as above, In 1 has been moved to the right 1 space

### 475-in1-test-secondrow(left|right).syx

Now the In 1 block is row 2, left-most or right-most space

### 475-in1-test-thirdrow(left|right).syx

Now the In 1 block is in row 3, left-most or right-most space

### 475-in1-test-bottom(left|right).syx

Now the In 1 block is in the bottom left or bottom right

