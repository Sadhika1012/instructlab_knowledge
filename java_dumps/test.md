## Subcomponent Dump Routine

**Trigger:** User event

**Date and Time:** 2025/02/19 at 21:26:26:598

**Timezones:** UTC-8 (PST)

**Javacore Filename:** /root/AI/slowthr/javacore.20250219.212626.1781319.0003.txt

**Request Flags:** 0x41 (exclusive+preempt)

**Prep State:** 0x84 (exclusive_vm_access+trace_disabled)

# GP Info

**OS Version:** Linux 5.15.0-131-generic

**Processor Architecture:** amd64

**CPU Count:** 8

## Environment Info

**VM Version:** 20241212_83587

**JIT Version:** tr.open_20241212_113905_32d7c6c9a17

**OMR Version:** ab5c961de_CMPRSS

**1CIIBMVERSION:** dd9cff8

**Vendor:** IBM Corporation

**Running in Container:** FALSE

**cgroups Support:** TRUE

**JVM Start Time:** 2025/02/19 at 21:25:03:320

**Process ID:** 1781319 (0x1B2E47)

**Command Line:** /root/JAVA8SR8FP40/bin/java XYZExample

**1CIJAVAHOMEDIR Java Home Dir::** /root/JAVA8SR8FP40/jre

**Java DLL Directory:** /root/JAVA8SR8FP40/jre/bin

**System Classpath:** /root/JAVA8SR8FP40/jre/lib/amd64/compressedrefs/jclSC180/vm.jar;/root/JAVA8SR8FP40/jre/lib/se-service.jar;/root/JAVA8SR8FP40/jre/lib/math.jar;/root/JAVA8SR8FP40/jre/lib/ibmorb.jar;/root/JAVA8SR8FP40/jre/lib/ibmorbapi.jar;/root/JAVA8SR8FP40/jre/lib/ibmcfw.jar;/root/JAVA8SR8FP40/jre/lib/ibmpkcs.jar;/root/JAVA8SR8FP40/jre/lib/ibmcertpathfw.jar;/root/JAVA8SR8FP40/jre/lib/ibmjgssfw.jar;/root/JAVA8SR8FP40/jre/lib/ibmjssefw.jar;/root/JAVA8SR8FP40/jre/lib/ibmsaslfw.jar;/root/JAVA8SR8FP40/jre/lib/ibmjcefw.jar;/root/JAVA8SR8FP40/jre/lib/ibmjgssprovider.jar;/root/JAVA8SR8FP40/jre/lib/ibmjsseprovider2.jar;/root/JAVA8SR8FP40/jre/lib/ibmcertpathprovider.jar;/root/JAVA8SR8FP40/jre/lib/xmldsigfw.jar;/root/JAVA8SR8FP40/jre/lib/xml.jar;/root/JAVA8SR8FP40/jre/lib/charsets.jar;/root/JAVA8SR8FP40/jre/lib/resources.jar;/root/JAVA8SR8FP40/jre/lib/rt.jar;/root/JAVA8SR8FP40/jre/lib/dataaccess.jar;

#### User Arguments

- **-Xoptionsfile:** /root/JAVA8SR8FP40/jre/lib/amd64/compressedrefs/options.default
- **-Xlockword:mode:** default,noLockword=java/lang/String,noLockword=java/util/MapEntry,noLockword=java/util/HashMap$Entry,noLockword=org/apache/harmony/luni/util/ModifiedMap$Entry,noLockword=java/util/Hashtable$Entry,noLockword=java/lang/invoke/MethodType,noLockword=java/lang/invoke/MethodHandle,noLockword=java/lang/invoke/CollectHandle,noLockword=java/lang/invoke/ConstructorHandle,noLockword=java/lang/invoke/ConvertHandle,noLockword=java/lang/invoke/ArgumentConversionHandle,noLockword=java/lang/invoke/AsTypeHandle,noLockword=java/lang/invoke/ExplicitCastHandle,noLockword=java/lang/invoke/FilterReturnHandle,noLockword=java/lang/invoke/DirectHandle,noLockword=java/lang/invoke/ReceiverBoundHandle,noLockword=java/lang/invoke/DynamicInvokerHandle,noLockword=java/lang/invoke/FieldHandle,noLockword=java/lang/invoke/FieldGetterHandle,noLockword=java/lang/invoke/FieldSetterHandle,noLockword=java/lang/invoke/StaticFieldGetterHandle,noLockword=java/lang/invoke/StaticFieldSetterHandle,noLockword=java/lang/invoke/IndirectHandle,noLockword=java/lang/invoke/InterfaceHandle,noLockword=java/lang/invoke/VirtualHandle,noLockword=java/lang/invoke/PrimitiveHandle,noLockword=java/lang/invoke/InvokeExactHandle,noLockword=java/lang/invoke/InvokeGenericHandle,noLockword=java/lang/invoke/VarargsCollectorHandle,noLockword=java/lang/invoke/ThunkTuple
- **-Djava.lang.stringBuffer.growAggressively:** false
- **-XX:+OriginalJDK8HeapSizeCompatibilityMode:** 
- **-XX:+LegacyXlogOption:** 
- **-XX:+EnsureHashed:** java/lang/Class,java/lang/Thread
- **-XX:+EnableExtendedHCR:** 
- **-Xjcl:** jclse29
- **-Dcom.ibm.oti.vm.bootstrap.library.path:** /root/JAVA8SR8FP40/jre/lib/amd64/compressedrefs:/root/JAVA8SR8FP40/jre/lib/amd64
- **-Dsun.boot.library.path:** /root/JAVA8SR8FP40/jre/lib/amd64/compressedrefs:/root/JAVA8SR8FP40/jre/lib/amd64
- **-Djava.library.path:** /root/JAVA8SR8FP40/jre/lib/amd64/compressedrefs:/root/JAVA8SR8FP40/jre/lib/amd64:/usr/lib64:/usr/lib
- **-Djava.home:** /root/JAVA8SR8FP40/jre
- **-Djava.ext.dirs:** /root/JAVA8SR8FP40/jre/fips140-2/lib/ext:/root/JAVA8SR8FP40/jre/lib/ext
- **-Duser.dir:** /root/AI/slowthr
- **-Djava.class.path:** .
- **-Dsun.java.command:** XYZExample
- **-Dsun.java.launcher:** SUN_STANDARD
- **-Dsun.java.launcher.pid:** 1781319

#### User Limits

- **RLIMIT_AS:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_CORE:**
  - **soft_limit:** 0
  - **hard_limit:** unlimited

- **RLIMIT_CPU:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_DATA:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_FSIZE:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_LOCKS:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_MEMLOCK:**
  - **soft_limit:** 2095632384
  - **hard_limit:** 2095632384

- **RLIMIT_NOFILE:**
  - **soft_limit:** 1048576
  - **hard_limit:** 1048576

- **RLIMIT_NPROC:**
  - **soft_limit:** 63518
  - **hard_limit:** 63518

- **RLIMIT_RSS:**
  - **soft_limit:** unlimited
  - **hard_limit:** unlimited

- **RLIMIT_STACK:**
  - **soft_limit:** 8388608
  - **hard_limit:** unlimited

- **RLIMIT_MSGQUEUE:**
  - **soft_limit:** 819200
  - **hard_limit:** 819200

- **RLIMIT_NICE:**
  - **soft_limit:** 0
  - **hard_limit:** 0

- **RLIMIT_RTPRIO:**
  - **soft_limit:** 0
  - **hard_limit:** 0

- **RLIMIT_SIGPENDING:**
  - **soft_limit:** 63518
  - **hard_limit:** 63518


#### Environment Variables

- **SHELL:** /bin/bash
- **PWD:** /root/AI/slowthr
- **LOGNAME:** root
- **XDG_SESSION_TYPE:** tty
- **MOTD_SHOWN:** pam
- **HOME:** /root
- **LANG:** C.UTF-8
- **LS_COLORS:** rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
- **SSH_CONNECTION:** 9.43.56.229 57870 9.30.245.182 22
- **LESSCLOSE:** /usr/bin/lesspipe %s %s
- **XDG_SESSION_CLASS:** user
- **TERM:** xterm-256color
- **LESSOPEN:** | /usr/bin/lesspipe %s
- **USER:** root
- **SHLVL:** 1
- **XDG_SESSION_ID:** 4934
- **LC_CTYPE:** C.UTF-8
- **XDG_RUNTIME_DIR:** /run/user/0
- **SSH_CLIENT:** 9.43.56.229 57870 22
- **DEBUGINFOD_URLS:** 
- **XDG_DATA_DIRS:** /usr/local/share:/usr/share:/var/lib/snapd/desktop
- **PATH:** /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
- **DBUS_SESSION_BUS_ADDRESS:** unix:path=/run/user/0/bus
- **SSH_TTY:** /dev/pts/0
- **_:** /root/JAVA8SR8FP40/bin/java
- **OLDPWD:** /root
- **IBM_JAVA_COMMAND_LINE:** /root/JAVA8SR8FP40/bin/java XYZExample
- **OPENJ9_JAVA_COMMAND_LINE:** /root/JAVA8SR8FP40/bin/java XYZExample
- **System Information:** 
- **Hypervisor name:** KVM
- **/proc/sys/kernel/core_pattern:** |/usr/share/apport/apport -p%p -s%s -c%c -d%d -P%P -u%u -g%g -- %E
- **/proc/sys/kernel/core_uses_pid:** 1

#### CPU Information

- **Physical CPUs:** 8
- **Online CPUs:** 8
- **Bound CPUs:** 8
- **Active CPUs:** 0
- **Target CPUs:** 8
- **CPU features (JIT):** fpu cx8 cmov mmx sse sse2 sse3 ssse3 fma sse4_1 sse4_2 popcnt aesni osxsave avx avx2
- **CPU features (AOT):** fpu cx8 cmov mmx sse sse2 sse3 ssse3 fma sse4_1 sse4_2 popcnt aesni osxsave avx avx2
- **subsystem:** memory
- **cgroup name:** /user.slice/user-0.slice/session-4934.scope
- **Memory Limit:** Not Set
- **Swap Limit:** Not Set
- **Memory Usage:** 35610624 bytes
- **Swap Usage:** 0 bytes
- **Approached memory limit count:** 0
- **Reached memory limit count:** 0
- **Approached swap limit count:** 0
- **Swap alloc failed count:** 0

## Native Memory Info

**JRE:** 1077194528 bytes

**VM:** 802085736 bytes

**Classes:** 4667304 bytes

**Memory Manager (GC):** 549591736 bytes

**Java Heap:** 536932352 bytes

**Other:** 1299808 bytes

**Threads:** 38471512 bytes

**Java Stack:** 1409040 bytes

**Native Stack:** 36306944 bytes

**Trace:** 1202384 bytes

**JVMTI:** 17776 bytes

**JNI:** 36688 bytes

**Port Library:** 206647272 bytes

**Unused <32bit allocation regions:** 206635784 bytes

**JIT:** 273806328 bytes

**JIT Code Cache:** 268435456 bytes

**JIT Data Cache:** 2097152 bytes

**Class Libraries:** 1302464 bytes

**VM Class Libraries:** 1302464 bytes

**sun.misc.Unsafe:** 2656 bytes

**Direct Byte Buffers:** 528 bytes

#### heapData

