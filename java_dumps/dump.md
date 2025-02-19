# Subcomponent Dump Routine

- **Trigger:** User event
- **Date and Time:** 2025/02/11 at 12:53:32:390
- **Timezones:** UTC+5:30 (IST)
- **Javacore Filename:** `/Users/aditisrinivas/Work/Generator/beetle/gen/hang/V3/output/javacore.20250211.125332.47420.0001.txt`
- **Request Flags:** `0x41 (exclusive+preempt)`
- **Prep State:** `0x84 (exclusive_vm_access+trace_disabled)`

# GP Info

- **OS Version:** Mac OS X 14.6
- **Processor Architecture:** aarch64
- **CPU Count:** 12

## Environment Info

- **VM Version:** 20241015_301
- **JIT Version:** j9jit_20241107_1552_jenkins
- **OMR Version:** d10a4d553
- **JCL Version:** b1b311c53fe based on jdk-21.0.5+11
- **Vendor:** IBM Corporation
- **Product:** IBM Semeru Runtime Open Edition
- **JDK Version:** 21.0.5.0
- **Running in Container:** FALSE
- **cgroups Support:** FALSE
- **JVM Start Time:** 2025/02/11 at 12:53:11:327
- **Process ID:** 47420 (0xB93C)
- **Command Line:** `/usr/bin/java d6vrykjlnv`
- **Java Home Directory:** `/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home`
- **Java DLL Directory:** `/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/bin`
- **System Classpath:** *None*

## User Arguments

```
-Xoptionsfile: /Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib/options.default
-Xlockword:mode=default,noLockword=java/lang/String,noLockword=java/util/MapEntry,noLockword=java/util/HashMap$Entry,noLockword=org/apache/harmony/luni/util/ModifiedMap$Entry,noLockword=java/util/Hashtable$Entry,noLockword=java/lang/invoke/MethodType,noLockword=java/lang/invoke/MethodHandle,noLockword=java/lang/invoke/CollectHandle,noLockword=java/lang/invoke/ConstructorHandle,noLockword=java/lang/invoke/ConvertHandle,noLockword=java/lang/invoke/ArgumentConversionHandle,noLockword=java/lang/invoke/AsTypeHandle,noLockword=java/lang/invoke/ExplicitCastHandle,noLockword=java/lang/invoke/FilterReturnHandle,noLockword=java/lang/invoke/DirectHandle,noLockword=java/lang/invoke/ReceiverBoundHandle,noLockword=java/lang/invoke/DynamicInvokerHandle,noLockword=java/lang/invoke/FieldHandle,noLockword=java/lang/invoke/FieldGetterHandle,noLockword=java/lang/invoke/FieldSetterHandle,noLockword=java/lang/invoke/StaticFieldGetterHandle,noLockword=java/lang/invoke/StaticFieldSetterHandle,noLockword=java/lang/invoke/IndirectHandle,noLockword=java/lang/invoke/InterfaceHandle,noLockword=java/lang/invoke/VirtualHandle,noLockword=java/lang/invoke/PrimitiveHandle,noLockword=java/lang/invoke/InvokeExactHandle,noLockword=java/lang/invoke/InvokeGenericHandle,noLockword=java/lang/invoke/VarargsCollectorHandle,noLockword=java/lang/invoke/ThunkTuple
-XX:+EnsureHashed=java/lang/Class,java/lang/Thread
-Xjcl=jclse29
-Dcom.ibm.oti.vm.bootstrap.library.path=/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib/default:/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib
-Dsun.boot.library.path=/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib/default:/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib
-Djava.library.path=/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib/default:/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home/lib:/usr/lib
-Djava.home=/Library/Java/JavaVirtualMachines/ibm-semeru-open-21.jdk/Contents/Home
-Duser.dir=/Users/aditisrinivas/Work/Generator/beetle/gen/hang/V3/output
-Djava.class.path=.
-Dsun.java.command=d6vrykjlnv
-Dsun.java.launcher=SUN_STANDARD
```

## User Limits

- **RLIMIT_AS:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_CORE:** Soft Limit: 0 / Hard Limit: unlimited
- **RLIMIT_CPU:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_DATA:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_FSIZE:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_MEMLOCK:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_NOFILE:** Soft Limit: 138240 / Hard Limit: unlimited
- **RLIMIT_NPROC:** Soft Limit: 6000 / Hard Limit: 9000
- **RLIMIT_RSS:** Soft Limit: unlimited / Hard Limit: unlimited
- **RLIMIT_STACK:** Soft Limit: 8372224 / Hard Limit: 67092480

## Environment Variables

