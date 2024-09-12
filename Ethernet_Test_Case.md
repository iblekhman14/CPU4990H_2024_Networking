9/12/2024 Roughly around 1PM

Testing the network conditions inside the library using three desktops all of them right next to each other. They will be called left, middle and right. The goal of this test is to determine if the issue is with the wireless access points or if the network itself can't handle a lot of traffic. The idea being that if I jam two computers on the same switch with full network utilization will that affect the other devices on the network?

Left(All connected to same switch yet this might either be misconfigured or just on a 100mb port)
 ![Computer1](https://github.com/user-attachments/assets/84e7e753-fda0-4056-a35f-26ba49b441fe)

Middle
 ![computer2](https://github.com/user-attachments/assets/2b7d1ec4-f75d-4937-97c5-b02faf2c4a61)

Right
 ![computer3](https://github.com/user-attachments/assets/8eaba934-8a9b-4144-ba9b-856a954916a1)

Either way for now after jamming the network with 2GB down and upload simultaneously the network performance did not suffer in terms of ping at all.
There are no spikes necessary. If we test multiple devices on the wireless network running a speedtest and then checking ping there will likely be a big drop. Will confirm later...


C:\Users\iblekhman>ping  134.71.58.1 -n 1000

Pinging 134.71.58.1 with 32 bytes of data:
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=4ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=2ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=3ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=4ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=2ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64

Ping statistics for 134.71.58.1:
    Packets: Sent = 122, Received = 122, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 4ms, Average = 0ms
Control-C
^C
C:\Users\iblekhman>ping  134.71.58.1 -n 1000

Pinging 134.71.58.1 with 32 bytes of data:
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=3ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time<1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
Reply from 134.71.58.1: bytes=32 time=1ms TTL=64