- **Object Memory:**
  - **TotalMemory:** 8388608
  - **MemoryInUse:** 1857664
  - **MemoryFree:** 6530944
  - **heapSpaces:**
    - **Item 1:**
      - **id:** 0x00007FBAD0093BE0
      - **spaceType:** Generational

    - **Item 2:**
      - **id:** 0x00007FBAD0094D70
      - **start:** 0x00000000E0000000
      - **end:** 0x00000000E0600000
      - **size:** 0x0000000000600000
      - **spaceType:** Generational/Tenured

    - **Item 3:**
      - **id:** 0x00007FBAD00944D0
      - **start:** 0x00000000FFE00000
      - **end:** 0x00000000FFF00000
      - **size:** 0x0000000000100000
      - **spaceType:** Generational/Nursery

    - **Item 4:**
      - **id:** 0x00007FBAD0093CB0
      - **start:** 0x00000000FFF00000
      - **end:** 0x0000000100000000
      - **size:** 0x0000000000100000
      - **spaceType:** Generational/Nursery



#### segments

- **Internal Memory:**
  - **segments:**
    - **Item 1:**
      - **segment:** 0x00007FBAD00715F0
      - **start:** 0x00007FBACE2E1000
      - **alloc:** 0x00007FBACE3E0FE0
      - **end:** 0x00007FBACE3E1000
      - **type:** 0x10800440
      - **size:** 0x0000000000100000

    - **Item 2:**
      - **segment:** 0x00007FBAD0071528
      - **start:** 0x00007FBACE3E1000
      - **alloc:** 0x00007FBACE45FC60
      - **end:** 0x00007FBACE4E1000
      - **type:** 0x10800440
      - **size:** 0x0000000000100000

    - **Item 3:**
      - **segment:** 0x00007FBAD0071398
      - **start:** 0x00007FBACFCE9030
      - **alloc:** 0x00007FBACFD23E40
      - **end:** 0x00007FBACFDE9030
      - **type:** 0x00800040
      - **size:** 0x0000000000100000

  - **memoryStats:**
    - **TotalMemory:** 3145728
    - **MemoryInUse:** 1808976
    - **MemoryFree:** 1336752


- **Class Memory:**
  - **segments:**
    - **Item 1:**
      - **segment:** 0x00007FBAD043E630
      - **start:** 0x00007FBAD04877F0
      - **alloc:** 0x00007FBAD048C4A0
      - **end:** 0x00007FBAD04A77F0
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 2:**
      - **segment:** 0x00007FBAD043E568
      - **start:** 0x0000000000136D38
      - **alloc:** 0x0000000000137158
      - **end:** 0x0000000000137158
      - **type:** 0x00010040
      - **size:** 0x0000000000000420

    - **Item 3:**
      - **segment:** 0x00007FBAD043E4A0
      - **start:** 0x00007FBAD031F720
      - **alloc:** 0x00007FBAD031F900
      - **end:** 0x00007FBAD031F900
      - **type:** 0x00020040
      - **size:** 0x00000000000001E0

    - **Item 4:**
      - **segment:** 0x00007FBAD043E3D8
      - **start:** 0x00000000001A3678
      - **alloc:** 0x00000000001AB678
      - **end:** 0x00000000001AB678
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 5:**
      - **segment:** 0x00007FBAD043E310
      - **start:** 0x000000000019B628
      - **alloc:** 0x00000000001A3628
      - **end:** 0x00000000001A3628
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 6:**
      - **segment:** 0x00007FBAD043E248
      - **start:** 0x00007FBAD0464D80
      - **alloc:** 0x00007FBAD0483A50
      - **end:** 0x00007FBAD0484D80
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 7:**
      - **segment:** 0x00007FBAD043E180
      - **start:** 0x00000000001935D8
      - **alloc:** 0x000000000019B5D8
      - **end:** 0x000000000019B5D8
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 8:**
      - **segment:** 0x00007FBAD043E0B8
      - **start:** 0x000000000018B588
      - **alloc:** 0x0000000000193588
      - **end:** 0x0000000000193588
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 9:**
      - **segment:** 0x00007FBAD043DFF0
      - **start:** 0x0000000000183538
      - **alloc:** 0x000000000018B538
      - **end:** 0x000000000018B538
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 10:**
      - **segment:** 0x00007FBAD043DF28
      - **start:** 0x00007FBAD043E740
      - **alloc:** 0x00007FBAD043EC60
      - **end:** 0x00007FBAD045E740
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 11:**
      - **segment:** 0x00007FBA8400D5A0
      - **start:** 0x000000000017B4E8
      - **alloc:** 0x00000000001834E8
      - **end:** 0x00000000001834E8
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 12:**
      - **segment:** 0x00007FBA8400D4D8
      - **start:** 0x00007FBA8405A060
      - **alloc:** 0x00007FBA84077350
      - **end:** 0x00007FBA8407A060
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 13:**
      - **segment:** 0x00007FBA8400D410
      - **start:** 0x0000000000170440
      - **alloc:** 0x0000000000178440
      - **end:** 0x0000000000178440
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 14:**
      - **segment:** 0x00007FBA8400D348
      - **start:** 0x00000000001683F0
      - **alloc:** 0x00000000001703F0
      - **end:** 0x00000000001703F0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 15:**
      - **segment:** 0x00007FBA8400D280
      - **start:** 0x00000000001603A0
      - **alloc:** 0x00000000001683A0
      - **end:** 0x00000000001683A0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 16:**
      - **segment:** 0x00007FBA8400D1B8
      - **start:** 0x00007FBA8402F4E0
      - **alloc:** 0x00007FBA8404F0E0
      - **end:** 0x00007FBA8404F4E0
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 17:**
      - **segment:** 0x00007FBA8400D0F0
      - **start:** 0x0000000000158350
      - **alloc:** 0x0000000000160350
      - **end:** 0x0000000000160350
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 18:**
      - **segment:** 0x00007FBA8400D028
      - **start:** 0x0000000000149288
      - **alloc:** 0x0000000000151288
      - **end:** 0x0000000000151288
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 19:**
      - **segment:** 0x00007FBA8400CF60
      - **start:** 0x0000000000141238
      - **alloc:** 0x0000000000149238
      - **end:** 0x0000000000149238
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 20:**
      - **segment:** 0x00007FBA8400CE98
      - **start:** 0x00007FBA8400D6B0
      - **alloc:** 0x00007FBA8402D4D0
      - **end:** 0x00007FBA8402D6B0
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 21:**
      - **segment:** 0x00007FBAD0321D70
      - **start:** 0x00000000001391E8
      - **alloc:** 0x00000000001411E8
      - **end:** 0x00000000001411E8
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 22:**
      - **segment:** 0x00007FBAD0321CA8
      - **start:** 0x000000000012D598
      - **alloc:** 0x0000000000135598
      - **end:** 0x0000000000135598
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 23:**
      - **segment:** 0x00007FBAD0321BE0
      - **start:** 0x00007FBAD0372E60
      - **alloc:** 0x00007FBAD0392D30
      - **end:** 0x00007FBAD0392E60
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 24:**
      - **segment:** 0x00007FBAD0321B18
      - **start:** 0x0000000000107548
      - **alloc:** 0x000000000010F548
      - **end:** 0x000000000010F548
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 25:**
      - **segment:** 0x00007FBAD0321A50
      - **start:** 0x00000000000FF4F8
      - **alloc:** 0x00000000001074F8
      - **end:** 0x00000000001074F8
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 26:**
      - **segment:** 0x00007FBAD0321988
      - **start:** 0x00000000000F74A8
      - **alloc:** 0x00000000000FF4A8
      - **end:** 0x00000000000FF4A8
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 27:**
      - **segment:** 0x00007FBAD03218C0
      - **start:** 0x00007FBAD0343170
      - **alloc:** 0x00007FBAD0362FE8
      - **end:** 0x00007FBAD0363170
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 28:**
      - **segment:** 0x00007FBAD03217F8
      - **start:** 0x00000000000EF458
      - **alloc:** 0x00000000000F7458
      - **end:** 0x00000000000F7458
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 29:**
      - **segment:** 0x00007FBAD0321730
      - **start:** 0x00000000000E0370
      - **alloc:** 0x00000000000E8370
      - **end:** 0x00000000000E8370
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 30:**
      - **segment:** 0x00007FBAD0321668
      - **start:** 0x00007FBAD0321E80
      - **alloc:** 0x00007FBAD0341DA0
      - **end:** 0x00007FBAD0341E80
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 31:**
      - **segment:** 0x00007FBAD02DA770
      - **start:** 0x00000000000D8320
      - **alloc:** 0x00000000000E0320
      - **end:** 0x00000000000E0320
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 32:**
      - **segment:** 0x00007FBAD02DA6A8
      - **start:** 0x00000000000D02D0
      - **alloc:** 0x00000000000D82D0
      - **end:** 0x00000000000D82D0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 33:**
      - **segment:** 0x00007FBAD02DA5E0
      - **start:** 0x00000000000C8280
      - **alloc:** 0x00000000000D0280
      - **end:** 0x00000000000D0280
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 34:**
      - **segment:** 0x00007FBAD02DA518
      - **start:** 0x00007FBAD02FE740
      - **alloc:** 0x00007FBAD031E358
      - **end:** 0x00007FBAD031E740
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 35:**
      - **segment:** 0x00007FBAD02DA450
      - **start:** 0x00000000000C0230
      - **alloc:** 0x00000000000C8230
      - **end:** 0x00000000000C8230
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 36:**
      - **segment:** 0x00007FBAD02DA388
      - **start:** 0x00000000000B81E0
      - **alloc:** 0x00000000000C01E0
      - **end:** 0x00000000000C01E0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 37:**
      - **segment:** 0x00007FBAD02DA2C0
      - **start:** 0x00007FBAD02DD530
      - **alloc:** 0x00007FBAD02FD208
      - **end:** 0x00007FBAD02FD530
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 38:**
      - **segment:** 0x00007FBAD02DA1F8
      - **start:** 0x00000000000B0190
      - **alloc:** 0x00000000000B8190
      - **end:** 0x00000000000B8190
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 39:**
      - **segment:** 0x00007FBAD02DA130
      - **start:** 0x00000000000A8140
      - **alloc:** 0x00000000000B0140
      - **end:** 0x00000000000B0140
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 40:**
      - **segment:** 0x00007FBAD02DA068
      - **start:** 0x00000000000A00F0
      - **alloc:** 0x00000000000A80F0
      - **end:** 0x00000000000A80F0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 41:**
      - **segment:** 0x00007FBAD02728C0
      - **start:** 0x00007FBAD02B9660
      - **alloc:** 0x00007FBAD02D90F0
      - **end:** 0x00007FBAD02D9660
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 42:**
      - **segment:** 0x00007FBAD02727F8
      - **start:** 0x00000000000980A0
      - **alloc:** 0x00000000000A00A0
      - **end:** 0x00000000000A00A0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 43:**
      - **segment:** 0x00007FBAD0272730
      - **start:** 0x0000000000090050
      - **alloc:** 0x0000000000098050
      - **end:** 0x0000000000098050
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 44:**
      - **segment:** 0x00007FBAD0272668
      - **start:** 0x00007FBAD0293EA0
      - **alloc:** 0x00007FBAD02B3D68
      - **end:** 0x00007FBAD02B3EA0
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 45:**
      - **segment:** 0x00007FBAD02725A0
      - **start:** 0x0000000000088000
      - **alloc:** 0x0000000000090000
      - **end:** 0x0000000000090000
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 46:**
      - **segment:** 0x00007FBAD02724D8
      - **start:** 0x000000000007FFB0
      - **alloc:** 0x0000000000087FB0
      - **end:** 0x0000000000087FB0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 47:**
      - **segment:** 0x00007FBAD0272410
      - **start:** 0x0000000000077F60
      - **alloc:** 0x000000000007FF60
      - **end:** 0x000000000007FF60
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 48:**
      - **segment:** 0x00007FBAD0272348
      - **start:** 0x00007FBAD0273960
      - **alloc:** 0x00007FBAD0292918
      - **end:** 0x00007FBAD0293960
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 49:**
      - **segment:** 0x00007FBAD0272280
      - **start:** 0x000000000006FF10
      - **alloc:** 0x0000000000077F10
      - **end:** 0x0000000000077F10
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 50:**
      - **segment:** 0x00007FBAD02721B8
      - **start:** 0x0000000000067EC0
      - **alloc:** 0x000000000006FEC0
      - **end:** 0x000000000006FEC0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 51:**
      - **segment:** 0x00007FBAD00724A0
      - **start:** 0x000000000005FE70
      - **alloc:** 0x0000000000067E70
      - **end:** 0x0000000000067E70
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 52:**
      - **segment:** 0x00007FBAD00723D8
      - **start:** 0x00007FBAD0252070
      - **alloc:** 0x00007FBAD0271790
      - **end:** 0x00007FBAD0272070
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 53:**
      - **segment:** 0x00007FBAD0072310
      - **start:** 0x0000000000057E20
      - **alloc:** 0x000000000005FE20
      - **end:** 0x000000000005FE20
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 54:**
      - **segment:** 0x00007FBAD0072248
      - **start:** 0x000000000004FDD0
      - **alloc:** 0x0000000000057DD0
      - **end:** 0x0000000000057DD0
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 55:**
      - **segment:** 0x00007FBAD0072180
      - **start:** 0x00007FBAD022E960
      - **alloc:** 0x00007FBAD024DC28
      - **end:** 0x00007FBAD024E960
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

    - **Item 56:**
      - **segment:** 0x00007FBAD00720B8
      - **start:** 0x0000000000047D80
      - **alloc:** 0x000000000004FD80
      - **end:** 0x000000000004FD80
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 57:**
      - **segment:** 0x00007FBAD0071FF0
      - **start:** 0x00007FBAD60597D0
      - **alloc:** 0x00007FBAD6059E28
      - **end:** 0x00007FBAD6059E28
      - **type:** 0x04020104
      - **size:** 0x0000000000000688

    - **Item 58:**
      - **segment:** 0x00007FBAD0071F28
      - **start:** 0x00007FBAD6059170
      - **alloc:** 0x00007FBAD6059798
      - **end:** 0x00007FBAD6059798
      - **type:** 0x04200104
      - **size:** 0x0000000000000658

    - **Item 59:**
      - **segment:** 0x00007FBAD0071E60
      - **start:** 0x000000000003FD30
      - **alloc:** 0x0000000000047D30
      - **end:** 0x0000000000047D30
      - **type:** 0x00010040
      - **size:** 0x0000000000008000

    - **Item 60:**
      - **segment:** 0x00007FBAD0071D98
      - **start:** 0x00007FBACE188030
      - **alloc:** 0x00007FBACE1A6C88
      - **end:** 0x00007FBACE1A8030
      - **type:** 0x00020040
      - **size:** 0x0000000000020000

  - **memoryStats:**
    - **TotalMemory:** 3511008
    - **MemoryInUse:** 3232472
    - **MemoryFree:** 278536


