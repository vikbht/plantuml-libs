# MaterialsInvertColors
```text
elements/materials/Action/MaterialsInvertColors
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsInvertColors icon](../../../icons/materials/Action/MaterialsInvertColors.png) | ![MaterialsInvertColors element](MaterialsInvertColors.element.png) | ![MaterialsInvertColors card](MaterialsInvertColors.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsInvertColors element
include('elements/materials/Action/MaterialsInvertColors')
MaterialsInvertColors('element', 'Invert Colors', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsInvertColors element
include('elements/materials/Action/MaterialsInvertColors')
MaterialsInvertColors('element', 'Invert Colors', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsInvertColors card
include('elements/materials/Action/MaterialsInvertColors')
MaterialsInvertColorsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsInvertColors card
include('elements/materials/Action/MaterialsInvertColors')
MaterialsInvertColorsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
