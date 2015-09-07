Embedded-toolkit
==

Embedded-toolkit是用来收集能够直接在嵌入式平台上运行的小工具的工具箱，比如各平台下的gdb、gdbserver、tcpdump等等。  
创建这个目录主要目的也是为了方便直接分析、调试各平台的程序。不用在需要的时候每次都自己去重新交叉编译。  
本目录主要收集Binary。   
希望大家也都补充。  

##Directory structure
GEmbedded-tools/  
├── arm  
│   ├── gdb  
│   ├── gdbserver  
│   ├── gdbserver.self  
│   ├── README  
│   └── tcpdump  
└── mips  
    ├── LSB  
    │   ├── gdb-linux.mipsle  
    │   ├── gdb.mipsle  
    │   ├── gdbserver  
    │   ├── gdbserver.mipsle  
    │   ├── README.md  
    │   └── tcpdump.mipsle  
    └── MSB  
        ├── gdb.mipsbe  
        ├── gdbserver.mipsbe  
        └── README.md  

##Cross compile

![cross_compile.pdf](./cross_compile.pdf)
