# Flag Sprite Maker

Make flag sprites effortlessly (requires `imagemagick`).

## Generate

1. Move all the flags you want to contact to a sprite from `flags/` to the repository root
  - If you want other names than the full country name simply rename the files
2. Run

  ```
  # Both arguments are optional
  ./make_sprite.sh <class-name> <image-extension>
  ```

3. The files will be available in `output/`

## Usage

```HTML
<a href="#" class="flag-sprite France"></a>
```

## Notes

Though it might be tempting to generate a sprite with __all__ the flags included, don't unless you
need them all. The flag-sprite for all countries will be ~250Kb.

Thanks to [jaymzcd](https://github.com/jaymzcd) for the [sprite generation code](https://gist.github.com/jaymzcd/342399), which I've modified slightly.
