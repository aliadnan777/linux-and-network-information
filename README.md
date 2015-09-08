# linux-and-network-information

* FAIL OVER
  * in fail over case we have to seprate servers on diffrent location
  * if primary server stop working, dns server  point to secondry server start responding
  * when primary server will be in working condition, dns server point to primary server  
  
* SSL Purchasing
  * when we purchase ssl , company ask some question
  * city, country
  * for what purpose for a company or personal
  * then they authorized
  * they give you insurance if traffic decript or hacked, they will pay you
* Paths
  * relative, A relative path is a way to specify the location of a directory relative to another directory
  * Exampl : /graphics/image.png
  * absolute,  the absolute path contains the root directory and all other subdirectories that contain a file or folder
  * Example http://www.mysite.com/graphics/image.png
* Data have issues, if issues then logs, when logs then we clustor to handle logs
  * ELK Elasticsearch log, it function is "indexing of logs"
  * Logstash, this clustor gathered logs and deliver to Elastic search
  * kibana , kibana is just for visualizing
* SSL , SSL Certificates are small data files that digitally bind a cryptographic key to an organization's details. When installed on a web server, it activates the padlock and the https protocol (over port 443) and allows secure connections from a web server to a browser.

### Permissions

* `----------`
* first desh `-` represent, is this document is file , directory or link
* if in starting is `-` then it is file , if d then it shows directory, if l it mean link
* next three dashes `---` represent owner
* r for first dash which mean read having 4 bits
* w for 2nd `-` which mean write having 2 bits
* x for 3rd `-` which mean exicute having one bit
* 
* next `---` dashes represent group, having same values as owner
* last `---` dashes for user, having same value as owner and group
* we can give permissions to owner, group and user according to requirement
* Example
* we have number 745 mean
* `rwx r-- r-x`
* `421 400 401`

 

