SeLinux:  
    system_server.te:  
        # for log record  
        allow system_server logd_socket:sock_file write;  

