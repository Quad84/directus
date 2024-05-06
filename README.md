# directusTask
Follow Me to learn how to use it

- [Installation](#installation)

```bash
git clone https://github.com/Quad84/directusTask
```

and install node-js Version 18.20.2 (LTS) from (https://nodejs.org/en/download)

- [Usage](#usage)

1: change directory to project
```bash
cd directusTask
```

2: migrate database 
```bash
npx directus bootstrap
```

3: import Databse Tables
```bash
npx directus schema apply snapshot.yaml
```

4: start project
```bash
npx directus start
```

# Tip 1 :
When you do step 2, the system will create a default email and password for you, which you must use in the panel.

# Tip 2 :
After completing the last step, go to the address 127.0.0.1:8055 in the browser and login with the default email and password.


# "Follow us , thank you <i love / you>"
