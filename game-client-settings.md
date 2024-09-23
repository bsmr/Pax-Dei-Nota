# Pax Dei - Game Client Settings

## Settings Location

Use `cmd` and `cd %USERPROFILE%\AppData\Local\PaxDei\Saved\Config\WindowsClient`.

Open `GameUserSettings.ini` with an editor, like `notepad`, or _Visual Studio Code_.

## Foliage

Set `sg.FoliageQuality` to `0`. The default value is `1`.

```ini
[ScalabilityGroups]
sg.ReflectionQuality=1
sg.PostProcessQuality=1
sg.GlobalIlluminationQuality=1
sg.ResolutionQuality=71
sg.ViewDistanceQuality=3
sg.EffectsQuality=1
sg.TextureQuality=1
sg.FoliageQuality=0
sg.ShadowQuality=1
sg.AntiAliasingQuality=1
sg.ShadingQuality=1
```

## Decrease Flickering

Set `bUseVSync` to `True`. The default value is `False`.

```ini
[/Script/PaxDei.PaxDeiGameUserSettings]
bUseVSync=True
```
