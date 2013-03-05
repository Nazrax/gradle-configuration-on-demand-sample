Sample for using Gradle 1.4's configuration on demand.

"gradle-1.4 :projA:hi" will configure the projects with a traditional allprojects {} block. Both projA and projB will be configured.

"gradle-1.4 :projA:hi -Pinclude=true" will configure the projects with an "apply from" in each subproject. Only projA will be configured.