```
MallocNanoZone=0
USER=aditisrinivas
COMMAND_MODE=unix2003
__CFBundleIdentifier=com.microsoft.VSCode
PATH=/Users/aditisrinivas/.nvm/versions/node/v22.13.1/bin:/opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/Users/aditisrinivas/.nvm/versions/node/v22.13.1/bin
LOGNAME=aditisrinivas
SSH_AUTH_SOCK=/private/tmp/com.apple.launchd.1uBo7U5NLt/Listeners
HOME=/Users/aditisrinivas
SHELL=/bin/zsh
TMPDIR=/var/folders/c9/t12vk1fs3b94b24w6nvzxw1r0000gn/T/
__CF_USER_TEXT_ENCODING=0x1F5:0x0:0x0
XPC_SERVICE_NAME=0
XPC_FLAGS=0x0
ORIGINAL_XDG_CURRENT_DESKTOP=undefined
SHLVL=1
PWD=/Users/aditisrinivas/Work/Generator/beetle/gen/hang/v3/output
OLDPWD=/Users/aditisrinivas/Work/Generator/beetle/gen/hang/v3
HOMEBREW_PREFIX=/opt/homebrew
HOMEBREW_CELLAR=/opt/homebrew/Cellar
HOMEBREW_REPOSITORY=/opt/homebrew
INFOPATH=/opt/homebrew/share/info:/opt/homebrew/share/info:
NVM_DIR=/Users/aditisrinivas/.nvm
NVM_CD_FLAGS=-q
NVM_BIN=/Users/aditisrinivas/.nvm/versions/node/v22.13.1/bin
NVM_INC=/Users/aditisrinivas/.nvm/versions/node/v22.13.1/include/node
TERM_PROGRAM=vscode
TERM_PROGRAM_VERSION=1.96.3
LANG=en_US.UTF-8
COLORTERM=truecolor
GIT_ASKPASS=/private/var/folders/c9/t12vk1fs3b94b24w6nvzxw1r0000gn/T/AppTranslocation/D10AE133-7A8F-4604-ABF6-9E5E5341AA61/d/Visual Studio Code.app/Contents/Resources/app/extensions/git/dist/askpass.sh
VSCODE_GIT_ASKPASS_NODE=/private/var/folders/c9/t12vk1fs3b94b24w6nvzxw1r0000gn/T/AppTranslocation/D10AE133-7A8F-4604-ABF6-9E5E5341AA61/d/Visual Studio Code.app/Contents/Frameworks/Code Helper (Plugin).app/Contents/MacOS/Code Helper (Plugin)
VSCODE_GIT_ASKPASS_EXTRA_ARGS=
VSCODE_GIT_ASKPASS_MAIN=/private/var/folders/c9/t12vk1fs3b94b24w6nvzxw1r0000gn/T/AppTranslocation/D10AE133-7A8F-4604-ABF6-9E5E5341AA61/d/Visual Studio Code.app/Contents/Resources/app/extensions/git/dist/askpass-main.js
VSCODE_GIT_IPC_HANDLE=/var/folders/c9/t12vk1fs3b94b24w6nvzxw1r0000gn/T/vscode-git-06a3f621ec.sock
VSCODE_INJECTION=1
ZDOTDIR=/Users/aditisrinivas
USER_ZDOTDIR=/Users/aditisrinivas
TERM=xterm-256color
_=/usr/bin/java
OPENJ9_JAVA_COMMAND_LINE=/usr/bin/java d6vrykjlnv
```

## CPU Information

- **Physical CPUs:** 12
- **Online CPUs:** 12
- **Bound CPUs:** 12
- **Active CPUs:** 0
- **Target CPUs:** 12
- **CPU features (JIT):** fp asimd crc32 atomics
- **CPU features (AOT):** fp asimd crc32 atomics

## Native Memory Info

- **JRE:** 10,224,262,012 bytes
- **VM:** 9,950,318,596 bytes
- **Classes:** 73,010,016 bytes
- **Shared Class Cache:** 67,108,960 bytes
- **Other:** 4,448,944 bytes
- **Modules:** 542,048 bytes
- **Memory Manager (GC):** 9,856,049,536 bytes
- **Java Heap:** 9,663,725,568 bytes
- **Threads:** 18,819,292 bytes
- **Java Stack:** 279,720 bytes
- **Native Stack:** 18,219,008 bytes
- **Trace:** 420,728 bytes
- **JVMTI:** 22,160 bytes
- **JNI:** 79,760 bytes
- **Port Library:** 10,096 bytes
- **JIT:** 273,933,104 bytes
- **JIT Code Cache:** 268,435,456 bytes
- **JIT Data Cache:** 1,048,704 bytes
- **Class Libraries:** 10,312 bytes
- **VM Class Libraries:** 10,312 bytes

## Heap Data

### Object Memory

- **Total Memory:** 8,519,680 bytes
- **Memory In Use:** 3,011,800 bytes
- **Memory Free:** 5,507,880 bytes

### Heap Spaces

#### Generational
- **ID:** `0x000000013501FA80`

#### Generational/Tenured
- **ID:** `0x00000001350211C0`
- **Start:** `0x0000000300000000`
- **End:** `0x0000000300600000`
- **Size:** `0x0000000000600000`

#### Generational/Nursery
- **ID:** `0x0000000135020680`
- **Start:** `0x000000053FDE0000`
- **End:** `0x000000053FEF0000`
- **Size:** `0x0000000000110000`

#### Generational/Nursery
- **ID:** `0x000000013501FB40`
- **Start:** `0x000000053FEF0000`
- **End:** `0x0000000540000000`
- **Size:** `0x0000000000110000`

## Segments 

### Internal Memory

### Segments

#### Segment 1
- **Segment ID:** `0x0000000135860E50`
- **Start Address:** `0x0000000118378020`
- **Allocation Address:** `0x00000001183CB900`
- **End Address:** `0x0000000118478020`
- **Type:** `0x00800040`
- **Size:** `0x0000000000100000`

#### Segment 2
- **Segment ID:** `0x0000000135860CC0`
- **Start Address:** `0x00000001397F0020`
- **Allocation Address:** `0x00000001398F0000`
- **End Address:** `0x00000001398F0020`
- **Type:** `0x00800040`
- **Size:** `0x0000000000100000`

