# QMetaObject

Qt元对象系统负责Qt信号槽通信机制、rtti（runtime type information）、Qt值系统。每个QObject子类在QApplication中使用的都会创建一个QMetaObject实例，这个实例存储了所有类的元信息，用QObject::metaObject()使用

