# icehello

## 1. Introduction

This example demonstrates a basic data transmission with zero-copy inter-process communication (IPC). It provides a publisher and a subscriber application.

## 2. Publisher

At first, we need to define what kind of data type the publisher and subscriber application will exchange:

## 3. Subscriber

The subscriber needs to have similar includes, but unlike the publisher `subscriber.hpp` is included:

## 4. Compile

```
mkdir bin
cd bin
cmake ..
make
```

![](https://iceoryx-thinking.readthedocs.io/en/latest/_images/2022-07-07_133736.png)

## 5. Expected Output

### 5.1. Start RouDi Firstly

[![asciicast](https://iceoryx-thinking.readthedocs.io/en/latest/_images/2022-07-10_131154.png)](https://iceoryx-thinking.readthedocs.io/en/latest/_static/icehello01.mp4)

### 5.2. Start RouDi Lastly

[![asciicast](https://iceoryx-thinking.readthedocs.io/en/latest/_images/2022-07-10_131525.png)](https://iceoryx-thinking.readthedocs.io/en/latest/_static/icehello02.mp4)



### 6. Shared Access to File Locks

When running the example in a linux environment one can observe the lock files `/tmp/roudi.lock`, `iox-cpp-publisher-helloworld.lock` and `iox-cpp-subscriber-helloworld.lock`

![](D:\sourcecode\myself\iceoryx-thinking\source\quick_start\icehello\images\2022-07-10_133815.png)



## 7. Reference

1. [https://github.com/eclipse-iceoryx/iceoryx/tree/v2.0.0/iceoryx_examples/icehello](https://github.com/eclipse-iceoryx/iceoryx/tree/v2.0.0/iceoryx_examples/icehello)
2. [https://iceoryx.io/v2.0.0/examples/icehello/](https://iceoryx.io/v2.0.0/examples/icehello/)
