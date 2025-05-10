# Thread Information and Field Descriptions

## Thread Information
- **Thread Name_J9VMThread**: Each thread is identified with a unique combination of its name and the J9VMThread identifier. For example, **Worker-10_0x000000013D1A3E00**. This helps in uniquely identifying the thread among others.

## Timestamps and Details
Each timestamp represents a snapshot of the thread's state at a specific moment in time. The details under each timestamp provide information about the thread's behavior and resource usage.

### Timestamp
- **Timestamp**: This indicates the exact date and time when the snapshot was taken. The timestamp has two parts:
  - **Date**: In the format **yyyy/mm/dd**. For example, **2025/04/30**.
  - **Time**: In the format **hour:minute:second:millisecond**. For example, **17:33:08:559**.

### Thread State
- **Thread State**: This field describes the current state of the thread. Common states include:
  - **Runnable**: The thread is ready to run and is waiting for CPU time.
  - **Condition Wait**: The thread is waiting for a specific condition to be met.
  - **Suspended**: The thread is temporarily paused.
  - **Zombie**: The thread has finished execution but has not yet been cleaned up by the system.
  - **Parked**: The thread is parked, waiting for a signal to continue.
  - **Blocked**: The thread is waiting for a resource, such as a lock, to become available.

### CPU Usage
- **CPU Usage**: This field indicates the amount of CPU time the thread has used, expressed in seconds. For example, **0.012340000** means the thread has used 0.01234 seconds of CPU time.

### Blocked On
- **Blocked On**: This section is populated only when the thread state is **Blocked**. It provides details about the resource the thread is waiting for. If the thread is not blocked, this field is specified as **Not Applicable**. When populated it includes:
  - **Object**: The specific object the thread is blocked on, often a lock or monitor. For example, **java/util/concurrent/locks/ReentrantLock@0x000000030007BF20**.
  - **Owned By**: The thread that currently holds the resource the blocked thread is waiting for. For example, **Worker-7**.

### Java Call Stack
- **Java Call Stack**: This is a list of method calls that were active in the thread at the time of the snapshot. It shows the sequence of method calls leading up to the current point. Each entry includes:
  - **Class and Method**: The class and method where the call occurred. For example, **com/example/pipeline/TaskQueue.dequeue**.
  - **File and Line Number**: The source file and line number where the method call is located. For example, **TaskQueue.java:120**.

## Example Breakdown
Let's break down one of the timestamps as an example:

### Complete Thread
### - **Worker-10_0x000000013D1A3E00**:
  - **thread_name**: Worker-10  
  - **J9VMThread**: 0x000000013D1A3E00  
  - **timestamps**:
    - **2025/04/30 17:33:08:559**:
      - **thread_state**: Blocked  
      - **cpu_usage**: 0.012340000  
      - **blocked_on**:
        - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007BF20  
        - **Owned By**: Worker-7
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.dequeue(TaskQueue.java:120)  
        - com/example/pipeline/TaskProcessor.process(TaskProcessor.java:89)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:33:48:655**:
      - **thread_state**: Blocked  
      - **cpu_usage**: 0.014560000  
      - **blocked_on**:
        - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007BF20  
        - **Owned By**: Worker-6
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.dequeue(TaskQueue.java:120)  
        - com/example/pipeline/TaskProcessor.process(TaskProcessor.java:89)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:34:38:800**:
      - **thread_state**: Runnable  
      - **cpu_usage**: 0.018670000  
      - **blocked_on**: None  
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.dequeue(TaskQueue.java:120)  
        - com/example/pipeline/TaskProcessor.process(TaskProcessor.java:89)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)

### Breakdown of Timestamp: 2025/04/30 17:33:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.012340000
- **Blocked On**:
  - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007BF20
  - **Owned By**: Worker-7
- **Java Call Stack**:
  - **com/example/pipeline/TaskQueue.dequeue(TaskQueue.java:120)**
  - **com/example/pipeline/TaskProcessor.process(TaskProcessor.java:89)**
  - **com/example/pipeline/Worker.run(Worker.java:48)**
  - **java/lang/Thread.run(Thread.java:833)**


## Additional Examples


