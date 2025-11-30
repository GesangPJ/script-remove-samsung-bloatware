# UNINSTALL SAMSUNG BLOATWARE AND OTHERS

Most of the listed application below is the app that you can't uninstall, you can only disable in your phone,
with these scripts, you can completely uninstall the apps you don't want.

If The Result is *error not found* or *not installed* it means *your phone is not pre-installed* with that Application.

Make sure you have developer option **ON** in your phone, and *activate debug mode* , this script is using ADB Shell.

Download platform-tools to use ADB Shell : https://developer.android.com/tools/releases/platform-tools

## ***Use at your own risk!***

## ADB Command to start

    adb devices
    
    adb shell

A popup will appear on your phone to *allow debug mode*, **Allow** it and ADB shell will work

To see / search other package not listed but you know the name, use this command below :

    pm list packages | grep "<the package name>"

## Samsung Bixby

    pm uninstall --user 0 com.samsung.android.bixby.service
    pm uninstall --user 0 com.samsung.android.bixby.agent
    pm uninstall --user 0 com.samsung.android.bixby.wakeup
    pm uninstall --user 0 com.samsung.android.app.settings.bixby
    pm uninstall --user 0 com.samsung.android.bixbyvision.framework


## Samsung AR

    pm uninstall --user 0 com.samsung.android.aremojieditor
    pm uninstall --user 0 com.samsung.android.ardrawing
    pm uninstall --user 0 com.samsung.android.arzone
    pm uninstall --user 0 com.samsung.android.aremoji

## Samsung Message
( Do not uninstall if you don't have other messaging app )

    pm uninstall --user 0 com.samsung.android.messaging

## Samsung Game tools & hub

    pm uninstall --user 0 com.samsung.android.game.gamehome
    pm uninstall --user 0 com.samsung.android.game.gametools
    pm uninstall --user 0 com.samsung.android.game.gos
    pm uninstall --user 0 com.samsung.android.game.gamehome

## Samsung Files
( Do not uninstall this except you already install other file manager )

    pm uninstall --user 0 com.sec.android.app.myfiles
    pm uninstall --user 0 com.samsung.android.app.spage

## Samsung Reminder & Calendar App

    pm uninstall --user 0 com.samsung.android.app.reminder
    pm uninstall --user 0 com.samsung.android.calendar

## Samsung Gift Indonesia

    pm uninstall --user 0 com.srin.indramayu

## The Spyware made by IS***

    pm uninstall --user 0 com.aura.oobe.samsung.gl

## Google Play Music (Discontinue), AR, Games

    pm uninstall --user 0 com.google.android.music
    pm uninstall --user 0 com.google.ar.core
    pm uninstall --user 0 com.google.android.play.games

## LinkedIn

    pm uninstall --user 0 com.linkedin.android

## Microsoft One Drive

    pm uninstall --user 0 com.microsoft.skydrive

## Google Keep

    pm uninstall --user 0 com.google.android.keep

## Facebook

    pm uninstall --user 0 com.facebook.appmanager
    pm uninstall --user 0 com.facebook.services
    pm uninstall --user 0 com.facebook.system
    pm uninstall --user 0 com.facebook.katana

## Netflix

    pm uninstall --user 0 com.netflix.mediaclient

## Google Meet / Duo

    pm uninstall --user 0 com.google.android.apps.tachyon