#### Segment 3
- **Segment ID:** `0x0000000135860BF8`
- **Start Address:** `0x00000001396E8020`
- **Allocation Address:** `0x00000001397E8010`
- **End Address:** `0x00000001397E8020`
- **Type:** `0x00800040`
- **Size:** `0x0000000000100000`

#### Segment 4
- **Segment ID:** `0x0000000135860A68`
- **Start Address:** `0x00000001395D0020`
- **Allocation Address:** `0x000000013965ECE0`
- **End Address:** `0x00000001396D0020`
- **Type:** `0x00800040`
- **Size:** `0x0000000000100000`

## Memory Statistics

- **Total Memory:** 4,194,304 bytes
- **Memory In Use:** 3,024,240 bytes
- **Memory Free:** 1,170,064 bytes

### JIT Code Cache

### Segments

#### Segment 1
- **Segment ID:** `0x0000000135027E68`
- **Start Address:** `0x0000000149550000`
- **Allocation Address:** `0x000000014961064D`
- **End Address:** `0x0000000159550000`
- **Type:** `0x00000068`
- **Size:** `0x0000000010000000`

## Memory Statistics

- **Total Memory:** 268,435,456 bytes
- **Memory In Use:** 788,045 bytes
- **Memory Free:** 267,647,411 bytes
- **Allocation Limit:** 268,435,456 bytes

### JIT Data Cache


### Segments

#### Segment 1
- **Segment ID:** `0x00000001350283B0`
- **Start Address:** `0x0000000139BF8020`
- **Allocation Address:** `0x0000000139C78020`
- **End Address:** `0x0000000139C78020`
- **Type:** `0x00000048`
- **Size:** `0x0000000000080000`

#### Segment 2
- **Segment ID:** `0x00000001350282E8`
- **Start Address:** `0x0000000139B28020`
- **Allocation Address:** `0x0000000139BA8020`
- **End Address:** `0x0000000139BA8020`
- **Type:** `0x00000048`
- **Size:** `0x0000000000080000`

## Memory Statistics

- **Total Memory:** 1,048,576 bytes
- **Memory In Use:** 1,048,576 bytes
- **Memory Free:** 0 bytes
- **Allocation Limit:** 402,653,184 bytes

## Garbage Collection History

### Events

- **07:23:21:403908963 GMT j9mm.134** -   Allocation failure end: newspace=521888/2228224 oldspace=4990088/6291456 loa=315392/315392
- **07:23:21:403906088 GMT j9mm.470** -   Allocation failure cycle end: newspace=521952/2228224 oldspace=4990088/6291456 loa=315392/315392
- **07:23:21:403902546 GMT j9mm.468** -   Cycle End: type 2 approximateFreeMemorySize 5512040
- **07:23:21:403894504 GMT j9mm.560** -   LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=6864 flipbytes=518256 newspace=521952/2228224 oldspace=4990088/6291456 loa=315392/315392 tenureage=0
- **07:23:21:403852214 GMT j9mm.140** -   Tilt ratio: 50",
- **07:23:21:403339558 GMT j9mm.64** -   LocalGC start: globalcount=0 scavengecount=6 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:21:403333100 GMT j9mm.467** -   Cycle Start: type 2 approximateFreeMemorySize 5075080
- **07:23:21:403265643 GMT j9mm.135** -   Exclusive access: exclusiveaccessms=0.009 meanexclusiveaccessms=0.009 threads=0 lastthreadtid=0x000000013589EFE8 beatenbyotherthread=0
- **07:23:21:403265018 GMT j9mm.469** -   Allocation failure cycle start: newspace=0/2228224 oldspace=5075080/6291456 loa=315392/315392 requestedbytes=64
- **07:23:21:403264518 GMT j9mm.133** -   Allocation failure start: newspace=0/2228224 oldspace=5075080/6291456 loa=315392/315392 requestedbytes=64
- **07:23:11:389446781 GMT j9mm.134** -   Allocation failure end: newspace=465312/2228224 oldspace=5103472/6291456 loa=315392/315392
07:23:11:389445156 GMT j9mm.470 -   Allocation failure cycle end: newspace=465664/2228224 oldspace=5103472/6291456 loa=315392/315392
- **07:23:11:389438281 GMT j9mm.468** -   Cycle End: type 2 approximateFreeMemorySize 5569136
- **07:23:11:389431572 GMT j9mm.560** -   LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=7881 flipbytes=560912 newspace=465664/2228224 oldspace=5103472/6291456 loa=315392/315392 tenureage=0
- **07:23:11:389416656 GMT j9mm.140** -   Tilt ratio: 50
- **07:23:11:389012915 GMT j9mm.64&& -   LocalGC start: globalcount=0 scavengecount=5 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:11:389009915 GMT j9mm.467** -   Cycle Start: type 2 approximateFreeMemorySize 5178224


- **07:23:11:388990832 GMT** - Exclusive access: exclusiveaccessms=0.003 meanexclusiveaccessms=0.003 threads=0 lastthreadtid=0x000000013589EFE8 beatenbyotherthread=0
- **07:23:11:388990624 GMT** - Allocation failure cycle start: newspace=0/2228224 oldspace=5178224/6291456 loa=315392/315392 requestedbytes=352
- **07:23:11:388990207 GMT** - Allocation failure start: newspace=0/2228224 oldspace=5178224/6291456 loa=315392/315392 requestedbytes=352
- **07:23:11:377120718 GMT** - Allocation failure end: newspace=818144/2228224 oldspace=5203504/6291456 loa=315392/315392
- **07:23:11:377119385 GMT** - Allocation failure cycle end: newspace=820208/2228224 oldspace=5203504/6291456 loa=315392/315392
- **07:23:11:377116427 GMT** - Cycle End: type 2 approximateFreeMemorySize 6023712
- **07:23:11:377112093 GMT** - LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=3215 flipbytes=192224 newspace=820208/2228224 oldspace=5203504/6291456 loa=315392/315392 tenureage=0
- **07:23:11:377101343 GMT** - Tilt ratio: 50



