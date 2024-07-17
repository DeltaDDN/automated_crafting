# Automated Crafting
> ~~This plugin will no longer be updated beyond 1.20.2 as vanilla has introduced the Crafter block making this plugin obsolete.~~


> This (DeltaDDN's) fork of the plugin is being poorly patched to work with newer releases until the Crafter block is put into release status.
> 
> It's not well-patched, throws exceptions, and generally should not be trusted. Honestly, I don't know how to write Java, and I'm just stumbling along. //DDDN
>
> 
> Release dated 24-05-09 was tested against Paper 1.20.6-54, which is an experimental build. This release will work exclusively with 1.20.6 servers, as server-version references are hardcoded.

**This fork of the plugin will not be updated, as Mojang officially released the crafter block in 1.21**

An open-source plugin for Bukkit which adds autocrafters capable of automatically crafting anything.

<br/>

**How to use (when using default configuration settings)**

1) Place a dropper in the world.

![Step 1](https://i.ibb.co/Mg3hKbD/2019-08-16-16-13-13.png)


2) Put an item frame on any side of the dropper.

![Step 2](https://i.ibb.co/vccK0T8/2019-08-16-16-13-21.png)


3) Put the item you want to craft in the item frame.

![Step 3](https://i.ibb.co/fxQ3p96/2019-08-16-16-13-30.png)

4) Fill up the dropper with the crafting ingredients.

![Step 4](https://i.ibb.co/5nCPpct/2019-08-16-16-13-44.png)

5) Enjoy your new autocrafter!

![Step 5](https://i.ibb.co/6Nqq03s/2019-08-16-16-13-50.png)

<br/><br/>

**Other Features**
- Autocrafters will put the items inside of containers adjacent to the face of the dropper. This saves performance for servers so players don't need to have hoppers to pick up the items. The dropped item is also always spawned in the same location right in front of the dropper.
- Powering the dropper will stop the autocrafting process even if there are still items inside.
- Deny users the permission `automatedcrafting.makeautocrafters` to prevent them from making auto crafters!
- There is a configuration file with various options to customize the plugin.

<br/> <br/>

**Adding this plugin as a dependency**

If you want to use this plugin as a dependency. You can use a very handy service called [**jitpack.io**](https://jitpack.io/). <br/>
This services makes it easy to add any git repository as a dependency.

_Gradle_<br/>
For Gradle you'll need to add the following six lines to your _build.gradle_ file:
```gradle
repositories {
     maven { url 'https://jitpack.io' }
}
dependencies {
    implementation 'com.github.Aeltumn:automated_crafting:main-SNAPSHOT'
}
```

_Maven_<br/>
For Maven you can add the following lines to your _pom.xml_ file:
```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.github.Aeltumn</groupId>
    <artifactId>automated_crafting</artifactId>
    <version>main-SNAPSHOT</version>
</dependency>
```
