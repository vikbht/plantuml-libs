# MaterialsFiberNew
```text
elements/materials/Av/MaterialsFiberNew
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsFiberNew icon](../../../icons/materials/Av/MaterialsFiberNew.png) | ![MaterialsFiberNew element](MaterialsFiberNew.element.png) | ![MaterialsFiberNew card](MaterialsFiberNew.card.png) |
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

' loads the MaterialsFiberNew element
include('elements/materials/Av/MaterialsFiberNew')
MaterialsFiberNew('element', 'Fiber New', 'an optional tech field')
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

' loads the MaterialsFiberNew element
include('elements/materials/Av/MaterialsFiberNew')
MaterialsFiberNew('element', 'Fiber New', 'an optional tech field')
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

' loads the MaterialsFiberNew card
include('elements/materials/Av/MaterialsFiberNew')
MaterialsFiberNewCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsFiberNew card
include('elements/materials/Av/MaterialsFiberNew')
MaterialsFiberNewCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
