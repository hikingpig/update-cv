- computer hardware
- concepts
  - processes
  - address spaces
  - files
  - input/output
  - protection
  - the shell

- system calls
  - process management
  - file management
  - directory management

- processes and threads
  - processes
    - process model
    - creating, termination
    - process hierarchies
    - process states
    - implementation
  - threads
    - thread models
    - thread usages
    - implementing thread in user space
    - implementing thread in kernel space
    - hybrid implementation
    - scheduler activation
  - interprocess communication
    - race conditions
    - critical regions
    - mutual exclusions with busy waiting
    - sleep and wakeup
    - semaphores
    - mutexes
    - monitors
    - message passing
    - barriers
    - avoding locks: read-copy-update

  - scheduling
    - batch systems
    - interactive systems
    - real-time systems
    - thread scheduling
  
  - classical problems
    - dining philosophers problem
    - readers and writers problem

- Memory Management
  - Memory abstraction: Address spaces
  - Virtual Memory
    - paging
    - page tables
    - speeding up paging
    - page tables for large memory
  - Page Replacement Algorithms
    - Optimal
    - Not Recently Used
    - First-In, First-Out
    - Second-change
    - Clock
    - Least Recently Used
    - Working Set
    - WSClock
  - Paging system design
    - local vs global allocation policies
    - Load control
    - Page Size
    - Separate instructions and data pages
    - Shared Pages
    - Shared Libraries
    - Mapped Files
    - Cleaning Policy
    - Virtual Memory Interface

  - Implementation Issues
    - Operating System involvement
    - Page Fault Handling
    - Instruction Backup
    - Backing Store

  - Segmentation
    - Pure segmentation
    - Segmentation with paging: x86

- Files
  - Files
    - naming
    - structure
    - types
    - access
    - attributes
    - operations
    - system calls
  - Directory
    - Directory systems
    - Path names
    - Operations
  - File System Implementation
    - Layout
    - Implementing Files
    - Implementing Directories
    - Shared Files
    - Log-Structured File Systems
    - Journal File Systems
    - Virtual File Systems

  - File System Management and Optimization
    - Disk-space management
    - Backups
    - Consistency
    - Performance
    - Defragmenting Disks

- Input/Output
  - Principles of I/O hardware
    - I/O devices
    - Device Controllers
    - Memory-mapped I/O
    - Direct Memory Access
    - Interrupts

  - Principles of I/O software
    - goals
    - programmed I/O
    - interrupt-driven I/O
    - I/O using DMA

  - I/O software layers
    - interrupt handlers
    - device drivers
    - device independent I/O software
    - user-space I/O software

  - Disks
    - Disk Hardware
    - Disk Formatting
    - Disk Arm scheduling algorithms
    - Error Handling
    - Stable Storage

  - Clocks
    - clock hardware
    - clock software
    - soft timers

  - user interfaces: keyboards, mouses, monitors
    - input software
    - output software

  - power management:
    - Hardware issues
    - Operating System Issues
    - Application Programm Issues

- Deadlocks
  - Resources
    - Preemptable and Nonpreemptable resources
    - Resource Acquisition
  - Deadlocks
    - Conditions for Deadlocks
    - Deadlock modeling
  
  - The Ostrich algorithm
  - Deadlock detection and recovery
  - Deadlock avoidance
    - resource trajectories
    - safe and unsafe states
    - the banker's algorithm
  - Deadlock prevention
    - mutual-exclusion condition
    - hold-and-wait condition
    - no-preemption condition
    - circular wait condition
  
  - other issues
    - two-phase locking
    - communication deadlocks
    - livelocks
    - starvation

- virtualization
  - cost of virtualization
  - type 1 and type 2 hypervisors
  - memory virtualization
  - I/O virtualization
  - virtual machines on multicore CPUs

- multiple processor systems
  - multiprocessors
    - hardware
    - operating systems
    - synchronization
    - scheduling
  - multicomputers
    - hardware
    - low-level communication
    - user-level communication
    - remote procedure call
    - distributed shared memory
    - scheduling
    - load balancing
  
  - distributed systems
    - hardware
    - services and protocols
    - document-based middleware
    - file-system based middleware
    - object-based middleware
    - coordinator-based middleware
  
- Security
  - Environment
    - Threats
    - Attackers
  - Controlling access to resources
    - protection domains
    - access control lists
    - capabilities
  - Covert Channels
  - Cryptography
    - Secret-Key
    - Public-Key
    - One-way functions
    - Digital Signatures
    - Trusted Platform Modules
  
  - Authentication 
    - using physical objects
    - using biometrics
  
  - exploiting software
    - buffer-overflow attacks
    - format string attacks
    - dangling pointers
    - null pointer dereference attacks
    - integer overflow attacks
    - command injection attacks
    - time of check to time of use attacks

  - insider attacks
    - Logic bombs
    - Back doors
    - Login Spoofing
  
  - malware
    - trojan horses
    - viruses
    - worms
    - spyware
    - rootkits

  - defenses
    - firewalls
    - antivirus
    - code signing
    - jailing
    - model-based intrusion detection
    - encapsulating mobile code
    - java security

- linux
  - overview
    - interfaces to linux
    - the shell
    - linux utility programs
    - kernel structures
  - processes in linux
    - concepts
    - system calls for process managements
    - implementation of processes and threads
    - scheduling
    - booting
  - memory management in linux
    - concepts
    - system calls
    - implementation
    - paging
  - input/output
    - concepts
    - file system calls
    - implementation of the Linux file system
    - NFS: Network File System
  - Security
    - concepts
    - security system calls
    - implementation

- android
  - design goals
  - architecture
  - linux extensions
  - Dalvik
  - Binder IPC
  - Android applications
  - Intents
  - Application Sandboxes
  - Security
  - Process Model

