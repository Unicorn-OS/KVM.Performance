# split_lock_detect=off
sch: https://www.google.com/search?q=KVM+split_lock_detect

# Guide:
https://x86.lol/generic/2023/11/07/split-lock.html

# Discuss:
https://www.reddit.com/r/linux_gaming/comments/10pg9rn/new_cpu_much_better_performances_then_much_worse/

# test:
>Alternatively, the punishment can be disabled by writing 0 into /proc/sys/kernel/split_lock_mitigate.

`cat /proc/sys/kernel/split_lock_mitigate`