- **JIT Code Cache:**
  - **segments:**
    - **Item 1:**
      - **segment:** 0x00007FBAD00B53B8
      - **start:** 0x00007FBA59000000
      - **alloc:** 0x00007FBA59009F10
      - **end:** 0x00007FBA69000000
      - **type:** 0x00000068
      - **size:** 0x0000000010000000

  - **memoryStats:**
    - **TotalMemory:** 268435456
    - **MemoryInUse:** 40720
    - **MemoryFree:** 268394736
    - **AllocationLimit:** 268435456


- **JIT Data Cache:**
  - **segments:**
    - **Item 1:**
      - **segment:** 0x00007FBAD00B5848
      - **start:** 0x00007FBACDF47000
      - **alloc:** 0x00007FBACE147000
      - **end:** 0x00007FBACE147000
      - **type:** 0x10000448
      - **size:** 0x0000000000200000

  - **memoryStats:**
    - **TotalMemory:** 2097152
    - **MemoryInUse:** 2097152
    - **MemoryFree:** 0
    - **AllocationLimit:** 402653184



#### gcHistory

- 05:25:03:624636670 GMT j9mm.134 -   Allocation failure end: newspace=439968/2097152 oldspace=6178456/6291456 loa=315392/315392
- 05:25:03:624626021 GMT j9mm.470 -   Allocation failure cycle end: newspace=440000/2097152 oldspace=6178456/6291456 loa=315392/315392
- 05:25:03:624606660 GMT j9mm.468 -   Cycle End: type 2 approximateFreeMemorySize 6618456
- 05:25:03:624570700 GMT j9mm.560 -   LocalGC end: rememberedsetoverflow=0 causedrememberedsetoverflow=0 scancacheoverflow=0 failedflipcount=0 failedflipbytes=0 failedtenurecount=0 failedtenurebytes=0 flipcount=5649 flipbytes=451872 newspace=440000/2097152 oldspace=6178456/6291456 loa=315392/315392 tenureage=0
- 05:25:03:624455630 GMT j9mm.140 -   Tilt ratio: 50
- 05:25:03:622227632 GMT j9mm.64 -   LocalGC start: globalcount=0 scavengecount=1 weakrefs=0 soft=0 phantom=0 finalizers=0
- 05:25:03:622184762 GMT j9mm.467 -   Cycle Start: type 2 approximateFreeMemorySize 6178456
- 05:25:03:621943212 GMT j9mm.135 -   Exclusive access: exclusiveaccessms=0.156 meanexclusiveaccessms=0.156 threads=0 lastthreadtid=0x000000000001A3A8 beatenbyotherthread=0
- 05:25:03:621940222 GMT j9mm.469 -   Allocation failure cycle start: newspace=0/2097152 oldspace=6178456/6291456 loa=315392/315392 requestedbytes=32
- 05:25:03:621938842 GMT j9mm.133 -   Allocation failure start: newspace=0/2097152 oldspace=6178456/6291456 loa=315392/315392 requestedbytes=32

## Locks Info

**Total Monitors:** 1

#### Monitor Pool

###  - **System Monitor Identifier:** 0x00007FBAD0637F58
  - **Inflated Monitor Identifier:** 0x00007FBAD0637FD8
  - **Objects:**
    - **Item 1:**
      - **Object:** java/lang/Object
      - **Address:** 0x00000000FFE0D4A0
      - **Locked By:**

      - **Entry Count:** 0
      - **Waiting Threads:**
        - Thread-2
        - Thread-3
        - Thread-6
        - Thread-7
        - Thread-8
        - Thread-9
        - Thread-10
        - Thread-11
        - Thread-12
        - Thread-13
        - Thread-14
        - Thread-15
        - Thread-17
        - Thread-18
        - Thread-19
        - Thread-20
        - Thread-21
        - Thread-22
        - Thread-23
        - Thread-24
        - Thread-25
        - Thread-26
        - Thread-27
        - Thread-28
        - Thread-29
        - Thread-30
        - Thread-31
        - Thread-32
        - Thread-33
        - Thread-34
        - Thread-35
        - Thread-36
        - Thread-37
        - Thread-39
        - Thread-40
        - Thread-41
        - Thread-42
        - Thread-43
        - Thread-44
        - Thread-45
        - Thread-46
        - Thread-47
        - Thread-48
        - Thread-49
        - Thread-50
        - Thread-51
        - Thread-52
        - Thread-53
        - Thread-55
        - Thread-56
        - Thread-57
        - Thread-58
        - Thread-59
        - Thread-60
        - Thread-61
        - Thread-62
        - Thread-63
        - Thread-64
        - Thread-65
        - Thread-66
        - Thread-67
        - Thread-68
        - Thread-69
        - Thread-70
        - Thread-71
        - Thread-72
        - Thread-73
        - Thread-74
        - Thread-75
        - Thread-76
        - Thread-77
        - Thread-78
        - Thread-79
        - Thread-80
        - Thread-81
        - Thread-82
        - Thread-83
        - Thread-84
        - Thread-85
        - Thread-86
        - Thread-87
        - Thread-88
        - Thread-90
        - Thread-91
        - Thread-92
        - Thread-93
        - Thread-94
        - Thread-95
        - Thread-96
        - Thread-97
        - Thread-99


#### Registered Monitors

