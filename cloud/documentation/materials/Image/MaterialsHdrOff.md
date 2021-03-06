# MaterialsHdrOff
```text
elements/materials/Image/MaterialsHdrOff
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsHdrOff icon](../../../icons/materials/Image/MaterialsHdrOff.png) | ![MaterialsHdrOff element](MaterialsHdrOff.element.png) | ![MaterialsHdrOff card](MaterialsHdrOff.card.png) |
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

' loads the MaterialsHdrOff element
include('elements/materials/Image/MaterialsHdrOff')
MaterialsHdrOff('element', 'Hdr Off', 'an optional tech field')
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

' loads the MaterialsHdrOff element
include('elements/materials/Image/MaterialsHdrOff')
MaterialsHdrOff('element', 'Hdr Off', 'an optional tech field')
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

' loads the MaterialsHdrOff card
include('elements/materials/Image/MaterialsHdrOff')
MaterialsHdrOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsHdrOff card
include('elements/materials/Image/MaterialsHdrOff')
MaterialsHdrOffCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
