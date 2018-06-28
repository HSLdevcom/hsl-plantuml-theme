# hsl-plantuml-theme

An unofficial PlantUML theme for HSL.
The fonts are not official but perhaps close enough.
No designer has been near this.

## Usage

Install the freely licensed fonts Nunito Bold ([releases](https://github.com/google/fonts/tree/master/ofl/nunito), [development](https://github.com/googlefonts/nunito/)) and [Source Code Pro](https://github.com/adobe-fonts/source-code-pro).

Use the theme from your diagram:
```
@startuml

!includeurl https://rawgit.com/HSLdevcom/hsl-plantuml-theme/master/hsl-theme.iuml

title My beautiful diagram
database "Generic DB" as db
rectangle "Generic backend" as backend
backend --> db : slurp

@enduml
```
