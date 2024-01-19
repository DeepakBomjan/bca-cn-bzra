```bash
loud_user@87cc425a423c:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
cloud_user@87cc425a423c:~$ cd Desktop
cloud_user@87cc425a423c:~/Desktop$ ls
cloud_user@87cc425a423c:~/Desktop$ cat > sample.txt
Hello I am learning linux.
cloud_user@87cc425a423c:~/Desktop$
cloud_user@87cc425a423c:~/Desktop$ ls
sample.txt
cloud_user@87cc425a423c:~/Desktop$ cat sample.txt
Hello I am learning linux.
cloud_user@87cc425a423c:~/Desktop$ pwd
/home/cloud_user/Desktop
cloud_user@87cc425a423c:~/Desktop$ mkdir myfolder
cloud_user@87cc425a423c:~/Desktop$ ls
myfolder  sample.txt
cloud_user@87cc425a423c:~/Desktop$ cd myfolder
cloud_user@87cc425a423c:~/Desktop/myfolder$ ls
cloud_user@87cc425a423c:~/Desktop/myfolder$ ls
cloud_user@87cc425a423c:~/Desktop/myfolder$ vi mynewfile.txt
cloud_user@87cc425a423c:~/Desktop/myfolder$ ls -l
total 4
-rw-rw-r-- 1 cloud_user cloud_user 53 Jan 19 01:25 mynewfile.txt
cloud_user@87cc425a423c:~/Desktop/myfolder$ ls -l
total 4
-rw-rw-r-- 1 cloud_user cloud_user 53 Jan 19 01:25 mynewfile.txt
cloud_user@87cc425a423c:~/Desktop/myfolder$ cat mynewfile.txt
Hello this is my first file created using vi editor.
cloud_user@87cc425a423c:~/Desktop/myfolder$
```