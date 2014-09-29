geneious-postgresql
===================

Documention and python code to setup and maintain a postgresql multi user database for Geneious


Usage
=====

Create a new user

```bash
	python geneious_pg.py -d geneious -p 'adminpassword' adduser brooke --userpassword 'userspassword'
```

Add to an existing collaboration

```bash
	python geneious_pg.py -d geneious -p 'adminpassword' adduser_to_collaboration BRO brooke Edit
```

Create a new collaboration

```bash
	python geneious_pg.py -d geneious -p 'adminpassword' create_collaboration sepiadarium		
```

Make user an admin of a collaboration. This user will be able to create folders and assign them to the collaboration's group

```bash
	python geneious_pg.py -d geneious -p 'adminpassword' adduser_to_collaboration sepiadarium nikeisha Admin		
```
