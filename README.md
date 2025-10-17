Process_Informer (LKM) : a Kernel Module to extract process information from kernel structures
              USAGE:
              
                    sudo insmod Process_Informer.ko tpid=<PID>
                    
You see results using dmesg or in /var/log/kern.log
Process_Informer deveoped in training procedure at kernel(version 4.18.0) and may not work properly at newer versions of kernel, i will update it as soon as possible with more features

