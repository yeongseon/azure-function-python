# azure-functions-python-v1


## Create a functions
func init --worker-runtime python -m v1

## Add a function
func new --name http_trigger --template "HTTP trigger" --authlevel "anonymous"


## Get the list of templates 
func templates list -l python