### - **pool-1-thread-1_0x000000012C1A4F00**:
  - **thread_name**: pool-1-thread-1
  - **J9VMThread**: 0x000000012C1A4F00
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Condition Wait
      - **cpu_usage**: 0.022676000
      - **blocked_on**: Not Applicable
      - **Java_Call_Stack**:
        - java/lang/Thread.sleepImpl(Native Method)
        - java/lang/Thread.sleep(Thread.java:516)
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:92)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Condition Wait
      - **cpu_usage**: 0.025515000
      - **blocked_on**: Not Applicable
      - **Java_Call_Stack**:
        - java/lang/Thread.sleepImpl(Native Method)
        - java/lang/Thread.sleep(Thread.java:516)
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:92)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.033531000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-2
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Condition Wait
- **CPU Usage**: 0.022676000
- **Blocked On**: Not Applicable
- **Java Call Stack**:
  - **java/lang/Thread.sleepImpl(Native Method)**
  - **java/lang/Thread.sleep(Thread.java:516)**
  - **DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:92)**
  - **DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)**
  - **DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)**
  - **java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)**
  - **java/util/concurrent/FutureTask.run(FutureTask.java:317)**
  - **java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)**
  - **java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)**
  - **java/lang/Thread.runWith(Thread.java:1608)**
  - **java/lang/Thread.run(Thread.java:1595)**

### - **pool-1-thread-2_0x000000011B8FF100**:
  - **thread_name**: pool-1-thread-2
  - **J9VMThread**: 0x000000011B8FF100
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.003229000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.013853000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Condition Wait
      - **cpu_usage**: 0.020938000
      - **blocked_on**: Not Applicable
      - **Java_Call_Stack**:
        - java/lang/Thread.sleepImpl(Native Method)
        - java/lang/Thread.sleep(Thread.java:516)
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:92)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.003229000
- **Blocked On**:
  - **Object**: java/lang/Object@0x0000000300059FD0
  - **Owned By**: pool-1-thread-1
- **Java Call Stack**:
  - **DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)**
  - **DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)**
  - **DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)**
  - **java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)**
  - **java/util/concurrent/FutureTask.run(FutureTask.java:317)**
  - **java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)**
  - **java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)**
  - **java/lang/Thread.run(Thread.java:1595)**


### - **pool-1-thread-3_0x000000011B905300**:
  - **thread_name**: pool-1-thread-3
  - **J9VMThread**: 0x000000011B905300
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.004144000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.016417000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.021554000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-2
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.004144000
- **Blocked On**:
  - **Object**: java/lang/Object@0x0000000300059FD0
  - **Owned By**: pool-1-thread-1
- **Java Call Stack**:
  - **DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)**
  - **DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)**
  - **DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)**
  - **java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)**
  - **java/util/concurrent/FutureTask.run(FutureTask.java:317)**
  - **java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))**
  - **java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)**
  - **java/lang/Thread.runWith(Thread.java:1608)**
  - **java/lang/Thread.run(Thread.java:1595)**


### - **pool-1-thread-4_0x000000011B90D100**:
  - **thread_name**: pool-1-thread-4
  - **J9VMThread**: 0x000000011B90D100
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.003684000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.015156000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.020052000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-2
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.003684000
- **Blocked On**:
  - **Object**: java/lang/Object@0x0000000300059FD0
  - **Owned By**: pool-1-thread-1
- **Java Call Stack**:
  - **DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)**
  - **DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)**
  - **DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)**
  - **java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)**
  - **java/util/concurrent/FutureTask.run(FutureTask.java:317)**
  - **java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))**
  - **java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)**
  - **java/lang/Thread.runWith(Thread.java:1608)**
  - **java/lang/Thread.run(Thread.java:1595)**


### - **pool-1-thread-5_0x000000011B913D00**:
  - **thread_name**: pool-1-thread-5
  - **J9VMThread**: 0x000000011B913D00
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.004614000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.016494000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-1
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Blocked
      - **cpu_usage**: 0.021498000
      - **blocked_on**:
        - **Object**: java/lang/Object@0x0000000300059FD0
        - **Owned By**: pool-1-thread-2
      - **Java_Call_Stack**:
        - DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)
        - DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)
        - DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)
        - java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)
        - java/util/concurrent/FutureTask.run(FutureTask.java:317)
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
        - java/lang/Thread.runWith(Thread.java:1608)
        - java/lang/Thread.run(Thread.java:1595)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.004614000
- **Blocked On**:
  - **Object**: java/lang/Object@0x0000000300059FD0
  - **Owned By**: pool-1-thread-1
