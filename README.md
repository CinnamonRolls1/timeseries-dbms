# TSDS

### Documentation (Due on 8th)
#### Reference issue #2
Fill details of your approach below:

- ### Safeer
  The storage will be done on a local database using Room Persistence Library on JAVA Android SDK. Room is an abstraction layer over SQLite which gives all functionality of SQLite in a simplistic manner. The room uses a abstract class annotated with @Database for defining the database. The @Entity annotated class defines a table in the database.@DAO annotated interface has all the methods to perform actions on the database. Once these class files are are compiled we use a ```Room.databaseBuilder()``` to get an instance of the database at runtime. Rest of the details are availabe in the [Documentation](https://developer.android.com/training/data-storage/room). The local storage can be synced to a server database however that will be discussed later once the local database implementation is completed.
- ### Kishan
[text here]
- ### Praveen
The system calls required for the application are available on the android library(Sensor Manager) on JAVA Android SDK.
The [Docs](https://developer.android.com/guide/topics/sensors/sensors_overview) has list of all the Sensors and their documentation with examples on how to use it in both JAVA and Kotlin.
``` java
import android.hardware.Sensor;
import android.hardware.SensorEvent;
import android.hardware.SensorEventListener;
import android.hardware.SensorManager;
```

- ### Chin
[text here]
