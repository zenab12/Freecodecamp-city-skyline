# [Live Demo ](https://zenab12.github.io/Freecodecamp-city-skyline/)
## tips i learned while coding this task 
- Variables implies only for it's children . That's just how CSS works. Because of this, variables are often declared in the `:root` selector. This is the highest level selector in CSS; putting your variables there will make them usable everywhere
and we make fallback value to avoid any problem.
- Gradients in CSS are a way to transition between colors across the distance of an element. They are applied to the background property and the syntax looks like this:

```
gradient-type(
  color1,
  color2
);
```
- You can specify where you want a gradient transition to complete by adding it to the color like this:

```
gradient-type(
  color1,
  color2 20%,
  color3
);
```
- So far, all the gradients you created have gone from top to bottom, that's the default direction. You can specify another direction by adding it before your colors like this:
```
gradient-type(
  direction,
  color1,
  color2
);
```
![Screen Shot 2022-07-24 at 18 57 26](https://user-images.githubusercontent.com/78083890/180658499-28c734b3-3c68-49bf-ba08-0cd02395fe58.png)
![Screen Shot 2022-07-24 at 19 48 20](https://user-images.githubusercontent.com/78083890/180659624-8ad86005-fba2-403c-bcfa-c1490a071c44.png)
