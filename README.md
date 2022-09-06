# Kode

### Flagg funksjon pyret

top = "white"
middle = "green"
bottom = "yellow"

flag = frame(above(rectangle(120,30,"solid",top), above((rectangle(120, 30 , "solid", middle)), rectangle(120, 30, "solid", bottom))))

fun tripBoxHorizFlag(topcolor, middlecolor, bottomcolor):frame(above(rectangle(120,30,"solid",topcolor), above((rectangle(120, 30 , "solid", middlecolor)), rectangle(120, 30, "solid", bottomcolor))))end

jeg har utført pull request