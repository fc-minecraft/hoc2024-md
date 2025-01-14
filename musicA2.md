### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
Это не совсем сработало, давайте сделаем песню немного сильнее, добавив инструмент Ксилофон, чтобы как ксилофон, так и гитара играли ноты.

#### ~ tutorialhint
Добавьте Ксилофон в начало кода.

```ghost
    hoc._add_instrument_activity()
    hoc.note()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/music
```