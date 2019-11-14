# Mopidy and Snapserver x64

Usage

    $ docker run -itd \
        --name <name> \
        --restart=always \ 
        --network=<bridge name> --ip=<ip> \ 
        -p 1704:1704 \
        -p 1705:1705 \
        -p 5353:5353 \
        -p 6680:6680 \
        -p 6600:6600 \
        -v <location>:/usr/home \
        -v <location>:/var/lib/mopidy/media
  
  Config files are located in /usr/home/.config
