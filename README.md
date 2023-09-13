# wiki
Notes for programming

<h1>General</h1>
<h2>Create and add SSH Keys</h2>
Generate and upload ssh key to remote server to log in without password<br/>
Generate - $ ssh-keygen<br/>
Upload to server - $ ssh-copy-id -i ~/.ssh/id_rsa.pub {user@host}

<h1>Programming languages:</h1>
<h2>Golang</h2>
<h3>ORM</h3>
<h4>SQLx</h4>
A mixture between traditional ORM and raw sql<br/>
https://github.com/jmoiron/sqlx<br/>
<h4>GORM</h4>
Traditional ORM, works fine, but not as good as Django ORM<br/>
https://gorm.io/index.html<br/>