- **07:23:11:376707394 GMT** - LocalGC start: globalcount=0 scavengecount=4 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:11:376704727 GMT** - Cycle Start: type 2 approximateFreeMemorySize 5886640
- **07:23:11:376694561 GMT** - Exclusive access: exclusiveaccessms=0.002 meanexclusiveaccessms=0.001 threads=1 lastthreadtid=0x0000000134809DE8 beatenbyotherthread=0
- **07:23:11:376694352 GMT** - Allocation failure cycle start: newspace=0/2228224 oldspace=5886640/6291456 loa=315392/315392 requestedbytes=2064
- **07:23:11:376693936 GMT** - Allocation failure start: newspace=0/2228224 oldspace=5886640/6291456 loa=315392/315392 requestedbytes=2064
- **07:23:11:371071435 GMT** - Allocation failure end: newspace=333032/2228224 oldspace=5912720/6291456 loa=315392/315392
- **07:23:11:371069893 GMT** - Allocation failure cycle end: newspace=333568/2228224 oldspace=5912720/6291456 loa=315392/315392
- **07:23:11:371067351 GMT** - Cycle End: type 2 approximateFreeMemorySize 6246288
- **07:23:11:371062851 GMT** - LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=10207 flipbytes=665144 newspace=333568/2228224 oldspace=5912720/6291456 loa=315392/315392 tenureage=0
- **07:23:11:371037644 GMT** - Tilt ratio: 50
- **07:23:11:370704359 GMT** - LocalGC start: globalcount=0 scavengecount=3 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:11:370701734 GMT** - Cycle Start: type 2 approximateFreeMemorySize 5912720
- **07:23:11:370693068 GMT** - Exclusive access: exclusiveaccessms=0.006 meanexclusiveaccessms=0.005 threads=1 lastthreadtid=0x0000000134809DE8 beatenbyotherthread=0
- **07:23:11:370692859 GMT** - Allocation failure cycle start: newspace=0/2097152 oldspace=5912720/6291456 loa=315392/315392 requestedbytes=536
- **07:23:11:370692443 GMT** - Allocation failure start: newspace=0/2097152 oldspace=5912720/6291456 loa=315392/315392 requestedbytes=536
- **07:23:11:366866902 GMT** - Allocation failure end: newspace=352672/2097152 oldspace=5926480/6291456 loa=315392/315392


- **07:23:11:366864860 GMT** - Allocation failure cycle end: newspace=354736/2097152 oldspace=5926480/6291456 loa=315392/315392
- **07:23:11:366861944 GMT** - Cycle End: type 2 approximateFreeMemorySize 6281216
- **07:23:11:366856069 GMT** - LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=9741 flipbytes=634824 newspace=354736/2097152 oldspace=5926480/6291456 loa=315392/315392 tenureage=0
- **07:23:11:366842236 GMT** - Tilt ratio: 50
- **07:23:11:366506118 GMT** - LocalGC start: globalcount=0 scavengecount=2 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:11:366503410 GMT** - Cycle Start: type 2 approximateFreeMemorySize 5926480
- **07:23:11:366489952 GMT** - Exclusive access: exclusiveaccessms=0.003 meanexclusiveaccessms=0.002 threads=1 lastthreadtid=0x0000000134809DE8 beatenbyotherthread=0
- **07:23:11:366489702 GMT** - Allocation failure cycle start: newspace=0/2097152 oldspace=5926480/6291456 loa=315392/315392 requestedbytes=2064
- **07:23:11:366489327 GMT** - Allocation failure start: newspace=0/2097152 oldspace=5926480/6291456 loa=315392/315392 requestedbytes=2064
- **07:23:11:360535125 GMT** - Allocation failure end: newspace=463664/2097152 oldspace=5982440/6291456 loa=315392/315392
- **07:23:11:360533250 GMT** - Allocation failure cycle end: newspace=463808/2097152 oldspace=5982440/6291456 loa=315392/315392
- **07:23:11:360529792 GMT** - Cycle End: type 2 approximateFreeMemorySize 6446248
- **07:23:11:360524542 GMT** - LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=8442 flipbytes=556080 newspace=463808/2097152 oldspace=5982440/6291456 loa=315392/315392 tenureage=0
- **07:23:11:360508333 GMT** - Tilt ratio: 50
- **07:23:11:360144841 GMT** - LocalGC start: globalcount=0 scavengecount=1 weakrefs=0 soft=0 phantom=0 finalizers=0
- **07:23:11:360139050 GMT** - Cycle Start: type 2 approximateFreeMemorySize 5982440
- **07:23:11:360121259 GMT** - Exclusive access: exclusiveaccessms=0.001 meanexclusiveaccessms=0.000 threads=2 lastthreadtid=0x000000013589EFE8 beatenbyotherthread=0
- **07:23:11:360119384 GMT** - Allocation failure cycle start: newspace=0/2097152 oldspace=5982440/6291456 loa=315392/315392 requestedbytes=144
- **07:23:11:360119009 GMT** - Allocation failure start: newspace=0/2097152 oldspace=5982440/6291456 loa=315392/315392 requestedbytes=144

