# MaterialsInsertInvitation
```text
elements/materials/Editor/MaterialsInsertInvitation
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsInsertInvitation icon](../../../icons/materials/Editor/MaterialsInsertInvitation.png) | ![MaterialsInsertInvitation element](MaterialsInsertInvitation.element.png) | ![MaterialsInsertInvitation card](MaterialsInsertInvitation.card.png) |
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

' loads the MaterialsInsertInvitation element
include('elements/materials/Editor/MaterialsInsertInvitation')
MaterialsInsertInvitation('element', 'Insert Invitation', 'an optional tech field')
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

' loads the MaterialsInsertInvitation element
include('elements/materials/Editor/MaterialsInsertInvitation')
MaterialsInsertInvitation('element', 'Insert Invitation', 'an optional tech field')
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

' loads the MaterialsInsertInvitation card
include('elements/materials/Editor/MaterialsInsertInvitation')
MaterialsInsertInvitationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsInsertInvitation card
include('elements/materials/Editor/MaterialsInsertInvitation')
MaterialsInsertInvitationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
