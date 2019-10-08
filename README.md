# Krieger Makros

## Stances

```lua
#showtooltip
/cast Verteidigungshaltung
/stopmacro [equipped:Schild]
/equipslot 16 4 1
/equipslot 17 4 2
```

```lua
#showtooltip
/cast Kampfhaltung
/use [equipped:Schild] 4 1
```

## Sturmangriff

```lua
#showtooltip Sturmangriff
/cast [stance:1] Sturmangriff
/stopmacro [stance:1]
/cast Kampfhaltung
/cast Sturmangriff
```

### Extended

```lua
#showtooltip [mod:alt]Abfangen;Sturmangriff
/cast [stance:1/2,mod:alt] Berserkerhaltung
/cast [mod:alt,stance:3] Abfangen
/stopmacro [mod:alt]
/cast [stance:1] Sturmangriff
/stopmacro [stance:1]
/cast Kampfhaltung
/cast Sturmangriff
```

## Schildblock

```lua
#showtooltip Schildblock
/cast [stance:1/3] Verteidigungshaltung
/equipslot [noequipped:Schild] 16 4 1
/equipslot [noequipped:Schild] 17 4 2
/cast Schildblock
```

## Entwaffnen

```lua
#showtooltip Entwaffnen
/cast [stance:2]Entwaffnen
/stopmacro [stance:2]
/cast Verteidigungshaltung
/cast Entwaffnen
```

## Schildhieb

```lua
#showtooltip Schildhieb
/cast [equipped:Schild]Schildhieb
/stopmacro [equipped:Schild]
/equipslot [noequipped:Schild] 16 4 1
/equipslot [noequipped:Schild] 17 4 2
/cast Schildhieb
```

## Spott

```lua
#showtooltip Spott
/cast [stance:2]Spott
/stopmacro [stance:2]
/cast Verteidigungshaltung
/cast Spott
```

```lua
#showtooltip Spöttischer Schlag
/cast [stance:1]Spöttischer Schlag
/stopmacro [stance:1]
/cast Kampfhaltung
/cast Spöttischer Schlag
```

## Attack / Stop Attack

```lua
#showtooltip
/stopattack [mod:alt]
/stopmacro [mod:alt]
/startattack
/cast Heldenhafter Stoß
```

```lua
#showtooltip
/stopattack [mod:alt]
/stopmacro [mod:alt]
/startattack
/cast Verwunden
```

## Fernkampf

```lua
#showtooltip
/cast [equipped:Wurfwaffe] Werfen
/cast [equipped:Bogen] Bogenschuss
/cast [equipped:Schusswaffe] Schusswaffe abfeuern
```

