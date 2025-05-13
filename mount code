
configs = {"fs.azure.account.auth.type": "OAuth",
"fs.azure.account.oauth.provider.type": "org.apache.hadoop.fs.azurebfs.oauth2.ClientCredsTokenProvider",
"fs.azure.account.oauth2.client.id": "",
"fs.azure.account.oauth2.client.secret": '',
"fs.azure.account.oauth2.client.endpoint": "https://login.microsoftonline.com/tanent_id/oauth2/token"}


dbutils.fs.mount(
source = "abfss://container name@storage account name .dfs.core.windows.net", # contrainer@storageacc
mount_point = "/mnt/retaildomain",
extra_configs = configs)
