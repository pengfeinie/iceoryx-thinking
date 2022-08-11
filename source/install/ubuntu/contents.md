# installation

## 1. installation

All iceoryx libraries are deployed as independent CMake packages. Posh is using functions from hoofs and is depending on it. You are able to build posh and hoofs and integrate them into existing CMake projects.

### 1.1 Linux

Although we strive to be fully POSIX-compliant, we recommend using Ubuntu 18.04 and at least GCC 7.5.0 for development.

You will need to install the following packages:

```
sudo apt install gcc g++ cmake libacl1-dev libncurses5-dev pkg-config
```

1. **Clone the repository**

   ```
   git clone https://github.com/eclipse-iceoryx/iceoryx.git
   ```

2. **Generate the necessary build files**

   ```
   cd iceoryx
   cmake -Bbuild -Hiceoryx_meta
   ```

3. **Compile the source code**

   ```
   cmake --build build
   ```

4. **Install to system**

   ```
   sudo cmake --build build --target install
   ```


