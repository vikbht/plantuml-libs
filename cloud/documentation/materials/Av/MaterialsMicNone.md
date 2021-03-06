# MaterialsMicNone
```text
elements/materials/Av/MaterialsMicNone
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsMicNone icon](../../../icons/materials/Av/MaterialsMicNone.png) | ![MaterialsMicNone element](MaterialsMicNone.element.png) | ![MaterialsMicNone card](MaterialsMicNone.card.png) |
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

' loads the MaterialsMicNone element
include('elements/materials/Av/MaterialsMicNone')
MaterialsMicNone('element', 'Mic None', 'an optional tech field')
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

' loads the MaterialsMicNone element
include('elements/materials/Av/MaterialsMicNone')
MaterialsMicNone('element', 'Mic None', 'an optional tech field')
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

' loads the MaterialsMicNone card
include('elements/materials/Av/MaterialsMicNone')
MaterialsMicNoneCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsMicNone card
include('elements/materials/Av/MaterialsMicNone')
MaterialsMicNoneCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
