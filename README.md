# Linux-NetSpeed
# BBRV2-test```

查看当前支持TCP算法
cat /proc/sys/net/ipv4/tcp_allowed_congestion_control
查看当前运行的算法
cat /proc/sys/net/ipv4/tcp_congestion_control
查看当前队列算法
sysctl net.core.default_qdisc

命令： uname -a
作用： 查看系统内核版本号及系统名称



