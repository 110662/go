# go
Perl script to transport directory of aim.

#~/.bash_profile
# To add follow to ".bash_profile".

go() {
    cd $(/home/tochibow9/script/go/disp.pl $1)
    ls -F
}

