# MaterialsPhotoAlbum
```text
elements/materials/Image/MaterialsPhotoAlbum
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsPhotoAlbum icon](../../../icons/materials/Image/MaterialsPhotoAlbum.png) | ![MaterialsPhotoAlbum element](MaterialsPhotoAlbum.element.png) | ![MaterialsPhotoAlbum card](MaterialsPhotoAlbum.card.png) |
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

' loads the MaterialsPhotoAlbum element
include('elements/materials/Image/MaterialsPhotoAlbum')
MaterialsPhotoAlbum('element', 'Photo Album', 'an optional tech field')
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

' loads the MaterialsPhotoAlbum element
include('elements/materials/Image/MaterialsPhotoAlbum')
MaterialsPhotoAlbum('element', 'Photo Album', 'an optional tech field')
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

' loads the MaterialsPhotoAlbum card
include('elements/materials/Image/MaterialsPhotoAlbum')
MaterialsPhotoAlbumCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the MaterialsPhotoAlbum card
include('elements/materials/Image/MaterialsPhotoAlbum')
MaterialsPhotoAlbumCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
