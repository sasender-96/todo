todo

This service is responsible for Todo Service in Todo app.

This service is written in NodeJS, Hence need to install NodeJS in the system.
# apt update
# apt install npm -y

Now , fetch the code from git-hub
# git clone https://github.com/zelar-soft-todoapp/todo.git
# cd todo
# npm install

Now, lets set up the service with systemctl.
# vi /etc/systemd/system/cart.service
# systemctl daemon-reload
# systemctl start todo
# systemctl enable todo