- **Java Call Stack**:
  - **DataPipelineExecutor.runJobWithIO(DataPipelineExecutor.java:71)**
  - **DataPipelineExecutor.lambda$main$0(DataPipelineExecutor.java:39)**
  - **DataPipelineExecutor$$Lambda/0x00000000318d0e88.run(Bytecode PC:4)**
  - **java/util/concurrent/Executors$RunnableAdapter.call(Executors.java:572)**
  - **java/util/concurrent/FutureTask.run(FutureTask.java:317)**
  - **java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144(Compiled Code))**
  - **java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)**
  - **java/lang/Thread.runWith(Thread.java:1608)**
  - **java/lang/Thread.run(Thread.java:1595)**


### - **Worker-1_0x000000013D1A2C00**:
  - **thread_name**: Worker-1  
  - **J9VMThread**: 0x000000013D1A2C00  
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Runnable  
      - **cpu_usage**: 2.513674000  
      - **blocked_on**: Not Applicable  
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskProcessor.process(TaskProcessor.java:85)  
        - com/example/pipeline/Worker.run(Worker.java:42)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Runnable  
      - **cpu_usage**: 2.679001000  
      - **blocked_on**: Not Applicable  
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskProcessor.process(TaskProcessor.java:91)  
        - com/example/pipeline/Worker.run(Worker.java:42)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Waiting  
      - **cpu_usage**: 0.015301000  
      - **blocked_on**: Not Applicable  
      - **Java_Call_Stack**:
        - java/util/concurrent/locks/LockSupport.park(LockSupport.java:194)  
        - java/util/concurrent/SynchronousQueue$TransferStack.awaitFulfill(SynchronousQueue.java:460)  
        - java/util/concurrent/SynchronousQueue.take(SynchronousQueue.java:924)  
        - java/util/concurrent/ThreadPoolExecutor.getTask(ThreadPoolExecutor.java:1053)  
        - java/util/concurrent/ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)  
        - java/util/concurrent/ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628)  
        - java/lang/Thread.run(Thread.java:833)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Runnable
- **CPU Usage**: 2.513674000
- **Blocked On**: Not Applicable
- **Java Call Stack**:
  - **com/example/pipeline/TaskProcessor.process(TaskProcessor.java:85)**
  - **com/example/pipeline/Worker.run(Worker.java:42)**
  - **java/lang/Thread.run(Thread.java:833)**

### - **Worker-2_0x000000013D1A2D00**:
  - **thread_name**: Worker-2  
  - **J9VMThread**: 0x000000013D1A2D00  
  - **timestamps**:
    - **2025/04/30 17:31:08:559**:
      - **thread_state**: Blocked  
      - **cpu_usage**: 0.005120000  
      - **blocked_on**:
        - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007AF10  
        - **Owned By**: Worker-5  
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.enqueue(TaskQueue.java:102)  
        - com/example/pipeline/TaskRetrier.retry(TaskRetrier.java:67)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:31:48:655**:
      - **thread_state**: Blocked  
      - **cpu_usage**: 0.006230000  
      - **blocked_on**:
        - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007AF10  
        - **Owned By**: Worker-9
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.enqueue(TaskQueue.java:102)  
        - com/example/pipeline/TaskRetrier.retry(TaskRetrier.java:67)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)
    - **2025/04/30 17:32:38:800**:
      - **thread_state**: Blocked  
      - **cpu_usage**: 0.009870000  
      - **blocked_on**:
        - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007AF10  
        - **Owned By**: Worker-8  
      - **Java_Call_Stack**:
        - com/example/pipeline/TaskQueue.enqueue(TaskQueue.java:102)  
        - com/example/pipeline/TaskRetrier.retry(TaskRetrier.java:67)  
        - com/example/pipeline/Worker.run(Worker.java:48)  
        - java/lang/Thread.run(Thread.java:833)

### Breakdown of Timestamp: 2025/04/30 17:31:08:559
- **Thread State**: Blocked
- **CPU Usage**: 0.005120000
- **Blocked On**:
  - **Object**: java/util/concurrent/locks/ReentrantLock@0x000000030007AF10
- **Java Call Stack**:
  - **com/example/pipeline/TaskQueue.enqueue(TaskQueue.java:102)**
  - **com/example/pipeline/TaskRetrier.retry(TaskRetrier.java:67)**
  - **com/example/pipeline/Worker.run(Worker.java:48)**
  - **java/lang/Thread.run(Thread.java:833)**