- Thread global lock (0x00007FBAD0004CA8):
- &(PPG_mem_mem32_subAllocHeapMem32.monitor) lock (0x00007FBAD0004D58):
- NLS hash table lock (0x00007FBAD0004E08):
- cgroup monitor lock (0x00007FBAD0004EB8):
- portLibrary_omrsig_registerHandler_monitor lock (0x00007FBAD0004F68):
- portLibrary_omrsig_asynch_reporter_shutdown_monitor lock (0x00007FBAD0005018):
- portLibrary_omrsig_async_monitor lock (0x00007FBAD00050C8):
- &(PHD_vendorMonitor) lock (0x00007FBAD0005178):
- &(vm->systemPropertiesMutex) lock (0x00007FBAD0005228):
- Hook Interface lock (0x00007FBAD00052D8):
- Hook Interface lock (0x00007FBAD0005388):
- OMR VM list mutex lock (0x00007FBAD0005438):
- OMR VM thread list mutex lock (0x00007FBAD00054E8):
- dump tokens mutex lock (0x00007FBAD0005598):
- VM hidden fields list lock (0x00007FBAD0005648):
- MM_SublistPool lock (0x00007FBAD00056F8):
- Hook Interface lock (0x00007FBAD00057A8):
- Hook Interface lock (0x00007FBAD0005858):
- GCExtensions::gcExclusiveAccessMutex lock (0x00007FBAD0005908):
- GCExtensions::_lightweightNonReentrantLockPoolMutex lock (0x00007FBAD00059B8):
- gcCycleOn lock (0x00007FBAD0005A68):
- Hook Interface lock (0x00007FBAD0005B18):
- MM_ParallelDispatcher::workerThread lock (0x00007FBAD0005BC8):
- MM_ParallelDispatcher::dispatcherControl lock (0x00007FBAD0005C78):
- MM_ParallelDispatcher::synchronize lock (0x00007FBAD0005D28):
- MM_Scavenger::scanCacheMonitor lock (0x00007FBAD0005DD8):
- MM_Scavenger::freeCacheMonitor lock (0x00007FBAD0005E88):
- MM_WorkPackets::inputList lock (0x00007FBAD0005F38):
- MM_WorkPackets::allocatingPackets lock (0x00007FBAD0005FE8):
- MM_WorkPacketOverflow::overflowList lock (0x00007FBAD0006098):
- MM_ConcurrentOverflow::cardsClearingMonitor lock (0x00007FBAD0006148):
- SweepPoolState Monitor lock (0x00007FBAD00061F8):
- MM_ConcurrentGC::conHelpersActivation lock (0x00007FBAD00062A8):
- MM_ConcurrentGC::initWork lock (0x00007FBAD0006358):
- MM_ConcurrentGC::concurrentTuning lock (0x00007FBAD0006408):
- MM_ConcurrentGC::initWorkComplete lock (0x00007FBAD00064B8):
- Undead Segment List Monitor lock (0x00007FBAD0006568):
- Class Loader List Monitor lock (0x00007FBAD0006618):
- GC string table lock (0x00007FBAD00066C8):
- GC string table lock (0x00007FBAD0006778):
- GC string table lock (0x00007FBAD0006828):
- GC string table lock (0x00007FBAD00068D8):
- GC string table lock (0x00007FBAD0006988):
- GC string table lock (0x00007FBAD0006A38):
- GC string table lock (0x00007FBAD0006AE8):
- GC string table lock (0x00007FBAD0006B98):
- MM_GCExtensions::gcStats lock (0x00007FBAD0006C48):
- Unsafe memory allocation tracking lock (0x00007FBAD0006CF8):
- JIT-PersistentAllocatorSmallBlockMonitor lock (0x00007FBAD0006DA8):
- JIT-PersistentAllocatorLargeBlockMonitor lock (0x00007FBAD0006E58):
- JIT-PersistentAllocatorSegmentMonitor lock (0x00007FBAD0006F08):
- &vm->verboseStateMutex lock (0x00007FBAD0006FB8):
- VM thread list lock (0x00007FBAD0007068): Flat locked by "[osthread]" (native thread ID:0x1B2E49), entry count 1
- VM exclusive access lock (0x00007FBAD0007118):
- VM Runtime flags Mutex lock (0x00007FBAD00071C8):
- VM Extended method block flags Mutex lock (0x00007FBAD0007278):
- Async event mutex lock (0x00007FBAD0007328):
- JIT/GC class unload mutex lock (0x00007FBAD00073D8):
- VM bind native lock (0x00007FBAD0007488):
- JCL cache mutex lock (0x00007FBAD0007538):
- VM Statistics List Mutex lock (0x00007FBAD00075E8):
- Field Index Hashtable Mutex lock (0x00007FBAD0007698):
- JNI critical region mutex lock (0x00007FBAD0007748):
- JNI Cryptography mutex lock (0x00007FBAD00077F8):
- JNI HIKM Cryptography mutex lock (0x00007FBAD006B6F8):
- VM class loader modules lock (0x00007FBAD006B7A8):
- VM class loader blocks lock (0x00007FBAD006B858):
- VM class table lock (0x00007FBAD006B908):
- VM segment lock (0x00007FBAD006B9B8):
- VM JNI frame lock (0x00007FBAD006BA68):
- VM GC finalize main lock (0x00007FBAD006BB18):
- VM GC finalize run finalization lock (0x00007FBAD006BBC8):
- VM AOT runtime init lock (0x00007FBAD006BC78):
- OSR global buffer lock lock (0x00007FBAD006BD28):
- JNI native library loading lock lock (0x00007FBAD006BDD8):
- VM state notification mutex lock (0x00007FBAD006BE88):
- Wait mutex for constantDynamic during resolve lock (0x00007FBAD006BF38):
- VM monitor table lock (0x00007FBAD006BFE8): Flat locked by "[osthread]" (native thread ID:0x1B2E49), entry count 1
- VM mem segment list lock (0x00007FBAD006C098):
- VM mem segment list lock (0x00007FBAD006C148):
- FinalizeListManager lock (0x00007FBAD006C1F8):
- &(jvmtiData->mutex) lock (0x00007FBAD006C2A8):
- &(jvmtiData->redefineMutex) lock (0x00007FBAD006C358):
- &(jvmtiData->compileEventMutex) lock (0x00007FBAD006C408):
- BCVD verifier lock (0x00007FBAD006C4B8):
- global mapMemoryBuffer mutex lock (0x00007FBAD006C568):
- Thread public flags mutex lock (0x00007FBAD006C618):
- &vmthread->threadNameMutex lock (0x00007FBAD006C6C8):
- jvmriDumpThread lock (0x00007FBAD006C778):
- J9VM Trace Lock lock (0x00007FBAD006C828):
- Global Trace lock (0x00007FBAD006C8D8):
- Global Record Subscribers lock (0x00007FBAD006C988):
- Global Trace Thread lock (0x00007FBAD006CA38):
- Trace Trigger on tpid lock (0x00007FBAD006CAE8):
- Trace Trigger on groups lock (0x00007FBAD006CB98):
- Global Trace Free Queue lock (0x00007FBAD006CC48):
- Trace Queue Alarm lock (0x00007FBAD006CCF8):
- Trace Queue lock (0x00007FBAD006CDA8):
- jvmriDumpThread lock (0x00007FBAD006CE58):
- JIT-MonitorTableMonitor lock (0x00007FBAD006CF08):
- JIT-ScratchMemoryPoolMonitor lock (0x00007FBAD006CFB8):
- JIT-IProfilerPersistenceMonitor lock (0x00007FBAD006D068):
- Hook Interface lock (0x00007FBAD006D118):
- JIT thunk table lock (0x00007FBAD006D1C8):
- JIT-AssumptionTableMutex lock (0x00007FBAD006D278):
- VM mem segment list lock (0x00007FBAD006D328):
- VM mem segment list lock (0x00007FBAD006D3D8):
- JIT-CompilationQueueMonitor lock (0x00007FBAD006D488):
- JIT-SchedulingMonitor lock (0x00007FBAD006D538):
- JIT-DLTmonitor lock (0x00007FBAD006D5E8):
- JIT-IProfilerBufferArrivalMonitor lock (0x00007FBAD006D698):
- JIT-GpuInitializationMonitor lock (0x00007FBAD006D748):
- JIT-ArtifactMonitor lock (0x00007FBAD006D7F8):
- CodeCacheRepositoryMonitor lock (0x00007FBAD006D8A8):
- JIT-CodeCacheListMutex lock (0x00007FBAD006D958):
- CodeCacheUsageMonitor lock (0x00007FBAD006DA08):
- JIT-CodeCacheMonitor-?? lock (0x00007FBAD006DAB8):
- JIT-DataCacheManagerMutex lock (0x00007FBAD006DB68):
- OptimizationPlanMonitor lock (0x00007FBAD006DC18):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD006DCC8):
- Thread public flags mutex lock (0x00007FBAD006DD78):
- &vmthread->threadNameMutex lock (0x00007FBAD006DE28):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD006DED8):
- Thread public flags mutex lock (0x00007FBAD006DF88):
- &vmthread->threadNameMutex lock (0x00007FBAD006E038):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD006E0E8):
- Thread public flags mutex lock (0x00007FBAD006E198):
- &vmthread->threadNameMutex lock (0x00007FBAD006E248):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD00C4DA8):
- Thread public flags mutex lock (0x00007FBAD00C4E58):
- &vmthread->threadNameMutex lock (0x00007FBAD00C4F08):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD00C4FB8):
- Thread public flags mutex lock (0x00007FBAD00C5068):
- &vmthread->threadNameMutex lock (0x00007FBAD00C5118):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD00C51C8):
- Thread public flags mutex lock (0x00007FBAD00C5278):
- &vmthread->threadNameMutex lock (0x00007FBAD00C5328):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD00C53D8):
- Thread public flags mutex lock (0x00007FBAD00C5488):
- &vmthread->threadNameMutex lock (0x00007FBAD00C5538):
- JIT-CompThreadMonitor-?? lock (0x00007FBAD00C55E8):
- Thread public flags mutex lock (0x00007FBAD00C5698):
- &vmthread->threadNameMutex lock (0x00007FBAD00C5748):
- JIT-LogMonitor lock (0x00007FBAD00C57F8):
- JIT-PersistentAllocatorSmallBlockMonitor lock (0x00007FBAD00C58A8):
- JIT-PersistentAllocatorLargeBlockMonitor lock (0x00007FBAD00C5958):
- JIT-PersistentAllocatorSegmentMonitor lock (0x00007FBAD00C5A08):
- JIT-InterpreterProfilingMonitor lock (0x00007FBAD00C5AB8):
- ValueProfilingMutex lock (0x00007FBAD00C5B68):
- InvokeExactJ2IThunkTable lock (0x00007FBAD00C5C18):
- JIT sampling thread lock (0x00007FBAD00C5CC8):
- Thread public flags mutex lock (0x00007FBAD00C5D78):
- &vmthread->threadNameMutex lock (0x00007FBAD00C5E28):
- JIT-iprofilerMonitor lock (0x00007FBAD00C5ED8):
- Thread public flags mutex lock (0x00007FBAD00C5F88):
- &vmthread->threadNameMutex lock (0x00007FBAD00C6038):
- flushProcessWriteBuffers lock (0x00007FBAD00C60E8):
- management fields lock lock (0x00007FBAD00C6198):
- &mgmt->notificationMonitor lock (0x00007FBAD00C6248):
- &mgmt->dlparNotificationMonitor lock (0x00007FBAD00C62F8):
- classPathEntries Mutex lock (0x00007FBAD00C63A8):
- countersMutex lock (0x00007FBAD00C6458):
- countersMutex lock (0x00007FBAD00C6508):
- JIT-QueueSlotMonitor-0 lock (0x00007FBAD00C65B8):
- JIT-QueueSlotMonitor-1 lock (0x00007FBAD00C6668):
- JIT-QueueSlotMonitor-2 lock (0x00007FBAD00C6718):
- JIT-QueueSlotMonitor-3 lock (0x00007FBAD00C67C8):
- JIT-QueueSlotMonitor-4 lock (0x00007FBAD00C6878):
- JIT-QueueSlotMonitor-5 lock (0x00007FBAD00C6928):
- JIT-QueueSlotMonitor-6 lock (0x00007FBAD00C69D8):
- JIT-QueueSlotMonitor-7 lock (0x00007FBAD00C6A88):
- Thread public flags mutex lock (0x00007FBAD00C6B38):
- &vmthread->threadNameMutex lock (0x00007FBAD00C6BE8):
- Thread public flags mutex lock (0x00007FBAD00C6C98):
- &vmthread->threadNameMutex lock (0x00007FBAD00C6D48):
- Thread public flags mutex lock (0x00007FBAD00C6DF8):
- &vmthread->threadNameMutex lock (0x00007FBAD00C6EA8):
- Thread public flags mutex lock (0x00007FBAD00C6F58):
- &vmthread->threadNameMutex lock (0x00007FBAD00C7008):
- Thread public flags mutex lock (0x00007FBAD00C70B8):
- &vmthread->threadNameMutex lock (0x00007FBAD00C7168):
- Thread public flags mutex lock (0x00007FBAD00C7218):
- &vmthread->threadNameMutex lock (0x00007FBAD00C72C8):
- Thread public flags mutex lock (0x00007FBAD00C7378):
- &vmthread->threadNameMutex lock (0x00007FBAD00C7428):
- Thread public flags mutex lock (0x00007FBAD00C74D8):
- &vmthread->threadNameMutex lock (0x00007FBAD00C7588):
- Thread public flags mutex lock (0x00007FBAD00C7638):
- &vmthread->threadNameMutex lock (0x00007FBAD00C76E8):
- JVM_RawMonitor lock (0x00007FBAD00C7798):
- JVM_RawMonitor lock (0x00007FBAD00C7848):
- JIT-QueueSlotMonitor-8 lock (0x00007FBAD00C78F8):
- JIT-QueueSlotMonitor-9 lock (0x00007FBA84051CF8):
- JIT-QueueSlotMonitor-10 lock (0x00007FBA84051DA8):
- JVM_RawMonitor lock (0x00007FBA84051E58):
- JIT-QueueSlotMonitor-11 lock (0x00007FBA84051F08):
- JVM_RawMonitor lock (0x00007FBA84051FB8):
- JIT-QueueSlotMonitor-12 lock (0x00007FBA84052068):
- JVM_RawMonitor lock (0x00007FBA84052118):
- JVM_RawMonitor lock (0x00007FBA840521C8):
- JIT-QueueSlotMonitor-13 lock (0x00007FBA84052278):
- JIT-QueueSlotMonitor-14 lock (0x00007FBA84052328):
- JIT-QueueSlotMonitor-15 lock (0x00007FBA840523D8):
- JIT-QueueSlotMonitor-16 lock (0x00007FBA84052488):
- JVM_RawMonitor lock (0x00007FBA84052538):
- JVM_RawMonitor lock (0x00007FBA840525E8):
- Thread public flags mutex lock (0x00007FBA84052698):
- &vmthread->threadNameMutex lock (0x00007FBA84052748):
- JVM_RawMonitor lock (0x00007FBA840527F8):
- JIT-QueueSlotMonitor-17 lock (0x00007FBA840528A8):
- Thread public flags mutex lock (0x00007FBA84052958):
- &vmthread->threadNameMutex lock (0x00007FBA84052A08):
- JVM_RawMonitor lock (0x00007FBA84052AB8):
- JVM_RawMonitor lock (0x00007FBA84052B68):
- JVM_RawMonitor lock (0x00007FBA84052C18):
- JVM_RawMonitor lock (0x00007FBA84052CC8):
- JVM_RawMonitor lock (0x00007FBA84052D78):
- JVM_RawMonitor lock (0x00007FBA84052E28):
- JVM_RawMonitor lock (0x00007FBA84052ED8):
- JVM_RawMonitor lock (0x00007FBA84052F88):
- JVM_RawMonitor lock (0x00007FBA84053038):
- JVM_RawMonitor lock (0x00007FBA840530E8):
- Thread public flags mutex lock (0x00007FBA84053198):
- &vmthread->threadNameMutex lock (0x00007FBA84053248):
- Thread public flags mutex lock (0x00007FBA840532F8):
- &vmthread->threadNameMutex lock (0x00007FBA840533A8):
- Thread public flags mutex lock (0x00007FBA84053458):
- &vmthread->threadNameMutex lock (0x00007FBA84053508):
- Thread public flags mutex lock (0x00007FBA840535B8):
- &vmthread->threadNameMutex lock (0x00007FBA84053668):
- Thread public flags mutex lock (0x00007FBA84053718):
- &vmthread->threadNameMutex lock (0x00007FBA840537C8):
- Thread public flags mutex lock (0x00007FBA84053878):
- &vmthread->threadNameMutex lock (0x00007FBA84053928):
- Thread public flags mutex lock (0x00007FBA840539D8):
- &vmthread->threadNameMutex lock (0x00007FBA84053A88):
- Thread public flags mutex lock (0x00007FBA84053B38):
- &vmthread->threadNameMutex lock (0x00007FBA84053BE8):
- Thread public flags mutex lock (0x00007FBA84053C98):
- &vmthread->threadNameMutex lock (0x00007FBA84053D48):
- Thread public flags mutex lock (0x00007FBA84053DF8):
- &vmthread->threadNameMutex lock (0x00007FBA84053EA8):
- Thread public flags mutex lock (0x00007FBA84053F58):
- &vmthread->threadNameMutex lock (0x00007FBA84054008):
- Thread public flags mutex lock (0x00007FBA840540B8):
- &vmthread->threadNameMutex lock (0x00007FBA84054168):
- Thread public flags mutex lock (0x00007FBA84054218):
- &vmthread->threadNameMutex lock (0x00007FBA840542C8):
- Thread public flags mutex lock (0x00007FBA84054378):
- &vmthread->threadNameMutex lock (0x00007FBA84054428):
- Thread public flags mutex lock (0x00007FBA840544D8):
- &vmthread->threadNameMutex lock (0x00007FBA84054588):
- Thread public flags mutex lock (0x00007FBA84054638):
- &vmthread->threadNameMutex lock (0x00007FBA840546E8):
- Thread public flags mutex lock (0x00007FBA84054798):
- &vmthread->threadNameMutex lock (0x00007FBA84054848):
- Thread public flags mutex lock (0x00007FBAD04FD978):
- &vmthread->threadNameMutex lock (0x00007FBAD04FDA28):
- Thread public flags mutex lock (0x00007FBAD04FDAD8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FDB88):
- Thread public flags mutex lock (0x00007FBAD04FDC38):
- &vmthread->threadNameMutex lock (0x00007FBAD04FDCE8):
- Thread public flags mutex lock (0x00007FBAD04FDD98):
- &vmthread->threadNameMutex lock (0x00007FBAD04FDE48):
- Thread public flags mutex lock (0x00007FBAD04FDEF8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FDFA8):
- Thread public flags mutex lock (0x00007FBAD04FE058):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE108):
- Thread public flags mutex lock (0x00007FBAD04FE1B8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE268):
- Thread public flags mutex lock (0x00007FBAD04FE318):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE3C8):
- Thread public flags mutex lock (0x00007FBAD04FE478):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE528):
- Thread public flags mutex lock (0x00007FBAD04FE5D8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE688):
- Thread public flags mutex lock (0x00007FBAD04FE738):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE7E8):
- Thread public flags mutex lock (0x00007FBAD04FE898):
- &vmthread->threadNameMutex lock (0x00007FBAD04FE948):
- Thread public flags mutex lock (0x00007FBAD04FE9F8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FEAA8):
- Thread public flags mutex lock (0x00007FBAD04FEB58):
- &vmthread->threadNameMutex lock (0x00007FBAD04FEC08):
- Thread public flags mutex lock (0x00007FBAD04FECB8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FED68):
- Thread public flags mutex lock (0x00007FBAD04FEE18):
- &vmthread->threadNameMutex lock (0x00007FBAD04FEEC8):
- Thread public flags mutex lock (0x00007FBAD04FEF78):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF028):
- Thread public flags mutex lock (0x00007FBAD04FF0D8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF188):
- Thread public flags mutex lock (0x00007FBAD04FF238):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF2E8):
- Thread public flags mutex lock (0x00007FBAD04FF398):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF448):
- Thread public flags mutex lock (0x00007FBAD04FF4F8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF5A8):
- Thread public flags mutex lock (0x00007FBAD04FF658):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF708):
- Thread public flags mutex lock (0x00007FBAD04FF7B8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF868):
- Thread public flags mutex lock (0x00007FBAD04FF918):
- &vmthread->threadNameMutex lock (0x00007FBAD04FF9C8):
- Thread public flags mutex lock (0x00007FBAD04FFA78):
- &vmthread->threadNameMutex lock (0x00007FBAD04FFB28):
- Thread public flags mutex lock (0x00007FBAD04FFBD8):
- &vmthread->threadNameMutex lock (0x00007FBAD04FFC88):
- Thread public flags mutex lock (0x00007FBAD04FFD38):
- &vmthread->threadNameMutex lock (0x00007FBAD04FFDE8):
- Thread public flags mutex lock (0x00007FBAD04FFE98):
- &vmthread->threadNameMutex lock (0x00007FBAD04FFF48):
- Thread public flags mutex lock (0x00007FBAD04FFFF8):
- &vmthread->threadNameMutex lock (0x00007FBAD05000A8):
- Thread public flags mutex lock (0x00007FBAD0500158):
- &vmthread->threadNameMutex lock (0x00007FBAD0500208):
- Thread public flags mutex lock (0x00007FBAD05002B8):
- &vmthread->threadNameMutex lock (0x00007FBAD0500368):
- Thread public flags mutex lock (0x00007FBAD0500418):
- &vmthread->threadNameMutex lock (0x00007FBAD05004C8):
- Thread public flags mutex lock (0x00007FBAD05996F8):
- &vmthread->threadNameMutex lock (0x00007FBAD05997A8):
- Thread public flags mutex lock (0x00007FBAD0599858):
- &vmthread->threadNameMutex lock (0x00007FBAD0599908):
- Thread public flags mutex lock (0x00007FBAD05999B8):
- &vmthread->threadNameMutex lock (0x00007FBAD0599A68):
- Thread public flags mutex lock (0x00007FBAD0599B18):
- &vmthread->threadNameMutex lock (0x00007FBAD0599BC8):
- Thread public flags mutex lock (0x00007FBAD0599C78):
- &vmthread->threadNameMutex lock (0x00007FBAD0599D28):
- Thread public flags mutex lock (0x00007FBAD0599DD8):
- &vmthread->threadNameMutex lock (0x00007FBAD0599E88):
- Thread public flags mutex lock (0x00007FBAD0599F38):
- &vmthread->threadNameMutex lock (0x00007FBAD0599FE8):
- Thread public flags mutex lock (0x00007FBAD059A098):
- &vmthread->threadNameMutex lock (0x00007FBAD059A148):
- Thread public flags mutex lock (0x00007FBAD059A1F8):
- &vmthread->threadNameMutex lock (0x00007FBAD059A2A8):
- Thread public flags mutex lock (0x00007FBAD059A358):
- &vmthread->threadNameMutex lock (0x00007FBAD059A408):
- Thread public flags mutex lock (0x00007FBAD059A4B8):
- &vmthread->threadNameMutex lock (0x00007FBAD059A568):
- Thread public flags mutex lock (0x00007FBAD059A618):
- &vmthread->threadNameMutex lock (0x00007FBAD059A6C8):
- Thread public flags mutex lock (0x00007FBAD059A778):
- &vmthread->threadNameMutex lock (0x00007FBAD059A828):
- Thread public flags mutex lock (0x00007FBAD059A8D8):
- &vmthread->threadNameMutex lock (0x00007FBAD059A988):
- Thread public flags mutex lock (0x00007FBAD059AA38):
- &vmthread->threadNameMutex lock (0x00007FBAD059AAE8):
- Thread public flags mutex lock (0x00007FBAD059AB98):
- &vmthread->threadNameMutex lock (0x00007FBAD059AC48):
- Thread public flags mutex lock (0x00007FBAD059ACF8):
- &vmthread->threadNameMutex lock (0x00007FBAD059ADA8):
- Thread public flags mutex lock (0x00007FBAD059AE58):
- &vmthread->threadNameMutex lock (0x00007FBAD059AF08):
- Thread public flags mutex lock (0x00007FBAD059AFB8):
- &vmthread->threadNameMutex lock (0x00007FBAD059B068):
- Thread public flags mutex lock (0x00007FBAD059B118):
- &vmthread->threadNameMutex lock (0x00007FBAD059B1C8):
- Thread public flags mutex lock (0x00007FBAD059B278):
- &vmthread->threadNameMutex lock (0x00007FBAD059B328):
- Thread public flags mutex lock (0x00007FBAD059B3D8):
- &vmthread->threadNameMutex lock (0x00007FBAD059B488):
- Thread public flags mutex lock (0x00007FBAD059B538):
- &vmthread->threadNameMutex lock (0x00007FBAD059B5E8):
- Thread public flags mutex lock (0x00007FBAD059B698):
- &vmthread->threadNameMutex lock (0x00007FBAD059B748):
- Thread public flags mutex lock (0x00007FBAD059B7F8):
- &vmthread->threadNameMutex lock (0x00007FBAD059B8A8):
- Thread public flags mutex lock (0x00007FBAD059B958):
- &vmthread->threadNameMutex lock (0x00007FBAD059BA08):
- Thread public flags mutex lock (0x00007FBAD059BAB8):
- &vmthread->threadNameMutex lock (0x00007FBAD059BB68):
- Thread public flags mutex lock (0x00007FBAD059BC18):
- &vmthread->threadNameMutex lock (0x00007FBAD059BCC8):
- Thread public flags mutex lock (0x00007FBAD059BD78):
- &vmthread->threadNameMutex lock (0x00007FBAD059BE28):
- Thread public flags mutex lock (0x00007FBAD059BED8):
- &vmthread->threadNameMutex lock (0x00007FBAD059BF88):
- Thread public flags mutex lock (0x00007FBAD059C038):
- &vmthread->threadNameMutex lock (0x00007FBAD059C0E8):
- Thread public flags mutex lock (0x00007FBAD059C198):
- &vmthread->threadNameMutex lock (0x00007FBAD059C248):
- Thread public flags mutex lock (0x00007FBAD0636488):
- &vmthread->threadNameMutex lock (0x00007FBAD0636538):
- Thread public flags mutex lock (0x00007FBAD06365E8):
- &vmthread->threadNameMutex lock (0x00007FBAD0636698):
- Thread public flags mutex lock (0x00007FBAD0636748):
- &vmthread->threadNameMutex lock (0x00007FBAD06367F8):
- Thread public flags mutex lock (0x00007FBAD06368A8):
- &vmthread->threadNameMutex lock (0x00007FBAD0636958):
- Thread public flags mutex lock (0x00007FBAD0636A08):
- &vmthread->threadNameMutex lock (0x00007FBAD0636AB8):
- Thread public flags mutex lock (0x00007FBAD0636B68):
- &vmthread->threadNameMutex lock (0x00007FBAD0636C18):
- Thread public flags mutex lock (0x00007FBAD0636CC8):
- &vmthread->threadNameMutex lock (0x00007FBAD0636D78):
- Thread public flags mutex lock (0x00007FBAD0636E28):
- &vmthread->threadNameMutex lock (0x00007FBAD0636ED8):
- Thread public flags mutex lock (0x00007FBAD0636F88):
- &vmthread->threadNameMutex lock (0x00007FBAD0637038):
- Thread public flags mutex lock (0x00007FBAD06370E8):
- &vmthread->threadNameMutex lock (0x00007FBAD0637198):
- Thread public flags mutex lock (0x00007FBAD0637248):
- &vmthread->threadNameMutex lock (0x00007FBAD06372F8):
- Thread public flags mutex lock (0x00007FBAD06373A8):
- &vmthread->threadNameMutex lock (0x00007FBAD0637458):
- Thread public flags mutex lock (0x00007FBAD0637508):
- &vmthread->threadNameMutex lock (0x00007FBAD06375B8):
- Thread public flags mutex lock (0x00007FBAD0637668):
- &vmthread->threadNameMutex lock (0x00007FBAD0637718):
- Thread public flags mutex lock (0x00007FBAD06377C8):
- &vmthread->threadNameMutex lock (0x00007FBAD0637878):
- Thread public flags mutex lock (0x00007FBAD0637928):
- &vmthread->threadNameMutex lock (0x00007FBAD06379D8):
- Thread public flags mutex lock (0x00007FBAD0637A88):
- &vmthread->threadNameMutex lock (0x00007FBAD0637B38):
- Thread public flags mutex lock (0x00007FBAD0637BE8):
- &vmthread->threadNameMutex lock (0x00007FBAD0637C98):
- &(workerData->monitor) lock (0x00007FBAD0637D48):
- Thread public flags mutex lock (0x00007FBAD0637DF8):
- &vmthread->threadNameMutex lock (0x00007FBAD0637EA8):

