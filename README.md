# gradle-properties-android-config
My personal gradle.properties config for maximum build speed.

org.gradle.caching=true
android.nonTransitiveRClass=true
kotlin.incremental.js=true
kotlin.incremental=true
org.gradle.daemon=true
org.gradle.parallel=true
org.gradle.jvmargs=-XX\:+UseG1GC -Dkotlin.daemon.jvm.options\="-Xmx4096M" -Xmx4096M -Dfile.encoding\=UTF-8
android.useAndroidX=true
android.enableJetifier=true
kotlin.code.style=official
kapt.incremental.apt=true
kotlin.parallel.tasks.in.project=true
org.gradle.configureondemand=true
kotlin.incremental.java=true
kotlin.caching.enabled=true
org.gradle.unsafe.configuration-cache-problems=warn
org.gradle.unsafe.configuration-cache=true
android.nonFinalResIds=false
