# siebel_cli

Known Recurring Variables:
- /u	Userid of the person doing the compile
  - Defaults to: `SADMIN`
- /p	Password for the Userid
  - Defaults to: `password`

- /d	Table Owner.  
  - Defaults to: `SIEBEL`
- /G	Language Code.  Set to ALL
  - Defaults to: `ALL`
- /g	Always SSE_ROLE
  - Defaults to: `SSE_ROLE`

## Parameter	Description
- /c	name of Seibel config file.  The config file has the login parameters and environmental information
- /d	ODBC data source name to the Siebel Server database
- ** /u	Userid of the person doing the compile **
- ** /p	Password for the Userid **
- /bc	Name of the Siebel Repository and the name of the compiled SRF

- /a	Type of import/export.  Set to E for export
- /c	ODBC data source name to the Siebel Server database
- ** /u	Userid of the person doing the compile **
- ** /p	Password for the Userid **
- ** /d	Table Owner.  Set to SIEBEL **
- ** /G	Language Code.  Set to ALL **
- /r	Name of the repository to export.  Set to Siebel Repository
- /f	Path and Data file name of the export
- /v	Verify data file
- /l	Path and file name of the log file

- /a	Type of import/export.  Set to I for import
- /c	ODBC data source name to the Siebel Server database
- ** /u	Userid of the person doing the compile **
- ** /p	Password for the Userid **
- ** /d	Table Owner.  Set to SIEBEL **
- ** /G	Language Code.  Set to ALL **
- /r	Name of the repository to import.  Set to Siebel Repository
- /f	Path and Data file name of the file being exported
- /v	Verify data file
- /l	Path and file name of the log file

- /a	Type of import/export.  Set to I for import
- /c	ODBC data source name to the Siebel Server database
- ?? Is this really the same as other User IDs in this usecase?? ** /u	Userid of the person doing the export or database owner (Siebel) **
- ** /p	Password for the Userid **
- ** /d	Table Owner.  Set to SIEBEL **
- ** /g	Always SSE_ROLE **
- /n	Repository that contains the schema information
- /f	Path and Name of the schema.ddl file
- /l	Path and file name of the log file
- /B	Tablespace name
- /X	Index Space name
