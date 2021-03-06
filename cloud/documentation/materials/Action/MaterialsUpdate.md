# MaterialsUpdate
```text
elements/materials/Action/MaterialsUpdate
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsUpdate icon](../../../icons/materials/Action/MaterialsUpdate.png) | ![MaterialsUpdate element](MaterialsUpdate.element.png) | ![MaterialsUpdate card](MaterialsUpdate.card.png) |
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

' loads the MaterialsUpdate element
include('elements/materials/Action/MaterialsUpdate')
MaterialsUpdate('element', 'Update', 'an optional tech field')
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

' loads the MaterialsUpdate element
include('elements/materials/Action/MaterialsUpdate')
MaterialsUpdate('element', 'Update', 'an optional tech field')
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

' loads the MaterialsUpdate card
include('elements/materials/Action/MaterialsUpdate')
MaterialsUpdateCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsUpdate card
include('elements/materials/Action/MaterialsUpdate')
MaterialsUpdateCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
