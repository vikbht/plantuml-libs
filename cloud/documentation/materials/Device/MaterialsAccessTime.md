# MaterialsAccessTime
```text
elements/materials/Device/MaterialsAccessTime
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsAccessTime icon](../../../icons/materials/Device/MaterialsAccessTime.png) | ![MaterialsAccessTime element](MaterialsAccessTime.element.png) | ![MaterialsAccessTime card](MaterialsAccessTime.card.png) |
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

' loads the MaterialsAccessTime element
include('elements/materials/Device/MaterialsAccessTime')
MaterialsAccessTime('element', 'Access Time', 'an optional tech field')
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

' loads the MaterialsAccessTime element
include('elements/materials/Device/MaterialsAccessTime')
MaterialsAccessTime('element', 'Access Time', 'an optional tech field')
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

' loads the MaterialsAccessTime card
include('elements/materials/Device/MaterialsAccessTime')
MaterialsAccessTimeCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsAccessTime card
include('elements/materials/Device/MaterialsAccessTime')
MaterialsAccessTimeCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
