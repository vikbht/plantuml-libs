# MaterialsAirlineSeatLegroomExtra
```text
elements/materials/Notification/MaterialsAirlineSeatLegroomExtra
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsAirlineSeatLegroomExtra icon](../../../icons/materials/Notification/MaterialsAirlineSeatLegroomExtra.png) | ![MaterialsAirlineSeatLegroomExtra element](MaterialsAirlineSeatLegroomExtra.element.png) | ![MaterialsAirlineSeatLegroomExtra card](MaterialsAirlineSeatLegroomExtra.card.png) |
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

' loads the MaterialsAirlineSeatLegroomExtra element
include('elements/materials/Notification/MaterialsAirlineSeatLegroomExtra')
MaterialsAirlineSeatLegroomExtra('element', 'Airline Seat Legroom Extra', 'an optional tech field')
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

' loads the MaterialsAirlineSeatLegroomExtra element
include('elements/materials/Notification/MaterialsAirlineSeatLegroomExtra')
MaterialsAirlineSeatLegroomExtra('element', 'Airline Seat Legroom Extra', 'an optional tech field')
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

' loads the MaterialsAirlineSeatLegroomExtra card
include('elements/materials/Notification/MaterialsAirlineSeatLegroomExtra')
MaterialsAirlineSeatLegroomExtraCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsAirlineSeatLegroomExtra card
include('elements/materials/Notification/MaterialsAirlineSeatLegroomExtra')
MaterialsAirlineSeatLegroomExtraCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
