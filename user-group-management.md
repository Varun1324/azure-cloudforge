    1  pwd
    2  cd /home
    3  ls
    4  cd
    5  pwd
    6  apt update
    7  apt install git -y
    8  apt list git
    9  git clone https://github.com/Varun1324/azure-cloudforge
   10  ls -lrth
   11  cd azure-cloudforge/
   12  ls
   13  git config --local user.name "Varun1324"
   14  git config --local user.email "varunkodamanchili@gmail.com"
   15  git config --local --list
   16  touch user-group-management.md
   17  ls
   18  chmod 777 user-group-management.md
   19  ls -lrth
   20  cd ~
   21  pwd
   22  useradd -m nick
   23  useradd -m tom
   24  cd /home
   25  ls -l
   26  id nick
   27  id tom
   28  cd ~
   29  useradd -m test
   30  cd /home/
   31  ls -l
   32  passwd nick
   33  passwd test
   34  groupadd dev
   35  groupadd prod
   36  groupadd testing
   37  cd ~
   38  cd /
   39  cat etc/
   40  cd etc/
   41  ls -lrth
   42  cd group
   43  cat group
   44  cat passwd
   45  echo "adding users to groups"
   46  usermod -g dev nick
   47  usermod -g prod tom
   48  usermod -g testing test
   49  usermod -g prod nick
   50  id nick
   51  usermod -g dev nick
   52  id nick
   53  usermod -G prod nick
   54  id nick
   55  id tom
   56  usermod -G prod,dev test
   57  id test
   58  id nick
   59  usermod -aG testing nick
   60  id nick
   61  cat group
   62  cd ~
   63  cd azure-cloudforge/
   64  history > user-group-management.md
