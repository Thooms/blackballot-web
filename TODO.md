* Clean deployment procedure
    - Write a settings-prod.py that will switch the good options for
    production (see <https://docs.djangoproject.com/en/1.7/howto/deployment/checklist/>)
	- The dev is on SQLite, the production on PostgreSQL, so we might
    have to script some things for the migrations.
* LDAP auth (clean, without secret stuff in git, all that)
