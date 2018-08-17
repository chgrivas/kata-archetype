[![Build Status](https://travis-ci.org/chgrivas/kata-archetype?branch=master)](https://travis-ci.org/chgrivas/kata-archetype)

# kata-archetype

> A maven archetype for efficient kata sessions.

## Get started

Generate a ready-to-go project for your next kata including Spock framework for testing.

### Configure archetype locally

Add kata-archetype to local archetype-catalog:

```
git clone https://github.com/chgrivas/kata-archetype.git
cd kata-archetype
mvn install archetype:update-local-catalog
```

### Use archetype

Generate a new project:

```
mvn archetype:generate -DarchetypeGroupId=com.chgrivas.learn -DarchetypeArtifactId=kata-archetype -DarchetypeVersion=1.0
```


