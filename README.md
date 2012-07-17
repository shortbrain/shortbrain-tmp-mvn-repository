# Temporary shortbrain maven repository

This is a temporary maven repository before using others services. You
**should'nt use this**.

source : http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/

If you **really** want to use it :

## Releases

    <repositories>
        <repository>
          <id>shortbrain-releases</id>
          <url>https://raw.github.com/shortbrain/shortbrain-tmp-mvn-repository/master/releases</url>
        </repository>
    </repositories>

## Snapshots  

    <repositories>
        <repository>
          <id>shortbrain-snapshots</id>
          <url>https://raw.github.com/shortbrain/shortbrain-tmp-mvn-repository/master/snapshots</url>
        </repository>
    </repositories>


