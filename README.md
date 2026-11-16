# raylib-demo

Bounce: a small game on [**raylib**](https://github.com/sysl-lang/raylib). Shapes spin and bounce
around the window while you steer a paddle to keep a ball off the floor.

*An independent sysl program using raylib. It is not affiliated with or endorsed by raylib's authors or trademark holders.*

```
brew install raylib
sysl run .
```

| key | what it does |
|---|---|
| `←` `→` or `A` `D` | move the paddle |
| `space` | add a shape |
| `R` | start again |
| `Esc` | quit |

It shows the binding's everyday surface:

- the `Window` handle;
- the frame loop;
- 2D shapes (circles, rotated rectangles, polygons);
- text with `measure_text`;
- keyboard state;
- `Vector2` arithmetic;
- circle–rectangle collision.
