1. Install Clojure CLI Tools
2. Download GraalVM and set to path, for example

   `export PATH="$HOME/Documents/graalvm-ce-19.0.0/Contents/Home/bin:$PATH"`
3. Set GRAALVM_HOME

   `export GRAALVM_HOME="$HOME/Documents/graalvm-ce-19.0.0/Contents/Home"`
   
4. Install `native-image` using `gu`

   `gu install native-image`

5. Compile project by executing

   `clojure -A:native-image` or `clj -A:native-image`
   
6. Run
   
   `./core`