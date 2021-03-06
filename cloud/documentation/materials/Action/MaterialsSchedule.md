# MaterialsSchedule
```text
elements/materials/Action/MaterialsSchedule
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsSchedule icon](../../../icons/materials/Action/MaterialsSchedule.png) | ![MaterialsSchedule element](MaterialsSchedule.element.png) | ![MaterialsSchedule card](MaterialsSchedule.card.png) |
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

' loads the MaterialsSchedule element
include('elements/materials/Action/MaterialsSchedule')
MaterialsSchedule('element', 'Schedule', 'an optional tech field')
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

' loads the MaterialsSchedule element
include('elements/materials/Action/MaterialsSchedule')
MaterialsSchedule('element', 'Schedule', 'an optional tech field')
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

' loads the MaterialsSchedule card
include('elements/materials/Action/MaterialsSchedule')
MaterialsScheduleCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsSchedule card
include('elements/materials/Action/MaterialsSchedule')
MaterialsScheduleCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
