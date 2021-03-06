# AwsElasticContainerService
```text
elements/aws/Compute/AwsElasticContainerService
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsElasticContainerService icon](../../../icons/aws/Compute/AwsElasticContainerService.png) | ![AwsElasticContainerService element](AwsElasticContainerService.element.png) | ![AwsElasticContainerService card](AwsElasticContainerService.card.png) |
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

' loads the AwsElasticContainerService element
include('elements/aws/Compute/AwsElasticContainerService')
AwsElasticContainerService('element', 'Elastic Container Service', 'an optional tech field')
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

' loads the AwsElasticContainerService element
include('elements/aws/Compute/AwsElasticContainerService')
AwsElasticContainerService('element', 'Elastic Container Service', 'an optional tech field')
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

' loads the AwsElasticContainerService card
include('elements/aws/Compute/AwsElasticContainerService')
AwsElasticContainerServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsElasticContainerService card
include('elements/aws/Compute/AwsElasticContainerService')
AwsElasticContainerServiceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