## Locks Info

### Total Monitors: 5

### Monitor Pool:

#### Monitor 1:
**System Monitor Identifier**: 0x000000013402DB20  
**Inflated Monitor Identifier**: 0x000000013402DBA0  
**Objects**:
- **Object**: java/lang/ref/ReferenceQueue  
  **Address**: 0x0000000300077700  
  **Locked By**: null  
  **Entry Count**: 0  
  **Waiting Threads**:
  - Common-Cleaner

#### Monitor 2:
**System Monitor Identifier**: 0x0000000135943930  
**Inflated Monitor Identifier**: 0x00000001359439B0  
**Objects**:
- **Object**: java/lang/StringBuilder  
  **Address**: 0x0000000300078248  
  **Locked By**: Thread-1  
  **Entry Count**: 1  
  **Waiting Threads**:
  - Thread-0
  - Thread-2
  - Thread-3

#### Monitor 3:
**System Monitor Identifier**: 0x0000000135943D18  
**Inflated Monitor Identifier**: 0x0000000135943D98  
**Objects**:
- **Object**: java/util/Random  
  **Address**: 0x0000000300070A30  
  **Locked By**: Thread-3  
  **Entry Count**: 1  
  **Waiting Threads**:
  - Thread-4
  - Thread-5

#### Monitor 4:
**System Monitor Identifier**: 0x0000000135944100  
**Inflated Monitor Identifier**: 0x0000000135944180  
**Objects**:
- **Object**: java/util/ArrayList  
  **Address**: 0x0000000300070A58  
  **Locked By**: Thread-5  
  **Entry Count**: 1  
  **Waiting Threads**:
  - Thread-6
  - Thread-7

#### Monitor 5:
**System Monitor Identifier**: 0x00000001359452F8  
**Inflated Monitor Identifier**: 0x0000000135945378  
**Objects**:
- **Object**: java/util/Hashtable  
  **Address**: 0x00000003000709F0  
  **Locked By**: Thread-0  
  **Entry Count**: 1  
  **Waiting Threads**:
  - Thread-1

---

### Registered Monitors:

- Thread global lock (0x000000013580A418)
- &(PPG_mem_mem32_subAllocHeapMem32.monitor) lock (0x000000013580A4E0)
- NLS hash table lock (0x000000013580A5A8)
- portLibrary_omrsig_registerHandler_monitor lock (0x000000013580A670)
- portLibrary_omrsig_asynch_reporter_shutdown_monitor lock (0x000000013580A738)
- portLibrary_omrsig_async_monitor lock (0x000000013580A800)
- &(PHD_vendorMonitor) lock (0x000000013580A8C8)
- MemberName lists mutex lock (0x000000013580A990)
- &(vm->systemPropertiesMutex) lock (0x000000013580AA58)
- Hook Interface lock (0x000000013580AB20)
- Hook Interface lock (0x000000013580ABE8)
- OMR VM list mutex lock (0x000000013580ACB0)
- OMR VM thread list mutex lock (0x000000013580AD78)
- dump tokens mutex lock (0x000000013580AE40)
- VM hidden fields list lock (0x000000013580AF08)
- MM_SublistPool lock (0x000000013580AFD0)
- Hook Interface lock (0x000000013580B098)
- Hook Interface lock (0x000000013580B160)
- GCExtensions::gcExclusiveAccessMutex lock (0x000000013580B228)
- GCExtensions::_lightweightNonReentrantLockPoolMutex lock (0x000000013580B2F0)
- gcCycleOn lock (0x000000013580B3B8)
- Hook Interface lock (0x000000013580B480)
- MM_ParallelDispatcher::workerThread lock (0x000000013580B548)
- MM_ParallelDispatcher::dispatcherControl lock (0x000000013580B610)
- MM_ParallelDispatcher::synchronize lock (0x000000013580B6D8)
- MM_Scavenger::scanCacheMonitor lock (0x000000013580B7A0)
- MM_Scavenger::freeCacheMonitor lock (0x000000013580B868)
- MM_WorkPackets::inputList lock (0x000000013580B930)
- MM_WorkPackets::allocatingPackets lock (0x000000013580B9F8)
- MM_WorkPacketOverflow::overflowList lock (0x000000013580BAC0)
- MM_ConcurrentOverflow::cardsClearingMonitor lock (0x000000013580BB88)
- SweepPoolState Monitor lock (0x000000013580BC50)
- MM_ConcurrentGC::conHelpersActivation lock (0x000000013580BD18)
- MM_ConcurrentGC::initWork lock (0x000000013580BDE0)
- MM_ConcurrentGC::concurrentTuning lock (0x000000013580BEA8)
- MM_ConcurrentGC::initWorkComplete lock (0x000000013580BF70)
- Undead Segment List Monitor lock (0x000000013580C038)
- Class Loader List Monitor lock (0x000000013580C100)
- GC string table lock (0x000000013580C1C8)
- GC string table lock (0x000000013580C290)
- GC string table lock (0x000000013580C358)
- GC string table lock (0x000000013580C420)
- GC string table lock (0x000000013580C4E8)
- GC string table lock (0x000000013580C5B0)
- GC string table lock (0x000000013580C678)
- GC string table lock (0x000000013580C740)
- GC string table lock (0x000000013580C808)
- GC string table lock (0x000000013580C8D0)
- GC string table lock (0x000000013580C998)
- GC string table lock (0x000000013580CA60)
- MM_GCExtensions::gcStats lock (0x000000013580CB28)
- Unsafe memory allocation tracking lock (0x000000013580CBF0)
- JIT-PersistentAllocatorSmallBlockMonitor lock (0x000000013580CCB8)
- JIT-PersistentAllocatorLargeBlockMonitor lock (0x000000013580CD80)
- JIT-PersistentAllocatorSegmentMonitor lock (0x000000013580CE48)
- &(vm->verboseStateMutex) lock (0x000000013580CF10)
- VM thread list lock (0x000000013580CFD8): Flat locked by "[osthread]" (native thread ID:0x61D2FF), entry count 1
- VM exclusive access lock (0x000000013580D0A0)
- VM Runtime flags Mutex lock (0x000000013580D168)
- VM Extended method block flags Mutex lock (0x000000013580D230)
- Async event mutex lock (0x000000013580D2F8)
- JIT/GC class unload mutex lock (0x000000013580D3C0)
- VM bind native lock (0x000000013580D488)
- JCL cache mutex lock (0x000000013580D550)
- VM Statistics List Mutex lock (0x0000000135850418)
- Field Index Hashtable Mutex lock (0x00000001358504E0)
- JNI critical region mutex lock (0x00000001358505A8)
- VM class loader modules lock (0x0000000135850670)
- VM class loader blocks lock (0x0000000135850738)
- VM class table lock (0x0000000135850800)
- VM segment lock (0x00000001358508C8)
- VM JNI frame lock (0x0000000135850990)
- VM GC finalize main lock (0x0000000135850A58)
- VM GC finalize run finalization lock (0x0000000135850B20)
- VM GC process reference lock (0x0000000135850BE8)
- VM AOT runtime init lock (0x0000000135850CB0)
- OSR global buffer lock lock (0x0000000135850D78)
- JNI native library loading lock lock (0x0000000135850E40)
- VM state notification mutex lock (0x0000000135850F08)
- Wait mutex for constantDynamic during resolve lock (0x0000000135850FD0)
- CIF cache mutex lock (0x0000000135851098)
- CIF argument types mutex lock (0x0000000135851160)
- Wait mutex for allocating the upcall thunk memory lock (0x0000000135851228)
- Wait mutex for a new global reference lock (0x00000001358512F0)
- Cache for generating JNI wrappers lock (0x00000001358513B8)
- JNI Global to Local Memory lock (0x0000000135851480)

