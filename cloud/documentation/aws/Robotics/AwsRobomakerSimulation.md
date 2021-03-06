# AwsRobomakerSimulation
```text
elements/aws/Robotics/AwsRobomakerSimulation
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsRobomakerSimulation icon](../../../icons/aws/Robotics/AwsRobomakerSimulation.png) | ![AwsRobomakerSimulation element](AwsRobomakerSimulation.element.png) | ![AwsRobomakerSimulation card](AwsRobomakerSimulation.card.png) |
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
include('styles/aws')

' loads the AwsRobomakerSimulation element
include('elements/aws/Robotics/AwsRobomakerSimulation')
AwsRobomakerSimulation('element', 'Robomaker Simulation', 'an optional tech field')
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
include('styles/aws')

' loads the AwsRobomakerSimulation element
include('elements/aws/Robotics/AwsRobomakerSimulation')
AwsRobomakerSimulation('element', 'Robomaker Simulation', 'an optional tech field')
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
include('styles/aws')

' loads the AwsRobomakerSimulation card
include('elements/aws/Robotics/AwsRobomakerSimulation')
AwsRobomakerSimulationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsRobomakerSimulation card
include('elements/aws/Robotics/AwsRobomakerSimulation')
AwsRobomakerSimulationCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
