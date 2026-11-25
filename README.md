		LINUX CAPABILITY


compile:    gcc bindport.c -o bindport

run without root-level privilege:   ./bindport

run with root-level privilege:     sudo ./bindport

assign capability to bindport :    sudo setcap cap_net_bind_service=ep ./bindport

see the set capability:            getcap ./bindport

run without root-level privilege:  ./bindport