---

# Deadlocks

- **Inference**: Deadlock Detected
- **Threads Involved**:
  - Thread-1
  - Thread-0

---

# Thread Pool Info

- **Total Threads**: 45
- **Live Threads**: 45
- **Daemon Threads**: 36

---

# Threads

### JIT Compilation Thread-000
- **J9VMThread**: 0x00000001358B2B00
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x4
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D315
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x000000016FEF0000
  - To: 0x000000016FFF3000
  - Size: 0x103000
- **CPU Usage**: 0.034088000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-001 Suspended
- **J9VMThread**: 0x00000001358BF500
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x5
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D316
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x000000016FFFC000
  - To: 0x00000001700FF000
  - Size: 0x103000
- **CPU Usage**: 0.000011000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-002 Suspended
- **J9VMThread**: 0x00000001358C8300
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x6
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D317
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170108000
  - To: 0x000000017020B000
  - Size: 0x103000
- **CPU Usage**: 0.000008000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-003 Suspended
- **J9VMThread**: 0x00000001358D1100
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x7
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D318
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170214000
  - To: 0x0000000170317000
  - Size: 0x103000
- **CPU Usage**: 0.000009000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-004 Suspended
- **J9VMThread**: 0x00000001358DB100
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x8
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D319
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170320000
  - To: 0x0000000170423000
  - Size: 0x103000
- **CPU Usage**: 0.000007000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-005 Suspended
- **J9VMThread**: 0x00000001358E3F00
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x9
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D31A
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x000000017042C000
  - To: 0x000000017052F000
  - Size: 0x103000
- **CPU Usage**: 0.000008000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Compilation Thread-006 Suspended
- **J9VMThread**: 0x00000001358ECD00
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xA
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D31B
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170538000
  - To: 0x000000017063B000
  - Size: 0x103000
- **CPU Usage**: 0.000007000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT Diagnostic Compilation Thread-007 Suspended
- **J9VMThread**: 0x00000001358F6D00
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xB
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D31C
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170644000
  - To: 0x0000000170747000
  - Size: 0x103000
- **CPU Usage**: 0.000007000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### JIT-SamplerThread
- **J9VMThread**: 0x0000000135935300
- **State**: CW
- **Priority**: 10
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xC
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D31D
- **Native Priority**: 0xB
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170750000
  - To: 0x0000000170793000
  - Size: 0x43000
- **CPU Usage**: 0.018659000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### IProfiler
- **J9VMThread**: 0x0000000134809300
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xD
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D31E
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x000000017079C000
  - To: 0x00000001707BF000
  - Size: 0x23000
- **CPU Usage**: 0.019126000
- **Category**: JIT
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### Common-Cleaner
- **J9VMThread**: 0x0000000134039300
- **State**: CW
- **Priority**: 8
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x3
- **Is Daemon**: true
- **Class Loader**: No Java context classloader associated with this thread
- **Native Thread ID**: 0x61D31F
- **Native Priority**: 0x8
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00080101
- **Stack Range**:
  - From: 0x00000001707C8000
  - To: 0x000000017080B000
  - Size: 0x43000
