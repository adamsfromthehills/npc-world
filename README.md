**First commit**

 If you’re on a Windows machine, set it to true – this converts LF endings into CRLF when you check out code:

$ git config --global core.autocrlf true

If you’re on a Linux or Mac system that uses LF line endings, then you don’t want Git to automatically convert them when you check out files; however, if a file with CRLF endings accidentally gets introduced, then you may want Git to fix it. You can tell Git to convert CRLF to LF on commit but not the other way around by setting core.autocrlf to input:

$ git config --global core.autocrlf input
