Initilising and cloning a git repository on QNAP NAS


Initialize repo
---

(1) SSH to QNAP

```
$ ssh -p 23 ACCOUNT_NAME@QNAP_IP
$ PASSWORD
```

(2) Navigate to git folder

```
# cd /share/Dan/git
```

(3) Create repo

```
# git init --bare REPO_NAME
```

(4) Close connection

```
# exit
```

Clone repo
---

(1) Navigate to local folder

```
$ cd FOLDER_PATH
```

(2) Clone repo

```
$ git clone ssh://ACCOUNT_NAME@QNAP_IP:23/share/Dan/git/REPO_NAME
$ PASSWORD
```