- **CPU Usage**: 0.000132000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### Concurrent Mark Helper
- **J9VMThread**: 0x0000000134064100
- **State**: R
- **Priority**: 1
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xE
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D321
- **Native Priority**: 0x0
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170860000
  - To: 0x00000001708A3000
  - Size: 0x43000
- **CPU Usage**: 0.000022000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### GC Worker Threads

#### 1. Thread 0xF
- **J9VMThread**: 0x0000000134073100
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0xF
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D322
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x00000001708AC000
  - To: 0x00000001708EF000
  - Size: 0x43000
- **CPU Usage**: 0.001003000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 2. Thread 0x10
- **J9VMThread**: 0x000000013407DF00
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x10
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D323
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x00000001708F8000
  - To: 0x000000017093B000
  - Size: 0x43000
- **CPU Usage**: 0.000832000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 3. Thread 0x11
- **J9VMThread**: 0x0000000134088500
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x11
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D324
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170944000
  - To: 0x0000000170987000
  - Size: 0x43000
- **CPU Usage**: 0.000726000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 4. Thread 0x12
- **J9VMThread**: 0x0000000134093D00
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x12
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D325
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170990000
  - To: 0x00000001709D3000
  - Size: 0x43000
- **CPU Usage**: 0.000452000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 5. Thread 0x13
- **J9VMThread**: 0x000000013409E300
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x13
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D326
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x00000001709DC000
  - To: 0x0000000170A1F000
  - Size: 0x43000
- **CPU Usage**: 0.000867000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 6. Thread 0x14
- **J9VMThread**: 0x00000001340A8900
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x14
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D327
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170A28000
  - To: 0x0000000170A6B000
  - Size: 0x43000
- **CPU Usage**: 0.000779000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 7. Thread 0x15
- **J9VMThread**: 0x00000001340B4100
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x15
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D328
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170A74000
  - To: 0x0000000170AB7000
  - Size: 0x43000
- **CPU Usage**: 0.000506000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 8. Thread 0x16
- **J9VMThread**: 0x00000001340BE700
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x16
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D329
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x0000000170AC0000
  - To: 0x0000000170B03000
  - Size: 0x43000
- **CPU Usage**: 0.000720000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 9. Thread 0x17
- **J9VMThread**: 0x00000001340C8D00
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x17
- **Is Daemon**: Yes
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D32A
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**: From: 0x0000000170B0C000, To: 0x0000000170B4F000, Size: 0x43000
- **CPU Usage**: 0.000496000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 10. Thread 0x18
- **J9VMThread**: 0x00000001340D4500
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x18
- **Is Daemon**: Yes
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D32B
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**: From: 0x0000000170B58000, To: 0x0000000170B9B000, Size: 0x43000
- **CPU Usage**: 0.000456000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

#### 11. Thread 0x19
- **J9VMThread**: 0x00000001340DEB00
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x19
- **Is Daemon**: Yes
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D32C
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**: From: 0x0000000170BA4000, To: 0x0000000170BE7000, Size: 0x43000
- **CPU Usage**: 0.000428000
- **Category**: GC
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Finalizer thread
- **J9VMThread**: 0x0000000120009D00
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x1C
- **Is Daemon**: Yes
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D32E
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**: From: 0x0000000170C3C000, To: 0x0000000170C7F000, Size: 0x43000
- **CPU Usage**: 0.000391000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Attach API wait loop
- **J9VMThread**: 0x000000011780B700
- **State**: R
- **Priority**: 10
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x1D
- **Is Daemon**: Yes
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D32F
- **Native Priority**: 0xA
- **Native Policy**: UNKNOWN
- **VM State**: R
- **VM Thread Flags**: 0x000000a1
- **Stack Range**: From: 0x0000000170C88000, To: 0x0000000170CCB000, Size: 0x43000
- **CPU Usage**: 0.000035000
- **Category**: System-JVM
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-0
- **J9VMThread**: 0x0000000134108B00
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/lang/StringBuilder@0x0000000300078248 (Owned By: Thread-1)
- **Java Thread ID**: 0x1E
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D330
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170BF0000, To: 0x0000000170C33000, Size: 0x43000
- **CPU Usage**: 0.006821000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-1
- **J9VMThread**: 0x000000013594BD00
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/util/Hashtable@0x00000003000709F0 (Owned By: Thread-0)
- **Java Thread ID**: 0x1F
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D331
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170CD4000, To: 0x0000000170D17000, Size: 0x43000
- **CPU Usage**: 0.006389000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-2
- **J9VMThread**: 0x000000013594DD00
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/lang/StringBuilder@0x0000000300078248 (Owned By: Thread-1)
- **Java Thread ID**: 0x20
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D332
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170D20000, To: 0x0000000170D63000, Size: 0x43000
- **CPU Usage**: 0.006475000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-3
- **J9VMThread**: 0x0000000135959700
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/lang/StringBuilder@0x0000000300078248 (Owned By: Thread-1)
- **Java Thread ID**: 0x21
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D333
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170D6C000, To: 0x0000000170DAF000, Size: 0x43000
- **CPU Usage**: 0.006583000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-4
- **J9VMThread**: 0x0000000135960500
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/util/Random@0x0000000300070A30 (Owned By: Thread-3)
- **Java Thread ID**: 0x22
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D334
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170DB8000, To: 0x0000000170DFB000, Size: 0x43000
- **CPU Usage**: 0.006781000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-5
- **J9VMThread**: 0x0000000135968500
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/util/Random@0x0000000300070A30 (Owned By: Thread-3)
- **Java Thread ID**: 0x23
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D335
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170E04000, To: 0x0000000170E47000, Size: 0x43000
- **CPU Usage**: 0.007243000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

