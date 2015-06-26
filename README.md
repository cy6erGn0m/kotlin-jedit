kotlin-jedit
============

[Kotlin](http://kotlinlang.org) syntax highlight and other related stuff for [jEdit](http://jedit.org). 
Not best for Kotlin programming but useful for quick editing

To enable syntax highlight put it to modes directory and add to catalog file the following lines:

```xml
<MODE NAME="kotlin" FILE="kotlin.xml"
     FILE_NAME_GLOB="*.{kt,ks,kts,jetl}"/>
```

If jEdit will not apply on the fly use jedit menu Utilities -> Troubleshooting -> Reload Edit Modes


