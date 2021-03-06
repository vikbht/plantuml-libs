# MaterialsNotificationsOff
```text
elements/materials/Social/MaterialsNotificationsOff
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsNotificationsOff icon](../../../icons/materials/Social/MaterialsNotificationsOff.png) | ![MaterialsNotificationsOff element](MaterialsNotificationsOff.element.png) | ![MaterialsNotificationsOff card](MaterialsNotificationsOff.card.png) |
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

' loads the MaterialsNotificationsOff element
include('elements/materials/Social/MaterialsNotificationsOff')
MaterialsNotificationsOff('element', 'Notifications Off', 'an optional tech field')
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

' loads the MaterialsNotificationsOff element
include('elements/materials/Social/MaterialsNotificationsOff')
MaterialsNotificationsOff('element', 'Notifications Off', 'an optional tech field')
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

' loads the MaterialsNotificationsOff card
include('elements/materials/Social/MaterialsNotificationsOff')
MaterialsNotificationsOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsNotificationsOff card
include('elements/materials/Social/MaterialsNotificationsOff')
MaterialsNotificationsOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