#### Deadlocks



#### Thread Pool Info

- **Total Threads:** 122
- **Live Threads:** 114
- **Daemon Threads:** 21

#### Threads

###  - **Name:** Unknown
  - **J9VMThread:** N/A
  - **State:** N/A
  - **Priority:** 0
  - **Details:**
    - **Java Call Stack:**
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E48593 [libj9prt29.so+0x5a593])
      - (0x00007FBAD5E491AF [libj9prt29.so+0x5b1af])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5953795 [libj9dmp29.so+0x1a795])
      - (0x00007FBAD5953B1D [libj9dmp29.so+0x1ab1d])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD59500BB [libj9dmp29.so+0x170bb])
      - (0x00007FBAD594ACDD [libj9dmp29.so+0x11cdd])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD594C1C5 [libj9dmp29.so+0x131c5])
      - (0x00007FBAD59560AC [libj9dmp29.so+0x1d0ac])
      - (0x00007FBAD593E922 [libj9dmp29.so+0x5922])
      - (0x00007FBAD593DF75 [libj9dmp29.so+0x4f75])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5941712 [libj9dmp29.so+0x8712])
      - (0x00007FBAD594189D [libj9dmp29.so+0x889d])
      - (0x00007FBAD59581CD [libj9dmp29.so+0x1f1cd])
      - (0x00007FBAD48CED10 [libjclse29.so+0x39d10])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD48CEC74 [libjclse29.so+0x39c74])
      - (0x00007FBAD5E14CBC [libj9prt29.so+0x26cbc])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Native Thread ID:** 0x1B2E49
    - **Native Priority:** N/A
    - **Native Policy:** UNKNOWN
    - **VM State:** N/A
    - **VM Thread Flags:** N/A


