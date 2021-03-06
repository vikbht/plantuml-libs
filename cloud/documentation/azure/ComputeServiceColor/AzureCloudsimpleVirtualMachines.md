# AzureCloudsimpleVirtualMachines
```text
elements/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureCloudsimpleVirtualMachines icon](../../../icons/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines.png) | ![AzureCloudsimpleVirtualMachines element](AzureCloudsimpleVirtualMachines.element.png) | ![AzureCloudsimpleVirtualMachines card](AzureCloudsimpleVirtualMachines.card.png) |
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
include('styles/azure')

' loads the AzureCloudsimpleVirtualMachines element
include('elements/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines')
AzureCloudsimpleVirtualMachines('element', 'Cloudsimple Virtual Machines', 'an optional tech field')
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
include('styles/azure')

' loads the AzureCloudsimpleVirtualMachines element
include('elements/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines')
AzureCloudsimpleVirtualMachines('element', 'Cloudsimple Virtual Machines', 'an optional tech field')
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
include('styles/azure')

' loads the AzureCloudsimpleVirtualMachines card
include('elements/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines')
AzureCloudsimpleVirtualMachinesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/azure')

' loads the AzureCloudsimpleVirtualMachines card
include('elements/azure/ComputeServiceColor/AzureCloudsimpleVirtualMachines')
AzureCloudsimpleVirtualMachinesCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
