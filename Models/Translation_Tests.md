
###Translation Tests

* In the table below, entity is exported from one column and imported into the next column.
* List below ordered in perceived priority to be addressed.  Please modify and reorder as you see fit. 

<u>Legend</u>
* SYF: [System Family](http://docs.autodesk.com/REVIT/2010/ENU/Revit%20Architecture%202010%20Users%20Guide/RAC/index.html?url=WS1a9193826455f5ff6abe274011cffbaa2b2-5c7b.htm,topicNumber=d0e32102)
* LOF: [Loadable Family](http://docs.autodesk.com/REVIT/2010/ENU/Revit%20Architecture%202010%20Users%20Guide/RAC/index.html?url=WS1a9193826455f5ff6abe274011cffbaa2b2-5c7b.htm,topicNumber=d0e32102)
* IPF: [In-Place Family](http://docs.autodesk.com/REVIT/2010/ENU/Revit%20Architecture%202010%20Users%20Guide/RAC/index.html?url=WS1a9193826455f5ff6abe274011cffbaa2b2-5c7b.htm,topicNumber=d0e32102)
* NT: No translation



|Revit-->|FreeCAD-->|Revit-->|Revit|Notes
| --- | --- | --- | --- | --- | --- |
|Wall (SYF)|-?-|Import Symbol|-|If simple wall, editable in Revit.  If has voids, uneditable.
|-|-|Wall (SYF)|Wall (SYF)|-|
|Door (LOF)|-?-|Import Symbol|-|Uneditable in Revit|
|-|-|Door (LOF)|Door (LOF)|Retains one-to-many relationship, that is, family definition to instances is retained|
|Window (LOF)|-?-|Import Symbol|-|Uneditable in Revit|
|-|-|Window (LOF)|Window (LOF)|Retains one-to-many relationship, that is, family definition to instances is retained|
|Floor|-|IPF|-|Is Editable|
|-|-|Floor|Floor|-|
|Roof|-?-|Import Symbol|-|Uneditable in Revit|
|-|-|Roof|IPF|Is editable|
|Ceiling (SYF)|-|Import Symbol|-|Uneditable in Revit|
|-|-|Ceiling (SYF)|Import Symbol|Uneditable in Revit|
|Model Lines|NT|-|-|-|
|-|-|Model Lines|Model Lines|-|
|Topography|NT|-|-|-|
|-|-|Topography|Topography|-|
|-|-|-|-|-|
|-|-|-|-|-|
|-|-|-|-|-|
|-|-|-|-|-|
|-|-|-|-|-|