###  - **Name:** Thread-67
  - **J9VMThread:** 0x00000000002A1800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA3
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC7D7000,
      - **To:** 0x00007FBACC817000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007434830
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-59
  - **J9VMThread:** 0x0000000000283800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x53
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9B
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC9DF000,
      - **To:** 0x00007FBACCA1F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009261060
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-57
  - **J9VMThread:** 0x000000000027C000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x51
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E99
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCA61000,
      - **To:** 0x00007FBACCAA1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008259440
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-50
  - **J9VMThread:** 0x0000000000261C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x4A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E92
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCC28000,
      - **To:** 0x00007FBACCC68000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007414300
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-45
  - **J9VMThread:** 0x000000000024F000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x45
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8D
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCD6D000,
      - **To:** 0x00007FBACCDAD000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009050270
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-21
  - **J9VMThread:** 0x00000000001F5000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2D
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E75
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD385000,
      - **To:** 0x00007FBACD3C5000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010483710
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-20
  - **J9VMThread:** 0x00000000001F1400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E74
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD3C6000,
      - **To:** 0x00007FBACD406000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011778570
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Unknown
  - **J9VMThread:** N/A
  - **State:** N/A
  - **Priority:** 0
  - **Details:**
    - **Java Call Stack:**
    - **Native Call Stack:**
      - (0x00007FBAD5E4C0E1 [libj9prt29.so+0x5e0e1])
      - (0x00007FBAD5E4B893 [libj9prt29.so+0x5d893])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - (0x00007FBAD6A30624 [libc.so.6+0x96624])
      - (0x00007FBAD6BDAA75 [libjli.so+0x12a75])
      - (0x00007FBAD6BD8C32 [libjli.so+0x10c32])
      - JLI_Launch+0x1594 (0x00007FBAD6BD73D4 [libjli.so+0xf3d4])
      - (0x000055E365E7908E [java+0x108e])
      - (0x00007FBAD69C3D90 [libc.so.6+0x29d90])
      - __libc_start_main+0x80 (0x00007FBAD69C3E40 [libc.so.6+0x29e40])
      - (0x000055E365E790B9 [java+0x10b9])
    - **Native Thread ID:** 0x1B2E47
    - **Native Priority:** N/A
    - **Native Policy:** UNKNOWN
    - **VM State:** N/A
    - **VM Thread Flags:** N/A


###  - **Name:** Thread-99
  - **J9VMThread:** 0x0000000000319800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x7B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EC3
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBA6BF7F000,
      - **To:** 0x00007FBA6BFBF000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.021570800
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Unknown
  - **J9VMThread:** N/A
  - **State:** N/A
  - **Priority:** 0
  - **Details:**
    - **Java Call Stack:**
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4AD40C7 [libj9gc29.so+0x290c7])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Native Thread ID:** 0x1B2E54
    - **Native Priority:** N/A
    - **Native Policy:** UNKNOWN
    - **VM State:** N/A
    - **VM Thread Flags:** N/A


###  - **Name:** GC Worker
  - **J9VMThread:** 0x000000000012CA00,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x13
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E5C
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDCFF000,
      - **To:** 0x00007FBACDD3F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.004069580
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** GC Worker
  - **J9VMThread:** 0x0000000000121600,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x10
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E59
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDDC2000,
      - **To:** 0x00007FBACDE02000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.002474010
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Concurrent Mark Helper
  - **J9VMThread:** 0x0000000000112600,
  - **State:** R
  - **Priority:** 1
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4C53FA4 [libj9gc29.so+0x1a8fa4])
      - (0x00007FBAD4C545DE [libj9gc29.so+0x1a95de])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4C52223 [libj9gc29.so+0x1a7223])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xC
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E55
    - **Native Priority:** 0x0
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDEC6000,
      - **To:** 0x00007FBACDF06000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.002958890
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Attach API wait loop
  - **J9VMThread:** 0x0000000000136200,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - at openj9/internal/tools/attach/target/IPC.waitSemaphore(Native Method)
      - at openj9/internal/tools/attach/target/CommonDirectory.waitSemaphore(CommonDirectory.java:264)
      - at openj9/internal/tools/attach/target/WaitLoop.waitForNotification(WaitLoop.java:66)
      - at openj9/internal/tools/attach/target/WaitLoop.run(WaitLoop.java:157)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - semtimedop+0xe (0x00007FBAD6AC23AE [libc.so.6+0x1283ae])
      - (0x00007FBAD5DFB3B7 [libj9prt29.so+0xd3b7])
      - (0x00007FBAD5E05B08 [libj9prt29.so+0x17b08])
      - Java_openj9_internal_tools_attach_target_IPC_waitSemaphore+0x63 (0x00007FBAD48A6E53 [libjclse29.so+0x11e53])
      - (0x00007FBA590087BC [<unknown>+0x0])
    - **Java Thread ID:** 0x17
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E5F
    - **Native Priority:** 0xA
    - **Native Policy:** UNKNOWN
    - **VM State:** R
    - **VM Thread Flags:** 0x000000a1
    - **Stack Range:**
      - **From:** 0x00007FBACD903000,
      - **To:** 0x00007FBACD943000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012223790
    - **Category:** System-JVM
    - **Heap Allocation:** 42088


