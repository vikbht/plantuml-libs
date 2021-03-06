# MaterialsMyLocation
```text
elements/materials/Maps/MaterialsMyLocation
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsMyLocation icon](../../../icons/materials/Maps/MaterialsMyLocation.png) | ![MaterialsMyLocation element](MaterialsMyLocation.element.png) | ![MaterialsMyLocation card](MaterialsMyLocation.card.png) |
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

' loads the MaterialsMyLocation element
include('elements/materials/Maps/MaterialsMyLocation')
MaterialsMyLocation('element', 'My Location', 'an optional tech field')
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

' loads the MaterialsMyLocation element
include('elements/materials/Maps/MaterialsMyLocation')
MaterialsMyLocation('element', 'My Location', 'an optional tech field')
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

' loads the MaterialsMyLocation card
include('elements/materials/Maps/MaterialsMyLocation')
MaterialsMyLocationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsMyLocation card
include('elements/materials/Maps/MaterialsMyLocation')
MaterialsMyLocationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
