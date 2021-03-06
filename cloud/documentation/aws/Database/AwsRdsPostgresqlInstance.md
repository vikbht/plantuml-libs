# AwsRdsPostgresqlInstance
```text
elements/aws/Database/AwsRdsPostgresqlInstance
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsRdsPostgresqlInstance icon](../../../icons/aws/Database/AwsRdsPostgresqlInstance.png) | ![AwsRdsPostgresqlInstance element](AwsRdsPostgresqlInstance.element.png) | ![AwsRdsPostgresqlInstance card](AwsRdsPostgresqlInstance.card.png) |
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

' loads the AwsRdsPostgresqlInstance element
include('elements/aws/Database/AwsRdsPostgresqlInstance')
AwsRdsPostgresqlInstance('element', 'Rds Postgresql Instance', 'an optional tech field')
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

' loads the AwsRdsPostgresqlInstance element
include('elements/aws/Database/AwsRdsPostgresqlInstance')
AwsRdsPostgresqlInstance('element', 'Rds Postgresql Instance', 'an optional tech field')
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

' loads the AwsRdsPostgresqlInstance card
include('elements/aws/Database/AwsRdsPostgresqlInstance')
AwsRdsPostgresqlInstanceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsRdsPostgresqlInstance card
include('elements/aws/Database/AwsRdsPostgresqlInstance')
AwsRdsPostgresqlInstanceCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
