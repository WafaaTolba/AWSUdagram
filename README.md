## install environment

# install RDS
- go to AWS console, search for RDS. install postgres database as
- DB instance identifier= udagramdb
- master password= postgres123
- Database port= 5432
- Initial database name= postgres
- Endpoint=udagramdb.c2jq7fozwq0s.us-east-1.rds.amazonaws.com
- screenshot=RDS.png

# install S3
- go to AWS console, search for s3
- create bucket with name= bkudagram
- front-end website url:
http://bkudagram.s3-website-us-east-1.amazonaws.com/home
- screenshot of front end= FrontEndWebsite.png
- screenshot of s3= S3.png

# install IAM
- create a group called admin group with AdministratorAccess
- create user  called cli with programatic access
- user name= cli
   Access key ID=AKIA5L5UQUCU5QHMRHG3
   Secret access key=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
- screenshot= IAM.png

# install ElasticBeanstalk
- go to AWS console, search for ElasticBeanstalk
- create Application called udagrameb
- create Environment called Udagrameb-env
- add environment variables like that exist in .env file of udagram-api
- screenshot= EB.png

## Refrences
1. https://stackoverflow.com/questions/68511124/you-may-not-specify-a-referenced-group-id-for-an-existing-ipv4-cidr-rule-prompt
2. https://stackoverflow.com/questions/66321327/npm-install-is-failing-could-not-resolve-dependency
3. https://stackoverflow.com/questions/14502612/delete-a-directory-and-its-files-using-command-line-but-dont-throw-error-if-it
4. https://stackoverflow.com/questions/21505129/xcopy-copy-folder-starting-with-a-dot
5. https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/xcopy
6. https://www.yonisfy.com/udacity/projects/hosting-full-stack-application#uploadfile/folders
7. https://stackoverflow.com/questions/51014647/aws-postgres-db-does-not-exist-when-connecting-with-pg
8. https://stackoverflow.com/questions/56799562/git-submodule-add-error-does-not-have-a-commit-checked-out



