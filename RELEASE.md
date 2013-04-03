# How to release to Clojars.org

After running the build you can push the build artifact (jar file) to the Clojars.org repo:

    $ scp pom.xml core/target/scala-2.9.2/kafka_2.9.2-0.8-SNAPSHOT.jar clojars@clojars.org:
