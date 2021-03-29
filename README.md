# spritescaler

Tool to upscale/downscale sprites

### Usage:

```
  --output string
        Specify output directory of processed files
  --scale float
        Specify scale to use (0.5 halves the size, 2.0 doubles it, etc) (default 1)
  --verbose
        Print additional messages
```

### Example:

```sh
# Scale "image.png" by 2 inplace
spritescaler --scale 2.0 image.png

# Scale each .png file in "images" into half its size, and output the result to "results"
spritescaler --scale 0.5 --output "results" --verbose "images/*.png"
```