###  - **Name:** Thread-8
  - **J9VMThread:** 0x00000000001C4400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x20
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E68
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD6D2000,
      - **To:** 0x00007FBACD712000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007809320
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** IProfiler
  - **J9VMThread:** 0x000000000003F200,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4F95FA6 [libj9jit29.so+0x228fa6])
      - (0x00007FBAD4F96127 [libj9jit29.so+0x229127])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xB
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E53
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE280000,
      - **To:** 0x00007FBACE2A0000,
      - **Size:** 0x20000

    - **CPU Usage:** 0.046808770
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-93
  - **J9VMThread:** 0x0000000000303000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x75
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBD
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC13D000,
      - **To:** 0x00007FBACC17D000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012594750
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-37
  - **J9VMThread:** 0x0000000000231000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x3D
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E85
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCF75000,
      - **To:** 0x00007FBACCFB5000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009321230
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-004 Suspended
  - **J9VMThread:** 0x000000000002C600,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x6
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4E
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE7E5000,
      - **To:** 0x00007FBACE8E5000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.001937750
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-47
  - **J9VMThread:** 0x0000000000256800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x47
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8F
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCCEB000,
      - **To:** 0x00007FBACCD2B000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009456790
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-005 Suspended
  - **J9VMThread:** 0x0000000000030200,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x7
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4F
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE6E4000,
      - **To:** 0x00007FBACE7E4000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.003959090
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** GC Worker
  - **J9VMThread:** 0x0000000000128E00,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x12
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E5B
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDD40000,
      - **To:** 0x00007FBACDD80000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.003859310
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Thread-90
  - **J9VMThread:** 0x00000000002F7C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x72
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBA
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC200000,
      - **To:** 0x00007FBACC240000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.019552170
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-84
  - **J9VMThread:** 0x00000000002E1400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB4
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC386000,
      - **To:** 0x00007FBACC3C6000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011988020
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-85
  - **J9VMThread:** 0x00000000002E5000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6D
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB5
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC345000,
      - **To:** 0x00007FBACC385000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007429940
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-92
  - **J9VMThread:** 0x00000000002FF400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x74
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBC
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC17E000,
      - **To:** 0x00007FBACC1BE000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012637390
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-56
  - **J9VMThread:** 0x0000000000278400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x50
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E98
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCAA2000,
      - **To:** 0x00007FBACCAE2000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007782390
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-63
  - **J9VMThread:** 0x0000000000292800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x57
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9F
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC8DB000,
      - **To:** 0x00007FBACC91B000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007081750
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Finalizer thread
  - **J9VMThread:** 0x00000000000EE500,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4AD37C2 [libj9gc29.so+0x287c2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4AD2EF5 [libj9gc29.so+0x27ef5])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x7D
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EC4
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBA6BF3E000,
      - **To:** 0x00007FBA6BF7E000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.006944700
    - **Category:** Application
    - **Heap Allocation:** 4192


###  - **Name:** Thread-83
  - **J9VMThread:** 0x00000000002DD800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB3
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC3C7000,
      - **To:** 0x00007FBACC407000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009146990
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-6
  - **J9VMThread:** 0x00000000001BCC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x1E
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E66
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD754000,
      - **To:** 0x00007FBACD794000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010595840
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-76
  - **J9VMThread:** 0x00000000002C3400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x64
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAC
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC58E000,
      - **To:** 0x00007FBACC5CE000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012295970
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-72
  - **J9VMThread:** 0x00000000002B4400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x60
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA8
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC692000,
      - **To:** 0x00007FBACC6D2000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009358730
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-97
  - **J9VMThread:** 0x0000000000312000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x79
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EC1
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC039000,
      - **To:** 0x00007FBACC079000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010951380
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-61
  - **J9VMThread:** 0x000000000028B000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x55
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9D
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC95D000,
      - **To:** 0x00007FBACC99D000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008885460
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** GC Worker
  - **J9VMThread:** 0x0000000000125200,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x11
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E5A
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDD81000,
      - **To:** 0x00007FBACDDC1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.004123570
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Thread-86
  - **J9VMThread:** 0x00000000002E8C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6E
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB6
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC304000,
      - **To:** 0x00007FBACC344000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.015540620
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-64
  - **J9VMThread:** 0x0000000000296400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x58
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA0
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC89A000,
      - **To:** 0x00007FBACC8DA000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010896830
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-69
  - **J9VMThread:** 0x00000000002A9000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5D
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA5
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC755000,
      - **To:** 0x00007FBACC795000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.005975700
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-74
  - **J9VMThread:** 0x00000000002BBC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x62
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAA
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC610000,
      - **To:** 0x00007FBACC650000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009373630
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-4
  - **J9VMThread:** 0x00000000001B5400,
  - **State:** CW
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at java/lang/Thread.sleepImpl(Native Method)
      - at java/lang/Thread.sleep(Thread.java:973)
      - at java/lang/Thread.sleep(Thread.java:956)
      - at XYZExample.XYZMethod(XYZExample.java:19)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B117 [libc.so.6+0x91117])
      - pthread_cond_timedwait+0x23b (0x00007FBAD6A2DE9B [libc.so.6+0x93e9b])
      - omrthread_sleep_interruptable+0x111 (0x00007FBAD5E8F4E1 [libj9thr29.so+0x94e1])
      - (0x00007FBAD5F8E4CA [libj9vm29.so+0xef4ca])
      - (0x00007FBAD5EC0588 [libj9vm29.so+0x21588])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x1C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E64
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000481
    - **Stack Range:**
      - **From:** 0x00007FBACD7D6000,
      - **To:** 0x00007FBACD816000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.013630210
    - **Category:** Application
    - **Heap Allocation:** 4096


###  - **Name:** GC Worker
  - **J9VMThread:** 0x0000000000119E00,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xE
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E57
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDE44000,
      - **To:** 0x00007FBACDE84000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.004749980
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Thread-55
  - **J9VMThread:** 0x0000000000274800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x4F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E97
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCAE3000,
      - **To:** 0x00007FBACCB23000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008651250
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-7
  - **J9VMThread:** 0x00000000001C0800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x1F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E67
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD713000,
      - **To:** 0x00007FBACD753000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011793310
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-34
  - **J9VMThread:** 0x0000000000225C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x3A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E82
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD038000,
      - **To:** 0x00007FBACD078000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012796320
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-94
  - **J9VMThread:** 0x0000000000306C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x76
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBE
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC0FC000,
      - **To:** 0x00007FBACC13C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010506910
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-2
  - **J9VMThread:** 0x0000000000157400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x1A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E62
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD858000,
      - **To:** 0x00007FBACD898000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011423040
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-80
  - **J9VMThread:** 0x00000000002D2400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x68
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB0
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC48A000,
      - **To:** 0x00007FBACC4CA000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009926720
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-60
  - **J9VMThread:** 0x0000000000287400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x54
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9C
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC99E000,
      - **To:** 0x00007FBACC9DE000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008573580
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-006 Suspended
  - **J9VMThread:** 0x0000000000033E00,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x8
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E50
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE5E3000,
      - **To:** 0x00007FBACE6E3000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.002008460
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-003 Suspended
  - **J9VMThread:** 0x0000000000028A00,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x5
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4D
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE8E6000,
      - **To:** 0x00007FBACE9E6000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.003406360
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-000
  - **J9VMThread:** 0x000000000001D600,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95F0A [libj9jit29.so+0x128f0a])
      - (0x00007FBAD4EA2548 [libj9jit29.so+0x135548])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x2
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4A
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACFBE9000,
      - **To:** 0x00007FBACFCE9000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.193058440
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** GC Worker
  - **J9VMThread:** 0x000000000011DA00,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xF
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E58
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDE03000,
      - **To:** 0x00007FBACDE43000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.006927630
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Thread-70
  - **J9VMThread:** 0x00000000002ACC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5E
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA6
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC714000,
      - **To:** 0x00007FBACC754000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010829050
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-96
  - **J9VMThread:** 0x000000000030E400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x78
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EC0
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC07A000,
      - **To:** 0x00007FBACC0BA000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.006024110
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-71
  - **J9VMThread:** 0x00000000002B0800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA7
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC6D3000,
      - **To:** 0x00007FBACC713000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.005619310
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-32
  - **J9VMThread:** 0x000000000021E400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x38
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E80
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD0BA000,
      - **To:** 0x00007FBACD0FA000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010931200
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-001 Suspended
  - **J9VMThread:** 0x0000000000021200,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x3
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4B
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACEAE8000,
      - **To:** 0x00007FBACEBE8000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.003668660
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-23
  - **J9VMThread:** 0x00000000001FC800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E77
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD303000,
      - **To:** 0x00007FBACD343000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.014391370
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-52
  - **J9VMThread:** 0x0000000000269400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x4C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E94
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCBA6000,
      - **To:** 0x00007FBACCBE6000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008037440
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-13
  - **J9VMThread:** 0x00000000001D7000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x25
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6D
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD58D000,
      - **To:** 0x00007FBACD5CD000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009171410
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-48
  - **J9VMThread:** 0x000000000025A400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x48
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E90
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCCAA000,
      - **To:** 0x00007FBACCCEA000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.006684160
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-33
  - **J9VMThread:** 0x0000000000222000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x39
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E81
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD079000,
      - **To:** 0x00007FBACD0B9000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010692310
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-46
  - **J9VMThread:** 0x0000000000252C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x46
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8E
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCD2C000,
      - **To:** 0x00007FBACCD6C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009046070
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-39
  - **J9VMThread:** 0x0000000000238800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x3F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E87
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCEF3000,
      - **To:** 0x00007FBACCF33000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007399970
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Compilation Thread-002 Suspended
  - **J9VMThread:** 0x0000000000024E00,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x4
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E4C
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE9E7000,
      - **To:** 0x00007FBACEAE7000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.003572440
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-3
  - **J9VMThread:** 0x00000000001B1800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x1B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E63
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD817000,
      - **To:** 0x00007FBACD857000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.015275780
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-65
  - **J9VMThread:** 0x000000000029A000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x59
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA1
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC859000,
      - **To:** 0x00007FBACC899000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007976680
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** GC Worker
  - **J9VMThread:** 0x0000000000116200,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4BD5A1D [libj9gc29.so+0x12aa1d])
      - (0x00007FBAD4BD48CA [libj9gc29.so+0x1298ca])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4BD451F [libj9gc29.so+0x12951f])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xD
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E56
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACDE85000,
      - **To:** 0x00007FBACDEC5000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.006093620
    - **Category:** GC
    - **Heap Allocation:** 0