###  Thread-6
- **J9VMThread**: 0x0000000135970500
- **State**: B
- **Priority**: 5
- **Java Call Stack**:
  - Java callstack:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: Object: java/util/Random@0x0000000300070A30 (Owned By: Thread-5)
- **Java Thread ID**: 0x24
- **Is Daemon**: No
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D336
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: B
- **VM Thread Flags**: 0x00000201
- **Stack Range**: From: 0x0000000170E50000, To: 0x0000000170E93000, Size: 0x43000
- **CPU Usage**: 0.007381000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 1. ForkJoinPool.commonPool-worker-1
- **J9VMThread**: 0x0000000134837700
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x26
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D338
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000170EE8000
  - To: 0x0000000170F2B000
  - Size: 0x43000
- **CPU Usage**: 0.000273000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 2. ForkJoinPool.commonPool-worker-2
- **J9VMThread**: 0x000000013402A500
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x27
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D339
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000170F34000
  - To: 0x0000000170F77000
  - Size: 0x43000
- **CPU Usage**: 0.000260000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 3. ForkJoinPool.commonPool-worker-3
- **J9VMThread**: 0x0000000134129B00
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x28
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33A
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x000a0001
- **Stack Range**:
  - From: 0x0000000170F80000
  - To: 0x0000000170FC3000
  - Size: 0x43000
- **CPU Usage**: 0.000239000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 4. ForkJoinPool.commonPool-worker-4
- **J9VMThread**: 0x000000013597D500
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x29
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33B
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000170FCC000
  - To: 0x000000017100F000
  - Size: 0x43000
- **CPU Usage**: 0.000179000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 5. ForkJoinPool.commonPool-worker-5
- **J9VMThread**: 0x000000013413A700
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2A
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33C
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000171018000
  - To: 0x000000017105B000
  - Size: 0x43000
- **CPU Usage**: 0.000135000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 6. ForkJoinPool.commonPool-worker-6
- **J9VMThread**: 0x000000012001EF00
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2B
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33D
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000171064000
  - To: 0x00000001710A7000
  - Size: 0x43000
- **CPU Usage**: 0.000066000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 7. ForkJoinPool.commonPool-worker-8
- **J9VMThread**: 0x0000000134146100
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2C
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33E
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x00000001710B0000
  - To: 0x00000001710F3000
  - Size: 0x43000
- **CPU Usage**: 0.000116000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 8. ForkJoinPool.commonPool-worker-7
- **J9VMThread**: 0x000000012080C500
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2D
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D33F
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x00000001710FC000
  - To: 0x000000017113F000
  - Size: 0x43000
- **CPU Usage**: 0.000069000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 9. ForkJoinPool.commonPool-worker-10
- **J9VMThread**: 0x000000013414C700
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2F
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D341
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000171194000
  - To: 0x00000001711D7000
  - Size: 0x43000
- **CPU Usage**: 0.000088000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 10. ForkJoinPool.commonPool-worker-9
- **J9VMThread**: 0x000000012002C700
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x2E
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D340
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x0000000171148000
  - To: 0x000000017118B000
  - Size: 0x43000
- **CPU Usage**: 0.000053000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### 11. ForkJoinPool.commonPool-worker-11
- **J9VMThread**: 0x0000000134151F00
- **State**: P
- **Priority**: 5
- **Java Call Stack**:
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x30
- **Is Daemon**: true
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D342
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: P
- **VM Thread Flags**: 0x00020001
- **Stack Range**:
  - From: 0x00000001711E2000
  - To: 0x0000000171225000
  - Size: 0x43000
- **CPU Usage**: 0.000053000
- **Category**: Application
- **Heap Allocation**: 0
- **Thread Type**: Platform

---

### DestroyJavaVM helper thread
- **J9VMThread**: 0x000000013589E500
- **State**: R
- **Priority**: 5
- **Java Call Stack**:
  - No Java call stack associated with this thread
  - No native callstack available for this thread
- **Native Call Stack**: None
- **Blocked On**: None
- **Java Thread ID**: 0x31
- **Is Daemon**: false
- **Class Loader**: jdk/internal/loader/ClassLoaders$AppClassLoader(0x0000000300062ED0)
- **Native Thread ID**: 0x61D2FE
- **Native Priority**: 0x5
- **Native Policy**: UNKNOWN
- **VM State**: CW
- **VM Thread Flags**: 0x00000001
- **Stack Range**:
  - From: 0x000000016FE58000
  - To: 0x000000016FE9B000
  - Size: 0x43000
- **CPU Usage**: 0.225897000
- **Category**: Application
- **Heap Allocation**: 4160
- **Thread Type**: Platform

---

### CPU Usage Summary
- **Warning**: Warning: to get more accurate CPU times for the GC, the option `-XX:-ReduceCPUMonitorOverhead` can be used. See the user guide for more information.
- **All JVM attached threads**: 0.371868000 secs
- **SystemJVM**: 0.278519000 secs
- **GC**: 0.007365000 secs
- **JIT**: 0.071930000 secs
- **Application**: 0.093349000 secs
