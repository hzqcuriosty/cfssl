> cfssl工具包

    cfssl.tar.gz
> 从github clone

    git clone https://github.com/hzqcuriosty/cfssl.git
    
> 解压添加权限

    cd cfssl && tar xf cfssl.tar.gz
    
> 拷贝文件到bin目录

    cp cfssl cfssl-certinfo  cfssljson  /usr/bin && chmod +x /usr/bin/{cfssl,cfssl-certinfo,cfssljson}
