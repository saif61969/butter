butter_manifest
=================

TO BUILD Butter
   repo init -u git://github.com/Android-Butter/butter.git -b master



TO BUILD M2
   repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1

mkdir -p .repo/local_manifests

wget https://github.com/Android-Butter/butter/raw/master/M2_manifest.xml -O .repo/local_manifests/M2_manifest.xml
