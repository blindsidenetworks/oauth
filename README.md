To use this GitHub repo as the bbb-lti oauth library (if removing the oauth library from the bbb-lti files), add the following to the _BuildConfig.groovy_

Under repositories add the following line near the other maven repos:
`mavenRepo "https://jitpack.io"`

Next add the following under dependencies:
`compile 'com.github.blindsidenetworks:oauth:master-SNAPSHOT'`

The master-SNAPSHOT can be replaced with any tagged release, if you don't want to use the latest version. When the bbb-lti is run with these lines in the BuildConfig.groovy, it will download the library from GitHub. 
