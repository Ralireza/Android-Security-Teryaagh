# Android-Security-Roadmap

## Prerequisites

### Programing languages
- Java : [[ 1 ]](https://www.homeandlearn.co.uk/java/java.html) - [[ 2 ]](https://www.codecademy.com/learn/learn-java) - [[ 3 ]](https://www.tutorialspoint.com/java/index.htm) - [[ 4 ]](https://www.youtube.com/watch?v=eIrMbAQSU34&t=6s)
- Kotlin : [[ 1 ]](https://developer.android.com/kotlin) - [[ 2 ]](https://kotlinlang.org/docs/home.html)
- XML : [[ 1 ]](https://www.w3schools.com/xml/) - [[ 2 ]](https://www.tutorialspoint.com/xml/index.htm)
- C / C++
- Smali : [[ 1 ]](https://github.com/JesusFreke/smali) - [[ 2 ]](https://source.android.com/devices/tech/dalvik/dalvik-bytecode) - [[ 3 ]](https://programmer.help/blogs/smali-introduction-manual.html) - [[ 4 ]](https://forum.xda-developers.com/t/guide-smali-coding-guide-for-beginners.2193735/)
- Assembly :  [[ 1 ]](https://www.tutorialspoint.com/assembly_programming/index.htm) - [[ 2 ]](https://cs.lmu.edu/~ray/notes/nasmtutorial/) - [[ 3 ]](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html) - [[ 4 ]](http://www.egr.unlv.edu/~ed/assembly64.pdf)


### Networking
- OSI Model : [[ 1 ]](https://www.javatpoint.com/osi-vs-tcp-ip) - [[ 2 ]](https://www.studytonight.com/computer-networks/complete-osi-model)
- TCP / IP
- DNS
- HTTP
- SSL / TLS
- Proxy


### Cryptography
- Encryption : [[ 1 ]](https://cryptohack.org/)
- Hashing
- MAC
- RSA 
- AES

## Android Design & Architecture
- Linux Kernel : [[ 1 ]](https://developer.android.com/guide/platform?hl=en)
- HAL
- Native Library
- Android Runtime
- Java API
- System App
- IPC
- Binder
- Dalvik VM
- SandBoxing
- User & group 
- Filesystem / Partition
- File
- Database
- Sqlite : [[ 1 ]](https://developer.android.com/training/data-storage/sqlite) - [[ 2 ]](https://www.sqlite.org/android)
- Room : [[ 1 ]](https://developer.android.com/training/data-storage/room) - [[ 2 ]](https://medium.com/mindorks/using-room-database-android-jetpack-675a89a0e942)
- Realm : [[ 1 ]](https://docs.mongodb.com/realm/sdk/android/) - [[ 2 ]](https://docs.mongodb.com/realm-legacy/docs/java/latest/)
- Sharedprefrence : [[ 1 ]](https://developer.android.com/training/data-storage/shared-preferences) - [[ 2 ]](https://blog.mindorks.com/android-shared-preferences-in-kotlin)


## Permissions
- Application level : [[ 1 ]](https://developer.android.com/guide/topics/permissions/overview)
- Protection levels
- Custom Permission


## Application Components
- Activity : [[ 1 ]](https://developer.android.com/guide/components/activities/intro-activities)
- Service : [[ 1 ]](https://developer.android.com/guide/components/services)
- Broadcast Reciever : [[ 1 ]](https://developer.android.com/guide/components/broadcasts)
- Content Provider : [[ 1 ]](https://developer.android.com/guide/topics/providers/content-providers)
- Manifest : [[ 1 ]](https://developer.android.com/guide/topics/manifest/manifest-intro)
- Intent : [[ 1 ]](https://developer.android.com/guide/components/intents-filters) - [[ 2 ]](https://blog.mindorks.com/what-are-intents-in-android)


## Core Api 
- Cryptography : [[ 1 ]](https://developer.android.com/guide/topics/security/cryptography?hl=en)
- Interacting with Other Apps : [[ 1 ]](https://developer.android.com/training/basics/intents)
- User Interface : [[ 1 ]](https://developer.android.com/guide/topics/ui)
- Images and graphics : [[ 1 ]](https://developer.android.com/guide/topics/graphics)
- Audio & Video : [[ 1 ]](https://developer.android.com/guide/topics/media)
- background processing : [[ 1 ]](https://developer.android.com/guide/background)
- App data and files : [[ 1 ]](https://developer.android.com/guide/topics/data)
- Touch and input : [[ 1 ]](https://developer.android.com/guide/input)
- Sensors : [[ 1 ]](https://developer.android.com/guide/topics/sensors)
- Connectivity : [[ 1 ]](https://developer.android.com/guide/topics/connectivity)


## Server Interaction
- Confidentiality & Authentication
- HTTP Library
- OkHttp
- Volley
- Retrofit
- Burp Suite
- SSL Pinning
- Certificate Validation
- Proxy & Sniffer for HTTP Traffic
- SSL / TLS Implementation


## Static Analysis
- APK Development Process
- APK Structure : [[ 1 ]](https://developer.android.com/studio/projects)
- Decompiling
- JADX
- APKtool
- Code Patching
- Native Code
- Decompiling
- Disassembling
- Ghidra
- IDA


## Dynamic Analysis
- Stack trace
- Hooking
- Debuging
- ADB
- Emulator
- Genymotion
- AVD
- Bluestack
- Detection / Bypass
- Virtual-machine
- SSL-pin
- Rooting
- Tools
- Frida
- Drozer
- Objection
- Xposed 
- RMS
- MOBSF


## Common Attacks 
- Insecure Data Transmission
- Insecure IPC 
- Permission Issue
- Insecure Data Storage
- Webview Issue
- Insecure Logs
