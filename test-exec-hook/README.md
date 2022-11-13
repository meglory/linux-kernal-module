# linux-kernel-module

"Hello World" Linux Kernel Module

Read simple output example messages in /var/log/messages

to install...

make

insmod test.ko

tail -n 1 /var/log/messages

rmmod test

tail -n 10 /var/log/messages