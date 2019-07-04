Getting Started
===========================
NerdyLib can be added as a dependency to a WPILib Java project in two ways:
- via Jitpack
- as a submodule

Jitpack
----------------
If you don't think you'll need to edit NerdyLib on the fly (such as at comp) it's probably better to add NerdyLib via Jitpack.
If you're a member of another team interested in using NerdyLib, it's also recommended to add NerdyLib via Jitpack.

Add the following to build.gradle in repositories.
.... code-block:: java
repositories {
    mavenCentral()

    maven {
        url "https://jitpack.io"
    }
}

And add the following to build.gradle under dependencies

.... code-block:: java
dependencies {
    compile 'com.github.nerdherd:NerdyLib:version-number'
}

Version number can be a github commit hash or a version number, look at `Jitpack <https://jitpack.io/>`_ for more information.
