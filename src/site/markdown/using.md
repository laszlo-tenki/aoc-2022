# Using

This component is available via maven.  Include in your pom.xml file the following :-

```
    <project>
        ...
        <dependencies>
            <dependency>
                <groupId>com.aoc</groupId>
                <artifactId>aoc-2022</artifactId>
                <type>ep-eventflow-fragment</type>
            </dependency>
            ...
        </dependencies>
        ...
        <dependencyManagement>
            <dependencies>
                <dependency>
                     <groupId>com.aoc</groupId>
                     <artifactId>aoc-2022</artifactId>
                     <version>0.0.1-SNAPSHOT</version>
                 </dependency>
                 ...
             </dependencies>
        </dependencyManagement>
        ...
    </project>
```