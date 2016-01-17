# openshift-sbt-precomp
* Use `sbt stage` with [SBT native packager](http://www.scala-sbt.org/sbt-native-packager/) and copy your compiled application (`bin` and `lib` directories) into the `app` directory
* Change application name in `.openshift/action_hooks/start`
