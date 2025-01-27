# ssputils
#### Python 3.12.3 or above was need to run this utility
###### Below will be the command to run the utility
#### python fix_netmaps.py <From_Netmap_Name> <To_Netmap_Name>
###### Example :  python fix_netmaps.py SFTP_LDAP SFTP_OKTA

### Create a  config file (config.py) as follows

```python
class config_info:
    sspcm_user = 'admin'
    sspcm_pasw = 'password'
    sspcm_base_url = 'https://host:port'
    session_token_uri = '/sspcmrest/sspcm/rest/session'
    all_netmap_uri = '/sspcmrest/sspcm/rest/netmap/getAllNetmaps'
    netmap_uri = '/sspcmrest/sspcm/rest/netmap/getNetmap/'
    update_netmap_uri='/sspcmrest/sspcm/rest/netmap/addNetmapNodes/'
```