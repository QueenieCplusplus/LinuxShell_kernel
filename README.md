# LinuxShell_kernel

* uname -option

        ✗ uname -m
        x86_64

        ✗ uname -s
        Darwin

        ✗ uname -v
        Darwin Kernel Version 19.4.0: Wed Mar  4 22:28:40 PST 2020; 
        root:xnu-6153.101.6~15/RELEASE_X86_64

        ✗ uname -n
        Pintde-MacBook-Pro.local

        ✗ uname -p
        i386
        
        ✗ uname -a
        Darwin Pintde-MacBook-Pro.local 19.4.0 
        Darwin Kernel Version 19.4.0: 
        Wed Mar  4 22:28:40 PST 2020; 
        root:xnu-6153.101.6~15/RELEASE_X86_64 x86_64

* hostname

        ✗ hostname
        Pintde-MacBook-Pro.local
        
        usage: hostname [-fs] [name-of-host]
        
        -a, alias
        -d, domain name (not host name)
        -f, full hostname + domain name
        -F [filename], 將主機名稱設定為檔案中的指定名稱
        -h, help
        -i, ip addr of host
        -n, 查詢 DECnet 網路節點名稱。
        -s, suffix
        -v, 顯示指令執行過程。
        -V, version
        -y, 查詢 NIS 網域名稱。
        
* host

         ✗ host
        Usage: host [-aCdilrTvVw] [-c class] [-N ndots] [-t type] [-W time]
                    [-R number] [-m flag] hostname [server]
               -a is equivalent to -v -t ANY
               -c specifies query class for non-IN data
               -C compares SOA records on authoritative nameservers
               -d is equivalent to -v
               -i IP6.INT reverse lookups
               -l lists all hosts in a domain, using AXFR
               -m set memory debugging flag (trace|record|usage)
               -N changes the number of dots allowed before root lookup is done
               -r disables recursive processing
               -R specifies number of retries for UDP packets
               -s a SERVFAIL response should stop query
               -t specifies the query type
               -T enables TCP/IP mode
               -v enables verbose output
               -V print version number and exit
               -w specifies to wait forever for a reply
               -W specifies how long to wait for a reply
               -4 use IPv4 query transport only
               -6 use IPv6 query transport only
