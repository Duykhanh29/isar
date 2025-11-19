packages/isar/README.md




* IMPORTANT NOTE
- These changes just apply for Android Gradle Plugin (AGP) 8.x
We change 
```
if (project.android.hasProperty("namespace")) { 
        namespace 'dev.isar.isar_flutter_libs'    
    }
```

to this
```
namespace 'dev.isar.isar_flutter_libs'
```
