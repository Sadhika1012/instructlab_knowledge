| | | | | | | | | | | | | | |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|log_id|Jvm_info|Jre_info| | | | |threads| | | | | | |
| | |jre_version|os|architecture|jit_enabled|aot_enabled|thread_name|priority|thread_id|state|stack_trace|waiting_for|held_by|
|2025-02-14T11:35:06.887957|Virtual machine: 32151 JVM information:|21|Mac OS X aarch64-64-Bit 20241015_301|aarch64-64-Bit|TRUE|TRUE|JIT Compilation Thread-000|10|4|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-001 Suspended|10|5|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-002 Suspended|10|6|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-003 Suspended|10|7|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-004 Suspended|10|8|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-005 Suspended|10|9|RUNNABLE| | | |
| | | | | | | |JIT Compilation Thread-006 Suspended|10|10|RUNNABLE| | | |
| | | | | | | |JIT Diagnostic Compilation Thread-007 Suspended|10|11|RUNNABLE| | | |
| | | | | | | |JIT-SamplerThread|10|12|TIMED_WAITING| | | |
| | | | | | | |IProfiler|5|13|RUNNABLE| | | |
| | | | | | | |Common-Cleaner|8|3|TIMED_WAITING|at java.base@21.0.5/java.lang.Object.waitImpl(Native Method)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Object.wait(Object.java:255)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Object.wait(Object.java:221)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.ref.ReferenceQueue.remove(ReferenceQueue.java:137)| | |
| | | | | | | | | | | |at java.base@21.0.5/jdk.internal.ref.CleanerImpl.run(CleanerImpl.java:140)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Thread.run(Thread.java:1595)| | |
| | | | | | | | | | | |at java.base@21.0.5/jdk.internal.misc.InnocuousThread.run(InnocuousThread.java:186)| | |
| | | | | | | |Concurrent Mark Helper|1|14|RUNNABLE| | | |
| | | | | | | |GC Worker|5|15|RUNNABLE| | | |
| | | | | | | |GC Worker|5|16|RUNNABLE| | | |
| | | | | | | |GC Worker|5|17|RUNNABLE| | | |
| | | | | | | |GC Worker|5|18|RUNNABLE| | | |
| | | | | | | |GC Worker|5|19|RUNNABLE| | | |
| | | | | | | |GC Worker|5|20|RUNNABLE| | | |
| | | | | | | |GC Worker|5|21|RUNNABLE| | | |
| | | | | | | |GC Worker|5|22|RUNNABLE| | | |
| | | | | | | |GC Worker|5|23|RUNNABLE| | | |
| | | | | | | |GC Worker|5|24|RUNNABLE| | | |
| | | | | | | |GC Worker|5|25|RUNNABLE| | | |
| | | | | | | |Finalizer thread|5|28|RUNNABLE| | | |
| | | | | | | |Thread-0|5|29|BLOCKED|at app//ekrflku7e5.lambda$jv9k5j4ftb$8(ekrflku7e5.java:72)|java.util.LinkedList@c6cc93a3|Thread-1|
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Thread.run(Thread.java:1595)| | |
| | | | | | | |Attach API wait loop|10|30|TIMED_WAITING|at java.base@21.0.5/java.lang.Thread.sleepImpl(Native Method)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Thread.sleep(Thread.java:516)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.WaitLoop.checkReplyAndCreateAttachment(WaitLoop.java:142)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.WaitLoop.waitForNotification(WaitLoop.java:117)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.WaitLoop.run(WaitLoop.java:157)| | |
| | | | | | | |Thread-1|5|31|BLOCKED|at app//ekrflku7e5.lambda$jv9k5j4ftb$11(ekrflku7e5.java:85)|java.util.ArrayDeque@25768791|Thread-0|
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Thread.run(Thread.java:1595)| | |
| | | | | | | |file lock watchdog|10|33|TIMED_WAITING|at java.base@21.0.5/java.lang.Object.waitImpl(Native Method)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Object.wait(Object.java:255)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.lang.Object.wait(Object.java:221)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.util.TimerThread.mainLoop(Timer.java:570)| | |
| | | | | | | | | | | |at java.base@21.0.5/java.util.TimerThread.run(Timer.java:523)| | |
| | | | | | | |DestroyJavaVM helper thread|5|34|RUNNABLE| | | |
| | | | | | | |Attachment portNumber: 57279|10|35|RUNNABLE|at java.base@21.0.5/openj9.internal.tools.attach.target.DiagnosticUtils.dumpAllThreadsImpl(Native Method)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.DiagnosticUtils.getThreadInfo(DiagnosticUtils.java:249)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.DiagnosticUtils.executeDiagnosticCommand(DiagnosticUtils.java:185)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.Attachment.doCommand(Attachment.java:249)| | |
| | | | | | | | | | | |at java.base@21.0.5/openj9.internal.tools.attach.target.Attachment.run(Attachment.java:160)| | |
