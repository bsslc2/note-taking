# note-taking
As being a resources for Linux use, the useful system knowledge and codes.

1. How to Release mememory in ubuntu:  
watch -n 1 free -m

#echo Freeing the page cache:
> echo 1 > /proc/sys/vm/drop_caches (or sudo sysctl -w vm.drop_caches=3)
#echo Free dentries and inodes:
> echo 2 > /proc/sys/vm/drop_caches
#echo Free the page cache, dentries and the inodes:
> echo 3 > /proc/sys/vm/drop_caches

2.windows Linux data sharing:
> sudo mount -t vboxsf Documents /home/ubuntu/Documents/data_share

