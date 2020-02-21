# Micropytho on Unikraft

To build and run this application please use the `kraft` script:

    pip3 install git+https://github.com/unikraft/kraft.git
    mkdir my-micropython && cd my-micropython
    kraft up -p PLATFORM -m ARCHITECTURE -a micropython my-micropython

For more information about `kraft` type ```kraft -h``` or read the
[documentation](http://docs.unikraft.org).
