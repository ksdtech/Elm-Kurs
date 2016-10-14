
[Back] (Start.md)

---

# First task

Complete `Nikolaus.elm` so that you paint the Nicholas's house:

```
elm
scene _ _ =
  group
  [ rectangle (100, 130)
  , path [ (-50, -65), (50, 65) ]
  ]

main = display (-200, -150) (200, 150) scene Nothing
```

The final image should look like this:

![Nicholas's House] (../images/Nikolaus.png)

## Additional credit 1

Draw a small circle at the top of the house.

## Additional credit 2

Positioning images. A image frame can be moved to any position to `image |> move (x, y)`, where `image` is the expression used to describe the image, and `(x, y)` specifies how much the image is to be moved in the x or y direction.

Show the image "Mario" ![Mario](http://elm-lang.org/imgs/mario/stand/right.gif) to the left of the house.

```
image (45, 45) "http://elm-lang.org/imgs/mario/stand/right.gif"
```

## Additional credit 3

Now show three of the same houses side by side instead of a single house.

---

[Next] (Forms.md)

---

([File](https://raw.githubusercontent.com/jvoigtlaender/Elm-Kurs/master/src/task01/Nikolaus.elm), [@share-elm](http://share-elm.com/sprout/55896e9be4b06aacf0e8a75a/0.14/view))

