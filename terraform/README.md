# In current directory bec of / in the hidden catalog /.terraform/ ignore all files or directories.
# Dont understand meaning of ** multiple catalogs before? 
**/.terraform/*

# In current and subsequent directories ignore all files which ending with .tfstate
*.tfstate
# In current and subsequent directories ignore all files with has text ".tfstate." in the middle.
*.tfstate.*

# In current and subsequence diretories ignore all files crash.log
crash.log
# In current and subsequence directories ignore all files which starts with crash. then it can be as many symbols and finish with .log
crash.*.log

# In current and subsequent directories ignore all files which ends with .tfvars
*.tfvars

# In current and subsequence directories ignore all files with name override.tf also files override.tf.json and files which end with _override.tf and _overrite.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# In current and subsequent directories ignore files which end with .terraformrc and all files terraform.rc 
.terraformrc
terraform.rc