###  - **Name:** Thread-73
  - **J9VMThread:** 0x00000000002B8000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x61
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA9
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC651000,
      - **To:** 0x00007FBACC691000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009976990
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-53
  - **J9VMThread:** 0x000000000026D000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x4D
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E95
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCB65000,
      - **To:** 0x00007FBACCBA5000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.014672220
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT Diagnostic Compilation Thread-007 Suspended
  - **J9VMThread:** 0x0000000000037A00,
  - **State:** R
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD4E95FEE [libj9jit29.so+0x128fee])
      - (0x00007FBAD4EA252A [libj9jit29.so+0x13552a])
      - (0x00007FBAD4EA25F2 [libj9jit29.so+0x1355f2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD4EA29BB [libj9jit29.so+0x1359bb])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x9
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E51
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE4E2000,
      - **To:** 0x00007FBACE5E2000,
      - **Size:** 0x100000

    - **CPU Usage:** 0.003089440
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-18
  - **J9VMThread:** 0x00000000001E9C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E72
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD448000,
      - **To:** 0x00007FBACD488000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009589650
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-77
  - **J9VMThread:** 0x00000000002C7000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x65
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAD
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC54D000,
      - **To:** 0x00007FBACC58D000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008928640
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-79
  - **J9VMThread:** 0x00000000002CE800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x67
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAF
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC4CB000,
      - **To:** 0x00007FBACC50B000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008808040
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-78
  - **J9VMThread:** 0x00000000002CAC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x66
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAE
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC50C000,
      - **To:** 0x00007FBACC54C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008170060
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-36
  - **J9VMThread:** 0x000000000022D400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x3C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E84
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCFB6000,
      - **To:** 0x00007FBACCFF6000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009327590
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-42
  - **J9VMThread:** 0x0000000000243C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x42
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8A
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCE30000,
      - **To:** 0x00007FBACCE70000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010336100
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-30
  - **J9VMThread:** 0x0000000000216C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x36
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7E
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD13C000,
      - **To:** 0x00007FBACD17C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009812730
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-75
  - **J9VMThread:** 0x00000000002BF800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x63
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EAB
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC5CF000,
      - **To:** 0x00007FBACC60F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009227180
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-62
  - **J9VMThread:** 0x000000000028EC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x56
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9E
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC91C000,
      - **To:** 0x00007FBACC95C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009796990
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-10
  - **J9VMThread:** 0x00000000001CBC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x22
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6A
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD650000,
      - **To:** 0x00007FBACD690000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010799900
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-12
  - **J9VMThread:** 0x00000000001D3400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x24
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6C
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD5CE000,
      - **To:** 0x00007FBACD60E000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011899580
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-17
  - **J9VMThread:** 0x00000000001E6000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x29
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E71
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD489000,
      - **To:** 0x00007FBACD4C9000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009638650
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-29
  - **J9VMThread:** 0x0000000000213000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x35
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7D
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD17D000,
      - **To:** 0x00007FBACD1BD000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010112570
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-11
  - **J9VMThread:** 0x00000000001CF800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x23
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6B
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD60F000,
      - **To:** 0x00007FBACD64F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.013188880
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-87
  - **J9VMThread:** 0x00000000002EC800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6F
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB7
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC2C3000,
      - **To:** 0x00007FBACC303000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.021391240
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-95
  - **J9VMThread:** 0x000000000030A800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x77
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBF
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC0BB000,
      - **To:** 0x00007FBACC0FB000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008109700
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-66
  - **J9VMThread:** 0x000000000029DC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA2
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC818000,
      - **To:** 0x00007FBACC858000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010750160
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** JIT-SamplerThread
  - **J9VMThread:** 0x000000000003B600,
  - **State:** CW
  - **Priority:** 10
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B117 [libc.so.6+0x91117])
      - pthread_cond_timedwait+0x23b (0x00007FBAD6A2DE9B [libc.so.6+0x93e9b])
      - omrthread_sleep_interruptable+0x111 (0x00007FBAD5E8F4E1 [libj9thr29.so+0x94e1])
      - (0x00007FBAD4EB21EE [libj9jit29.so+0x1451ee])
      - (0x00007FBAD5E91393 [libj9thr29.so+0xb393])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0xA
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E52
    - **Native Priority:** 0xB
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBACE2A1000,
      - **To:** 0x00007FBACE2E1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.129875250
    - **Category:** JIT
    - **Heap Allocation:** 0


###  - **Name:** Thread-88
  - **J9VMThread:** 0x00000000002F0400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x70
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB8
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC282000,
      - **To:** 0x00007FBACC2C2000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.015951890
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-58
  - **J9VMThread:** 0x000000000027FC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x52
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E9A
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCA20000,
      - **To:** 0x00007FBACCA60000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010151910
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-31
  - **J9VMThread:** 0x000000000021A800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x37
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7F
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD0FB000,
      - **To:** 0x00007FBACD13B000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010376430
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Attach API update file access time
  - **J9VMThread:** 0x0000000000135600,
  - **State:** CW
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at java/lang/Thread.sleepImpl(Native Method)
      - at java/lang/Thread.sleep(Thread.java:973)
      - at java/lang/Thread.sleep(Thread.java:956)
      - at openj9/internal/tools/attach/target/AttachHandler$1.run(AttachHandler.java:348)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B117 [libc.so.6+0x91117])
      - pthread_cond_timedwait+0x23b (0x00007FBAD6A2DE9B [libc.so.6+0x93e9b])
      - omrthread_sleep_interruptable+0x111 (0x00007FBAD5E8F4E1 [libj9thr29.so+0x94e1])
      - (0x00007FBAD5F8E4CA [libj9vm29.so+0xef4ca])
      - (0x00007FBAD5EC0588 [libj9vm29.so+0x21588])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x16
    - **Is Daemon:** true
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E5E
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000481
    - **Stack Range:**
      - **From:** 0x00007FBACD944000,
      - **To:** 0x00007FBACD984000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008654640
    - **Category:** System-JVM
    - **Heap Allocation:** 0


###  - **Name:** Thread-51
  - **J9VMThread:** 0x0000000000265800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x4B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E93
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCBE7000,
      - **To:** 0x00007FBACCC27000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009900770
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-43
  - **J9VMThread:** 0x0000000000247800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x43
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8B
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCDEF000,
      - **To:** 0x00007FBACCE2F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007584710
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-81
  - **J9VMThread:** 0x00000000002D6000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x69
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB1
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC449000,
      - **To:** 0x00007FBACC489000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007247310
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-24
  - **J9VMThread:** 0x0000000000200400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x30
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E78
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD2C2000,
      - **To:** 0x00007FBACD302000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009274580
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-82
  - **J9VMThread:** 0x00000000002D9C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x6A
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EB2
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC408000,
      - **To:** 0x00007FBACC448000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.024731070
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-28
  - **J9VMThread:** 0x000000000020F400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x34
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7C
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD1BE000,
      - **To:** 0x00007FBACD1FE000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010271370
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-25
  - **J9VMThread:** 0x0000000000204000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x31
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E79
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD281000,
      - **To:** 0x00007FBACD2C1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010713980
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-44
  - **J9VMThread:** 0x000000000024B400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x44
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E8C
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCDAE000,
      - **To:** 0x00007FBACCDEE000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.013166460
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** DestroyJavaVM helper thread
  - **J9VMThread:** 0x0000000000019A00,
  - **State:** R
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - No Java call stack associated with this thread
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8DCC5 [libj9thr29.so+0x7cc5])
      - (0x00007FBAD5F68F2C [libj9vm29.so+0xc9f2c])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5F6842A [libj9vm29.so+0xc942a])
      - (0x00007FBAD606ABAB [libjvm.so+0xfbab])
      - (0x00007FBAD6BD8326 [libjli.so+0x10326])
      - (0x00007FBAD6A2EAC3 [libc.so.6+0x94ac3])
      - (0x00007FBAD6AC0850 [libc.so.6+0x126850])
    - **Java Thread ID:** 0x7C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E48
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** CW
    - **VM Thread Flags:** 0x00000081
    - **Stack Range:**
      - **From:** 0x00007FBAD6098000,
      - **To:** 0x00007FBAD6898000,
      - **Size:** 0x800000

    - **CPU Usage:** 0.289103540
    - **Category:** Application
    - **Heap Allocation:** 4128


###  - **Name:** Thread-27
  - **J9VMThread:** 0x000000000020B800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x33
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7B
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD1FF000,
      - **To:** 0x00007FBACD23F000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.011179610
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-19
  - **J9VMThread:** 0x00000000001ED800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E73
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD407000,
      - **To:** 0x00007FBACD447000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.013269450
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-14
  - **J9VMThread:** 0x00000000001DAC00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x26
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6E
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD54C000,
      - **To:** 0x00007FBACD58C000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012440200
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-9
  - **J9VMThread:** 0x00000000001C8000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x21
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E69
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD691000,
      - **To:** 0x00007FBACD6D1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010251300
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-41
  - **J9VMThread:** 0x0000000000240000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x41
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E89
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCE71000,
      - **To:** 0x00007FBACCEB1000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.008557980
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-35
  - **J9VMThread:** 0x0000000000229800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x3B
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E83
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCFF7000,
      - **To:** 0x00007FBACD037000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.007109380
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-26
  - **J9VMThread:** 0x0000000000207C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x32
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E7A
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD240000,
      - **To:** 0x00007FBACD280000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010768890
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-22
  - **J9VMThread:** 0x00000000001F8C00,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x2E
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E76
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD344000,
      - **To:** 0x00007FBACD384000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010270720
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-40
  - **J9VMThread:** 0x000000000023C400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x40
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E88
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCEB2000,
      - **To:** 0x00007FBACCEF2000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.010927950
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-68
  - **J9VMThread:** 0x00000000002A5400,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x5C
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EA4
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC796000,
      - **To:** 0x00007FBACC7D6000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.016429660
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-15
  - **J9VMThread:** 0x00000000001DE800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x27
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E6F
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACD50B000,
      - **To:** 0x00007FBACD54B000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.012389900
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-49
  - **J9VMThread:** 0x000000000025E000,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x49
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2E91
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACCC69000,
      - **To:** 0x00007FBACCCA9000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.009380000
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


###  - **Name:** Thread-91
  - **J9VMThread:** 0x00000000002FB800,
  - **State:** B
  - **Priority:** 5
  - **Details:**
    - **Java Call Stack:**
      - at XYZExample.XYZMethod(XYZExample.java:15)
      - at XYZExample.lambda$main$0(XYZExample.java:6)
      - at XYZExample$$Lambda$1/0x00000000d031f720.run(Bytecode PC:0)
      - at java/lang/Thread.run(Thread.java:821)
    - **Native Call Stack:**
      - (0x00007FBAD5E4B9B2 [libj9prt29.so+0x5d9b2])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4BE8E [libj9prt29.so+0x5de8e])
      - (0x00007FBAD5E154A9 [libj9prt29.so+0x274a9])
      - (0x00007FBAD5E4B837 [libj9prt29.so+0x5d837])
      - (0x00007FBAD5E4821C [libj9prt29.so+0x5a21c])
      - (0x00007FBAD69DC520 [libc.so.6+0x42520])
      - (0x00007FBAD6A2B115 [libc.so.6+0x91115])
      - pthread_cond_wait+0x211 (0x00007FBAD6A2DA41 [libc.so.6+0x93a41])
      - (0x00007FBAD5E8CB8C [libj9thr29.so+0x6b8c])
      - (0x00007FBAD5E8DE26 [libj9thr29.so+0x7e26])
      - (0x00007FBAD5F36A22 [libj9vm29.so+0x97a22])
      - (0x00007FBAD5EC7A52 [libj9vm29.so+0x28a52])
      - (0x00007FBAD5EB23E4 [libj9vm29.so+0x133e4])
      - (0x00007FBAD5F97FD2 [libj9vm29.so+0xf8fd2])
    - **Java Thread ID:** 0x73
    - **Is Daemon:** false
    - **Class Loader:** sun/misc/Launcher$AppClassLoader(0x00000000FFE0BA00)
    - **Native Thread ID:** 0x1B2EBB
    - **Native Priority:** 0x5
    - **Native Policy:** UNKNOWN
    - **VM State:** B
    - **VM Thread Flags:** 0x00000281
    - **Stack Range:**
      - **From:** 0x00007FBACC1BF000,
      - **To:** 0x00007FBACC1FF000,
      - **Size:** 0x40000

    - **CPU Usage:** 0.028879890
    - **Category:** Application
    - **Blocked On:**
      - **Object:** java/lang/Object@0x00000000FFE0D4A0
      - **Owned By:** Thread-4

    - **Heap Allocation:** 0


#### CPU Usage Summary

- **Warning:** Warning: to get more accurate CPU times for the GC, the option -XX:-ReduceCPUMonitorOverhead can be used. See the user guide for more information.
- **All JVM attached threads:** 2.066558000 secs
- **SystemJVM:** 0.879602000 secs
- **GC:** 0.038902000 secs
- **JIT:** 0.392191000 secs
- **Application:** 1.186956000 secs


