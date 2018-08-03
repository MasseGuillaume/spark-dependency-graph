# Graph

https://masseguillaume.github.io/spark-dependency-graph/graph.html

Generated with: `sbt dependencyBrowseGraph` + manual fix, see (https://github.com/jrudolph/sbt-dependency-graph/pull/158)

# Tree

```
default:spark-graph_2.11:0.1.0-SNAPSHOT [S]
  +-org.apache.spark:spark-core_2.11:2.3.0 [S]
    +-com.clearspring.analytics:stream:2.7.0
    +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    |
    +-com.fasterxml.jackson.module:jackson-module-scala_2.11:2.6.7.1 [S]
    | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7 (evicted by: 2.6.7.1)
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | |
    | +-com.fasterxml.jackson.module:jackson-module-paranamer:2.7.9
    | | +-com.thoughtworks.paranamer:paranamer:2.8
    | |
    | +-org.scala-lang:scala-reflect:2.11.12 [S]
    |
    +-com.github.luben:zstd-jni:1.3.2-2
    +-com.google.code.findbugs:jsr305:1.3.9
    +-com.ning:compress-lzf:1.0.3
    +-com.twitter:chill-java:0.8.4
    | +-com.esotericsoftware:kryo-shaded:3.0.3
    |   +-com.esotericsoftware:minlog:1.3.0
    |   +-org.objenesis:objenesis:2.1
    |
    +-com.twitter:chill_2.11:0.8.4 [S]
    | +-com.esotericsoftware:kryo-shaded:3.0.3
    | | +-com.esotericsoftware:minlog:1.3.0
    | | +-org.objenesis:objenesis:2.1
    | |
    | +-com.twitter:chill-java:0.8.4
    |   +-com.esotericsoftware:kryo-shaded:3.0.3
    |     +-com.esotericsoftware:minlog:1.3.0
    |     +-org.objenesis:objenesis:2.1
    |
    +-commons-net:commons-net:2.2
    +-io.dropwizard.metrics:metrics-core:3.1.5
    | +-org.slf4j:slf4j-api:1.7.16
    | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    |
    +-io.dropwizard.metrics:metrics-graphite:3.1.5
    | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | |
    | +-org.slf4j:slf4j-api:1.7.16
    | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    |
    +-io.dropwizard.metrics:metrics-json:3.1.5
    | +-com.fasterxml.jackson.core:jackson-databind:2.4.2 (evicted by: 2.6.7.1)
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | |
    | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | |
    | +-org.slf4j:slf4j-api:1.7.16
    | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    |
    +-io.dropwizard.metrics:metrics-jvm:3.1.5
    | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | |
    | +-org.slf4j:slf4j-api:1.7.16
    | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    |
    +-io.netty:netty-all:4.1.17.Final
    +-io.netty:netty:3.9.9.Final
    +-javax.servlet:javax.servlet-api:3.1.0
    +-log4j:log4j:1.2.17
    +-net.java.dev.jets3t:jets3t:0.9.4
    | +-com.jamesmurty.utils:java-xmlbuilder:1.1
    | | +-net.iharder:base64:2.3.8
    | |
    | +-commons-codec:commons-codec:1.11
    | +-javax.activation:activation:1.1.1
    | +-org.apache.httpcomponents:httpclient:4.5
    | | +-commons-codec:commons-codec:1.11
    | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | +-commons-codec:commons-codec:1.9 (evicted by: 1.11)
    | | +-org.apache.httpcomponents:httpcore:4.4.1
    | |
    | +-org.apache.httpcomponents:httpcore:4.4.1
    | +-org.bouncycastle:bcprov-jdk15on:1.52
    | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    |   +-org.codehaus.jackson:jackson-core-asl:1.9.13
    |
    +-net.razorvine:pyrolite:4.13
    +-net.sf.py4j:py4j:0.10.6
    +-org.apache.avro:avro-mapred:1.7.7
    | +-org.apache.avro:avro-ipc:1.7.7
    | | +-org.apache.avro:avro:1.7.7
    | | | +-com.thoughtworks.paranamer:paranamer:2.3 (evicted by: 2.8)
    | | | +-com.thoughtworks.paranamer:paranamer:2.6 (evicted by: 2.8)
    | | | +-com.thoughtworks.paranamer:paranamer:2.8
    | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | +-org.tukaani:xz:1.0
    | | | |
    | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |
    | | | +-org.slf4j:slf4j-api:1.6.4 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.xerial.snappy:snappy-java:1.0.5 (evicted by: 1.1.2.6)
    | | | +-org.xerial.snappy:snappy-java:1.1.2.6
    | | |
    | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | |
    | | +-org.slf4j:slf4j-api:1.6.4 (evicted by: 1.7.16)
    | | +-org.slf4j:slf4j-api:1.7.16
    | |
    | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | |
    | +-org.slf4j:slf4j-api:1.6.4 (evicted by: 1.7.16)
    | +-org.slf4j:slf4j-api:1.7.16
    |
    +-org.apache.avro:avro:1.7.7
    | +-com.thoughtworks.paranamer:paranamer:2.3 (evicted by: 2.8)
    | +-com.thoughtworks.paranamer:paranamer:2.6 (evicted by: 2.8)
    | +-com.thoughtworks.paranamer:paranamer:2.8
    | +-org.apache.commons:commons-compress:1.4.1
    | | +-org.tukaani:xz:1.0
    | |
    | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | |
    | +-org.slf4j:slf4j-api:1.6.4 (evicted by: 1.7.16)
    | +-org.slf4j:slf4j-api:1.7.16
    | +-org.xerial.snappy:snappy-java:1.0.5 (evicted by: 1.1.2.6)
    | +-org.xerial.snappy:snappy-java:1.1.2.6
    |
    +-org.apache.commons:commons-crypto:1.0.0
    +-org.apache.commons:commons-lang3:3.5
    +-org.apache.commons:commons-math3:3.4.1
    +-org.apache.curator:curator-recipes:2.6.0
    | +-com.google.guava:guava:11.0.2
    | | +-com.google.code.findbugs:jsr305:1.3.9
    | |
    | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | +-org.apache.curator:curator-framework:2.6.0
    | | +-com.google.guava:guava:11.0.2
    | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | |
    | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | +-org.apache.curator:curator-client:2.6.0
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | | +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | | +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | | +-io.netty:netty:3.9.9.Final
    | | | | +-jline:jline:0.9.94
    | | | | +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | |
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | |
    | | +-org.apache.zookeeper:zookeeper:3.4.6
    | |   +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | |   +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | |   +-io.netty:netty:3.9.9.Final
    | |   +-jline:jline:0.9.94
    | |   +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | |   +-log4j:log4j:1.2.17
    | |   +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | |   +-org.slf4j:slf4j-api:1.7.16
    | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | |   +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | |
    | +-org.apache.zookeeper:zookeeper:3.4.6
    |   +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    |   +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    |   +-io.netty:netty:3.9.9.Final
    |   +-jline:jline:0.9.94
    |   +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    |   +-log4j:log4j:1.2.17
    |   +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    |   +-org.slf4j:slf4j-api:1.7.16
    |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    |   +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    |
    +-org.apache.hadoop:hadoop-client:2.6.5
    | +-org.apache.hadoop:hadoop-annotations:2.6.5
    | +-org.apache.hadoop:hadoop-common:2.6.5
    | | +-com.google.code.findbugs:jsr305:1.3.9
    | | +-com.google.code.gson:gson:2.2.4
    | | +-com.google.guava:guava:11.0.2
    | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | |
    | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | +-com.google.protobuf:protobuf-java:2.5.0
    | | +-commons-cli:commons-cli:1.2
    | | +-commons-codec:commons-codec:1.11
    | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | +-commons-collections:commons-collections:3.2.2
    | | +-commons-configuration:commons-configuration:1.6
    | | | +-commons-beanutils:commons-beanutils-core:1.8.0
    | | | +-commons-collections:commons-collections:3.2.1 (evicted by: 3.2.2)
    | | | +-commons-collections:commons-collections:3.2.2
    | | | +-commons-digester:commons-digester:1.8
    | | | | +-commons-beanutils:commons-beanutils:1.7.0
    | | | |
    | | | +-commons-lang:commons-lang:2.4 (evicted by: 2.6)
    | | | +-commons-lang:commons-lang:2.6
    | | |
    | | +-commons-httpclient:commons-httpclient:3.1
    | | | +-commons-codec:commons-codec:1.11
    | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | |
    | | +-commons-io:commons-io:2.4
    | | +-commons-lang:commons-lang:2.6
    | | +-commons-net:commons-net:2.2
    | | +-commons-net:commons-net:3.1 (evicted by: 2.2)
    | | +-log4j:log4j:1.2.17
    | | +-org.apache.avro:avro:1.7.4 (evicted by: 1.7.7)
    | | +-org.apache.avro:avro:1.7.7
    | | | +-com.thoughtworks.paranamer:paranamer:2.3 (evicted by: 2.8)
    | | | +-com.thoughtworks.paranamer:paranamer:2.6 (evicted by: 2.8)
    | | | +-com.thoughtworks.paranamer:paranamer:2.8
    | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | +-org.tukaani:xz:1.0
    | | | |
    | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | +-org.codehaus.jackson:jackson-mapper-asl:1.9.13
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |
    | | | +-org.slf4j:slf4j-api:1.6.4 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.xerial.snappy:snappy-java:1.0.5 (evicted by: 1.1.2.6)
    | | | +-org.xerial.snappy:snappy-java:1.1.2.6
    | | |
    | | +-org.apache.commons:commons-compress:1.4.1
    | | | +-org.tukaani:xz:1.0
    | | |
    | | +-org.apache.commons:commons-math3:3.1.1 (evicted by: 3.4.1)
    | | +-org.apache.commons:commons-math3:3.4.1
    | | +-org.apache.curator:curator-client:2.6.0
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | | +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | | +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | | +-io.netty:netty:3.9.9.Final
    | | | | +-jline:jline:0.9.94
    | | | | +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | |
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | |
    | | +-org.apache.curator:curator-recipes:2.6.0
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | +-org.apache.curator:curator-framework:2.6.0
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | | +-org.apache.curator:curator-client:2.6.0
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | | | | +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | | | | +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | | | | +-io.netty:netty:3.9.9.Final
    | | | | | | +-jline:jline:0.9.94
    | | | | | | +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | |   +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | |   +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | |   +-io.netty:netty:3.9.9.Final
    | | | |   +-jline:jline:0.9.94
    | | | |   +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | |   +-log4j:log4j:1.2.17
    | | | |   +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |   +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | |   +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | |   +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | |   +-io.netty:netty:3.9.9.Final
    | | |   +-jline:jline:0.9.94
    | | |   +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | |   +-log4j:log4j:1.2.17
    | | |   +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | |   +-org.slf4j:slf4j-api:1.7.16
    | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | |   +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | |
    | | +-org.apache.hadoop:hadoop-annotations:2.6.5
    | | +-org.apache.hadoop:hadoop-auth:2.6.5
    | | | +-commons-codec:commons-codec:1.11
    | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | +-log4j:log4j:1.2.17
    | | | +-org.apache.curator:curator-framework:2.6.0
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | | +-org.apache.curator:curator-client:2.6.0
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.guava:guava:16.0.1 (evicted by: 11.0.2)
    | | | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | | | | +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | | | | +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | | | | +-io.netty:netty:3.9.9.Final
    | | | | | | +-jline:jline:0.9.94
    | | | | | | +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.zookeeper:zookeeper:3.4.6
    | | | |   +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | | |   +-io.netty:netty:3.7.0.Final (evicted by: 3.9.9.Final)
    | | | |   +-io.netty:netty:3.9.9.Final
    | | | |   +-jline:jline:0.9.94
    | | | |   +-log4j:log4j:1.2.16 (evicted by: 1.2.17)
    | | | |   +-log4j:log4j:1.2.17
    | | | |   +-org.slf4j:slf4j-api:1.6.1 (evicted by: 1.7.16)
    | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |   +-org.slf4j:slf4j-api:1.7.6 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.directory.server:apacheds-kerberos-codec:2.0.0-M15
    | | | | +-org.apache.directory.api:api-asn1-api:1.0.0-M20
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.directory.api:api-util:1.0.0-M20
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.directory.server:apacheds-i18n:2.0.0-M15
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.httpcomponents:httpclient:4.2.5 (evicted by: 4.5)
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-codec:commons-codec:1.6 (evicted by: 1.11)
    | | | | +-org.apache.httpcomponents:httpcore:4.2.4 (evicted by: 4.4.1)
    | | | | +-org.apache.httpcomponents:httpcore:4.4.1
    | | | |
    | | | +-org.apache.httpcomponents:httpclient:4.5
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-codec:commons-codec:1.9 (evicted by: 1.11)
    | | | | +-org.apache.httpcomponents:httpcore:4.4.1
    | | | |
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | |
    | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | +-org.htrace:htrace-core:3.0.4
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.guava:guava:12.0.1 (evicted by: 11.0.2)
    | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | |
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | +-log4j:log4j:1.2.17
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | |
    | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | +-xmlenc:xmlenc:0.52
    | |
    | +-org.apache.hadoop:hadoop-hdfs:2.6.5
    | | +-com.google.guava:guava:11.0.2
    | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | |
    | | +-com.google.protobuf:protobuf-java:2.5.0
    | | +-commons-cli:commons-cli:1.2
    | | +-commons-codec:commons-codec:1.11
    | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | +-commons-io:commons-io:2.4
    | | +-commons-lang:commons-lang:2.6
    | | +-io.netty:netty:3.6.2.Final (evicted by: 3.9.9.Final)
    | | +-io.netty:netty:3.9.9.Final
    | | +-log4j:log4j:1.2.17
    | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | +-org.htrace:htrace-core:3.0.4
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.guava:guava:12.0.1 (evicted by: 11.0.2)
    | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | |
    | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | +-xerces:xercesImpl:2.9.1
    | | | +-xml-apis:xml-apis:1.3.04
    | | |
    | | +-xmlenc:xmlenc:0.52
    | |
    | +-org.apache.hadoop:hadoop-mapreduce-client-app:2.6.5
    | | +-com.google.protobuf:protobuf-java:2.5.0
    | | +-org.apache.hadoop:hadoop-mapreduce-client-common:2.6.5
    | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | +-org.apache.hadoop:hadoop-mapreduce-client-core:2.6.5
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | |
    | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-client:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-commons-cli:commons-cli:1.2
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | |   +-com.google.guava:guava:11.0.2
    | | | |   | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |   |
    | | | |   +-com.google.inject:guice:3.0
    | | | |   | +-aopalliance:aopalliance:1.0
    | | | |   | +-javax.inject:javax.inject:1
    | | | |   | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | |   |
    | | | |   +-com.google.protobuf:protobuf-java:2.5.0
    | | | |   +-commons-cli:commons-cli:1.2
    | | | |   +-commons-codec:commons-codec:1.11
    | | | |   +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | |   +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | |   +-commons-io:commons-io:2.4
    | | | |   +-commons-lang:commons-lang:2.6
    | | | |   +-javax.xml.bind:jaxb-api:2.2.2
    | | | |   | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | |   | +-javax.activation:activation:1.1.1
    | | | |   | +-javax.xml.stream:stax-api:1.0-2
    | | | |   |
    | | | |   +-log4j:log4j:1.2.17
    | | | |   +-org.apache.commons:commons-compress:1.4.1
    | | | |   | +-org.tukaani:xz:1.0
    | | | |   |
    | | | |   +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | |   | +-com.google.guava:guava:11.0.2
    | | | |   | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |   | |
    | | | |   | +-com.google.protobuf:protobuf-java:2.5.0
    | | | |   | +-commons-lang:commons-lang:2.6
    | | | |   |
    | | | |   +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   |
    | | | |   +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   |
    | | | |   +-org.mortbay.jetty:jetty-util:6.1.26
    | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.inject:guice:3.0
    | | | | | +-aopalliance:aopalliance:1.0
    | | | | | +-javax.inject:javax.inject:1
    | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-commons-cli:commons-cli:1.2
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-io:commons-io:2.4
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | +-javax.activation:activation:1.1.1
    | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | |
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | +-org.tukaani:xz:1.0
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |
    | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |
    | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | |
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | |
    | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.apache.hadoop:hadoop-mapreduce-client-shuffle:2.6.5
    | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | +-org.apache.hadoop:hadoop-mapreduce-client-common:2.6.5
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-mapreduce-client-core:2.6.5
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | |
    | | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-client:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | |   +-com.google.guava:guava:11.0.2
    | | | | |   | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |   |
    | | | | |   +-com.google.inject:guice:3.0
    | | | | |   | +-aopalliance:aopalliance:1.0
    | | | | |   | +-javax.inject:javax.inject:1
    | | | | |   | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |   |
    | | | | |   +-com.google.protobuf:protobuf-java:2.5.0
    | | | | |   +-commons-cli:commons-cli:1.2
    | | | | |   +-commons-codec:commons-codec:1.11
    | | | | |   +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | |   +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | |   +-commons-io:commons-io:2.4
    | | | | |   +-commons-lang:commons-lang:2.6
    | | | | |   +-javax.xml.bind:jaxb-api:2.2.2
    | | | | |   | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | |   | +-javax.activation:activation:1.1.1
    | | | | |   | +-javax.xml.stream:stax-api:1.0-2
    | | | | |   |
    | | | | |   +-log4j:log4j:1.2.17
    | | | | |   +-org.apache.commons:commons-compress:1.4.1
    | | | | |   | +-org.tukaani:xz:1.0
    | | | | |   |
    | | | | |   +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | |   | +-com.google.guava:guava:11.0.2
    | | | | |   | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |   | |
    | | | | |   | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | |   | +-commons-lang:commons-lang:2.6
    | | | | |   |
    | | | | |   +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   |
    | | | | |   +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   |
    | | | | |   +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | |
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | |
    | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-nodemanager:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.inject:guice:3.0
    | | | | | +-aopalliance:aopalliance:1.0
    | | | | | +-javax.inject:javax.inject:1
    | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | +-javax.activation:activation:1.1.1
    | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | |
    | | | | +-org.codehaus.jettison:jettison:1.1
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | |
    | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | +-log4j:log4j:1.2.17
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | |
    | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | |
    | +-org.apache.hadoop:hadoop-mapreduce-client-core:2.6.5
    | | +-com.google.protobuf:protobuf-java:2.5.0
    | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | +-com.google.guava:guava:11.0.2
    | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |
    | | | +-com.google.inject:guice:3.0
    | | | | +-aopalliance:aopalliance:1.0
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | |
    | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | +-commons-cli:commons-cli:1.2
    | | | +-commons-codec:commons-codec:1.11
    | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | +-commons-io:commons-io:2.4
    | | | +-commons-lang:commons-lang:2.6
    | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | +-javax.activation:activation:1.1.1
    | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | |
    | | | +-log4j:log4j:1.2.17
    | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | +-org.tukaani:xz:1.0
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-commons-lang:commons-lang:2.6
    | | | |
    | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |
    | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |
    | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | +-log4j:log4j:1.2.17
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | |
    | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | |
    | +-org.apache.hadoop:hadoop-mapreduce-client-jobclient:2.6.5
    | | +-com.google.protobuf:protobuf-java:2.5.0
    | | +-org.apache.hadoop:hadoop-mapreduce-client-common:2.6.5
    | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | +-org.apache.hadoop:hadoop-mapreduce-client-core:2.6.5
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | |
    | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-client:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-commons-cli:commons-cli:1.2
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | |   +-com.google.guava:guava:11.0.2
    | | | |   | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |   |
    | | | |   +-com.google.inject:guice:3.0
    | | | |   | +-aopalliance:aopalliance:1.0
    | | | |   | +-javax.inject:javax.inject:1
    | | | |   | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | |   |
    | | | |   +-com.google.protobuf:protobuf-java:2.5.0
    | | | |   +-commons-cli:commons-cli:1.2
    | | | |   +-commons-codec:commons-codec:1.11
    | | | |   +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | |   +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | |   +-commons-io:commons-io:2.4
    | | | |   +-commons-lang:commons-lang:2.6
    | | | |   +-javax.xml.bind:jaxb-api:2.2.2
    | | | |   | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | |   | +-javax.activation:activation:1.1.1
    | | | |   | +-javax.xml.stream:stax-api:1.0-2
    | | | |   |
    | | | |   +-log4j:log4j:1.2.17
    | | | |   +-org.apache.commons:commons-compress:1.4.1
    | | | |   | +-org.tukaani:xz:1.0
    | | | |   |
    | | | |   +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | |   | +-com.google.guava:guava:11.0.2
    | | | |   | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | |   | |
    | | | |   | +-com.google.protobuf:protobuf-java:2.5.0
    | | | |   | +-commons-lang:commons-lang:2.6
    | | | |   |
    | | | |   +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   |
    | | | |   +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | |   |
    | | | |   +-org.mortbay.jetty:jetty-util:6.1.26
    | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.inject:guice:3.0
    | | | | | +-aopalliance:aopalliance:1.0
    | | | | | +-javax.inject:javax.inject:1
    | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-commons-cli:commons-cli:1.2
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-io:commons-io:2.4
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | +-javax.activation:activation:1.1.1
    | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | |
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | +-org.tukaani:xz:1.0
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |
    | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |
    | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | |
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | |
    | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.apache.hadoop:hadoop-mapreduce-client-shuffle:2.6.5
    | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | +-org.apache.hadoop:hadoop-mapreduce-client-common:2.6.5
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-mapreduce-client-core:2.6.5
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | |
    | | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-client:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | |   +-com.google.guava:guava:11.0.2
    | | | | |   | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |   |
    | | | | |   +-com.google.inject:guice:3.0
    | | | | |   | +-aopalliance:aopalliance:1.0
    | | | | |   | +-javax.inject:javax.inject:1
    | | | | |   | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |   |
    | | | | |   +-com.google.protobuf:protobuf-java:2.5.0
    | | | | |   +-commons-cli:commons-cli:1.2
    | | | | |   +-commons-codec:commons-codec:1.11
    | | | | |   +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | |   +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | |   +-commons-io:commons-io:2.4
    | | | | |   +-commons-lang:commons-lang:2.6
    | | | | |   +-javax.xml.bind:jaxb-api:2.2.2
    | | | | |   | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | |   | +-javax.activation:activation:1.1.1
    | | | | |   | +-javax.xml.stream:stax-api:1.0-2
    | | | | |   |
    | | | | |   +-log4j:log4j:1.2.17
    | | | | |   +-org.apache.commons:commons-compress:1.4.1
    | | | | |   | +-org.tukaani:xz:1.0
    | | | | |   |
    | | | | |   +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | |   | +-com.google.guava:guava:11.0.2
    | | | | |   | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |   | |
    | | | | |   | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | |   | +-commons-lang:commons-lang:2.6
    | | | | |   |
    | | | | |   +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   |
    | | | | |   +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | |   | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | |   |
    | | | | |   +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | |   +-org.slf4j:slf4j-api:1.7.16
    | | | | |   +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | |
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | |
    | | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | |
    | | | +-org.apache.hadoop:hadoop-yarn-server-nodemanager:2.6.5
    | | | | +-com.google.guava:guava:11.0.2
    | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | |
    | | | | +-com.google.inject:guice:3.0
    | | | | | +-aopalliance:aopalliance:1.0
    | | | | | +-javax.inject:javax.inject:1
    | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | |
    | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | +-commons-codec:commons-codec:1.11
    | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | +-commons-lang:commons-lang:2.6
    | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | +-javax.activation:activation:1.1.1
    | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.inject:guice:3.0
    | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | +-javax.inject:javax.inject:1
    | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-commons-cli:commons-cli:1.2
    | | | | | +-commons-codec:commons-codec:1.11
    | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | +-commons-io:commons-io:2.4
    | | | | | +-commons-lang:commons-lang:2.6
    | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | |
    | | | | | +-log4j:log4j:1.2.17
    | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | +-org.tukaani:xz:1.0
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | |
    | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | |
    | | | | +-org.apache.hadoop:hadoop-yarn-server-common:2.6.5
    | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | |
    | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | |
    | | | | | +-org.apache.hadoop:hadoop-yarn-common:2.6.5
    | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | |
    | | | | | | +-com.google.inject:guice:3.0
    | | | | | | | +-aopalliance:aopalliance:1.0
    | | | | | | | +-javax.inject:javax.inject:1
    | | | | | | | +-org.sonatype.sisu.inject:cglib:2.2.1-v20090111
    | | | | | | |
    | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | +-commons-cli:commons-cli:1.2
    | | | | | | +-commons-codec:commons-codec:1.11
    | | | | | | +-commons-codec:commons-codec:1.2 (evicted by: 1.11)
    | | | | | | +-commons-codec:commons-codec:1.4 (evicted by: 1.11)
    | | | | | | +-commons-io:commons-io:2.4
    | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | +-javax.xml.bind:jaxb-api:2.2.2
    | | | | | | | +-javax.activation:activation:1.1 (evicted by: 1.1.1)
    | | | | | | | +-javax.activation:activation:1.1.1
    | | | | | | | +-javax.xml.stream:stax-api:1.0-2
    | | | | | | |
    | | | | | | +-log4j:log4j:1.2.17
    | | | | | | +-org.apache.commons:commons-compress:1.4.1
    | | | | | | | +-org.tukaani:xz:1.0
    | | | | | | |
    | | | | | | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    | | | | | | | +-com.google.guava:guava:11.0.2
    | | | | | | | | +-com.google.code.findbugs:jsr305:1.3.9
    | | | | | | | |
    | | | | | | | +-com.google.protobuf:protobuf-java:2.5.0
    | | | | | | | +-commons-lang:commons-lang:2.6
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | +-org.codehaus.jackson:jackson-jaxrs:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.codehaus.jackson:jackson-xc:1.9.13
    | | | | | | | +-org.codehaus.jackson:jackson-core-asl:1.9.13
    | | | | | | |
    | | | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | | | |
    | | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | |
    | | | | +-org.codehaus.jettison:jettison:1.1
    | | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | | +-org.mortbay.jetty:jetty-util:6.1.26
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | |
    | | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | | +-log4j:log4j:1.2.17
    | | | | +-org.slf4j:slf4j-api:1.7.16
    | | | |
    | | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | | |
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.5 (evicted by: 1.7.16)
    | | +-org.slf4j:slf4j-log4j12:1.7.16
    | | | +-log4j:log4j:1.2.17
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | |
    | | +-org.slf4j:slf4j-log4j12:1.7.5 (evicted by: 1.7.16)
    | |
    | +-org.apache.hadoop:hadoop-yarn-api:2.6.5
    |   +-com.google.guava:guava:11.0.2
    |   | +-com.google.code.findbugs:jsr305:1.3.9
    |   |
    |   +-com.google.protobuf:protobuf-java:2.5.0
    |   +-commons-lang:commons-lang:2.6
    |
    +-org.apache.ivy:ivy:2.4.0
    +-org.apache.spark:spark-kvstore_2.11:2.3.0
    | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | |
    | +-org.apache.spark:spark-tags_2.11:2.3.0 [S]
    | | +-org.spark-project.spark:unused:1.0.0
    | |
    | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.spark:spark-launcher_2.11:2.3.0
    | +-org.apache.spark:spark-tags_2.11:2.3.0 [S]
    | | +-org.spark-project.spark:unused:1.0.0
    | |
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.spark:spark-network-common_2.11:2.3.0
    | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | |
    | +-com.google.code.findbugs:jsr305:1.3.9
    | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | |
    | +-io.netty:netty-all:4.1.17.Final
    | +-org.apache.commons:commons-crypto:1.0.0
    | +-org.apache.commons:commons-lang3:3.5
    | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.spark:spark-network-shuffle_2.11:2.3.0
    | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | +-org.slf4j:slf4j-api:1.7.16
    | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | |
    | +-org.apache.spark:spark-network-common_2.11:2.3.0
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | | |
    | | +-com.google.code.findbugs:jsr305:1.3.9
    | | +-io.dropwizard.metrics:metrics-core:3.1.5
    | | | +-org.slf4j:slf4j-api:1.7.16
    | | | +-org.slf4j:slf4j-api:1.7.7 (evicted by: 1.7.16)
    | | |
    | | +-io.netty:netty-all:4.1.17.Final
    | | +-org.apache.commons:commons-crypto:1.0.0
    | | +-org.apache.commons:commons-lang3:3.5
    | | +-org.fusesource.leveldbjni:leveldbjni-all:1.8
    | | +-org.spark-project.spark:unused:1.0.0
    | |
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.spark:spark-tags_2.11:2.3.0 [S]
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.spark:spark-unsafe_2.11:2.3.0
    | +-com.google.code.findbugs:jsr305:1.3.9
    | +-com.twitter:chill_2.11:0.8.4 [S]
    | | +-com.esotericsoftware:kryo-shaded:3.0.3
    | | | +-com.esotericsoftware:minlog:1.3.0
    | | | +-org.objenesis:objenesis:2.1
    | | |
    | | +-com.twitter:chill-java:0.8.4
    | |   +-com.esotericsoftware:kryo-shaded:3.0.3
    | |     +-com.esotericsoftware:minlog:1.3.0
    | |     +-org.objenesis:objenesis:2.1
    | |
    | +-org.apache.spark:spark-tags_2.11:2.3.0 [S]
    | | +-org.spark-project.spark:unused:1.0.0
    | |
    | +-org.spark-project.spark:unused:1.0.0
    |
    +-org.apache.xbean:xbean-asm5-shaded:4.4
    +-org.glassfish.jersey.containers:jersey-container-servlet-core:2.22.2
    | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | | +-javax.annotation:javax.annotation-api:1.2
    | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | |   +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.javassist:javassist:3.18.1-GA
    | | |
    | | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |
    | +-org.glassfish.jersey.core:jersey-server:2.22.2
    |   +-javax.annotation:javax.annotation-api:1.2
    |   +-javax.validation:validation-api:1.1.0.Final
    |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | +-javax.inject:javax.inject:1
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   +-javax.inject:javax.inject:1
    |   |
    |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.javassist:javassist:3.18.1-GA
    |   |
    |   +-org.glassfish.jersey.core:jersey-client:2.22.2
    |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | |   +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.javassist:javassist:3.18.1-GA
    |   | |
    |   | +-org.glassfish.jersey.core:jersey-common:2.22.2
    |   |   +-javax.annotation:javax.annotation-api:1.2
    |   |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   |   | +-javax.inject:javax.inject:1
    |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   |   +-javax.inject:javax.inject:1
    |   |   |
    |   |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   |   | | +-javax.inject:javax.inject:1
    |   |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   | |   +-javax.inject:javax.inject:1
    |   |   | |
    |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   | | +-javax.inject:javax.inject:1
    |   |   | |
    |   |   | +-org.javassist:javassist:3.18.1-GA
    |   |   |
    |   |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   |   +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |   |
    |   +-org.glassfish.jersey.core:jersey-common:2.22.2
    |   | +-javax.annotation:javax.annotation-api:1.2
    |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | |   +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.javassist:javassist:3.18.1-GA
    |   | |
    |   | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |   |
    |   +-org.glassfish.jersey.media:jersey-media-jaxb:2.22.2
    |     +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | +-javax.inject:javax.inject:1
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     |   +-javax.inject:javax.inject:1
    |     |
    |     +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | |   +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.javassist:javassist:3.18.1-GA
    |     |
    |     +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |     +-org.glassfish.jersey.core:jersey-common:2.22.2
    |       +-javax.annotation:javax.annotation-api:1.2
    |       +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |       +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |       +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |       | +-javax.inject:javax.inject:1
    |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       |   +-javax.inject:javax.inject:1
    |       |
    |       +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |       | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |       | | +-javax.inject:javax.inject:1
    |       | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       | |   +-javax.inject:javax.inject:1
    |       | |
    |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       | | +-javax.inject:javax.inject:1
    |       | |
    |       | +-org.javassist:javassist:3.18.1-GA
    |       |
    |       +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |       +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |
    +-org.glassfish.jersey.containers:jersey-container-servlet:2.22.2
    | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | +-org.glassfish.jersey.containers:jersey-container-servlet-core:2.22.2
    | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | | | +-javax.annotation:javax.annotation-api:1.2
    | | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | |   +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | | +-javax.inject:javax.inject:1
    | | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | |   +-javax.inject:javax.inject:1
    | | | | |
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | | +-javax.inject:javax.inject:1
    | | | | |
    | | | | +-org.javassist:javassist:3.18.1-GA
    | | | |
    | | | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | | | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | | |
    | | +-org.glassfish.jersey.core:jersey-server:2.22.2
    | |   +-javax.annotation:javax.annotation-api:1.2
    | |   +-javax.validation:validation-api:1.1.0.Final
    | |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | +-javax.inject:javax.inject:1
    | |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   |   +-javax.inject:javax.inject:1
    | |   |
    | |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | |   +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.javassist:javassist:3.18.1-GA
    | |   |
    | |   +-org.glassfish.jersey.core:jersey-client:2.22.2
    | |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | |   +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | | +-javax.inject:javax.inject:1
    | |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | |   +-javax.inject:javax.inject:1
    | |   | | |
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | | +-javax.inject:javax.inject:1
    | |   | | |
    | |   | | +-org.javassist:javassist:3.18.1-GA
    | |   | |
    | |   | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | |   |   +-javax.annotation:javax.annotation-api:1.2
    | |   |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |   |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   |   | +-javax.inject:javax.inject:1
    | |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   |   |   +-javax.inject:javax.inject:1
    | |   |   |
    | |   |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   |   | | +-javax.inject:javax.inject:1
    | |   |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   |   | |   +-javax.inject:javax.inject:1
    | |   |   | |
    | |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   |   | | +-javax.inject:javax.inject:1
    | |   |   | |
    | |   |   | +-org.javassist:javassist:3.18.1-GA
    | |   |   |
    | |   |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | |   |   +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |   |
    | |   +-org.glassfish.jersey.core:jersey-common:2.22.2
    | |   | +-javax.annotation:javax.annotation-api:1.2
    | |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | |   +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | | +-javax.inject:javax.inject:1
    | |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | |   +-javax.inject:javax.inject:1
    | |   | | |
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | | +-javax.inject:javax.inject:1
    | |   | | |
    | |   | | +-org.javassist:javassist:3.18.1-GA
    | |   | |
    | |   | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | |   | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |   |
    | |   +-org.glassfish.jersey.media:jersey-media-jaxb:2.22.2
    | |     +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |     +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |     | +-javax.inject:javax.inject:1
    | |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |     |   +-javax.inject:javax.inject:1
    | |     |
    | |     +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |     | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |     | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |     | | +-javax.inject:javax.inject:1
    | |     | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |     | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |     | |   +-javax.inject:javax.inject:1
    | |     | |
    | |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |     | | +-javax.inject:javax.inject:1
    | |     | |
    | |     | +-org.javassist:javassist:3.18.1-GA
    | |     |
    | |     +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | |     +-org.glassfish.jersey.core:jersey-common:2.22.2
    | |       +-javax.annotation:javax.annotation-api:1.2
    | |       +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |       +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |       +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |       | +-javax.inject:javax.inject:1
    | |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |       |   +-javax.inject:javax.inject:1
    | |       |
    | |       +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |       | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |       | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |       | | +-javax.inject:javax.inject:1
    | |       | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |       | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |       | |   +-javax.inject:javax.inject:1
    | |       | |
    | |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |       | | +-javax.inject:javax.inject:1
    | |       | |
    | |       | +-org.javassist:javassist:3.18.1-GA
    | |       |
    | |       +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | |       +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |
    | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | | +-javax.annotation:javax.annotation-api:1.2
    | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | |   +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.javassist:javassist:3.18.1-GA
    | | |
    | | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |
    | +-org.glassfish.jersey.core:jersey-server:2.22.2
    |   +-javax.annotation:javax.annotation-api:1.2
    |   +-javax.validation:validation-api:1.1.0.Final
    |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | +-javax.inject:javax.inject:1
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   +-javax.inject:javax.inject:1
    |   |
    |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.javassist:javassist:3.18.1-GA
    |   |
    |   +-org.glassfish.jersey.core:jersey-client:2.22.2
    |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | |   +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.javassist:javassist:3.18.1-GA
    |   | |
    |   | +-org.glassfish.jersey.core:jersey-common:2.22.2
    |   |   +-javax.annotation:javax.annotation-api:1.2
    |   |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   |   | +-javax.inject:javax.inject:1
    |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   |   +-javax.inject:javax.inject:1
    |   |   |
    |   |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   |   | | +-javax.inject:javax.inject:1
    |   |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   | |   +-javax.inject:javax.inject:1
    |   |   | |
    |   |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   | | +-javax.inject:javax.inject:1
    |   |   | |
    |   |   | +-org.javassist:javassist:3.18.1-GA
    |   |   |
    |   |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   |   +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |   |
    |   +-org.glassfish.jersey.core:jersey-common:2.22.2
    |   | +-javax.annotation:javax.annotation-api:1.2
    |   | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | |   +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | | +-javax.inject:javax.inject:1
    |   | | |
    |   | | +-org.javassist:javassist:3.18.1-GA
    |   | |
    |   | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |   |
    |   +-org.glassfish.jersey.media:jersey-media-jaxb:2.22.2
    |     +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | +-javax.inject:javax.inject:1
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     |   +-javax.inject:javax.inject:1
    |     |
    |     +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | |   +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.javassist:javassist:3.18.1-GA
    |     |
    |     +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |     +-org.glassfish.jersey.core:jersey-common:2.22.2
    |       +-javax.annotation:javax.annotation-api:1.2
    |       +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |       +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |       +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |       | +-javax.inject:javax.inject:1
    |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       |   +-javax.inject:javax.inject:1
    |       |
    |       +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |       | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |       | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |       | | +-javax.inject:javax.inject:1
    |       | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |       | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       | |   +-javax.inject:javax.inject:1
    |       | |
    |       | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |       | | +-javax.inject:javax.inject:1
    |       | |
    |       | +-org.javassist:javassist:3.18.1-GA
    |       |
    |       +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |       +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |
    +-org.glassfish.jersey.core:jersey-client:2.22.2
    | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | +-javax.inject:javax.inject:1
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   +-javax.inject:javax.inject:1
    | |
    | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | |
    | | +-org.javassist:javassist:3.18.1-GA
    | |
    | +-org.glassfish.jersey.core:jersey-common:2.22.2
    |   +-javax.annotation:javax.annotation-api:1.2
    |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | +-javax.inject:javax.inject:1
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   +-javax.inject:javax.inject:1
    |   |
    |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.javassist:javassist:3.18.1-GA
    |   |
    |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |
    +-org.glassfish.jersey.core:jersey-common:2.22.2
    | +-javax.annotation:javax.annotation-api:1.2
    | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | +-javax.inject:javax.inject:1
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   +-javax.inject:javax.inject:1
    | |
    | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | |
    | | +-org.javassist:javassist:3.18.1-GA
    | |
    | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |
    +-org.glassfish.jersey.core:jersey-server:2.22.2
    | +-javax.annotation:javax.annotation-api:1.2
    | +-javax.validation:validation-api:1.1.0.Final
    | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | +-javax.inject:javax.inject:1
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   +-javax.inject:javax.inject:1
    | |
    | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | |
    | | +-org.javassist:javassist:3.18.1-GA
    | |
    | +-org.glassfish.jersey.core:jersey-client:2.22.2
    | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | |   +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.javassist:javassist:3.18.1-GA
    | | |
    | | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | |   +-javax.annotation:javax.annotation-api:1.2
    | |   +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | +-javax.inject:javax.inject:1
    | |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   |   +-javax.inject:javax.inject:1
    | |   |
    | |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | |   +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | |   | | +-javax.inject:javax.inject:1
    | |   | |
    | |   | +-org.javassist:javassist:3.18.1-GA
    | |   |
    | |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | |   +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |
    | +-org.glassfish.jersey.core:jersey-common:2.22.2
    | | +-javax.annotation:javax.annotation-api:1.2
    | | +-javax.ws.rs:javax.ws.rs-api:2.0.1
    | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | +-javax.inject:javax.inject:1
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | |   +-javax.inject:javax.inject:1
    | | |
    | | +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    | | | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    | | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | |   +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    | | | | +-javax.inject:javax.inject:1
    | | | |
    | | | +-org.javassist:javassist:3.18.1-GA
    | | |
    | | +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    | | +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    | |
    | +-org.glassfish.jersey.media:jersey-media-jaxb:2.22.2
    |   +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | +-javax.inject:javax.inject:1
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   |   +-javax.inject:javax.inject:1
    |   |
    |   +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |   | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |   | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |   | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | |   +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |   | | +-javax.inject:javax.inject:1
    |   | |
    |   | +-org.javassist:javassist:3.18.1-GA
    |   |
    |   +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |   +-org.glassfish.jersey.core:jersey-common:2.22.2
    |     +-javax.annotation:javax.annotation-api:1.2
    |     +-javax.ws.rs:javax.ws.rs-api:2.0.1
    |     +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | +-javax.inject:javax.inject:1
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     |   +-javax.inject:javax.inject:1
    |     |
    |     +-org.glassfish.hk2:hk2-locator:2.4.0-b34
    |     | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | +-org.glassfish.hk2.external:javax.inject:2.4.0-b34
    |     | +-org.glassfish.hk2:hk2-api:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | | +-org.glassfish.hk2.external:aopalliance-repackaged:2.4.0-b34
    |     | | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | |   +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.glassfish.hk2:hk2-utils:2.4.0-b34
    |     | | +-javax.inject:javax.inject:1
    |     | |
    |     | +-org.javassist:javassist:3.18.1-GA
    |     |
    |     +-org.glassfish.hk2:osgi-resource-locator:1.0.1
    |     +-org.glassfish.jersey.bundles.repackaged:jersey-guava:2.22.2
    |
    +-org.json4s:json4s-jackson_2.11:3.2.11 [S]
    | +-com.fasterxml.jackson.core:jackson-databind:2.3.1 (evicted by: 2.6.7.1)
    | +-com.fasterxml.jackson.core:jackson-databind:2.6.7.1
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.0 (evicted by: 2.6.7)
    | | +-com.fasterxml.jackson.core:jackson-annotations:2.6.7
    | | +-com.fasterxml.jackson.core:jackson-core:2.6.7
    | |
    | +-org.json4s:json4s-core_2.11:3.2.11 [S]
    |   +-com.thoughtworks.paranamer:paranamer:2.6 (evicted by: 2.8)
    |   +-com.thoughtworks.paranamer:paranamer:2.8
    |   +-org.json4s:json4s-ast_2.11:3.2.11 [S]
    |   +-org.scala-lang:scalap:2.11.12
    |     +-org.scala-lang:scala-compiler:2.11.12 [S]
    |       +-org.scala-lang.modules:scala-parser-combinators_2.11:1.0.4 [S]
    |       +-org.scala-lang.modules:scala-xml_2.11:1.0.5 [S]
    |       +-org.scala-lang:scala-reflect:2.11.12 [S]
    |
    +-org.lz4:lz4-java:1.4.0
    +-org.roaringbitmap:RoaringBitmap:0.5.11
    +-org.slf4j:jcl-over-slf4j:1.7.16
    | +-org.slf4j:slf4j-api:1.7.16
    |
    +-org.slf4j:jul-to-slf4j:1.7.16
    | +-org.slf4j:slf4j-api:1.7.16
    |
    +-org.slf4j:slf4j-api:1.7.16
    +-org.slf4j:slf4j-log4j12:1.7.16
    | +-log4j:log4j:1.2.17
    | +-org.slf4j:slf4j-api:1.7.16
    |
    +-org.spark-project.spark:unused:1.0.0
    +-org.xerial.snappy:snappy-java:1.1.2.6
    +-oro:oro:2.0.8
```

Generated with: `sbt -no-colors dependencyTree | xclip -i`
