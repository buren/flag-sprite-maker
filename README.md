# Flag Sprite Maker

Make flag sprites effortlessly from a total of 260 flags.

* Requires `imagemagick`:
  - OSX (using homebrew): `brew install imagemagick`
  - Ubuntu: `sudo apt-get install imagemagick --fix-missing`

## Generate

1. Move all the flags you want to contact to a sprite from `flags/`
  - _Note:_ If you want other names than the full country name simply rename the files
2. Run

  ```
  # All arguments are optional
  ./make_sprite.sh <path_to_flags> <desired_class_name>
  ```

3. The files will be available in `output/`
  - [See example output](example/test.html)

## HTML Usage

Include the generated css file and then in your HTML-template you can write.

```HTML
<a href="#" class="flag-sprite Sweden"></a>
<a href="#" class="flag-sprite Germany"></a>
```

## Notes

Though it might be tempting to generate a sprite with __all__ the flags included, don't unless you
need them all. The flag-sprite for all countries will be ~250Kb.

Thanks to [jaymzcd](https://github.com/jaymzcd) for the [gist](https://gist.github.com/jaymzcd/342399), which I've modified slightly.
