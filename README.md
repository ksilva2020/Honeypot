# Honeypot
# Honeypot Assignment

**Time spent:** **14** hours spent in total

**Objective:** Give a brief report of the current state of Internet security. 
**


### MHN-Admin Deployment (Required)**

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?


Deployment: The MHN-Admin was deployed using GCP. Using the instructions from Codepath (CP), I created firewall rules that allowed two ports to be used (80, 3000 and 10000) to allow ingress traffic.

Installation: Established SSH access to the MHN-Admin and used commands from CP. 



<img src="mhn-admin.gif">



https://user-images.githubusercontent.com/98780052/204158878-728e5e8d-26b9-4972-a21c-b52d8fd580b7.mp4




### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?

Dionaea is a server decoy used to capture malware attacks exploiting the server vulnerabilities. Dionaea was installed by using the script from the server into the honeypot instance after SSH-ing into it



<img src="dionaea-honeypot.gif">


https://user-images.githubusercontent.com/98780052/204121802-64dd0b71-c6bb-45cb-828e-6a82ed6c0d06.mp4



3.### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*


The MHN-Admin uses mongoDb as RDBMS.
JSON files are used to log information about the attacks against the honeypot. The information it logs is: timestamps, IPS, ports, protocol and the target honeypot. 

4.### Deploying Additional Honeypot(s) (Optional)

#### P0F Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?
P0F attempts to identify system running on remote machines 

<img src="x-honeypot.gif">



https://user-images.githubusercontent.com/98780052/204121834-e0327eff-554a-4855-bd27-cc7c913d27e5.mp4


### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

Found malware using VirusTotal

MD5 Hash: *Run `md5sum` on the file and record the hash here.*

SHA1 Hash: *Run `sha1sum` on the file and record the hash here.*

<img src="x-malware.gif">


### Resources

Google Cloud

Kali Linux 

### Notes

Describe any challenges encountered while doing the assignment.

At first  I could not download the session.json to my computer. 
I started the process a second time. 
The second time around I was having a hard time accessing the mhn server. 
I was not able to access any charts or payloads reports. 

I did not get a report on the Top 5 Signature Attacks, they did not show. 

I used Kali Linux to initiate the first attacks.




